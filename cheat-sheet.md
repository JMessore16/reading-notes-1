## What is the Command Line?

The **command line** is a text-based interface. Most people are used to Windows and MacOS, which utilize a Graphical User Interface (GUI). The GUI allows you to point and click to interact with the system. The command line utilizes text-based commands to interact with the system. The command line is a very powerful tool and should be used with care.

Some basic commands:
- **cd**: Changes the current directory. For example: `cd ~/projects/courses/`
- **mkdir**: Creates a directory. For example: `mkdir ./projects/courses/course-102/`
- **pwd**: Outputs what your current directory is. For example: `pwd` output: `Users/david/projects/`
- **ls**: Lists the contents of the current directory. For example: `ls -a` shows all files in a directory.

**cd**: In order to navigate the file system using the command line, you will need to use `cd`. The syntax can be tricky at first. The basic syntax is `cd /folder-name/`. However, the location is relative. This means that `cd` will assume that the directory you are changing to exists within the same directory you are currently in. The way around this is using absolute paths. For example, if I am currently in `/projects/courses/courses/course-102` and I wanted to move to a folder in the home directory, I would have to type `cd /~/other-folder/`. Below are some more examples of how to use it:
- `cd ./projects/courses`: Sets your working directory to `/courses/`. 
- `cd ..` : Sets your working directory to the directory above it. For example if you are in `/folder/courses/`, entering `cd ..` will cause your working directory to change to `/folder/`. 
