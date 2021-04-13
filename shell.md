## The Shell
### Which shell is running
> ps $$

### To check shell version
> bash --version **if the shell is bash shell*

### "type" command
*to check whether a command is a built-in command or a location of program*

> type whoami

### Location of the shell
*e.g: location of the bash shell*

> echo $SHELL

### Wildcards
#### ?
*for single character*
> ls image-0?.jpg </br>
> *i.e: lists files with name image-0X.jpg where X is 0..9*

#### *
> ls *.dat </br>
> *i.e: lists all .dat files*
#### [*set*]
#### [*!set*]

