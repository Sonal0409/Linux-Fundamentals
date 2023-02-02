1. Change to home directory
2. Create a 2 new directory mydemo1 mydemo2
3. Change to directory mydemo1
4. Create a file fil1 using touch command in directory mydemo
5. add contents to the file file1
6. move the file file1 into directory mydemo2
7. Change to directory mydemo2 
8. Check if file is present in directory mydemo2
9. copy the contents of the file 'file1' to a new file 'file2'
10. list the contents of directory mydemo2
11. Delete the file file1 in directory mydemo2
12. Go to directory mydemo1
13. Delete the directory mydemo2

============================================
SOLUTION
============================================

1. cd
2. mkdir mydemo1 mydemo2
3. cd mydemo1
4. touch file1
5. cat "this is file in directory mydemo1" > file1
6. mv file1 mydemo2
7. cd mydemo2
8. ls
9. cp file1 file2
10. ls
11. rm file1
12. cd mydemo1
13. rm -r mydemo2
