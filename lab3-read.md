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
