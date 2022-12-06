<h1 align='center'>Shell-Scripting(Linux)</h1>

### Notes
- Case sensitive
- Terminal open = CTRL + ALT + T
- In linux we have tree like structures for files
- In linux we call directory not folder like in windows
- **(.)** it represent current directory
- **(..)** it represent parent direcotry
- Path
  - Absolute **-:** start from root ```~```
  - Relative **-:** start from the current working dir ```/```
  - ```CTRL + C```-: kill process

- Types of Linux Command
  - Executable program which is in bin/userbin. example-: cp,wc
  - Shell buttons built in shell example-: cd,mv
  - Shell Scripts files that contains codes
  - Alias command that we can define by our own like example given in last commands section below
  
### Commands
- ```pwd``` **print working directory** gives the absolute path from the root 
- ```date``` 
- ```cal -y```
- ```clear``` to clear the shell
- ```ls``` list the dir
- ```ls -l``` all non hidden file
- ```ls -a``` hidden file
- ```ls -la``` combo of above two
- ```cd``` change dir
- ```cd..``` to move one step toward root
- ```cd~``` move directly to home
- ```cd /``` go to root dir
- ```cd -``` to get prev working dir
- ```touch filename``` to create a file to update filename same command
- ```cat > file.txt```
- ```cat "hello" > hello.txt```
- ```touch file1 file2``` multiple file creation
- ```mkdir dir``` To create dir
- ```rmdir dirname``` To removedir only work with empty dir
- ```rmdir -R dir``` remove all subdirectory
- ```rm -i file``` prompt base Y or N 
- ```rm -f file``` 
- ```rm -rf /``` delete everthing
- ```cp oldfile newfile```
- ```cp -R dir1 dir2``` to copy folder
- ```mv oldfile newfile``` rename also can be done
- ```mkdir 'my dir'``` to give space between file name
- ```rmdir "my cat"``` 
- ```history```
- ```history -c``` to delete history
- ```cat file1 file2``` to read multiple file from l to r
- ```which cp``` to get absolute path
- ```help cd``` to get detail of cd
- ```man cp``` to get manual
- ```man cd``` 
- ```whatis cp``` to get brief of cp
- ```ifconfig``` linux and ```ipconfig``` windows
- ```date;time``` ';' it is for sepration not termination
- ```alias dat="date"``` it create a command dat which perform date operaton _*_

### Shortcut key

- **CTRL + A** move to very beggining of line.
- **CTRL + D** to remove next char
- **CTRL + E** move to last element
- **CTRL + F** move one char forward
- **CTRL + B** move one char backward
- **ALT + U** upper case
- **ALT + L** Lower case
- **CTRL + U** cut from right to left
- **CTRL + V** paste
- **clear or CTRL + L**

### Text editior

- ```gedit filename```
- ```nano filename```
- ```vi filename```
- ```vim filename``` advance vi
- **CTRL + O** save 
- **CTRL + X** exit

