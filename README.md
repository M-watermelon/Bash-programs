# Bash-programs I made, what they do, and how to use them:
This is a repository I will be uploading my BASH programs to as I learn to program shell programs. 

<mark>Note: Some programs might not work because they are meant for specific things on my computer. </mark>

## Files that will only work for me:
* navi -> It opens folder paths that only exist on my pc
* notes.sh -> I use this to test out new commands I learn
* osu -> Launches osu lazer app image but uses paths only on my pc
* krita -> Runs Krita app image (directory paths could be different for other people)
* shellcode -> takes me to the directory on my PC that has all my BASH scripts

## Files that will probably work for anyone (no guarantees)
* doit -> automatically makes a shell program executable and copies it to the `/usr/local/bin` directory to make it runable in any directory
* fancycat -> creates a file for BASH scripting (has no extension / .sh, just the name for simplicity) including the `#!/bin/bash` so you don't have to type it every time 
    * fancycat will only allow you to edit in one line, pressing ENTER ends the editing process
* fancycat V2 -> **WORK IN PROGRESS**, its fancycat but trying to fix the one liner issue

## Running the programs: 

To make a file executable anywhere:

First make it executable:
> chmod +x filename 

Then run:
> sudo cp filename /usr/local/bin/

## Additionally:

I suggest using the doit program to automate the process above (all you have to do is type the name of the file)

First make doit executable (navigate to the directory you have the program in first):
> chmod +x doit 

Then run:
> sudo cp doit /usr/local/bin/

**It will probably ask you to enter your password before it copies the file, so make sure you do that.**

Now you can make this the last time you have to make shellcode universally executable by hand!