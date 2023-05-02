Download Link: https://assignmentchef.com/product/solved-cloud-computing-lab-2-basic-interface-and-programming
<br>
<h2>Lab 2: Bash Programming</h2>

Dear Script Programming Newbees

<ul>

 <li>I think the Docker experiment starts to exhaust your strength and intellect on finding a good solution</li>

 <li>Now you need to do more for your work</li>

 <li>When you start coding, basically you are bashing Perquisite: you installed VM with a Linux-kernel system • Help docs for bashing:</li>

 <li><a href="https://devhints.io/bash">https://devhints.io/bash</a></li>

 <li><a href="https://linuxconfig.org/bash-scripting-tutorial-for-beginners">https://linuxconfig.org/bash</a><a href="https://linuxconfig.org/bash-scripting-tutorial-for-beginners">–</a><a href="https://linuxconfig.org/bash-scripting-tutorial-for-beginners">scripting</a><a href="https://linuxconfig.org/bash-scripting-tutorial-for-beginners">–</a><a href="https://linuxconfig.org/bash-scripting-tutorial-for-beginners">tutorial</a><a href="https://linuxconfig.org/bash-scripting-tutorial-for-beginners">–</a><a href="https://linuxconfig.org/bash-scripting-tutorial-for-beginners">for</a><a href="https://linuxconfig.org/bash-scripting-tutorial-for-beginners">–</a><a href="https://linuxconfig.org/bash-scripting-tutorial-for-beginners">beginners</a></li>

 <li>Our course has established a well-defined relationship with Baidu Inc. and Google Inc. For any of your questions, you can use their service to find out</li>

</ul>

<h2>Goal for Lab 2</h2>

<ul>

 <li>Objectives:</li>

 <li>To write shell scripts to solve problems</li>

 <li>To implement some standard Linux-kernel utilities such as ls,cp,etc using system calls.</li>

 <li>Understanding the idea of multi-programming (or multiplexing) and threading</li>

 <li>Learn to read an English poem</li>

 <li>Learn to read instructions, carefully</li>

 <li>Write a decent report</li>

</ul>

<h2>Use Bash for Shell scripts</h2>

<ol>

 <li>Write a Shell script that accepts a filename, starting and ending line numbers as arguments and displays all the lines between the given line numbers.</li>

 <li>Write a Shell script that deletes all lines containing a specified word in one or more files supplied as arguments to it.</li>

 <li>Write a Shell script that displays list of all the files in the current directory to which the user has read, Write and execute permissions.</li>

 <li>Write a Shell script that receives any number of file names as arguments checks if every argument supplied is a file or a directory and reports accordingly. Whenever the argument is a file, the number of lines on it is also reported.</li>

 <li>Write a Shell script that accepts a list of file names as its arguments, counts and reports the occurrence of each word that is present in the first argument file on other argument files.</li>

 <li>Write a Shell script to list all of the directory files in a directory</li>

 <li>Write a Shell script to find factorial of a given integer.</li>

</ol>

<h2>File to use in your Test Linux Poem: The Reentrant Kernel</h2>

By Morgan Phillips

<table width="738">

 <tbody>

  <tr>

   <td width="738">A reentrant function, if interrupted,will return a result,which is not perturbed.int global_int;int is_not_reentrant(int x) { int x = x; return global_int + x; },depends on a global variable,which may change during execution.int global_int;int is_reentrant(int x) { int saved = global_int; return saved + x; },mitigates external dependency,it is reentrant, though not thread safe.</td>

  </tr>

 </tbody>

</table>

Save the poem as your text file

<h2>Now to Show it Off</h2>

<ul>

 <li>Instead of running basic bash coding solely, you need to <em>exec </em>it</li>

 <li>You need to write a control script (i.e., script for script) that execute all your previous bash code one by one in a certain order</li>

 <li>You need to append this piece of code to your report, as well as screen shot of running this code</li>

 <li>HINTS: bash allows multiplexing in executing certain codes, the specific cmd to run it is hidden in this page.</li>

</ul>