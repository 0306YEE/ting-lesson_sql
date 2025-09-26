#README.md
#Install
. git
. DB Browser for SQLite

#Linux command
mkdir[folder.name]#create new folder in current directory
cd [folder.name] #go to next level folder in current directory
cd ..#go to 1 stage high root of current directory
ls # show file and folder and folder list of current directory

# Initialize Environment
in terminal:
. git --version
. git config --global user.name 'YEE Ting LIAO'
. git config --global user.email 'a0932111445@gmail.com'
. git init

#Common Used Instruction
. git status
. git log --oneline

#Track File and Folder
create a new README.md file, ctrl+s
. git add[full file name]
. git add *.file_sub_name
. git add.
. git commit -m 'message'

#Supplementary: others instruction of modify file
. git reset --soft HEAD~
. git reset --hard[version.number]--[filename]