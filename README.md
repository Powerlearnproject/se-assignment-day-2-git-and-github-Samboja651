[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/8wgCKhpZ)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=16977485&assignment_repo_type=AssignmentRepo)
# se-day-2-git-and-github
## Explain the fundamental concepts of version control and why GitHub is a popular tool for managing versions of code. How does version control help in maintaining project integrity?
> Version control means tracking changes in code. Whether its a single line, a character or file I add to a code, that's a change and git tracks it and records who made the change and which changes.\
> Github is cloud storage that stores code in repositories. Inside each repo there are commits(changes or versions of code) pushed from a local environment.
> By using version control in code management we can know what was changed and who made the changes. Optionally we can decide who can make the change and under what conditions(clean code). We can also roll back to previous commit.

## Describe the process of setting up a new repository on GitHub. What are the key steps involved, and what are some of the important decisions you need to make during this process?
> Setting up a Github Repository
> - sign up on github
> - go to profile page
> - click create new repository
> - write your repo name
> - **select repo owner**
> - click add Readme 
> - optionally add gitignore for your language of choice
> - **Carefully choose the type of License**
> - set **visibility** to either **public** or **private**
> - You are Done

## Discuss the importance of the README file in a GitHub repository. What should be included in a well-written README, and how does it contribute to effective collaboration?
> README is like a documentation. It defines the project, what it does and how to use it.\
> A well written README should have:
> - Appropriate styling for easy readability.
> - Project Title and description
> - How to intall, run and use the software
> - Include licensing. e.g CC, MIT
> - How to contribute to the project
> - Credit or reference to resources used or people involved.\
> **Including a readme will enable developers learn about your project, spark an interest and even offer to contribute.**

## Compare and contrast the differences between a public repository and a private repository on GitHub. What are the advantages and disadvantages of each, particularly in the context of collaborative projects?
> Public and Private Repositories\
> - **Comparison**
> - Both are stored on Github.
> - Both have a common structure like READMEs\
> **Contrast**
> - Private repository is proprietary while publi repos don't have owners.
> - Private repos can be accessed by only invited contributors choosen by owner while public repos can be accessed by anyone with the repo link.
> - Private repos have proprietary license while public repo can have open source license like GNU.
> - Private repos are strict on the development languages to use while public repos are open to any language, although most have a main language to use.

## Detail the steps involved in making your first commit to a GitHub repository. What are commits, and how do they help in tracking changes and managing different versions of your project?
> A commit is change made in a code. It shows what has been changed, who changed it and at what time. Each commit represents a new version of code.
> Commits are also used in collaboration, e.g pull requests. With commits, you can roll back and forth to versions of code.
> To make a commit:
> - create a github repo and clone to local machine.
> - write your code or add files.
> - stage changes, run `git add` on terminal.
> - commit changes run `git commit -m "message"`
> - push commit to github, run `git push`.

## How does branching work in Git, and why is it an important feature for collaborative development on GitHub? Discuss the process of creating, using, and merging branches in a typical workflow.
> **Example**
> **I want to contribute to an open source project, I would:**
> - go to the project repository and fork it.
> - clone the the forked repo into my local machine.
> - create a new branch `git branch name`.
> - switch to that branch `git checkout name`.
> - make changes to code, test it, and create a commit.
> - push my branch to remote repository and make a pull request.
> - Alternatively if working in a less restrictive repository, I can:
> - merge the branch to main `git merge branch_name`.
> - solve any conflicts and push to github.

> From the scenario, branches are used in collaborations to create similar versions of code and make changes  without affecting the main branch.
>
## Explore the role of pull requests in the GitHub workflow. How do they facilitate code review and collaboration, and what are the typical steps involved in creating and merging a pull request?
> A pull request is a way of requesting that changes you've made in a branch be merged into another branch. It allows for code reviews and discussions before it is merged into main branch.
> Steps to create a PR:
> - go to project repository and fork it.
> - clone the forked repo into local machine.
> - create a branch `git branch branch_name`.
> - switch to that branch `git checkout branch_name`.
> - make changes to code and commit.
> - push branch to remote repository `git push -u origin branch_name`.
> - create a pull request specifying the new branch.
> - wait for review and discussions on what you changed.
>
## Discuss the concept of "forking" a repository on GitHub. How does forking differ from cloning, and what are some scenarios where forking would be particularly useful?
> Forking a repository is creating a similar codebase to my own github account. This way I can modify the code without affecting main codebase.\
> By forking, I will create the entire codebase including all branches to my own github account while in cloning I only get a specific branch of the main codebase.\
> I would use forking if I want contribute to large open sauce software. All if I want to get the entire codebase and play with it safely without any accidents commits to main codebase.

## Examine the importance of issues and project boards on GitHub. How can they be used to track bugs, manage tasks, and improve project organization? Provide examples of how these tools can enhance collaborative efforts.
> **Example** \
> **scenario: There's an open sauce project with about 50000 commits and almost 900 contributors.**\
> I want to contribute to the project, I would explore the codebase, may be the documentation and identify a bug or error.
> I would then create an issue referencing the bug identified. The issue is then listed on the projects issue tab on github.
> If I want to, I can claim the issue and be assigned to fix it or someone else can claim the issue. Discussions are then made within that issue.
> With 900 contributors there are many issues identified and all are listed in the issues tab and assigned labels/tags. This is where most contributors start, exploring the issues section.

## Reflect on common challenges and best practices associated with using GitHub for version control. What are some common pitfalls new users might encounter, and what strategies can be employed to overcome them and ensure smooth collaboration?
> **challenges for using Github for version control**
> - I will be limited to only what is in github. Other cool projects are hosted in gitlab, bitbucket ...
