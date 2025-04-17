## 01 : Listing : 

```sh
# lists all files and folders but not the hidden ones
ls

# lists all files and folders along with hidden ones
ls -a

# show all files and folders in list format
ls -l

# display all files and folder size in human readable format
ls -h
```

## 02 : Change directory 

```sh
# change to root directory
cd /

# change to home directory
cd ~

# move one directory up
cd ..

# go back to the previous directory
cd -
```

## 03 : New directory

```sh
# create a new directory
mkdir ProgrammingLanguage

# creates nested directories in one go. Skips errors if parent folders don't exist.
mkdir -p ProgrammingLanguage/JavaScript
```

## 04 : New file

```sh
# create a file using touch command 
touch hello.txt

# create a file using vim 
vim hello.js

# create a file using nano 
nano hello.java
```

## 05 : Move

```sh
# rename a file (file1 renamed to file2)
mv file1 file2

# moves file to a directory.
mv file.txt /dir1

# mv command doesnot have -r option
```

## 06 : Copy

```sh
# copy from file1 to file2
cp file1 file2

# recursively copies a directory and its contents.
cp -r dir1 dir2
```

## 07 : Delete files & folders

```sh
# delete a file
rm <file_name>

# delete an empty folder
rm <folder_name>

# delete a non-empty folder
rm -r <folder_name>

# forcefully delete a file
rm -f <file_name>

# forcefully delete a non empty folder
rm -rf <folder_name>
```