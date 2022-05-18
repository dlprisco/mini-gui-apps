### mini gui applications

A collection of small desktop applications written in Python
using the PyQt framework. These apps are intended as examples from
which you can poke, hack and prod your way to writing your own tools.

> Many of these apps have more detailed write-ups on my PyQt5/PySide2 site at [LearnPyQt.com](https://www.learnpyqt.com/apps/).
If you're new to creating GUI apps check out the introductory [pyqt5 tutorial](https://www.learnpyqt.com/courses/start/).

## The apps

The apps showcase various parts of the Qt framework, including advanced widgets,
multimedia, graphics views and decorationless windows. However, the most
generally interesting/feature complete applications are Minesweeper, Solitaire
and Paint.

1. [Web Browser (untabbed)](browser/) MooseAche 
1. [Web Browser (tabbed)](browser_tabbed/) 
1. **[Minesweeper](minesweeper/)  "Moonsweeper"**
1. [Calculator](calculator/) (QtDesigner)
1. [Media Player](mediaplayer/) 

#### Getting started

To use each app you first need to install the requirements. In most cases
the only requirements are PyQt5, and occasionally requests. To install
app-specific requirements change to the folder of the app and run:

    pip3 install -r requirements.txt
    
Once the requirements are installed, you can run the app using Python 3.

    python3 <filename>.py
 
The application window should appear.

<br> 
