Python On Command-Line Installation
=======================================

Windows
---------------
* Installing Python3
    * Open a command prompt and type ``python3``
    * Once it opens the Microsoft Store, install Python 3.9
    * After this completes, retype ``python3`` in the command prompt. It should run the interactive environment, which you can exit by typing ``exit()``
* Navigating the Command-Line Interface
    * Your command prompt is (sort of) like a text-only version of the file explorer. You can navigate from your current folder to another using ``cd folder_name`` where folder_name is replaced with the name of the folder you're going to. To leave the folder you're in currently, use '..' as folder_name. e.g:

        .. code:: bash

            cd C:\Users\Matthew
            mkdir Programming
            cd Programming

        This will change the command prompt to the folder "C:\Users\Matthew", and create the folder "Programming" and then enter it. You may want to create a folder called "CMPM146" inside of the Programming folder.

    * Once you're in the right place, it's time to get the project files in your folder.
* Download the P1 folder from Canvas
    * Under 'Files', you will see "CM146 Syllabus Fall 2021.pdf", and "P1". Instead of entering P1, just click on the three vertical dots on the far right side and click "Download". This will download the project as a .zip, and you can drop the contents into your C:\Users\<your name>\Programming\...\P1 folder.
* Testing the code
    * In your command prompt, you can type ``dir`` to make sure you now see the project files. If you don't, you may need to use ``cd`` to get into the right directory.
    * Once you're certain that the command prompt is in the right place, try ``python3 src\nm_interactive.py``. If it works correctly, you will see a line printed starting with "usage: " which means that everything works, but the program was executed incorrectly.
    * To run the program correctly, try ``python3 src\nm_interactive.py input\homer.gif input\homer.gif.mesh.pickle 2``, which should open a little "tk" visual of the homer gif.
    * Also attempt to run ``python3 src\nm_meshbuilder.py input\homer.png``. It should result in an error along the lines of "ModuleNotFound: matplotlib". To fix this, type ``pip3 install matplotlib``, which will install the correct libraries, and then try running meshbuilder again.
* Editing the code
    * If you have Visual Studio Code installed, you can type ``code src`` which will start Visual Studio Code in the src folder. If you're using another program, you may be able to try running it from the command line, but your mileage may vary.
* Final notes
    * The benefits of running all of this in the command line are
        * Easier to follow what Alex is doing in the end-of-class tutorials
        * Easier to run different python commands with new arguments (you can easily change around what input file you're using, etc)
        * You look like a hacker B)

MacOS
---------------

* Installing Python3
    * Open the terminal and type ``python3 --version``
    * If you get an error message, go to https://python.org and Download Python 3.9 for MacOS there. 
    * After this completes, retype ``python3 --version`` in the terminal. It should state your working Python version.
* Navigating the Terminal Interface
    * Your terminal is (sort of) like a text-only version of Finder. You can navigate from your current folder to another using ``cd folder_name`` where folder_name is replaced with the name of the folder you're going to. To leave the folder you're in currently, use '..' as folder_name. e.g:

        .. code:: bash

            pwd
            ls
            mkdir test_folder
            ls
            cd test_folder
            ls
            pwd
            cd ..
            rmdir test_folder
            ls

        ``pwd`` will state what your current directory is. ``ls`` will tell you all the files in your current folder. ``mkdir <x>`` will create a new directory with the name specified as <x>. The order of commands are: 
        * tell me where I am
        * tell me what I can see
        * make a folder called "test_folder"
        * tell me what I can see (hopefully we can now see "test_folder")
        * go into test_folder
        * tell me what I see
        * tell me where I am
        * take me out of the test_folder
        * delete test_folder
        * and now tell me what I see one final time.
    * Now that you have a bit of an idea how the terminal works, make a folder called "CMPM146" and go into it.
    * Once you're in the right place, it's time to get the project files in your folder.
* Download the P1 folder from Canvas
    * Under 'Files', you will see "CM146 Syllabus Fall 2021.pdf", and "P1". Instead of entering P1, just click on the three vertical dots on the far right side and click "Download". This will download the project as a .zip, and you can drop the contents into your CMPM146 folder.
* Testing the code
    * In your command prompt, you can type ``ls`` to make sure you now see the project files. If you don't, you may need to use ``cd`` to get into the right directory.
    * Once you're certain that the command prompt is in the right place, try ``python3 src/nm_interactive.py``. If it works correctly, you will see a line printed starting with "usage: " which means that everything works, but the program was executed incorrectly.
    * To run the program correctly, try ``python3 src/nm_interactive.py input/homer.gif input/homer.gif.mesh.pickle 2``, which should open a little "tk" visual of the homer gif.
    * If you don't see the tk visual, and instead see "ModuleNotFound: tkinter", then try ``pip3 install tk`` and then try again.
    * Also attempt to run ``python3 src\nm_meshbuilder.py input\homer.png``. It should result in an error along the lines of "ModuleNotFound: matplotlib". To fix this, type ``pip3 install matplotlib``, which will install the correct libraries, and then try running meshbuilder again.
* Editing the code
    * If you have Visual Studio Code installed, you can type ``code src`` which will start Visual Studio Code in the src folder. If you're using another program, you may be able to try running it from the command line, but your mileage may vary.
* Final notes
    * The benefits of running all of this in the command line are
        * Easier to follow what Alex is doing in the end-of-class tutorials
        * Easier to run different python commands with new arguments (you can easily change around what input file you're using, etc)
        * You look like a hacker B)