# Purpose:

Learn how to navigate through directories, list files, and understanding your position in the Linux File System.

# Key Commands

## pwd
This shows your current location in the filesystem.

example pwd

 output: /home/pharrelloncloud/projects

## ls
This command lists files and directories in your current directory.
examples:

- ls -l , this shows the long format of the files and directories inside a directory.
- ls -a , this shows all files and directories including hidden ones.
- ls -la , this shows the long format of all files and directories including hidden ones.
- ls -lh , this shows the long format + human-readable file sizes.

## cd 
This command allows you to change directory

example cd Documents

pwd 

Output: /home/pharrelloncloud/Documents

cd  
Output /home/pharrelloncloud (takes you back to home directory if no directory is selected).

if /home/pharrelloncloud/Documents/Projects  
cd ..   
Output: /home/pharrelloncloud/Documents  

## tree
This command allows you to view the directory structure as a tree  
You will have to install it if it isnt installed using the following command:  
sudo apt install tree

## find 
This command allows you to search for Files or Directories.  
example: find /home/pharrelloncloud -name "*.txt".  
This should find all txt files on the home directory and return them to me in the terminal.  

## Bonus
You can combine navigation commands.  
example: cd Documents && ls -lh.  
Output: /home/pharrelloncloud/Documents$ and then should display all the files and directories in a long format that has a human-readable file size.

## Tip
Use the Tab button to auto-complete directory names and use the up and down arrow to use previous commands.