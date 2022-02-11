<h1 style="font-size:35px;">Week 3 Lab Report</h1>
<br>
<br>

<h3 style="font-size:25px;">Copying Directories With "scp -r"</h3>

This will be an example of copying over an entire directory to the remote host; a link to the program can be found <a href="https://ucsd-cse15l-w22.github.io/week/week5/#group-choice-3-copy-whole-directories-with-scp--r">here</a>.

<br>

<h3 style="font-size:25px;">Copying To ieng6</h3>

In order to copy a directory over, first check that the current directory is the one that you wish to have copied over with <code>pwd</code>:

<br>
<img src="CurrentDirectory.png">
<br>

Once the directory is correct, use the command <code>scp -r . cs15lwi22zz@ieng6.ucsd.edu:~/markdown-parse</code> in order to copy over the entire directory; it should look like this:

<br>
<img src="SCPCopied.png">
<br>

<br>
<img src="SCPCopied2.png">
<br>


<br>

<h3 style="font-size:25px;">Running On ieng6</h3>




<br>

<h3 style="font-size:25px;">Streamlining the Process</h3>
