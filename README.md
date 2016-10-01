build c enviromnet on windows 10
============
notepad++ and MinGW
-----------
1. [Download MinGW tools](https://sourceforge.net/projects/mingw/files/)
2. install with all options
3. Add bin directory in MinGW directory  (e.g., d:\MinGW\bin) to  path enviromnet variable
4. verify c++ enviromnet     
open windows common ,input    
gcc -version    
if you see version information,then installing for mingw finished.    
5. [Download notepad++](https://notepad-plus-plus.org/)   
Notepad++ is a free source code editor and Notepad replacement that supports several languages.
6. open notepad++
7. new a file with  name "test.c".  
example:  
~~~~~~
  #include <stdio.h>    
  int main(){   
    putc("hello world");    
  }   
~~~~~~~
save to local drive   
8. open windows command    
enter the dictionary in which c file save   
input gcc -o test.c && test   
done
visual studio 2015
-------------------
1. new project->Visual c++ ->Win32 console application
2.  select empty project and uncheck safe develpment life (SDL)check on options in applicatin setup page.
3. mouse right button click on source file ,select add ->new item->select c++ file(.cpp) then change name test.c then click add button
4. edit test.c using given example.
5. click run
If it complie error,then add comment(#pragma warning(disable:4996)) to first line in source file  
6. done

eclipse c++
-------------------
eclipse may run on linux system.      
1. download eclipse  
2. Unpack   
3. run eclipse.exe  
4. done   
add version control 
--------------
1. open https://github.com/
2. login in 
3. build new project on github.com
3. download [git](https://git-scm.com/) and install
4. download [tortoisegit](https://tortoisegit.org/) and install
5. build new file dictionary with name "projects" on local drive
6. right mouse click on this file select "git clone",input your project's url on github.com
7. add or move your project to this dictionary
8. sync  mean sync between github.com and local
9. commit mean add file to local version.
10. push mean push fiels on local to github.com
10. pull mean pull files on github.com to local








