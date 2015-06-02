#English Questions

######How big is foo.txt?

>To find this, we use the disk usage command: `du -sh foo.txt`

>The output is: `4.0K	foo.txt`

>I can also use `ls -sk foo.txt'

>Output: 4 foo.txt

######Can you output all the txt files in this directory?

>Definitely, using the `cat` & `*` commands: `cat *.txt`.

>Output: `This is fun!
          This is cool!
          This is neat!
          What's up foo?
          Uncool bro...`
          
######Show me the content of the text files in slash temp.

>This can be achieved just like above: `cat /temp/*.txt`

>Output: `This is fun!
          This is cool!
          This is neat!
          What's up foo?
          Uncool bro...`
