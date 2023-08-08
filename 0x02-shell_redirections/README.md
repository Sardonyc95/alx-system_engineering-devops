# Shell Redirections Commands
- The script {echo 'Hello, World'} is used to print "Hello, World" to the Standard output.
- The script {echo "(Ôo)'} is also used to display a confused smiley.
- The script {cat /etc/passwd} is used to display the content of the file /etc/passwd.
- The script {cat /etc/passwd /etc/hosts} is used to display the content of the files /etc/passwd /etc/hosts.
- The script {tail /etc/passwd} is used to display the last 10 lines of the file /etc/passwd.
- The script {head /etc/passwd} is used to display the first 10 lines of the file /etc/passwd.
- The script {head -3 iacta | tail -1} is used to display the 3 line of the file iacta.
- The script {echo 'Best School' > \*\\'"Best School"\'\\*$\?\*\*\*\*\*:)} is used to create a file containing the text.
- The script {ls -la > ls_cwd_content} is used to overwrite into the file ls_cwd_content.
- The script {tail -n 1 < iacta >> iacta} is used to duplicate the last line of the file iacta.
- The script {find . -type f -name "*.js" -delete} is used to deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
- The script {find . -type d -not -name '.' | wc -l} is used counts the number of directories and sub-directories in the current directory.The current and parent directories should not be taken into account, also Hidden directories should be counted.
- The script {ls -t1 | head} is used to Create a script that displays the 10 newest files in the current directory. One file per line and Sorted from the newest to the oldest.
- The script {sort | uniq -u} is used takes a list of words as input and prints only words that appear exactly once. Input format& Output format: One line, one word and words should be sorted.
- The script {grep -i "root" /etc/passwd} is used to display lines containing the pattern “root” from the file /etc/passwd.
- The script {grep -i "bin" /etc/passwd | wc -l} is used to display the number of lines that contain the pattern “bin” in the file /etc/passwd.
- The script {grep -iA 3 "root" /etc/passwd} is used display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.
- The script {grep -v "bin" /etc/passwd} is used display all the lines in the file /etc/passwd that do not contain the pattern “bin”.
- The script {grep -i '^[a-z]' /etc/ssh/sshd_config} is used to display all lines of the file /etc/ssh/sshd_config starting with a letter.include capital letters as well.
- The script {tr "A" "Z" | "c" "e"} is used to replace all characters A and c from input to Z and e respectively.
- The script {tr -d "Cc"} is used to removes all letters c and C from input.
- The script {rev} is used reverse its input.
- The script {cut -d ":" -f1,6 /etc/passwd | sort} is used to displays all users and their home directories, sorted by users based on the /etc/passwd file.
- The script {find . -empty | rev | cut -d '/' -f 1 | rev} is used to finds all empty files and directories in the current directory and all sub-directories. Only the names of the files and directories should be displayed (not the entire path), Hidden files should be listed, One file name per line, The listing should end with a new line, You are not allowed to use basename, grep, egrep, fgrep or rgrep.
- The script {find -type f -name "*.gif" | rev | cut -d "/" -f 1 | cut -d '.' 2- | rev | LC_ALL=C sort -f} is used to  lists all the files with a .gif extension in the current directory and all its sub-directories. Hidden files should be listed
Only regular files (not directories) should be listed
The names of the files should be displayed without their extensions
The files should be sorted by byte values, but case-insensitive (file aaa should be listed before file bbb, file .b should be listed before file a, and file Rona should be listed after file jay)
One file name per line
The listing should end with a new line
You are not allowed to use basename, grep, egrep, fgrep or rgrep.
- The script {cut -c 1 | paste -s -d ''} is used decodes acrostics that use the first letter of each line. The ‘decoded’ message has to end with a new line, You are not allowed to use grep, egrep, fgrep or rgrep.
