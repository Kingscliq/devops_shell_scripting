# Linux Shell Scripting

This task takes me through practical steps in learning Linux bash scripting.

---

## Task One
#### Creating Directories

1. I created a folder named **shell-scripting**.
   ![Screenshot of the shell-scripting folder creation](screenshots/creating-dir.png)


2. I used the **cd** command to change into the **shell-scripting** folder before creating the **my_first_shell_script.sh** file.
   ![Screenshot of navigating into the shell-scripting folder](screenshots/folder-mavigation.png)

3. Using Vim, I created a file called **my_first_shell_script.sh**.
   ![Screenshot of the file creation using Vim](screenshots/vim-text-editor.png)

4. I used **ls -latr** to confirm that the file was successfully created.
   ![Screenshot of the file listing](screenshots/create-shell-script-file-checking-permission.png)

5. I ran the script using **./my_first_shell_script.sh** but got an error: "Permission denied!" because the file wasn't executable, as I noticed in the file listing.
   ![Screenshot of the permission denied error](screenshots/execute-shell-script-permission-error.png)

---

## Task Two
#### Adding Permissions to the File

1. I added executable permission to the file using **chmod +x my_first_shell_script.sh**.
   ![Screenshot of adding executable permissions](screenshots/change-file-permission.png)

2. I ran the shell script and noticed that only the folders were created.
   ![Screenshot of running the shell script](screenshots/running-shell-script-create-users-folders.png)

**Note:** I couldn't create the users because I am running Vim and Terminal on macOS, and the `useradd` command is not supported. This is why it didn't run.

---

## Task Three
#### Variable Declaration and Initialization

1. In my shell, I was able to create a variable called `name` and retrieve its value from the terminal.
   ![Screenshot of variable declaration and retrieval](screenshots/variables.png)

---

## Conclusion

I was able to successfully complete the tasks, including creating directories, adding permissions to files, and working with variables in Linux shell scripting. However, due to the limitations of macOS, I couldn't use the `useradd` command to create users.
