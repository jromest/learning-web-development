# Learning Git

Download Git [here](https://Git-scm.com/) and portable version [here](https://Github.com/Git-for-windows/Git/releases/download/v2.14.2.windows.2/PortableGit-2.14.2.2-64-bit.7z.exe) (*for Windows machine*).

### Setting up Git

You need to setup Git to be able to recognized you (specially when you made commits).

Set up your username and email:
```
$ git config --global user.name "Jrom"
$ git config --global user.email "email@sample.com"
```

The `--global` means that Git will always use the information in every project you created. A `.gitconfig` file will be created in root folder of your computer (`C:/Users/$USER` in Windows) that contains your information.

Checking your settings:
```
$ git config --list
```

It will show your configuration settings and information.
```
...
user.name=Jrom
user.email=email@sample.com
...
```

### Using Git

##### Creating a Git repository

Create a new directory, open it and perform Git initialization.
```
$ mkdir <FolderName>
$ cd <FolderName>
$ git init
```

The `mkdir` command means make a new directory with the name `<FolderName>`, `cd` means to open the directory and `git init` will created the directory a Git repository.

*You can now create initial files to be added in your projects.*

##### Adding your files to Git
```
$ git add <File>
```
or you can add it all:
```
$ git add *
```

##### Checking your repository's status
```
$ git status
```

Where you can see files that have been added or removed, files that ready to be committed, and changes to your file and repository.

##### Saving your files and changes to your Git repository
```
$ git commit -m "Your meaningful message"
```

The `-m` command tells that everything after it is a message.

You can check your addition and deletion of the file.
```
$ git diff
```

Where it will show you what you modified in a file.

##### Copying a repository
```
$ git clone <PATH>
```

It will copy a local git repository.

```
$ git clone <URL>
```

It will copy a remote repository in Github.
