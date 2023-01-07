<!-- bash commands cheatsheet -->

# Bash
- Bash allows users to provide commands through which the user can specify what they want to do. Before providing the commands, bash displays a prompt, as you open the command line (in Linux and macOS), such as the one below.

    user@localhost:~$

- This prompt would typically state the current username with the hostname of the system. By default, the current directory of the terminal will be the user's root (or home) directory.

**echo**
- echo is the most basic command in bash, which displays its arguments on standard output (on the terminal).
1. user@localhost:~$ echo "Hello World!"
2. Hello World!
3. user@localhost:~$ echo Hello World!
4. Hello World!

**pwd**
- pwd is a command that stands for Print Working Directory. It displays your current working directory as output.
1. user@localhost:~$ pwd
2. /home/user

**ls**
- ls is a command short for list. It lists down the contents of a directory. By default, it lists the contents of the current working directory. From the example introduced at the start of the section, if we list down the contents of our current directory we get
1. user@localhost:~$ ls
2. Documents Pictures Videos

**ls -a**
- This option enables us to view hidden files. In the code block below, the files with a preceding dot ., are hidden files. These hidden files are not visible on GUI unless you enable the option to view them.
1. user@localhost:~$ ls -a
2. Documents Pictures .temp_file Videos .webpage

**cd**
- cd is a command to change directory. By providing a path along with this command, we can change the current directory to a different directory. This command does not give an output and only changes the directory. You can later use ls to display the directory contents to check that the current directory has been changed.
1. user@localhost:~$ cd Documents
2. user@localhost:~$ ls
3. file1.txt 
4. user@localhost:~$ cd ..
5. user@localhost:~$ ls
6. Documents Pictures Videos

In the above example, we used a shortcut .. to change back to the parent directory. This can be used several times in a single path to go up the hierarchy of parent directories. Of course, you can provide the entire path to the directory as well.

# Bash Commands for File Modifications
Working with files means modifying them in any capacity. Renaming, moving, creating, and deleting new files are the basic operations when working with files. Let's have a look at these operations using bash in this section.

**mkdir**
- mkdir is a command short for Make Directory. It creates a new directory with the specified name.

1. user@localhost:~$ mkdir BashTutorial
2. user@localhost:~$ ls
3. BashTutorial Documents Pictures Videos

**rmdir**
- rmdir is a command for Remove Directory. It removes the specified directory. It should be noted that the directory to be removed must be empty or the terminal will throw an error.

1. user@localhost:~$ mkdir BashTutorial
2. user@localhost:~$ ls
3. BashTutorial Documents Pictures Videos

**touch**
- touch is a command used for creating blank files. This command only creates a blank file and does not add anything to it.

1. user@localhost:~$ touch Newfile
2. user@localhost:~$ ls
3. Documents Newfile Pictures Videos




