# memory-reducer-waterfox


autoit script to reduce memory on waterfox , firefox, and possibly other programs 

derived from this script : https://github.com/rizonesoft/Firemin


checks memory usage in an intervall against a threshold and reduces the memory of the process
-------------------------
differences to firemin:

-no gui 

-checks memory of processes individually, firemin just checks the mainthread and then reduces all subprocesses too without checking their memory 

-------------------------

edit the script to set your own values ! 

precompiled exes have 10 seonds intervall and 300/400/500 MB threshhold respectively. use the correct 32 or 64 bit version for your system ! 
