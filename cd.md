# cd
- it stands for change directory
- it is used to change the current working directory in the shell.
- usage:
    - `cd directory_location` : changes the current working directory to ***directory_location***
    - `cd ~` or `cd` : changes the current working directory to ***home directory***
    - `cd ..` : changes the current working directory to ***parent directory***
    - `cd .` : changes the current working directory to ***current directory***
- handle spaces in directory name :
    - `cd "My Folder"`
    - `cd My\ Folder`
- Environment variables related to `cd` :
    - `$HOME` : home directory
    - `$PWD` : current directory
    - `$OLDPWD` : previous directory

![example of cd](./screenshots/cd-1.png)
fig: example of `cd new_folder`

![example of cd](./screenshots/cd-2.png)
fig: example of `cd ~`

![example of cd](./screenshots/cd-3.png)
fig: example of `cd `

![example of cd](./screenshots/cd-4.png)
fig: example of `cd new\ folder`

![example of cd](./screenshots/cd-5.png)
fig: example of `cd "new folder"`

![example of cd](./screenshots/cd-6.png)
fig: showing values of  `$HOME`, `$PWD`, `$OLDPWD`
