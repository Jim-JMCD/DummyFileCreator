## DummyFileCreator ( *DFileCreate* )
Dummy Data File Creator

DFileCreate - a bash script to create files with random content. 

A test file generator that can generate random data in a directory tree or single directory.
* The number of subdirectories within a directory (tree width) and number of directories in a path (tree depth) is your choice.  
* The number of directories and files within a tree increases exponentially as tree width and dept increase. Tree width increase more slowly, tree depth is very exponential.
* __Includes a calculator option__
* Minimum file number = 1
* Minimum file size = 2 bytes to multiples of GiB. 
* Files can all be the same or filled with individual random data from /dev/urandom. 
* Files can be all the same size or random sizes within a specified range. 

  

__DFileCreate -h__ lists all options   

__DFileCreate -C__  calculator option to explore directory and files numbers and resource usage.

Calculator limits: 100 PiB, 100 million files and directories, 

Recommended maximum tree size for full screen terminal 17 depth, no limit on tree width

_Inspired by HPCreateData (~2003)_
  
Author - Jim McDonald, Sydney 
