# GIT Exercise 1

Download the git software from the website below:
https://git-scm.com/download/win

Install it!

In your start menu, search for "Git Bash" <br>_If you don't have Git Bash, you can use cmd.exe too._
Run the following commands to define your email address and name for later git commands.


``git config --global user.email "iskolai.email.cimed@vajdasuli.hu" ``

``git config --global user.name "TesztElek"``


Clone (basically download) the repository to your computer

``git clone https://github.com/vmattschool/10a.git``

- Sign in with your Browser 
- Provide your username and password 
- After successful login, the cloned folder is located in C:\Users\[yourUserName]\10a 

Enter the folder in Git Bash with the command cd:

``cd 10a``

  - Open your the folder in your File browser. 
  - The cloned folder is located in C:\Users\[yourUserName]\10a
  - Create a .txt file **with your name**. (Right Click - New - New Text Document (Jobbklikk, új, Új szöveges dokumentum)

Switch back to the Git Bash window, enter command 

`` git add . ``

With this command, you added any new files to the repository. 

The next command is:

``git commit -m 'SajátNeved mappa hozzáadása' ``

With the git commit command, you "save" your changes to your local git repository. 
But if you want to upload it, one more command is needed:

``git push ``

If there's any error message, ask me on https://www.facebook.com/valko2!
