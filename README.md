# Linux
<br>
pwd :- Display the current working directory of the terminal
<br>
/  :- root directory
<br> 
echo :- command that writes its arguments to standard output
<br>
su :- used to switch to root user ( so that super permissions can be used to execute commands)
<br>
su username :- used to switch to a different user
sudo :- executes only that command with root/ super privileges
<br>
clear :- this command is used to clear the terminal screen. Contents will not be deleted but scrolled down
<br>
ls path :- by specifiying the path ls, the content content in that path will be displayed
<br> 
ls -l :- using "l" flag, list all the contents along with its ower setting, permissions & time stamp (long format)
<br>
ls -a :- using 'a' flag, list all the hidden contents in the specified directory
<br>
ls --author :- using "--author" flag, sort and list the content in the specified directory along with its owner
<br>
ls -S :- using "S" flag, sorts and list all the contents in the specified directory by size
<br>
ls *.hmtl :- using "*" lists only the contents in the directory of a particular format
<br>
ls -lS > file.txt :- using '>' flag, copies the result of ls command into text file
<br>
cd ~ :- this command also changes the directory to home directory
<br>
cd / :- changes the directory to root directrory
<br>
cd.. :- changes the directory to its parent directory 
<br>
cd 'xx yy' :- we specify the folder name in inverted commas because there is a space in the folder name
<br>
cat  :- this command is used to display the content of text file and concatenate serveral files into one 
<br>
cat -b :- this is used to add line number to non blank lines
<br>
cat -n : this is used to add line number to all lines 
<br>
cat -s :- this is used to squeeze blank lines into one line 
<br>
cat -E :- show $ at the end of line
<br>
$ cat > file1.txt  :- the '>' flag can be used to create a new file and enter contents from the terminal
<br>
$ cat >> file1.txt   :- the '>>' flag can be used to append text contents to an exixting file from the terminal
<br>
grep :- we uase the grep command to search for a particular string/ word in a text
<br>
grep option file 1.txt :- returns result for matching string "option"
<br>
grep -i option file1.txt :- return the results for case insensitive strings
<br>
grep -n option file1.txt :- return the matching string along with their line number
<br>
grep -v option file1.txt :- return the result of lines not matching the  searching string
<br>
grep -c option file1.txt :- returns the number of line in which the results matched search string
<br>
Sort :- we use the sort command to sort the results of a search either alphabetically or numerically.
<br>
sort file1.txt :- sorts the contents of file1.txt and return them in alphabetical order 
<br>
sort file1.txt File2.txt :- sorts the contents of both File1.txt & File2.txt
<br>
sort  -r file1.txt :- "r" flag returns the results in reverse order
<br>
sort -f file.txt :- "f" flag does case insenitive sorting 
<br>
sort -n file.txt :- "n" flag returns the returns the results as per numberical order








