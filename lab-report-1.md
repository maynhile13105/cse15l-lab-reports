**_CSE 15L - LAB REPORT 1_**
======================

Command: 'cd'
------------
1) _With no arguments_

  ![image](https://github.com/maynhile13105/cse15l-lab-reports/assets/146885739/72b49eb7-b0bc-4ad1-9b60-fdffe1658fe4)
- Before the command was run, the working directory was /home/lecture1. After the command was run, the working directory  was /home
- It means that when the command is run without any arguments, the system automatically defaults that the path users want to switch to is /home.
- There is no output after the command is executed but there is a little change in the part below the user's name to announce user knows where the working directory is.
- This is not an error.

2) _With a path to a directory as an argument_
   
   ![image](https://github.com/maynhile13105/cse15l-lab-reports/assets/146885739/b9c04828-aebf-44cd-9708-9d567998a03a)
- Before the command was run, the working directory was /home. After the command was run, the working directory was switched to /home/lecture1/messages.
- Similarly to the case of the command 'cd' with no arguments, there is nothing printed out after the command was executed. However, there is a little change in the part that goes after the user's name. 
This part announces to the user where the working directory is.
- This is not an error.

3) _With a path to a file as an argument_

   ![image](https://github.com/maynhile13105/cse15l-lab-reports/assets/146885739/a8398b21-fd6c-4955-94d3-2456a1d04a52)
   
- Before the command was run, the working directory was /home/lecture1. And it was not changed after the command was run.
- The output announced that the path we entered was not a directory. It is right because the path we entered was a path to a file, not a directory.
- This is not an error. The command ‘cd’ is used to change the directory but the path we passed as an argument was a path to a file. 
So, in this case, a new directory was not given so the working directory was not changed.



Command: 'ls'
-------------

1) _With no argument_

  ![image](https://github.com/maynhile13105/cse15l-lab-reports/assets/146885739/3eee7049-9415-49db-85be-32116eb26457)

  

2) _With a path to a directory as an argument_

  ![image](https://github.com/maynhile13105/cse15l-lab-reports/assets/146885739/4ae1ae42-d0c3-473e-9937-948ed9c1976b)
  

3) _With a path to a file as an argument_

  ![image](https://github.com/maynhile13105/cse15l-lab-reports/assets/146885739/1ea70574-de92-4363-be9e-0e6e558f5398)


Command: 'cat'
-------------
This command is used to print out the content of files. 
1) _With no argument_

  ![image](https://github.com/maynhile13105/cse15l-lab-reports/assets/146885739/1b737300-e61c-4276-ada4-a218038487e0)

- The working directory was /home/lecture1/messages and it was not changed when the command was run.
- No arguments are passed means that no files are given, so right after the command was run, there was nothing happened or printed out. There was just a blank page.
- When we enter anything later, it doesn't matter if it's a command or not, the system will output exactly what we entered. And other commands after the command 'cd' without arguments will be treated as normal text.
  
  ![image](https://github.com/maynhile13105/cse15l-lab-reports/assets/146885739/513434ed-fa62-408d-8495-3c7a671ee7f6)
- This is an error. Because 'cat' is the command used to print out the content of files. But no files were passed so it became a bug. This bug seems like a loop and it just ends when we use the key ‘Ctrl’+ ‘C’.

2) _With a path to a directory as an argument_

  ![image](https://github.com/maynhile13105/cse15l-lab-reports/assets/146885739/83995680-6e3b-4174-a019-40137ab2fcac)
- The working directory was /home and it was not changed when the command was executed.
- The path we passed was a directory, so after the command was run, we received an output announcing that the path we passed was a directory. As the figure above shows.
- This is not an error. 

3) _With a path to a file as an argument_

  ![image](https://github.com/maynhile13105/cse15l-lab-reports/assets/146885739/48ffbe71-ed9c-4638-8494-7dce6ce7d877)
- The working directory was /home/lecture1.
- Since the command 'cat' prints out all content in files and is not used to run a file. So, what we get is all the text contained in the README file. It is accurate down to every mark and line break. 
- This is not an error.
     



