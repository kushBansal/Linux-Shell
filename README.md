# Linux Shell
Basic Linux shell developed using C

The shell is an interactive interface that allows users to execute other commands and utilities in Linux and other UNIX-based operating systems.<br/><br/>
Linux shells are a lot more powerful than the Windows command line, because they function as a scripting language as well, with a complete set of tools. Multiple shells can be installed on a system and it is possible to quickly switch between them. <br/>


### Guide to run the code

> Make sure you have GCC installed

**1.Clone the repository in your local system**
```
git clone https://github.com/kushBansal/Linux-Shell.git
```

**2.Navigate to the main folder**
```
cd Linux-Shell
```

**3.Compile and execute the shell using following command**
```
bash init.sh
```
### Features
`sh_cd` : To change the current directory<br/>
`sh_exit` : To terminate the terminal <br>
`sh_bg` : Return current running process<br>
`sh_bglist` : Return the list of running processes <br>
`sh_kill` : Kill the current process<br> 

### New features
`sh_yahoo() method` : similarly as sh_google method,yahoo string will search string on yahoo. For example: myshell> google will open google and writing "google meme" will open meme<br/>
`sh_google() method` : This method will help you search google with whatever query you provide next to it. Usage : Simple google will open Google on your browser, and google strings will search strings on the same. You can also search for strings with multiple words separated by spaces.<br/>
