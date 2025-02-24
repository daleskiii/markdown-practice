# Writing in Markdown

Below you'll find several sections with instructions. Inbetween the two comment tags marked "Start of Section #" and "End of Section #" complete the instructions for that section.

Check off each step as you complete it and [refer back to the reading](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) often to assist!

---

#### Section 1 Instructions
- [x] Add a level 2 heading called "Collaborative Programming"
- [x] Add a link to the collaborative programming reading, the link should say "What is pair programming?" 
- [x] Add a JavaScript code block that contains a jsdoc comment. Take one from a previous replit, use the one from the reading, or create a new one. 
- [x] Add a level 3 heading called "Pair Programming at Pursuit"
- [x] Make an ordered list of the reasons Pursuit wants you to pair program. This list should be bold.

---

<!-- Start of Section 1 -->
## Collabortive Programing
[What is pair programing?](https://github.com/9-5-pursuit/unit-fundamentals/tree/main/collaborative-programming)
```js
function myName() {
    console.log('Aundale Walker')
}/** logging out name */

```
### Pair Programing at Pursuit
**1. Harder to Procastinate**
**2. Easier to learn**
**3. Shared best practices**
<!-- End of Section 1 -->

---

#### Section 2 Instructions
- [x] Add a level 2 heading called "Intro to the Command Line"
- [x] Add a link to the intro to command line reading, the link should say "What is the terminal?" 
- [x] Add a level 3 heading called "Keywords"
- [x] Re-create the list of keywords from the intro to command line reading, making sure to mark all code keywords as the reading did.
- [x] Add a level 3 heading called "Examples"
- [x] Create a bash code block containing the following examples, each example should have a code comment above it describing what it's doing:
    - Check your current file path
    - List the files and folders in your current directory
    - Make a directory
    - Navigate to that directory
    - Create a file within that directory
    - Move up one directory
    - Open a directory in Visual Studio Code
    - Open a directory in Finder
- [x] Add a level 3 heading called "Tips"
- [x] Recreate the tips section from the intro to command line reading
---

<!-- Start of Section 2 -->
## Intro to the CommandLine
[What is the terminal](https://github.com/9-5-pursuit/unit-fundamentals/tree/main/intro-to-command-line)
### Keywords
- Operating System (OS)
- Graphical User Interface (GUI)
- Comman Line Interface (CLI)
- Terminal 
- Shell
- Folder = Directory 
- `pwd` - print work directory
- `cd ..` - go to parent directory (aka up)
- `cd [folder]` - go into folder 
- `~` - represents your home folder
- `ls` - list files and subfolders in current folder
- `touch [filename]` - create a new file
- `mkdir [directory name]` - make a new directory 
- `code [filename]` - open the VSCode editor.
### Examples
```bash
#Check your current file path
#List the files and folders in your current directory
#Make a directory
#Navigate to that directory
#Create a file withing that directory
#Move up one directory
#Open a directory in Visual Studio Code
#Open a directory in Finder.
```
### Tips 
- Use tab to autocomplete. for exxample, if the current folder has subfolders titled `games`, `photos`, and `photography`, typing `pho` and pressing the tab key will result in displayin `photo` and ` photograpy`. If we then type the letter `g` to get `photog`, and press the tab key - the command will be autocomplete to `photography`.
- You can also use the up and down arrow keys to cycle through all the commands you've typed. 




<!-- End of Section 2 -->

---

#### Section 3 Instructions
- [x] Add a level 2 heading called "Git"
- [x] Add a link to the git presentation that we covered in class, the link should say "Git, what is it good for?" 
- [x] Create a bash code block showing how to do the following:
    - Make a directory
    - Navigate to that directory
    - Initialize a Git Repo
    - Create a readme.md file
    - Check the status of the repo
    - Stage the readme.md file
- [x] Put together instructions, utilizing code blocks when necessary, describing the following steps:
    - Open the directory you created previously in Visual Studio Code
    - Update the readme.md file
    - Compare the differences between the staged and unstaged readme.md files
    - Stage the changes to the readme.md file
    - Commit the changes
---

<!-- Start of Section 3 -->
## Git
[Git, what is it good for?](https://docs.google.com/presentation/d/1KSqHQw8DxaZTtGQn5VKjP_Ljv4H_zc2hfE1CEVH8M8o/edit#slide=id.g1ccb7498cf2_0_73)
```bash
# Make a directory 
# Navigate to that directory 
# Initialize a Git Repo
# Create a readme.md file
# Check the status of the repo
# Stage the readme.md file 
```
### Instructions
- Open the directory you created previously in Visual Studio Code, then updaate the `readme.md` file. Compare the differences between the staged and unstaged `readme.md` file. Stage the changes to the `readme.md` files.
- Commit the changes when done.
<!-- End of Section 3 -->

---

#### Section 4 Instructions
- [x] Add a level 2 heading called "GitHub (YourGithubUsername)"
- [x] Add a link to the GitHub reading, the link should say "GitHub, Let's build from here"
- [x] Create a level 3 heading called "Connecting Local to Remote"
- [x] Create a level 4 heading called "Local vs. Remote"
- [x] Describe, in your own words, what the difference between a local repo and remote repo is. 
- [x] Create a level 4 heading called "Getting ready on your local machine"
- [x] Copy the above section from the GitHub reading and highlight the code snippets where necessary.
-  [x] Create a level 4 heading called "Creating a new repository"
- [x] Create a list detailing how to create a repository on GitHub (use the GitHub reading)
- [x] Create a level 3 heading called "Push your code"
- [x] Copy the "Push Your Code" section from the GitHub reading and format it the same way.
- [x] Create a level 3 heading called "Collaborating with GitHub"
- [x] Create a step by step task list for the collaboration process. Include the following:
    - Forking
    - Cloning
    - Making Changes
    - Pull Requests

---

<!-- Start of Section 4 -->
## Github (YourGithubUsername)
[Github,lets build from here](https://github.com/9-5-pursuit/unit-fundamentals/tree/main/github)
### Connecting Local to Remote

#### Local vs. Remote 

- The difference between Local repo and Remote Repo is being able to access a file from your own computer or from a server. 

#### Getting ready on your local machine 
Before creating a remote repository on GitHub, you'll need a local repository with at least a single commit. That means you'll need to:

Create a new directory with at least one file.

Initialize that directory as a git repository with `git init`.

Stage and commit files, with `git add` and `git commit`.

You can always check if your directory is a git repository and has a single commit by running `git log`.

#### Creating new Repository
1. Go to Github Homepage then Click the Green new button to get the processed started.
2. Name your Repository 
3. Push create Repository button and you'll be brought to a page with code blocks.

### Push Your Code 
There are three commands that are run to connect your local repository to your remote repository. Typically, you can copy and paste these commands directly into your terminal. However, it's important to generally understand what each command is doing.

`git remote add origin <url>`

When you run this command inside of your local git repository, this command connects your local repository with your remote repository.

As you can see by reading the command, a new "remote" is added at the given URL. The name "origin" is just that -- a name for the remote. This name could be whatever you want, but you can just leave it as origin.

`git branch -M main`

This command sets the name of the main "branch" to be called `main`. You will learn more about branches later on. For now, know that the `main` branch is where your commit history will live. Your local repository also has a `main` branch -- these two branches will be connected.

`git push -u origin main`

The `git push` command moves all of the commits from your local repository to your remote repository. This is the command that gets the two synchronized.

The `-u` flag sets the "upstream" default for this branch to always be the remote with a name of "origin" and the branch with the name of "main."

Because of the `-u` flag, moving forward you can just write `git push` from your local `main` branch and git will know that you want to push to the `main` branch of the remote repository by the name of "origin".

### Collaborating with Github
- Forking
- Cloning
- Making Changes
- Pull Requests

<!-- End of Section 4 -->

---

#### Section 5 Instructions
- [x] Add a level 2 heading called "My Time at Pursuit"
- [x] Add an image that represents your time in the program so far.
- [x] Add a list with the following 3 things:
    - One thing you need to work on
    - One thing you feel you understand well
    - One thing you are looking forward to learning
- [x] Create a to-do list for your long weekend
- [X] Add a quote that keeps you motivated to keep pushing.
- [ ] Add a paragraph of bold text describing who you're doing this program for and why.
---

<!-- Start of Section 5 -->
## My Time at Pursuit 
![:upside_down_face:](https://parade.com/.image/t_share/MTkwNTgwOTUyNjU2Mzg5MjQ1/albert-einstein-quotes-jpg.jpg)

One thing I need to work on is :
- Getting more conditioned with JS syntex
One thing you feel you understand well
- I understand but I want to know how to use common-methods easier
One thing Im looking forward to learning is:
- how to build a app.

To Do list:
1. Study
2. Study
3. Study 

WE FALL DOWN, BUT WE MUST GET BACK UP!

I'M DOING THIS PROGRAM FOR ME. I've been looking for a career where it doesnt feel like work. I want to enjoy what I do. Software engireering is something that I know I'll enjoy. 

<!-- End of Section 5 -->

---

## Done?
- Rename your markdown file using your first name and first initial of your last name (for example, mine would be anthonyp.md)
- Create a pull request