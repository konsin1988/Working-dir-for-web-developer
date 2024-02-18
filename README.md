The utility creates a working folder with all the necessary folders, files and working tools for web development.
Usage: 
        wd [OPTIONS]...[NAME OF DIR]...[TITLE OF WEBSITE]..[NAME OF GITHUB REPO]
  The utility creates a working folder with all the necessary folders, files and working tools for web development.
   Options:
           -p              Creating a PRIVATE repository on github
                           (default option: public);
           -g              Initialization of gulp, creation of 
                          gulpfile.js containing a simple default 
                          task for minimizing main.css and main.js. 
                          The public version is saved in the \"public\" 
                          folder.
  NAME OF DIR - name of creating directory.
  TITLE OF WEBSITE - <title> of website.
  NAME OF GITHUB REPO - name of the github repository that will be created.
  
  To continue using gulp in your project, use the \"gulp\" or \"gulp default\" command.
  
 To correctly create a remote repository on github, you will need your personal login token with the authority to create a repository (\$Token in the program).
