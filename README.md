
# Document Engineering (CMPSC 104) Lab 1 Assignment

Assigned : Monday 2 September 2024

Due : Friday 6 September 2024

<p align="center">
  <img src="https://github.com/allegheny-college-cmpsc-104-Fall-2024/lab01/blob/main/graphics/github-mark.png" alt="Lab 1 Assignment" width="250"/>
</p>

## Project Goals
This lab assignment aims to introduce you to the concepts and operations of Git and GitHub. By the end of this lab, you should be able to install Git, configure it, perform basic Git operations such as creating repositories, adding files, checking status, committing changes, and understand how to work with branches.

## Tools
- A computer
- Internet connection for installation and documentation reference
- Terminal (for macOS users) or Command Prompt (cmd) (for Windows users)

## Learning Outcomes
These assignment learning outcomes contribute to the following course learning outcomes described in the course syllabus:

1. Describe and explain processes such as software installation or design for a variety of technical and non-technical audiences ranging from inexperienced to expert.
2. Use professional-grade integrated development environments (IDEs), command-line tools, and version control systems to compose, edit, and deploy well-structured, web-ready documents and industry-standard documentation tools.

## Instructions

### Part 1: Writing
- **What is Version Control?** Write about version control systems and understand why they are crucial for developers. 
- Understand the importance of the staging area in Git's workflow and why commit messages are important.

### Part 2: Installation and Configuration
1. **Install Git**: Follow the instructions on [Git's official site](https://git-scm.com/downloads) to download and install Git for your operating system.
2. **Configure Git**:
    - Open Terminal (macOS) or cmd (Windows).
    - Configure your user name with `git config --global user.name "Your Name"`.
    - Configure your email address with `git config --global user.email "youremail@example.com"`.

### Part 3: Creating a New Git Repository
1. Create a new directory on your computer where you want to initialize a new Git repository.
2. Open Terminal or cmd, navigate to the newly created directory.
3. Initialize the repository with `git init`.

### Part 4: Adding Files and Committing Changes
1. **Creating a File**: Inside the repository directory, create a new file named `firstLabAssigment.txt` and write "Hello, Git!" inside it.
2. **Adding the File**:
    - Use `git add hello.txt` to add the file to the staging environment.
3. **Checking Status**:
    - Use `git status` to see the status of the file.
4. **Committing the File**:
    - Commit the file to the repository with `git commit -m "First commit"`.

### Part 5: Working with Branches
1. **Creating a Branch**: Learn how to create a new branch using `git branch <branch-name>`.
2. **Switching Branches**: Switch to your new branch with `git checkout <branch-name>`.
3. **Merging Branches**: Merge changes from your branch back to the main branch with `git merge <branch-name>`.

### Part 6: Exploring More Git Commands
- View the commit history with `git log`.
- Learn about more advanced Git features (optional).

## Summary
- Create a repository on GitHub and push your local repository to GitHub, including your branches.
- Submit a report that includes your understanding of version control, Git, and the importance of the staging environment and commit process.

## Deliverables
Please submit your work by pushing it to your GitHub Classroom repository.
- You will modify the files `writing/git_command.md` and `writing/reflection.md` to respond questions in the document.

## Project Assessment
- **Report Quality (40%)**: The quality of the writing in `writing/reflection.md` will be assessed, focusing on clarity, structure, and adherence to the assignment guidelines.
- **Git Command Proficiency (60%)**: Correctly answer questions related to Git commands in `writing/git_command.md`.

## Gator Grade
### GatorGrade Checks for Immediate Feedback

To provide immediate feedback on your submissions, we're utilizing GatorGrade. Upon submission, if there's a thick red X, it indicates missing components. This X will turn into a green check mark once your submission is complete. For details on what's missing, click on the red X.

To meet the lab assignment's baseline writing and commit requirements, you can use the department's `GatorGrade` tool. Ensure Python3 is installed on your computer (check with `python --version`). If Python is not installed, please follow these guides:

- [Setting Up Python on Windows](https://realpython.com/lessons/python-windows-setup/)
- [Python 3 Installation and Setup Guide](https://realpython.com/installing-python/)
- [Setting Up a Local Programming Environment on Windows 10](https://www.digitalocean.com/community/tutorials/how-to-install-python-3-and-set-up-a-local-programming-environment-on-windows-10)

Installing `GatorGrade`:

- [Install](https://pipx.pypa.io/stable/) [pipx](https://pipx.pypa.io/stable/) if you haven't already (`pip install pipx`).
- Install `GatorGrade` using pipx (`pipx install gatorgrade`).
- Running `GatorGrade`:
 `gatorgrade --config config/gatorgrade.yml`

Good luck!
