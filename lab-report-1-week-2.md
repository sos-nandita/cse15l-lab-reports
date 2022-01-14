# Lab Report 1 Week 2

## Topic: Remote Access
How to access the `ieng6` servers remotely.
---
### Step 1: Install VScode
* Go to [ https://code.visualstudio.com/]( https://code.visualstudio.com/) and hit the top right **Download** button.

![Image](downloadvscodeimg1.png)
---
* Choose the OS you are using

![Image](do.png)
---
* Set up and open VScode. Should look like this.

![Image](do3.png)

### Step 2: Remotely Connecting
* [Install OpenSSH](https://docs.microsoft.com/en-us/windows-server/administration/openssh/openssh_install_firstuse) and find your [student account information](https://sdacs.ucsd.edu/~icc/index.php).
* Open a new terminal and type the following command, but rpelace the `zz` with your account specific sequence.
```
$ ssh cs15lwi22zz@ieng6.ucsd.edu
```
* It will display `Are you sure you want to continue connecting (yes/no/[fingerprint])?`. Just type `yes`.
Then, it will prompt you for your `Password: `. Type in your password (it wont display anything as you are typing it).
The outcome should look like this.
![Image](connectingrem.png)
