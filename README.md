# Using-Tools-on-Executables

Homework objectives:

Learn how to use debugging tools to inspect executables (this is useful for both debugging and reverse engineering)
Learn how to build and link a shared library
The Challenge!

In the last homework you looked at the symbol table of your own compiled program. This time we’ll be watching and interacting with precompiled programs as they execute.  You will use gdb, ltrace, and strace for this.

Go to https://classroom.github.com/assignment-invitations/e5969f2722a13036015723042fb3c026 to create your github repository.

Your task will be to fill out two files in your personal repository called secrets.txt and howto.txt.

The format for secrets.txt should be:

      0. these
       1. are
       2. not
       3. real
       4. secrets  
howto.txt is also required: you must describe in English how to find the secret for that given executable. Each individual howto should be on one more more lines after a line with only the executable number and a period on it, like so:

      0. 
          This was the really easy one. You had to run it and then type in the secret of life.
      
          1. 
          For this one, I had to:
        * Run a specific           unix utility to learn some specific information
        * Perform some specific task that I found out about by checking part of a specific line in the
           output of the           unix utility.   ... 
Your howto.txt should enable any other CS 361 student to find the password within a minute of reading it.

Hints:

Open your howto.txt alongside your shell as you work on each puzzle, and use it to take notes. If you don’t give a full description of how to arrive at the answer, you may not receive points.

The content of lab section will be incredibly helpful for this assignment. If you miss it, ask someone that went if they’re willing to share their notes with you.

Template

All binaries will be provided when you create your repository.  We are not providing any testing this time - if you get the programs to print out their secrets, it's correct!
