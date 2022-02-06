# Linux commands to know

if you're getting a permissions error, add `sudo` to the start of your command. i.e. `sudo cd folder`

`ls` - print what's in this folder

`ls /path/to/directory` ls somwhere where you're not right now

`ls -al` - print what's in this folder with hidden stuff shown (linux hides folders that begin with ., i.e. `.git`)

`pwd` - print where you @

`cd` - move folders, for example:
- `cd folder1` - moves you into folder 1
- `cd ../` - moves you one folder "up"
- `cd ../../folder2` - move 2 folders up, and into folder2, if it's in there
- `cd "folder has a spacebar in the name"` - add quotations to go into folders with spaces

`mkdir <foldername>` - makes a folder called "<foldername>"

`rm <filename>` - remove file called <filename>

`rm -r folder` - remove everything inside of a folder

`nano filename` - open a basic text editor and create a the file if it doesn't exist

### Things to note:
Linux sees everything as existing somwhere on the root directory. Which is just `/`. You can try it yourself and see how your entire disk is organised by going `cd /` and then `ls`. 

**NEVER MODIFY YOUR LINUX FILES FROM WINDOWS** You have to go out of your way to find them, but it's worth stating. You can modify files on windows that you open with linux, but don't go into where your windows stores linux files.

Smug linux posters think they're better than you, so they though of something called a "home" directory, this is like "My Documents" on windows. It's denoted by `~` and it is shorthand for `/home/username`. For example:
- `~/potato/pie` and I'm logged in as the user "aster" is the same as `/home/aster/potato/pie`

Your windows files are stored in `/mnt/c` or appropriate drive letter. `/mnt` is the directory where drives are "mounted".
Once you're in `/mnt/c` it's the same as opening `C:\` in windows file explorer.
