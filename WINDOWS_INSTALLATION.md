## Running the uARMSolver under Windows

To successfully run the uARMSolver under Windows we recommend following these next short steps:
1.	Since we need to run makefile, we first need functionality similar to Linux distribution on the Windows OS. We recommend using Cygwin for that purpose.
2.	Go to https://www.cygwin.com/ and download installation file.
3.	Begin installation of Cygwin, during which you will get the chance to choose from the list of packages that can also be installed. We highly recommend installing the packages related to: c++, gcc, g++, gdb and make (you can use the search tool inside the package installation manager or go manually through the Devel category to find them). Note: if you find the need to install additional packages later on, you can do that by re-running the Cygwin installation file (Cygwin doesn’t incorporate self-standing packet manager).
4.	Go to the Cygwin installation folder, open home folder and then the folder with your name and surname (usually found at C:\cygwin64\home\Name Surname), which was already created there during installation of Cygwin. This is the place where you need to copy the uARMSolver-master.
5.	Run Cygwin64 terminal (quickly accessed from the Windows search tool).
6.	In the Cygwin64 terminal position yourself (use cd command) inside the main uARMSolver-master folder.
7.	Run make.

Important note: when changing settings file (e.g. arm.set found in uARMSolver-master\bin), only use Notepad (WordPad and other programs will almost certainly change the coding table of the file and executing make command will not go through anymore). 
