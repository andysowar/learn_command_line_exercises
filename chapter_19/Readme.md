#English Questions

######What option to ls tells it to output file size in human readable form?

>I can figure this out by using `man ls`.

>`ls -sk` will print the size of each file in kilobytes.

######Is there a case insensitive option to grep?

>Yes I can find this out by using `man grep`:
 
>`grep -i` or `grep --ignore-case`.

######What does the -r and -f options to rm do exactly?

>Let's use `man rm` and see.

>The -r function removes the entire hierarchy of the selected 
 directory & will remove all types of files. 
 
>The -f function removes files without prompting for confirmation.
It will override any -i options which do ask for confirmation.

>-rf will remove all files in the entire hierarchy of a directory without
asking permission!

######What does the ifconfig command do?

>To find this out, type `man ifconfig`: 

>ifconfig assigns an address to a network interface and configures network
interface parameters.


