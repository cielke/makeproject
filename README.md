# makeproject
This is a helper bash script to automate new project creation.

### Installation:
1. Download the template
2. Set template path in the script
3. Make script executable:<br/>
`chmod +x makeproject.sh`
4. copy makeproject.sh to your bin directory<br/>
`sudo cp makeproject.sh /usr/bin/`

### Usage:
Just type 'makeproject' or 'makeproject <project_name>' to create a project.<br/>
It will:<br/>
- copy your the template to given directory (the template is set to Maven Java8 project).<br/>
- create a new repository *(oh! irony @ bitbacket)* and push the files with initial commit.<br/>
- open the project in Intellij
