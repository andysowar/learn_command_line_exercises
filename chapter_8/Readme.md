>######Explain what the pushd and popd commands do, in your own words.

`pushd` takes my current directory, saves it to a list, and then changes your current
directory to one that I specify.

`popd` switches my current directory to the last directory that I used `pushd` on.<p>

>######For the Do More section, explain what directories you visited in the Readme.md.

I started in the /temp directory & used the command `mkdir -p what/a/nice/day` to create my directories.
I then used `pushd what/a`. This pushed the temp directory
into a saved list & switched my directory to temp/what/a.

I then used `popd` & this took me back to the temp directory.

After that, I used `pushd what/a/nice`. This pushed the temp directory to a saved list 
& switched mine to temp/what/a/nice.

I then used `popd` & this switched me back to temp.
