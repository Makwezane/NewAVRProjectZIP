# NewAVRProjectTemplateZIP
This sets up a .sh file and a template folder that the .sh uses to start a new AVR project.

## Setup   
Copy the zip file to your AVR folder where all your projects are stored.  
Unzip.  
This will give you a NewProject folder. Move it's contents up one level (i.e. to your current folder).   
Delete the NewProject folder.  

## Usage   

    ./a_new_project.sh <project_name>
    
This will result in a folder called <project_name> that contains several sub folders and a Makefile.  

## Additional
If you have a 'library' of .c and .h files, read the comment at the top of the Makefile. I suggest in the src folder of your new project you refer to these 'library' files using a soft symbolic link specified with a **_relative path_**.  

I suppose this could be used for any other type of development but the Makefile is specific to AVR's.

