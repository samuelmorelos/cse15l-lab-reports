## Resources
[Course Website](https://ucsd-cse15l-s23.github.io/)\
[Github Website](https://yourcousinfrog.github.io/cse15l-lab-reports/)\
[Markdown Reference](https://commonmark.org/help/)

## Remote Commands

Remotely Connecting: `ssh remote-server`\
Ex: `$ ssh cs15lsp23cu@ieng6.ucsd.edu`

Cloning a Repository: `git clone repository-url optional-location`\
Ex: `$ git clone https://github.com/ucsd-cse15l-s23/stringsearch`

Webpage from Terminal: `curl website-url`\
Ex: `$ curl http://ieng6-202.ucsd.edu:4005/search?q=on`

Secure Copy: `scp file-1 optional-file-2 desired-location`\
Ex: `$ scp message.txt cs15lsp23cu@ieng6.ucsd.edu:~/test-dir/`

## Terminal Commands
### Lab 1
"Concatenate" print the contents of files: `cat path1 optional-path2...`\
Ex: `$ cat Read.java`

"List" lists files and folders in the path: `ls path`\
Ex: `$ ls some-files`

"Print working directory" display the current directory: `pwd`

"Change directory" switch the current directory to the given path `cd path`\
Ex: `$ cd some-files`

"Find" recursively traverse the given path and list all files in the directory and subdirectories: `find path`\
Ex: `$ find */some-files > files.txt`\
This example takes the contents of some-files and prints it into a new file called files.txt

"Grep" search files for the given string and print matching lines: `grep string file-1 optional-file-2`\
Ex: `$ grep even some-files-list.txt`\
This example searches inside some-files-list.txt for any lines containing "even"

"WC" prints the number of lines, words, and characters in a file or files: `wc file-1 optional-file-2`\
Ex: `$ wc some-files-list.txt` which outputs `8   8   257 some-files-list.txt`
The first 8 is # of lines, the second 8 is # of words, and 257 is # of characters
