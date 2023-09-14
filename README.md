A package for Windows 11 users who use the Tkinter framework.
With the help of this package, you will be able to change the title bar color of your software in Windows 11.

To change the color of the toolbar:

     from tkoplus import wind11
     wind11.titlebar.bg(master,color="cyan").draw()
     
To change the color of the text in the title bar:
     
     from tkoplus import wind11
     wind11.titlebar.title(master,color="cyan").draw()

Note that color codes cannot be used in the "color" field.

To display the available colors in tkoplus:

     from tkoplus import colors
     print(colors)

To receive the package:

     pip install tkoplus

*Note that this package is only applicable on Windows 11 and Python 3.11+
