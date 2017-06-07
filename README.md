### Learn-git 
### This is a note for learning git and github from Xuefeng Liao

* Install from Windows : https://git-for-windows.github.io  
   Install the downloaded .exe file. You can find "Git Bash from the start menu", indicate the successuful installation  

* Configue the user information by following commands  
   $ git config --global user.name "Your Name"  
   $ git config --global user.email "email@example.com"

* Create the first git repo  
1. $ mkdir "create a new local name here"    
2. $ cd "the dir you create"  
3. $ git init  

* Add the first file to your git repo
1. Create a sample file "readme.txt" in your working directory by using editor like Notepad++, avoid using Notepad from MS Windows.  
----
### readme.txt
>Git is a version control system.  
>Git is free software.
----
2. add this file to the .git repo you created before. This takes two steps of git command  
$ git add readme.txt
$ git commit -m "add readme file"
