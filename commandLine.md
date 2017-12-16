[Source](https://learnpythonthehardway.org/book/appendix-a-cli/introduction.html)

## Commands
```command
$ pwd 
/Users/kiyun
$
```
Prints working directory

```command
$ cd ~
$ pwd
/Users/kiyun
$ mkdir temp
$ mkdir temp/something
```
Use `cd ~` to go back to the home directory and print working directory to check you are at home.  
`mkdir temp` and `mkdir temp/something` creates the folder 'temp' in the home directory, and the folder 'something' inside of the 'temp' folder.


## Vocabulary
- **Shell**
  - In computing, a **shell** is a user interface for access to an operating system's services. In general, operating system shells use either a **command-line interface** (CLI) or graphical user interface (GUI), depending on a computer's role and particular operation. It is named a shell because it is the outermost layer around the operating system kernel.
- **Folder and Directory** are the same thing
- **Session**
  - Do not type in the `$` (Unix) or `>` (Windows). That's just showing you my **session** so you can see what I got.
- **Prompt**
  - You can then see what I have for output followed by another `$` or `>` **prompt**. That content is the output and you should see the same output.

---
### To Memorize

Command Name | Description
---------- | -----------
`pwd`|print working directory
`hostname`|my computer network name
`mkdir`|make directory
`cd`|change directory
`ld`|list directory
`rmdir`|remove directory
`pushd`|push directory
`popd`|pop directory
`cp`|copy a file or directory
`mv`|move a file or directory
`less`|page through a file
`cat`|print the whole file
`xargs`|execute arguments
`find`|find files
`grep`|find things inside files
`man`|read a manual page
`apropos`|find what man apge is appropriate
`env`|look at your environment
`echo`|print some arguments
`export`|export/set a new environment variable
`exit`|exit the shell
`sudo`|become super user root **CAUTION!**

`cd ~` to go home


---
### Questions to Review
- Is there a way to comment?