Chromebooks are no longer supported directly but you can try the below and see if you can get running.

In Chromebooks settings you will need to enable Linux support. This will install the terminal cmd line
 
 Then just go into Sidequest folder.
 `cd SideQuest-0.7.4` (Version number may differ)
 
 Then use
 `chmod u+x sidequest`
 To apply permission to it
 
 Then type in
 `sudo apt-get install libnss3`
 to let it install the libnss3.so library
 
 And finally type in
 `./sidequest`
 to execute the launcher
 
 If you get
 `error: sidequest: sidequest: cannot execute binary file `
 this means the permissions didn't apply
If you get error 
 `./sidequest: error while loading shared libraries: libnss3.so: cannot open shared object file: No such file or directory`
 this means you need to install libnss3.so
 
 In either case just re run the commands in order again and it should work.
 
 
 Courtesy of
 https://github.com/the-expanse/SideQuest/blob/master/README.md#chromebook-install