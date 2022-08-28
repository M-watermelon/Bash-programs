# Bash-programs
This is a repository I will be uploading my BASH programs to as I learn to program shell programs. 

* Note: Some programs might not work because they are meant for specific things on my computer. 

## Files that will only work for me:
* navi -> It opens folder paths that only exist on my pc
* notes.sh -> I use this to test out new commands I learn
* osu -> Launches osu lazer app image but uses paths only on my pc
* krita -> Runs Krita app image (directory paths could be different for other people)

## Files that will probably work for anyone (no guarantees)
* doit -> automatically copies a shell program to the `/usr/local/bin` directory to make it runable in any directory

## Running the programs: 

To make a file executable anywhere:
First make it executable:
> chmod +x filename 

Then run:
> sudo cp filename /usr/local/bin/
