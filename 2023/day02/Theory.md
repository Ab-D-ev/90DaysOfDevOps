💻🐧What is Linux?
Linux is an operating system, like Windows or macOS, that powers computers and devices. It's free, secure, and highly customizable. Think of it as the "brain" of your computer, managing everything and allowing you to run programs and use your device smoothly. Many smart gadgets, servers, and even smartphones use Linux behind the scenes.

🐧Why is Linux preferred in DevOps?
Linux's open nature, command-line efficiency, stability, cloud/container compatibility, security emphasis, community support, configuration management integration, and customization flexibility makes it a perfect choice for driving success in the DevOps domain. Its usage in DevOps empowers teams to build scalable, reliable, and efficient software delivery pipelines.

The above terms would be explained in a dedicated blog, so don't worry about that. For now, let's just focus on the basic commands as an introduction.

👨‍💻Some basic commands to get you started:
In this blog, I will share some Listing and Directory Commands as an introduction so you can navigate through Linux.

📃Listing Commands:
💠 ls: List files and directories in the current directory.


COPY
ls #This will list all of the files in your current directory
💠 ls -l: List files and directories in long format, displaying detailed information like permissions, owner, size, and modification date.


COPY
ls -l #List files in long format
💠 ls *.sh: list all the files having .sh extension.


COPY
ls *.sh #list all the files having .sh extension.
💠 ls -d */: list only directories.(we can also specify a pattern)


COPY
 ls -d */ #list only directories.
💠 ls -t: List files and directories, sorted by modification time, with the newest files first.


COPY
ls -t #Newest files first
Remember, the options can be combined to get the desired output.

For example : ls -al will display all files and directories in a long format including hidden files.

📑Directory Commands:
💠 pwd: Print the current working directory, showing your present location in the file system.


COPY
pwd #Print Working Directory
💠 cd: Change the directory to the specified location. You can use relative or absolute paths.


COPY
cd /path/to/directory #Absolute Path
cd ../parent_directory # Relative Path
cd ~username # Switch according to Username
💠 mkdir: Create a new directory with the specified name.


COPY
mkdir directory_name
💠 rmdir: Remove an empty directory. Note that the directory must be empty for this command to work.


COPY
rmdir directory_name
💠 rm: Remove files or directories. (Use with caution, as it permanently deletes files and non-empty directories.)


COPY
rm file_name
rm -r directory_name
These commands provide essential functionality for working with directories in Linux, allowing you to navigate, create, delete, and manage directory structures making it easier to work with files and directories in the terminal.

