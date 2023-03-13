0. echo ""Hello, World""	- To display "Hello, World" on the screen.
1. echo "\"(Ôo)'"	- To display confused smiley and ignore some characters.
2. less /etc/passwd	- To show the content of the file
3. cat /etc/passwd /etc/hosts	- To display the contents of two files.
4. tail /etc/passwd	- To display the last 10 lines of a file.
5. head /etc/passwd	- To display the first 10 lines of a file.
6. head -3 | tail -1 	- To display the 3rd line of a file.
7. echo "Best School" > "\*\\\'\"Best School\"\'\\\*$\?\*\*\*\*\*:)"	- To create a file, ignore special characters and input text.
8. ls -al >> filename	- To write into a file
9. tail -n 1 iacta >> iacta	- To duplicate the last line of a file
10.find . -name '*.js' -type f -delete	- To delete all .js
11. find . -mindepth 1 -type d | wc -1	- To count the number of directories and subdirectories in th current directory
12. ls-t | head -n 10	- T0 display 10 newest files in the current directory
13. sort | uniq -u	-a list of words that take input and prints only words that appear exactly onc
14. grep root /etc/passwd	- Lines containing root from the file /etc/passwd
15. grep bin /etc/passwd |wc -l	- To count words that contain bin in the file etc/passwd
16. grp -A 3 'root' /etc/passwd		-To display lines containing the ppatter root and three lines after them in the file /etc/passwd
17. grep -v bin /etc/passwd 	- To display all the lines that does not contain bin in the file /etc/passwd
18. grep '^[[:upper:]]\|^[[:lower:]]' /etc/ssh/sshd_config	- To display all lines of a file starting with letters only
19. tr Ac Ze	- To replace A and c with Z and e respectively
20. tr -d cC	- To remove all letters c and C from the input
21. rev		- To reverse inputs
22. cut -d':' -f1,6 /etc/passwd | sort	- To display all users and their home dir, sorted by users
23. find. -empty -printf '%f\n'		-EMpty casks make the most noise
24. find -type f -name "*.gif" | rev | cut -d "/" -f 1 | cut -d '.' -f 2- | rev | LC_ALL=C sort -f    - A gif is worth ten thousand words
25. cut -c 1 | paste -s -d ''		- Acrostic
16. tail -n +2 | cut -f1 | sort | uniq -c | sort -nr | head -11 | tr -s ' ' | cut -d' ' -f3   - The biggest fan
