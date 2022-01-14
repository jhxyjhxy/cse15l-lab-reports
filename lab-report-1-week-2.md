Overall, make sure you have at least 6 screenshots, one for each of the steps below (though more is useful, remember that this will help out your future self). For each step include 2-3 sentences or bullet points describing what you did.

## 1. Installing VSCode
> Start by going to the Visual Studio Code's website ([Download VSCode](https://code.visualstudio.com/Download)) to find instructions to download and install it on your system. After successfully installing VSCode, you should have a window similar to the picture below!
<br><br>
![Image](photos/vscode2.png "VSCode example")



## 2. Remotely Connecting
> Since CSE 15L (and many other courses) requires us to connect remotely often, we should learn to use the `ssh` command. First, you need to install the OpenSSH program ([Install OpenSSH](https://docs.microsoft.com/en-us/windows-server/administration/openssh/openssh_install_firstuse)) and follow the instructions to set it up for your system. 
<br><br>
Next, find your course-specific account and reset its password using UCSD's ETS site. ([Find your account](https://sdacs.ucsd.edu/~icc/index.php)) Using a VSCode terminal, type the following command (replacing the `cs15lwi22asz` with your course-specific account):
<br><br>
`ssh cs15lwi22asz@ieng6.ucsd.edu`
<br><br>
There will most likely be a message asking if you're sure you want to connect, since it is your first time connecting to this server. Since you do want to, type `yes`, and press the enter key. Enter your password when prompted, then the terminal will output something like this:
<br><br>
![Image](photos/ssh.png "ssh example")



## 3. Trying Some Commands
> To make things easier, especially if you've never used a terminal before, commands are a super helpful way to navigate your files. We can use terminal commands both locally (on our machines) and remotely (while ssh'ed through the internet). The following are fairly common and you'll probably use them frequently in this course:
<br><br>
>
>- `cd <name-of-directory>`
>- `ls`
>- `pwd`
>- `mkdir <name-of-new-directory>`
>- `cp <file-path>`
<br><br>
>
> Try using these commands locally and remotely. The outputs should look similar to the pictures below.
<br><br>
![Image](photos/commands1.png "Local commands example")
![Image](photos/commands2.png "Remote commands example")



## 4. Moving Files with scp



## 5. Setting an SSH Key



## 6. Optimizing Remote Connecting
