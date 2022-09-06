
# Linux Shell
Basic Linux shell developed using C

The shell is an interactive interface that allows users to execute other commands and utilities in Linux and other UNIX-based operating systems.<br/><br/>
Linux shells are a lot more powerful than the Windows command line, because they function as a scripting language as well, with a complete set of tools. Multiple shells can be installed on a system and it is possible to quickly switch between them. <br/>


### Guide to run the code

> Make sure you have GCC installed

**1.Clone the repository in your local system**
```
git clone https://github.com/mahir29/Linux-Shell.git
```

**2.Navigate to the main folder**
```
cd Linux-Shell
```

**3.Compile the shell using following command**
```
gcc -o runshell  temp-sh.c utilities.c utilities.h linkedlist.c linkedlist.h
```

**4.Run this command**

```
./runshell
```

### New features
`sh_yahoo() method` : similarly as sh_google method,yahoo string will search string on yahoo. For example: myshell> google will open google and writing "google meme" will open meme<br/>
`sh_google() method` : This method will help you search google with whatever query you provide next to it. Usage : Simple google will open Google on your browser, and google strings will search strings on the same. You can also search for strings with multiple words separated by spaces.<br/>

