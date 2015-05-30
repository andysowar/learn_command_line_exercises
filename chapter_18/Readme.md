#English Questions

######Show me the lines in foo.txt that have "ERROR" in them.

>To do this we must use the `grep` command: `grep ERROR foo.txt`

>Output: `ERROR`

######Show me the lines in bar.txt that have "davinci" in them.

>Same as above: `grep davinci bar.txt`

>Output: `davinci`

######Can you print all the lines in text files that have your first and last name in them?

>Yeah, lets use the `grep` command again: `grep "Andy Sowar" *.txt`

>Output: `bar.txt:Andy Sowar
         foo.txt:Andy Sowar`
         
## -i option for grep

>The -i option for grep ignores case. For example if I typed `grep "andy sowar" *.txt`,
I would get no results. 

>If I typed `grep -i "andy sowar" *.txt`, I would get results that inclue "Andy Sowar".
