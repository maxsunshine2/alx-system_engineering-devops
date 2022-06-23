pwd: prints the absolute path of the current working directory
ls: lists all the contents of current directory
cd: g oback to home directory
ls -l: display current directory content in long format
ls -a -l: list more files even hidden files
ls lna: list files along with user and group ids numerically
mkdir /tmp/my_first_directory: a script that creates a diecroty in tmp
mv /tmp/betty /tmp/my_first_directory: moves the file betty from one directory to another
rm /tmp/my_first_directory/betty
rmdir /tmp/my_first_directory: deletes the directory from /tmp
cd - : changes pwd to the previous pwd
ls -a -l . .. /boot : list files even hidden ones in the order . .. /boot directories
file /tmp/iamafile : prints type  of file with the arguement
ln -s /bin/ls __ls__: creates a symbolic between the two arguments
cp -nu *.html .. : copies html from to parent folder except duplicates and newer ones
mv [[:upper:]]* /tmp/u : move all files beginning with a capital letter to tmp/u
rm *~ : removes all files ending with ~
mkdir welcome/ welcome/to/ welcome/to/school : creates the directoriers in the argument 
