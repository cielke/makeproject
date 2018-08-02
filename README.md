# makeproject
This is a helper bash script to automate new project creation.

##Installation:
1. Download the template
2. Set template path in the script
3. Make script executable:
  chmod +x makeproject.sh
4. copy makeproject.sh to your bin directory
  sudo cp makeproject.sh /usr/bin/


##Usage:
Just type 'makeproject' or 'makeproject <project_name>' to create a project.
It will copy your the template to given directory.
The template is set to Maven Java8 project.
It will create a new repository (oh! irony @ bitbacket) and push the files with initial commit.
