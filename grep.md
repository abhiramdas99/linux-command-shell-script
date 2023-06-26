grep command is used to search a string or text in given files or file 

# find a word /string/txt in multple file from present directory to  all child directories
 - grep -r -w "abhi" shellscript_practice/ 
 - grep -r -w -i "abhi" shellscript_practice/ 
 -  note : -r : directory  -w : word , -i : ignore case
   
# Grep files with a specific file extension
 - grep -r "abhi" . --include \*.js
 - note : -r : directory , search word : abhi

#  Display cpu model name using grep command 
- cat /proc/cpuinfo | grep -i "model"
- grep -i "model" /proc/cpuinfo

 
