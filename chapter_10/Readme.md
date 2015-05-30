##Add a comment to the Readme.md that explains what Robocopy is...

>Robocopy stands for "Robust File Copy." It is a directory & file replication command much like `cp`.


#Do More

Use the cp -r command to copy more directories with files in them.

>`cp -r newplace bananas`


Copy a file to your home directory or desktop.

>`cp neat.txt ~`

Find these files in your graphical user interface and open them in a text editor.

>Open a new finder window. On the far left I can find my home directory (AndySowar).
Open the home directory & neat.txt is now in this directory. Double click on neat.txt
& it opens in text editor. 


Notice how sometimes I put a / (slash) at the end of a directory? That makes sure the file is really a directory, so if the directory doesn't exist I'll get an error.

>I could technically have a directory with a file extension in the name, 
so this is a great idea. 

#English Questions

Can you copy the foo.txt file to slash temp? (Create foo.txt first...)

>First I need to `touch foo.txt`. No you can't. This is what happens `cp foo.txt /temp`
                                          
>`cp: /temp: Permission denied`.
                                                                      

Can you copy .bash_profile in your home directory to the current directory?

> Yes! First, `cd` to go to my home directory. 

>Next,  `cp .bash_profile ~/workspace/davinci_coders_t2_2015/homework/learn_command_line_exercises/chapter_10`
. And that's it, no errors. 


