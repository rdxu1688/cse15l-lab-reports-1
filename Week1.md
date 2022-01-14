# Week 1 - Remote Access and File sysyem

\
Hi, CSE 15L student. Welcome to your first Lab.
\
\
\
Today, we are going to teach you how to connect to the ___ieng6___ server.

Imagine that you are working to a company. YOu are not working on your computer only. You also need to work with the server and upload your file with your collegue. Today, we are going to upload our file into the school server ieng6.
\
\
![Image](hunting)
\
__Since there is so many people working with the server, some errors may be happened. Please be patients and keep trying.__ 
\
\
\
\
\
Feel Free to ask questions if you feel lost.
## Part 0 Password Reset and Looking up your account
\
This part is a part of part 2, but I recommand doing early because you may have trouble on reseting your password.
* Go to https://sdacs.ucsd.edu/~icc/index.php to look up your ieng6 account
## Part 1 Installing Visual Studio
\
The first thing we need to do is downloading Visual Studio Code(VSCode). VSCode is one of the famous Integrated Development Environment(IDE). This web and cloud application allows people to code with various extensions. We are going to use it to connect to our ieng6 server, but now, let download it on our computer first.

1. Go to VScode website to download this application https://code.visualstudio.com/.html
2. After you download it sucessfully, screenshot the VSCode interface and upload it to the google doc.

![Image](VS)

## Part 2 Remotely Connecting
After we download the VScode, we can try to connect to the ieng6 server. 

    If you have not finished part 0 yet, please go back and finish it beacause you need to know your account to log-in the server.
   --- 
    Window User: Your first step is downloading two program called OpenSSH Client and OpenSSh Server to allow your computer to communicate with another computer.




If you know your account and have changed your password, then please go ahead.

The following steps are coming from this article: [Remote Development using SSH](https://code.visualstudio.com/docs/remote/ssh#_connect-to-a-remote-host). If you want to learn more or clearfy the idea, you can use this link, but you can also use the follwing step.
1. Open a terminal in VSCode(ctrl+shift+`)
![Image](terminal)
2. type your command at terminal(replace the yourAccountNumber)

        $ ssh yourAccountNumber@ieng6.ucsd.edu
3. Since this is your first time to connect the server, you may have such question

        ![Image](connection)

## Part 3 Trying Some Commands
## Part 4 moving FIles with ___scp___
## Part 5 Setting an ___SSH___ Key
## Part 6 Optimizing Remote Running





