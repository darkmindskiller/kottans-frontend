# kottans-frontend
kottans-frontend course

## Git та GitHub - done
Now I new why my team loves "Releases" so much


## Linux CLI, and HTTP 
<img width="749" alt="Снимок экрана 2022-08-04 145343" src="https://user-images.githubusercontent.com/18643300/182856330-61faf52b-8af7-4504-8b6f-f953c535c7a0.png">

ls - list of contents of the directory
ls -l will tell more file info
cd - перемещение, например cd .. перемещение по дереву вверх
mkdir - create folder

more *file_name* - opens file

mv - move file. example mv *file_name* *dir_name*

pwd - where am I

cp - copy, example cp dir_name/file_name dir_name - to copy file from dir to other dir
cp -r ~jester/jokes ~ - copy the entire "jokes" directory tree to your home directory

rm - remove file
rmdir - remove directory
rm -r - remove all three

Permissions:
-rw-r--r--

first -(file) or d(directory)
 9 letters 3 rwx combo
 first for user second for group third for other
 r - read
 w - edit(write)
 x - execute

 chmod to change permissions
 parametrs u(user) g(group) o(other)
 chmod o+x - give execute right to other
 chmod g+x gorillas - give execute right to group gorillas
 + - gives permission - - takes away

* - selects all
*part - selects all files containing "part" in the end
sp??t - ? helps to select file if you forgot a lettes in it

man - manual
man ls - manual for ls command
man man - manual for man command
man -k spell - show you every command which has the letters "spell" somewhere in its brief description

find - search command
example:
finnd ~ -name "poem*"

cat - combine files
example cat file1 file2
combine files in new file cat file1 file2 > file3 if file 3 exists use >> to save its content

lpr - send to printer
lpq - display print queue
lprm - remove from print queue

lpr -P hp14 thoughts - sending file on printer (-P) named hp14

df - show free disk spase

ps - examine running programs
ps aux - 

| - sends the output of a command as the input to another command

grep - find patterns in data

kill PID - kill process wih id
kill -9 PID - kill immediately
