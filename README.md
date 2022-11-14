<h1> 0x16. C - Simple Shell</h1>
<p>This is a simple UNIX command interpreter<img src="https://s3.amazonaws.com/intranet-projects-files/holbertonschool-low_level_programming/235/shell.jpeg" alt="Shell"></p>

<h3>Compilation</h3>

<p>How Our Shell is compiled:</p>

<pre><code>gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hsh </code></pre>

<h3>Our Shell in modes:</h3>



<p>in interactive mode:</p>



<pre><code>$ ./hsh

($) /bin/ls
AUTHORS  built-ins.c  helper.c  hsh  man_simple_shell  path.c  README.md  shell.c  shell.h  str.c

($)

($) exit

$

</code></pre>

<p>But also in non-interactive mode:</p>



<pre><code>$ echo &quot;/bin/ls&quot; | ./hsh

AUTHORS  built-ins.c  helper.c  hsh  man_simple_shell  path.c  README.md  shell.c  shell.h  str.c

$

$ cat AUTHORS
# This file lists all individuals who contributed to the repository                                                                     

                                                                                                                                        

Ashley John <nightburn2003@gmail.com>                                                                                                   

Princess Nnaji <princessamphora@gmail.com>     
$
</code></pre>

<h4>List of helpful commands</h4>
<ul>
<li><pre><code>cat</code></pre> -  prints and concatenates files to the standard output</li>
<li><pre><code>ls</code></pre> - will list all files and directories in current working directory</li>
<li><pre><code>cp</code></pre> - copies a file into another file</li>
<li><pre><code>grep</code></pre> - helps to search for a file in a specific pattern</li>
<li><pre><code>less</code></pre> - will let you go backward and forward in the files</li>
<li><pre><code>pwd</code></pre> - given you the current working directory
<li><pre><code>mv</code></pre> -  helps to move one file into another file
</ul>

<h4>Exiting the Shell</h4>
<p><pre><code>exit</code></pre>To quit the shell the user can simple type in "exit"</p>
