#  Find Files Using Name in Current Directory & control through for loop
![image](https://github.com/abhiramdas99/linux-command-shell-script/assets/62290469/e9e0ba87-9040-4b74-b16f-f3ad794a13a3)
![image](https://github.com/abhiramdas99/linux-command-shell-script/assets/62290469/90bca992-a7cd-49a7-829a-06bfdb75621e)

# Find Files Under Home Directory
Find all the files under /home directory with the name abhi.txt.<br>
command : find /home -name abhi.txt

# Find Files Using Name and Ignoring Case
Find all the files whose name is abhi.txt and contains both capital and small letters in /home directory<br>
command : # find /home -iname abhi.txt

# Find the file patten and delete it in all location 
$ find . -type f -name "abhi*" -exec rm -f {} \;

# Find the directory using name  
find . -type d -name "abhi*"

# Find the  directory using name and delete it 
$ find . -type d -name "abhi"  -exec rm -rf "{}" \;

# Find the empty file in all loation from present directory and delete it 
$ find . -type f -empty -exec rm -f {} \;

# Find all files from the present directory which are modified before 10 minute 
$ find . -type f -mmin -10

# Find all files from the present directory which are modified before 10 days 
$ find . -type f -mtime -10
