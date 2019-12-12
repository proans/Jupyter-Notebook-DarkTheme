# Jupyter-Notebook-DarkTheme
Jupyter Notebook DarkTheme With Toggle Toolbar
----------------------------------------------------

You can use the "-T" flag to enable the toolbar.
jt -t gruvboxd -T

# gruvboxd ---> Theme Name i.e. (jt -t onedork -T)
______________
Available Themes:
______________
   chesterish
   grade3
   gruvboxd
   gruvboxl
   monokai
   oceans16
   onedork
   solarizedd
   solarizedl
 ______________
 ------------------------------------------------
# make sure you have the latest version installed (pip install --upgrade jupyterthemes) and try jt -t grade3 -T
 ------------------------------------------------
 
* if you've uninstalled jupyterthemes and cannot see the toolbar, try clicking the 'View' dropdown menu in a notebook and then 'Toggle Toolbar'.

* If that doesn't work, then try reinstalling jupyterthemes, then reset to the default UI
jt -r (if still not fixed, try step 1 again after running the reset command)

* If you're still toolbar-less, then try installing a theme with the toolbar toggled on jt -t grade 3 -T (then steps 2 and 1)
