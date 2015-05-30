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

>After making it with `mkdir temp/foo/` we use `rm -rf temp/foo/` to recursively remove foo. 


