0. alias ls="rm *"		- To create an alias ls to rm 
1. echo "hello $USER"	- To print hello and the current user
2. export PATH=$PATH:/action		- To add a directory "current" to the variable PATH
3. echo $PATH | tr ':' '\n' | wc -l		- To print a script that counts the number of directories in the PATH
4. printenv		- Use to print global variable
5. set			- Use to print global and local enviroment with their functions
6. export BEST="School"		- To create a local variable with name BEST and value School
7. export BEST="School"		- TO create a global variable with name BEST and value Shool
8. echo $((128 + TRUEKNOWLEDGE))		- To add 128 to value of the variable TRUEKNOWLEDGE
9. echo $((POWER / DIVIDE))		- To display the reult of  POWER divided by DIVIDE
10. echo $((BREATH ** LOVE))		- To display the result of BREATH to the power LOVE
11. echo "$((2#${BINARY}))"		-To convert the value of BINARY from base 2 to base 1
12. echo {a..n}{a..z} | tr " " "\n" | grep -v "oo"		- To print all possible combinations of two letters except oo
13. printf '%.2f\n' $NUM		- To print a number with two decimal places
14.  printf '%X\n' $DECIMAL		- To convert a number in variable DECIMAL from base 10 to base 16
15. 
