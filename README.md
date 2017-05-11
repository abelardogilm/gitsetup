Shell script to generate new repo local and on git server, and connect it

## Configure
Make script executable if it's not
```
chmod +x git-create
```
Make sure you save it somewhere on your PATH, or load this folder on it. If you don't have a directory for custom shell scripts on your PATH, you can save it in ~/bin and then add that to your PATH by editing ~/.bash_profile as follows:
```sh
PATH=$PATH:~/bin
export PATH
```
# Use item
You can run it in 2 ways, executing the script ```./git-create <repo-name> ``` or using it from PATH ```git-create <repo-name>```

