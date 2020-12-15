  ###note : it work normally in my github folder location but not online     
# GIT 
   * git stands for control version system, and it give me control over my project.
   * control version means whenever i finish a sigment of a project i take a snapshot or node shot for the project.
   * each snapshot have information about what has changed where has changed who changed it and when happened.
   * to control my project i have to run a command that initalize a repository.
      **git init**
      
## how git works
  * there are 3 areas in repository the directory area, staging area and the commit area.
    1. directory area : files in this stage are not tracked by git.
    2. staging area : files in this stage are tracked and ready to be commited so git control the version.
    3. commit area : when files added to this area the git will take a snap shot and save it with id
    
## GIT AND GITHUB
   * github help me store my project on the cloud and cloud is basically a computer living on the internet.
   * in order to share my project so other developers can contribute i have to upload my project on the cloud.
   * other developers can clone the project from the cloud using the CLI.
    **Note** if i download project directly from github instead of CLI project will be downloaded without commit history
      in another word I download the current version only.
      
## GIT AND THE CLI
   * git init - create a new repository.
   * git add *file.extention* : will add file under control or **git add .** to add all files.
   * git status : show which files has been added to staging area in green color and files not tracked or in directory area in red color.
   * git commit -m "" : add tracked files to commit area with a breif message about the commit.
   * git clone *URL* : download the project from the store like github or bitbucket.
   * git push origin master : push my commits to the cloud.
   * git pull origin : download latest project update to match my project update.
   
   
   
# CLI
# there are 2 ways to communicate with computer
  1. The GUI - stands for graphical user interface
     it's the one we know and use all the time and interact with the computer throught it.
  
  2. The CLI - the command line interface
     * A command line, or terminal, is a text based interface to the system. You are able to enter commands by typing them on the keyboard and 
       feedback will be given to you similarly as text.
     * It's a powerful tool it allow me to open multi pages and I do work in each one individually.
     * shell is a part of the operating system that defines how the terminal will behave and looks after running (or executing) commands.
     * echo - return which shell i am using.
   
##  Shortcuts:
   * When you enter commands, they are actually stored in a history. You can traverse this history using the up and down arrow keys. So don't bother re-typing out commands you   have previously entered.
   * When you start typing a path (anywhere on the command line, you're not just limited to certain commands) you may hit the Tab key on your keyboard at any time which will  invoke an auto complete action.
   
### Basic Navigation
   1. Many tasks rely on being able to get to, or reference the correct location in the system. As such, this stuff really forms the foundation of being able to work effectively in Linux.
   
   2. I will be moving around the system often.
     
  * pwd - stands for print working directory and print the current url where I stand.
     example result : ya@a: /home/yaz
  
  * ls - stands for list and it list all files and directorys inside location i stand right now and it takes options tho.
      example results:   bin   Documents  public_html    file.txt
       
      **options:**
        there are many options but these are most used and we can combine them.
        1. ls -l : stands for long listing and it return directories and files with informations and show permissions read write.
        2. ls -t : sort by time & date
        3. ls -a : list all files including hidden file starting with '.'
  
  * cd - stands for change directory, it allow me to navigate around directories.
       example : **yaz@a: cd document** will navigate me to document file
       
       **NOTE**: If you run the command cd without any arguments then it will always take you back to your home directory.


# FILES in linux
  linux is that under the hood, everything is actually a file. A text file is a file, a directory is a file, your keyboard is a file (one that the system reads from only), your monitor is a file (one that the system writes to only) etc.
  
### Linux is an Extensionless System
  1. In other systems such as Windows the extension is important and the system uses it to determine what type of file it is.
  2. Linux the system actually ignores the extension and looks inside the file to determine what type of file it is. So for instance I could have a file myself.png which is a picture of me. I could rename the file to myself.txt or just myself and Linux would still happily treat the file as an image file. As such it can sometimes be hard to know for certain what type of file a particular file is.
   * command called file which we can use to find this out.
         file [path]
   3. whenever we specify a file or directory on the command line it is actually a path. Also because directories are actually just a special type of file, it would be more accurate to say that a path is a means to get to a particular location in the system and that location is a file.
      
     
   
