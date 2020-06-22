# linux_handbook
## This repo consists of some useful terminal commands 

### Basic cmds

1. This lists out the contents in the directory with user permissions.
 ``` 
ls -l
```
2. The first one refers to the present directory.
The second one refers to the directory one level below.
``` 
cd ./ 
```

``` 
cd ../ 
```

3. Creates a new file , while nano being a txt editor in terminal
``` 
sudo nano <filename_ with_extension>
```

4.To avail all permissions one should login as root. The following does it. To come back to user use the later cmd
``` 
sudo su
```
```
su <user> 
e.g; su surya
```

### File Management
1. To create a directory
``` 
mkdir
```
2. To move a file
``` 
<file> --> refers to just file name with extension e.g; f1.txt  :: Dont include the <>
make use of ./ --> current directory
../ --> directory one level below

mv <file>  <destination>
```

3. To copy a file
``` 
cp <file> <destination>
```

4. To remove 
``` 
# file

rm <file>

# files with certain extensions

rm ./*cpp --> *refers to everything with cpp extension'

# a complete directory 

rm -rf <directory>
```

5. Create files
``` 
touch <f1> <f2> <f3> 

this creates 3 files in the present directory.
```
6. To change ownership / permission
``` 
chown user:group 
e.g; chown root:surya
```
7. To open a pdf file in pdf viewer:
``` 
evince "pdf name"
```

### find cmd
1. to find a file of same extension:

type refers f->file
d->directory

-name --> search by name
-iname --> search by name ignoring case sensitivity
``` 
find . -type f -name  "*.txt"
```
### grep cmd :
refer to the below link:

``` 
https://phoenixnap.com/kb/grep-command-linux-unix-examples
```
### Processes:
``` 
top (This cmd outputs the live running process)

kill <process id> --> kills the process 

```





