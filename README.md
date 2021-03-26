# tagfs

Tag based file manager written in python (Currently a CLI)

#### Coded in python--2.7

## How to use:

### Setting Up: 

Step 1:
python prepare_commands.py

Step 2:
python generate_tag_vs_files.py

Step 3:
python main.py

### Commands:

tagfs# help  
tagfs# U [tag or space separated tags] UNION Searches for files which match the given tag or space separated tags  
tagfs# add [tag] [file or folder] Indexes files/folders with the given tag  
tagfs# quit or tagfs# q Exits the program loop  
tagfs# I [tags sepatated by spaces] INTERSECTION returns a list of files which have all specified tags  
tagfs# stats Shows- total no. of tags total no. of files  
tagfs# ! [any command] or tagfs# sys [any command] Executes a given command to system shell  

### Near Future Plans:  
Add intelligent tags for files  
Use less space for storing tag_vs_files.pkl  
Add more features  
