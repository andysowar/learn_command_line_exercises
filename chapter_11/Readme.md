#English Questions

######Can you rename foo.txt to blah.txt?

>Yes. First, `touch foo.txt`. Next, `mv foo.txt blah.txt`.

######Can you move the production.log file in the log directory to slash temp?

>To start we need these files. So, `mkdir log`, then `touch log/production.log`.

No, you can't. This is what happens: 

>`mv production.log /temp`

>mv: rename production.log to /temp: Permission denied

######Can you zero out that file?

> Yes. If it type `rm production.log` it will zero it out.




