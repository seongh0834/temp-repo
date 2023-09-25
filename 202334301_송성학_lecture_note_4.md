# My lecture note about Shell Commands (CLI)
----

#### What is Shell Commands? 
> shell commands allows user to **communicates** with **kernel**, like bash, zsh type. 
> It means access Operating System to controls and communicates through kernel. 

#### Shell Commands
- **pwd** : pwd command is showing current path for directory or file.
- **cd** : cd changes directory. (.like **select** specific directory) (You can use extend arguments.)
1\. ' **/** ' means root of directory path.
2\. ' **.** ' means current directory.
3\. ' **.\.** ' means upper level directory for current directory.
4\. .etc

- **ls** : ls showing list files and directories in current directories. (You can use extend arguments.)
1\. ' **-l** ' -l show detailed information ( **file name**, **modification time**, **size in bytes**, **owner**, **.etc**) file and directory in current directories.
2\. ' **-lh** ' -lh show same as above, but use size in units.

- **You can use Autocompletion and Past commands**
(By press ' **Tab** ' and ' **Up Arrow Key** ')

- **cp** : cp is copying files and directories. 
```sh
$ cp file1 file2        // file2 copied file1`s contents
$ cp -r directory       // copied all of files, directories recursively by select directory 
```

- **mv** : mv is moving files, directories or rename (overwriting) them.
```sh
$ mv file1 file2        // file1 is renamed (overwritten) file2
```

- **rm** : rm delete files and directories, **(So, you must have to use this command carefully! Because this command can't recover file, directories after active)**
```sh
$ rm file1 file2        // delete file1 and file2
```

- **mkdir** : mkdir is making a new directory.

- **help** : help command_name 

- **man** : man command_name ( gave you manual about command )

- **.etc**

---
#### Wildcards
- **\*** : ' \* ' means **all** filenames. (You can use this wildcards with **cp**, **mv**, **rm ...** commands)

- **Be careful before using rm command (Especially using ' \* ' wildcard with rm command!!! )**
Using **ls** command before use **rm** command is good for you.
