# Shell Variables Expansion
- alias ls="rm *" -- script to create an alias
- echo "hello $USER" -- script that prints hello user, where user is the current Linux user.
- export PATH=$PATH:/action -- script to add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.
- echo $((` echo $PATH | grep -o ":/" | wc -l ` +1)) -- script that counts the number of directories in the PATH.
