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



