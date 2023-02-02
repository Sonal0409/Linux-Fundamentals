1. Create a directory TEST
2. Change to directory TEST
3. Create empty files file1 and file2 under Present Working Directory
4. Display the files file1 and file2. 
5. Append more lines in the file1 
6. Append more lines in the file2
7. List contents of file1 and file3 together
8. copy and append content of file1 file2 to file3

=========================================
SOLUTION:
=========================================

1. mkdir TEST
2. cd TEST
3. touch file1 file2
4. ls -al
5. echo "This is file1" >> file1
6. echo "This is file2" >> file2
7. cat file1 file2
8. cat file1 file2 >> file3
