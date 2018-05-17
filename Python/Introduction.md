
Introduction

Anaconda Distribution is a package manager and a Python distribution; it contains an open-source web application called Jupyter Notebook which allows one to create and share “notebooks” or documents that contain Python code. Python is an object-oriented programming language usually used for general-purpose programming. It can be used for web-development, scientific and mathematical computing, and graphical user interfaces or GUIs. The language and syntax of Python allows for the building of clear and easy-to understand programs that are usually more concise in number of lines of code than Java or C++.

Installation
 Anaconda Distribution can be downloaded at: https://www.anaconda.com/download/. You want to download the Python 3.6 version!

 In order to download Anaconda Distribution for either your Windows computer or your Mac computer, you want to pick the desired symbol at the top of the download page where it says “Download For: “.
 
 
 P.1 Choose the symbol that fits the version of your computer

Once you have chosen which installer you need for your specific computer, you should open the downloaded installer and follow the various steps that are issued for you.
 
Once you have installed Anaconda-Navigator on your system, your application should open to a screen that looks like the design below. We will be utilizing the Jupyter notebook application of Anaconda for our work in this class.


 P.2 We will be using the Jupyter Notebook aspect (top-left box) of Anaconda!
 
Using Jupyter Notebook and Running Code!
Upon opening Anaconda-Navigator, you should “Launch” the Jupyter Notebook application. A pop-up will open on the bottom of the screen, warning you that the manager is “Launching notebook”.
        	
Once Jupyter Notebook has been launched, a terminal window will open. You should allow the terminal window to run its output until a URL is typed in the window.

   P.3 Terminal window that will open upon launching Jupyter Notebook-- you want to copy the URL that is found near the bottom of the window. 
   
Then, you should copy and paste the URL typed onto the screen into a web browser (Safari, Chrome, etc.). The screen below should appear!

P.4 This is the web page that appears upon pasting the URL from the terminal window into your browser
 
This URL will give you access to various files, where you can store your Python programs.
 
In order to start writing some code, you want to click on the file named “AnacondaProjects” and click the “New” drop-down button in the top right of the screen. AnacondaProjects is where you want to store all of your Python programs, so they can be easily accessible! Also, you want to make sure to title your programs accordingly, so you can quickly know which program you want to use. 

Then, you want to click on “Python 3” under “Notebook:”, which will open a new tab that has a screen with a line of code starting with “In [ ]:”. This is where you will write your Python code!! You can title the program by clicking on where it says “Untitled” or you can click on “File” and then “Rename…” to change the name of the notebook.

P.5 When you create a new notebook, it will bring you to this screen, where you can start your coding!

Hello, World!

This will be a walk-through tutorial for how to write a simple program that prints out “Hello, World!”. After following the steps written above, you are going to write in the box next to where it states “In [  ]: “.

In order to print a variable in Python, we first need to instantiate it. In Python, you don’t have to declare the type of the variable unlike in Java, where you would have to declare a word as a String variable before printing it out. Therefore, we just have to type a name for the variable such as “word” and set it equal to the word we want printed which in this case is “Hello, World!”.
 
P.5 First step in printing out “Hello, World!” is instantiating a new variable

Once a variable is instantiated, we can print out the variable by typing “print(“ + the name of the variable + “)”. That’s it! There is no semi-colon needed to end the statement unlike in Java.
 
P.6 Once you’ve declared a variable, you can write a print statement for it!

Now, we just have to run the lines of code! In order to do this, you want to press on the button at the top of the screen named “Cell”. Then, you should press “Run Cells” and the code will hopefully be outputted to the window. If there is an error, the system will let you know, so it can be fixed.
 
In this case, “Hello, World!” is outputted to the screen below the lines of code, and we have created a successful program!
 
P.7 Running your Python code in Jupyter Notebook

Style Tips for Python

If you want to create a new line in your code, you can simply type “print()” which will act as a line break and create a space/tab between the various print() statements.
 
Also, comments are a great addition to your code, in order to keep it organized and clean! They can act as reminders to you of what you want your code to accomplish, and they are especially beneficial to any collaborators who might be working on your code, so they can understand your thought processes. In Python, you can make a comment by starting a line with the “#” symbol and then typing whatever you want to convey to yourself or a collaborator following it. If you want to write a multi-lined comment, you should start and end the comment with three quotation marks as such “ ‘’’ “. 
 
Make sure you save your code by clicking on “File” and then “Save and Checkpoint” before exiting the application! Check-pointing the program is very beneficial, because you can revert to a checkpoint if any mistakes are made or any code is lost. Once your program is saved, you can exit the terminal window and the Anaconda application. 
