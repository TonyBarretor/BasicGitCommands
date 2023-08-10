# BasicGitCommands
Here you can find some basic git commands to start the commit

Firs of all you must set your credentials:

    git config --global user.email "abc@gmail.com"
    git config --global user.name "Randomname" - you can set a name whatever you want

Commands:

    pwd - print working directory
    cd - change directory. This is to enter to a new folder
    cd .. - this is to go back to the preview folder
    mkdir - To create a folder
    touch - to create a file, like .txt, .js, .md
    rm - to delete files .txt, .js, .md, etc
    rm -r - to delete folder
    ls - to print the folder's files
    ls -a - to print the hide folder's files (you can use this to check if the .git file is hidde in the master folder)
    code "Nameoffile.txt" - this command opens VSC to modify it
    code . - Open the unique file in VSC
    git status - to check if exist a commit of a file
    git push: comando para mandar nuestros commits a un servidor remoto.
    git pull: sirve para recibir cambios de repositorio remoto a local.
    git push: comando para mandar nuestros commits a un servidor remoto.

To start a commit from local folder to publish on Github

    0. Create a folder from Git, then enter to it, then...
    1. git init - Use this command to select the folder you are going to star to follow or commit
    2. git add "Nameofthefile.txt" - to add the file to commit
    3. **git add . - to add all the files inside the folder to the commit (add the files to the "photo" commit)
    4. git commit -m "Message to descript the changes on the project"
    5. git push -u origin main - if you star with a local folder and want to sync with an online repository without README.md file by default
    6. git log - to list the commits in our repository (to check previous commit)

To start a commit from Github with README.md file by default and then update the content

    0. Create a repository on Github, clone it to Desktop, then select the folder to enter to the folder cloned from Gitbub, then...
    1. git add "Nameofthefile.txt" - to add the file to commit.
    2. **git add . - to add all the files inside the folder to the commit (add the files to the "photo" commit)
    3. git commit -m "Message to descript the changes on the project"
    4. git push origin main - if you start with an online repository with README.md file by default

To sync the changes 

    git push origin main - if you start with an online repository with README.md file by default
    git push -u origin main - if you star with a local folder and want to sync with an online repository without README.md file by default

BECAREFUL!

    Never do git init in a folder of big files like Disk C, or a folder with many files because your star a follow of all those files.

ONLINE REPOSITORY

    If you choose Add README.md, github automatically creates an init commit
