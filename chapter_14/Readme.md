##DANGER: Why is it dangerous to run "rm -rf /".

>Yikes! This will recursively remove all of my files starting with my home directory.

#English Questions

######Can you remove blah.txt?

>Yes, first: `touch blah.txt`.

>Next: `rm blah.txt`.

######Let's get rid of our development log file.

>Ok lets do that! But first... `touch development.log`

>Then: `rm development.log`.

######Can you remove everything in the slash temp slash foo directory?

> Yes, after making the folder with `mkdir /tmp/foo`, & checking to see if it's there with `ls /tmp/ `, I
 can remove it with `rm -rf /tmp/foo`.
 
 

