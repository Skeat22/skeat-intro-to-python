# skeat-intro-to-python
Hello! This is my intro to python code repository that contains a few practical applications using python. All of which have come up from brainstorming needs with friends. Enjoy!



# Installing Python
Follow this link for a python setup how-to (there are tons, but this is the most recent good one I have found)
https://data-flair.training/blogs/install-python-windows/
Alternatively here are the big steps I would recommend:
1. visit https://www.python.org/downloads/ and find the download that best suits your system (windows vs. mac vs. linux)
2. Double click the download to begin installation. To get started, almost all the defaults should be fine except one thing you want to make sure to select the following on the first step of the installer (becomes very important for almost all python exercise/applications) ![Adding Python to path step ](/images/py-to-path.PNG)
3. At the end of the installation attempt to find & fire up python either by searching in the searchbar for pyhton, or better using your machine's terminal. On windows this is probably CMD. So search for that in on you machine like so: ![Finding CMD](/images/finding-cmd.PNG). Once you have CMD open (aka a terminal) type in the word 'python' and hit enter you should see results similar to mine between the first two red dots. Next ty typing the following **print('hello world!')** and you should see results like mine after the last red dot. and BOOM you just fired up a programming language, wrote & executed some code!


# Getting a Text Editor (I recommend and wil ldemonstrate getting VsCode)
Next you are gonna need a space to write your code and get to work. Often referred to as **Text Editors** or an **IDE** (Integrated Development Environment)
Best part, there are a ton of free ones out there! Woo-hoo for open-source!
Here is a link to where you can download VsCode: https://code.visualstudio.com/
Set up for this one should be as simple as downloading and running the installer

# Using python in VsCode

Once you have both Python & VsCode available on your machine, you should have all the basic tools you need to start experimenting & learning!
To replicate what we did earlier in the CMD terminal VsCode, all you have to do is open Vscode and create a new folder on your hard drive (i.e. **C:** typically for windows computers).
I recommend adding to extensions to your VsCode installation, you can look them up via the **Extensions** panel in VsCode (first circle)
![VsCode Extensions](/images/vscode-extensions.PNG).
The one's I recommend are the last 2 circled: 
- Python  (utlilties that make using python in VsCode even easier/efficient/productive)
- Jupyter (package that allows you to write python in an interactive way conducive to exploring the Python language as well as the data you are working with itself)

VsCode also has its own baked in terminal panels so that you do not have to search for **CMD** like we did earlier. 
You can open anew terminal like this: ![VsCode New Terminal](/images/vscode-new-terminal.PNG)

and you should end up with something like this: ![VsCode Example Terminal](/images/vscode-example-terminal.PNG)

Now try and do the same things we did in CMD earlier, but in this new nifty embedded terminal within your IDE (VsCode): ![VsCode Terminal Python](/images/vscode-terminal-py.PNG)

*Don't worry if terminals seem foreign and intimidating. At first they can seem intense since most things are so graphically based. But eventually as you exlore, practice, and learn it will become a lifeline thats really not as complicated as it presents!*

# Two code file types to start with
To begin exploration with python, there are two great types of files to begin with. 

1. **.py** files are the most basic files that contain python code. As you begin with, you can sort of think of this as your scripting file (eventually it can and will be much more than that but for startes that will help frame it against our other file type). For example a file could be **my_script.py** (you will see this file within this repository I have created as we will use it later)
2. **.ipynb** files are interactive pyhton files that work great with that **Jupyter** extension I suggested installing earlier during the VsCode setup. You can think of these files as your notebooks, scratch pads, exploration files. The biggest distinction from a **.py** script would be that these are useful for visualizations and being able to analyze your code in chunks as opposed to all of your code at once as you would in a **.py**

*Quick callout, python is an INTERPRETED language as opposed to a COMPILED language (good article --> https://www.geeksforgeeks.org/difference-between-compiled-and-interpreted-language/), this is a quick tutorial but ig you intend to spend time diving in you might want to begin reading up to begin to understand*

Go ahead and either use my folder (downloadable from this page), or create your own folde ron your computer in VsCode and place/create two files in it:
*Top: you can right click in VsCode and create a new file, naming it and giving it th eappropriate file extension like .py or .ipynb*
- my_script.py
- my_notebook.ipynb (this one will only work so that you can follow along  if you installed the **Jupyter** extension)

Here is what my workspace with VsCode looks like once I have created these two files (*I moved them into side-by-side panes by dragging them*): ![Skeat's Workspace](/images/workspace.PNG)

On the left is my python script file (i.e. **.py**) and on the right is my Jupyter Notebook for Python (i.e. **.ipynb**)

# Coming Soon....
- Exercise using Python to work with many spreadsheet files (i.e. .xlsx) that require cross referencing & other types of manipulation (If you want to explore ahead, I will be using this library to work with the files: https://towardsdatascience.com/a-quick-introduction-to-the-pandas-python-library-f1b678f34673,  https://pandas.pydata.org/pandas-docs/stable/user_guide/10min.html)

- Exercise using folders containing images to craft consolidated PDFs contianing said images
