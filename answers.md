Answer 1: 
    The output of the command "git --version" is "git version 2.32.1 (Apple Git-133)
Answer 2:   
    After inputting my name and email, and running the "git config --list" command, the terminal output is:
        user.name=Nova Fitzmaurice
        user.email=nf927617@ohio.edu

Answer 3:
    When you type "git --help", it displays an explanation of common Git commands used in different situations, as well as a description of use cases. For example, to start a working area, it suggests you use the clone command, or the init command. It also explains what each of those commands do. Clone clones a repository into a new directory, and init creates an empty Git repository or re-initializes an existing one. There are several more common Git command descriptions here, including commands to work on current changes, examine history and state, grow, mark, and tweak your common history, and collaborate. It seems pretty helpful to reference when you need to work in a collaborative environment, or anytime you use version control with Git.

Answer 4:
    After modifying the README.md file by inputting my name and github username, and then running the "git status" command, this is the output I see in the terminal:
        On branch master

        No commits yet

        Untracked files:
            (use "git add <file>..." to include in what will be committed)
                README.md
                answers.md

        nothing added to commit but untracked files present (use "git add" to track)

Answer 5:
    After tracking the README.md file by staging it using the "git add README.md" command, and checking the status via "git status", this is the output:
        On branch master

        No commits yet

        Changes to be committed:
            (use "git rm --cached <file>..." to unstage)
	        new file:   README.md

        Untracked files:
            (use "git add <file>..." to include in what will be committed)
	        answers.md
    The newly tracked file, README.md, is now colored green.

Answer 6:
    After adding the second file, answers.md, to the staging area, and checking the status, this is what I see:
        On branch master

        No commits yet

        Changes to be committed:
            (use "git rm --cached <file>..." to unstage)
	            new file:   README.md
	            new file:   answers.md

Answer 7:
    After using the commit command "git command -m "Initial commit", and checking the status, this is what I see:
        On branch master
        nothing to commit, working tree clean

Answer 8:
    After viewing the repository history "git log" this is what is outputted:
        commit fa894537cd5e283312d8122ef05ee94c18c4e538 (HEAD -> master)
        Author: Nova Fitzmaurice <nf927617@ohio.edu>
        Date:   Tue Sep 6 21:26:21 2022 -0400

        initial commit

Answer 9:
    After creating the public repository, git-lab, on my github and committing my git-lab local repository, and checking the status, this is the output:
        On branch main
        Your branch is up to date with 'origin/main'.

        nothing to commit, working tree clean

Answer 10:
    After editing my README.md file on my github through the web browser, and checking the contents of the local version of my file using the "more README.md" file, the changes are not reflected in my local copy. This is because I haven't pulled the most recent version from the server!

Answer 11:
    After trying to use the push command "git push" on my readme file, it returns an error. It says that updates were rejected because the remote contains work that you do not have locally. This is usually caused by another repository pushing to the same ref. I get this error because there are currently 2 different versions: The one on the github server, and the local version on my computer. I'm trying to push my edits without pulling the most recent version from the public repo. 

Answer 12:
    After running the git pull command to get the most recent updates from the server, my local copy now reflects all changes made on the github website. 

Answer 13: 
    After cloning the new public repository I made on github, and running the ls -a command, this is what I see:
        .			.git			README.md		
        ..			.gitignore
    It is a list of all contents of the repository





