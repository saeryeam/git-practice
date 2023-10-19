# **Shell command NOTE 2**
##### 202334469 박세렴
　

### **Standard Output**
---
**">" :** put ">" after command to create and save the output in a file
**">>" :** appends output to an existing file or create and write to a new if it doesn't exist
**cat :** command "cat" display the content of a text file

　
### **Standard Input**
---
**"<" :** you can redirect input from a file using "<"
　
　
### **Pipelines "|"**
---
**Pipeline :** Pipeline feeds output of previous command to input of next command
<ls | wc -1> : you can see the number of files in the current directory

　
### **Echo**
---
**Echo :** Echo print out the letters that follow it
<Echo *> : Outputting files currently in the directory (similar to ls)
<Echo ~> : Current user's home directory output
　
### **Backslash "\\"**
---
**Backslash :** Backslash can be used to ignore line change in command("enter"), to enter a long command in multiple lines

### **Changing Permissions**
---
**"chmod" changes permissions**
<ex>
rwx rwx rwx = 111 111 111
rw- rw- rw- = 110 110 110
rew --- --- = 111 000 000
　　　and so on , , ,
rwx = 111 in binary = 7
rw- = 110 in binary = 6
r-x = 101 in binary = 5
r-- = 100 in binary = 4
```sh
777 | (rwxrwxrwx)No restrictions on permissions. Anybody may do anything not a desirable setting.
755 | (rwx-xr-x)The file's owner may read, write, and execute the file. All others may read and execute the file. This setting is common for programs that are used by all users.
700 | (rwx------)The file's owner may read, write, and execute the file. Nobody else has any rights. This setting is useful for programs that only the owner mqy use and must be kept private from others.
666 | (rw-rw-rw-) All users may read and write the file.
644 | (rw-r--r--) The owner may read and write a file, while all others may only read the file. A common setting for data files that everybody may read, but only the owner may change.
600 | (rw-------) The owner may read and write a file. All others have no rights. A common settingfor data files that the owner wants to keep private.
```



### **Tip**
---
**History :** Type "history" to see previous command history or save it to a text file
　
