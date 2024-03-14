
# Lab 01 - Intro to Git

## Timeline
<table>
  <thead>
    <tr>
      <td style="text-align:left;">Assigned</td>
      <td style="text-align:left;">Monday 2 September 2024</td>
    </tr>
  </thead>
  <tfoot>
    <tr>
      <td style="text-align:left; color: #9e3436;">Deadline</td>
      <td style="text-align:left; color: #9e3436;">Friday 6 September 2024</td>
    </tr>
  </tfoot>
</table>

![Lab 1 Assignment](https://github.com/allegheny-college-cmpsc-104-Fall-2024/lab01/blob/main/graphics/github-mark2.png)

## Project Goals
- Install and configure Git
- Create and manage repositories
- Add files and check their status
- Commit changes to a repository
- Understand and work with Git branches

## Tools
- A computer
- Internet connection for installation and documentation reference
- Terminal (for macOS users) or Command Prompt (cmd) (for Windows users)

## Learning Outcomes
These assignment learning outcomes contribute to the following course learning outcomes described in the course syllabus:

1. Describe and explain processes such as software installation or design for a variety of technical and non-technical audiences ranging from inexperienced to expert.
2. Use professional-grade integrated development environments (IDEs), command-line tools, and version control systems to compose, edit, and deploy well-structured, web-ready documents and industry-standard documentation tools.

## Instructions

### Part 1: Check a Git Setting
Please verify that Git is installed on your machine and that your Git environment is correctly configured.
- Execute `git --version` in Command Prompt (CMD)/Terminal to confirm your Git installation.
- Run `git config --global user.name` in Command Prompt (CMD)/Terminal to verify your Git username.

### Part 2: Git Commands
- Please complete the TODOs in `writing/git_command.md` based on the information you gathered in the previous tasks.

### Part 3: Write about Version Control Systems
1. **What is Version Control?** Understand why they are crucial for developers.
2. Understand the importance of the staging area in Git's workflow and why commit messages are important.

### _Notes_: 
- Within `writing/git_command.md` and `writing/reflection.md`, you will find several TODOs awaiting your completion. As you work, please ensure to remove all TODO markers. 
- For this lab, GatorGrader will verify that all TODOs have been eliminated and that your submission includes a minimum of 300 words.

## Resources
- Git Documentation: https://git-scm.com/doc
    - Pro Git book: https://git-scm.com/book/en/v2
- Coursera: https://www.coursera.org/learn/introduction-git-github

## Deliverables
Please submit your work by pushing it to your GitHub Classroom repository.
- You will modify the files `writing/git_command.md` and `writing/reflection.md` to respond questions in the document.

## Project Assessment
- **Report Quality (40%)**: The quality of the writing in `writing/reflection.md` will be assessed, focusing on clarity, structure, and adherence to the assignment guidelines.
- **Git Command Proficiency (50%)**: Correctly answer questions related to Git commands in `writing/git_command.md`.
- **Achieve GatorGrader Compliance (10%)**: Successfully meets the criteria set by GatorGrader.

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
