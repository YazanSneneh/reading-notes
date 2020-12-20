  # CLI
# there are 2 ways to communicate with computer
  1. The GUI - stands for graphical user interface
     it's the one we know and use all the time and interact with the computer throught it.
  
  2. The CLI - the command line interface
     * A command line, or terminal, is a text based interface to the system. You are able to enter commands by typing them on the keyboard and 
       feedback will be given to you similarly as text.
     * It's a powerful tool it allow me to open multi pages and I do work in each one individually.
     * prompt in CLI is `name@na~:`
     * shell is inside the CLI come after prompt it's where i type commands and before.
     * echo - return which shell i am using.
### SHELL
 * Shell is a user interface connect between the **CLI** and **OS** responsible for processing all commands typed on CLI.
 * Shell instruct the OS to process task assigned to do.
 * shell scripting is ways of using the script in CLI to run certain tasks.
 * Tasks Shell process to OS.
   1. Work with files and directories like Navigating and manipulate them e.g. open and edit file or add and delete.
   2. Open and Close programms e.g `yaz@admin: code .` open VScode.
   3. Managing computer processes.
   4. Performing repetitive tasks.
   
##  Shortcuts:
   * When you enter commands, they are actually stored in a history. You can traverse this history using the up and down arrow keys. So don't bother re-typing out commands you   have previously entered.
   * When you start typing a path (anywhere on the command line, you're not just limited to certain commands) you may hit the Tab key on your keyboard at any time which will  invoke an auto complete action.

## USING CLI
 * most commands consist of: the command itself, the argument, and the option.
 * command contains the instruction we want to perform, the argument tells where the command should operate and the option requests the modification of the output.
 * there are many commands you can use with CLI, they all fall into two categories:
    * The commands that handle the processes.
    * The commands that handle the files.
### Basic Navigation 
  * pwd - stands for print working directory and print the current url where I stand.
     example result : ya@a: /home/yaz
  
  * ls - List files in directory.
      example results:   `bin   Documents  public_html    file.txt`.
       
      **options:**
        there are many options but these are most used and we can combine them.
        1. ls -l : stands for long listing and it return directories and files with informations and show permissions read write.
        2. ls -t : sort by time & date
        3. ls -a : list all files including hidden file starting with:  `.git .gitignore bin   Documents  public_html    file.txt`
  
  * cd - stands for change directory, it allow me to navigate around directories.
       example : **yaz@a: cd document** will navigate me to document file.
       **NOTE**: If you run the command cd without any arguments then it will always take you back to your home directory.
### manipulation of files
   * mv - move file from source to distination if dist not found will create one and trasfer everything in source to new file.
     * i use it to rename too.  `mv file.txt file2.txt`
    
   * rm - remove file `rm file.txt`.
     * rm -r to remove folder including files inside : `rm -r folderName`

# FILES in linux
  linux is that under the hood, everything is actually a file. A text file is a file, a directory is a file, your keyboard is a file (one that the system reads from only), your monitor is a file (one that the system writes to only) etc.
  
### Linux is an Extensionless System
  1. In other systems such as Windows the extension is important and the system uses it to determine what type of file it is.
  2. Linux the system actually ignores the extension and looks inside the file to determine what type of file it is. So for instance I could have a file myself.png which is a picture of me. I could rename the file to myself.txt or just myself and Linux would still happily treat the file as an image file. As such it can sometimes be hard to know for certain what type of file a particular file is.
   * command called file which we can use to find this out.
         file [path]
   3. whenever we specify a file or directory on the command line it is actually a path. Also because directories are actually just a special type of file, it would be more accurate to say that a path is a means to get to a particular location in the system and that location is a file.
      
## Why Choose CLI over GUI ?

 * Resource: text-based program needs very little resources of your computer
   * CLI :  do tasks with minimum resources.
   * GUI : Require Visual process.
 * High Precision: 
   * can use a specific command to target specific destinations with ease. As long as you don’t type the wrong command.
 * Repetitive Tasks Friendly :
    * GUI : operating system may not give you all the menus and buttons to perform all tasks. One of the reasons is safety. This leaves you overwhelmed if you have to do     repetitive tasks.
    * CLI : handle hundreds of files within a folder, CLI enables you to use a single command to do automate the repetition easily.
 * Powerful : Most operating systems today prevent you from messing up the system’s core process.
    * GUI: You won’t be able to perform certain tasks which are system protected. 
    * CLI : You will have full control over your system.
