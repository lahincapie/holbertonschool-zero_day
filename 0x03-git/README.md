# 📖 [0-Day - 0-Day](https://github.com/lahincapie/holberton_school/wiki/0-Day---0-Day)

******

# 0x03. Git


## 0. Create and setup your Git and GitHub account


You will need Git for this project, you might have to `install it` on your computer if it's not done yet:

   - Configure your basic info (name, email) on your local machine - they will be part of your commits. [Tips](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup).
    
On [GitHub.com](https://github.com/):
   - Using the graphic interface on the website, create the repository (if it is not done yet)
       - Name: `zero_day`.
       - Description: `This is my first repository as a full-stack engineer`.
       - Public repo.
       - No `README`, `.gitignore`, or license.

On your computer, open a terminal and do the following:

   - Navigate to your home directory. [Tips](https://linuxconfig.org/single-linux-command-to-return-to-home-directory)
   - Create a directory `zero_day`. [Tips](https://help.ubuntu.com/community/Beginners/BashScripting)
   - Navigate to this new directory. [Tips](https://askubuntu.com/questions/232442/how-do-i-navigate-between-directories-in-terminal)
   - Initialize git and add the remote origin
   - Create a file `README.md` with Emacs or Vi (or other command line editors) and write a small [Markdown](https://wordpress.com/support/markdown-quick-reference/) text to present this project. This file is mandatory in all School projects
   - Add this new file to git, commit the change with this message “My first commit” and push to the remote server / origin (Note: You will probably need to set your login/password to push to the remote server)

Good job!

You pushed your first file in your first repository of the first task of your first School project.

**Repo:**

   - GitHub repository: [zero_day](https://github.com/lahincapie/holbertonschool-zero_day)
   - File: [README.md](https://github.com/lahincapie/holbertonschool-zero_day/blob/main/README.md)

********

## 1. Repo-session

Create a new directory called `0x03-git` in your `zero_day` repo.

Make sure you include a not empty `README.md` in your directory:

   - at the root of your repository `zero_day`
   - AND in the directory `0x03-git`
 
And important part: **Make sure your commit and push your code to Github - otherwise the Checker will always fail**.

**Repo:**

   - GitHub repository: [zero_day](https://github.com/lahincapie/holbertonschool-zero_day)

********

## 2. Coding fury road

For the moment we have an empty project directory containing only a `README.md`. It’s time to code!

   - Create these directories at the root of your project: `bash`, `c`, `js`
   - Create these empty files:
      - `c/c_is_fun.c`
      - `js/main.js`
      - `js/index.js`
   - Create a file `bash/best` with these two lines inside: `#!/bin/bash` and `echo "Best"`
   - Create a file `bash/school` with these two lines inside: `#!/bin/bash` and `echo "School"`
   - Add all these new files to git
   - Commit your changes (message: “Starting to code today, so cool”) and push to the remote server

**Repo:**

   - GitHub repository: [zero_day](https://github.com/lahincapie/holbertonschool-zero_day)
   - Directory: [0x03-git](https://github.com/lahincapie/holbertonschool-zero_day/tree/main/0x03-git)
   - File: bash/best, [bash/school](https://github.com/lahincapie/holbertonschool-zero_day/blob/main/0x03-git/bash/school), [c/c_is_fun.c](https://github.com/lahincapie/holbertonschool-zero_day/tree/main/0x03-git/c), js/main.js, js/index.js

********

## 3. Collaboration is the base of a company

A branch is like a copy of your project. It’s used mainly for:

   - adding a feature in development
   - collaborating on the same project with other developers
   - not breaking your entire repository
   - not upsetting your co-workers

The purpose of a branch is to isolate your work from the main code base of your project and/or from your co-workers’ work.

For this project, create a branch `update_script` and in this branch:

   - Create an empty file named `bash/98`
   - Update `bash/best` by replacing `echo "Best"` with `echo "Best School"`
   - Update `bash/school` by replacing `echo "School"` with `echo "The school is open!"`
   - Add and commit these changes (message: “My personal work”)
   - Push this new branch [Tips](https://docs.github.com/en/get-started/using-git/pushing-commits-to-a-remote-repository)

Perfect! You did an amazing update in your project and it’s isolated correctly from the main branch.

Ho wait, your manager needs a quick fix in your project and it needs to be deployed now:

   - Change branch to `main`
   - Update the file `bash/best` by replacing `echo "Best"` with `echo "This School is so cool!"`
   - Delete the directory `js`
   - Commit your changes (message: “Hot fix”) and push to the origin

Ouf, hot fix is done!

***Repo:***

   - GitHub repository: [zero_day](https://github.com/lahincapie/holbertonschool-zero_day)
   - Directory: [0x03-git](https://github.com/lahincapie/holbertonschool-zero_day/tree/main/0x03-git)
   - File: bash/best, [bash/school](https://github.com/lahincapie/holbertonschool-zero_day/blob/main/0x03-git/bash/school), [bash/98](https://github.com/lahincapie/holbertonschool-zero_day/blob/main/0x03-git/bash/98)

*********

## 4. Collaboration: be up to date

Of course, you can also work on the same branch as your co-workers and it’s best if you keep up to date with their changes.

For this task – **and only for this task** – please update your file `README.md` in the main branch from GitHub.com. It’s the **only time** you are allowed to update and commit from GitHub interface.

After you have done that, in your terminal:

   - Get all changes of the main branch locally (i.e. your `README.md` file will be updated)
   - Create a new file `up_to_date` at the root of your directory and in it, write the git command line used
   - Add `up_to_date` to git, commit (message: “How to be up to date in git”), and push to the origin

**Repo:**

   - GitHub repository: [zero_day](https://github.com/lahincapie/holbertonschool-zero_day)
   - Directory: [0x03-git](https://github.com/lahincapie/holbertonschool-zero_day/tree/main/0x03-git)
   - File: [README.md](https://github.com/lahincapie/holbertonschool-zero_day/blob/main/0x03-git/README.md), [up_to_date](https://github.com/lahincapie/holbertonschool-zero_day/blob/main/0x03-git/up_to_date)

***********

5. HAAA what did you do???

Collaboration is cool, but not really when you update the same file at the same time…

To illustrate that, please merge the branch `update_script` to `main`: “Cool, all my changes will be now part of the main branch, ready to be deployed!”

**HHHHHHHAAAAAAAA**

`CONFLICT (content): Merge conflict in bash/best`

As you can see, you have conflicts between two branches on the same file.

Your goal now is to resolve conflicts by using the version of the branch `update_script`, and push the result to the origin.

At the end, you should have all your work from the branch `update_script` (new file and two updated files) and all latest `main` commits (new files, delete folder, etc.), without conflicts.

**Repo:**

   - GitHub repository: [zero_day](https://github.com/lahincapie/holbertonschool-zero_day)
   - Directory: [0x03-git](https://github.com/lahincapie/holbertonschool-zero_day/tree/main/0x03-git)

****************

## 6. Never push too much

Create a `.gitignore` file and define a rule to never push ~ files (generated by Emacs). [Tips](https://git-scm.com/docs/gitignore)

**Repo:**

   - GitHub repository: [zero_day](https://github.com/lahincapie/holbertonschool-zero_day)
   - Directory: [0x03-git](https://github.com/lahincapie/holbertonschool-zero_day/tree/main/0x03-git)
   - File: .gitignore


