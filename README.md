# DummyFileCreator
Dummy Data File Creator 
DFileCreator - a bash script to create files with random content. 

A test file generator that can generate random data in a directory tree or single directory.
* Minimum file number = 1
* Minimum file size = 2 bytes to multiples of GiB. 
* Files can all be the same or filled with individual random data from /dev/urandom. 
* Files can be all the same size or random sizes within a specified range. 
* For files in a tree the number of subdirectories with a directory (tree width) and number of directories in a path (tree depth) is your choice.  
* The number of directories and files within a tree increases exponentially as tree width and dept increase. Tree width increase more slowly, tree depth is very exponential.
* Includes a calculator option.   

DFileCreator -h lists all options   

Use DFileCreator -C  calculator option to explore directory and files numbers and resource usage.

Calculator limits: 100 PiB, 100 million files and directories, 

Recommended maximum tree size for full screen terminal 17 depth, no limit on tree width

  
Author - Jim McDonald, Sydney 
