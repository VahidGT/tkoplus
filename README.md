A package for Windows 11 users who use the Tkinter framework.
With the help of this package, you will be able to change the title bar color of your software in Windows 11.

To receive the package:

     pip install tkoplus

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
     
Also, if needed, each drawing can be placed in the variable and configured at the right time.

     from tkoplus import wind11
     draw_master1 = wind11.titlebar.title(master,color="cyan")
     draw_master1.draw()

     def select(colorname):
          draw_master1.config(color=colorname)
          
     select("red")

*Note that this package is only applicable on Windows 11 and Python 3.11+
