Jupyterhub basic usage
======================

Logging into Jupyterhub
-----------------------
  - If you already have a FEIDE account, you should've receive an email with the invitation link to `eScience2024` group
  - Follow the link in the email
  - Accept the policies and agree to become a member of the `eScience2024` group
  - Now go to [eScience2024 Jupyterhub](https://escience2024.craas1.sigma2.no)
  - Log in with your Feide account 
  - You should be able to see Jupyterhub within your browser



Starting and stopping your server
---------------------------------

Your Jupyterhub tab should have the following panels:


To start/stop your server, click "**File** --> **Hub Control Panel**":

When your server is not running, the button "Stop My Server" does not appear and you only see the button "My Server".

- To stop your server, click on "Stop My Server"
- To start your server, click on "My Server"

.. Warning ::

  Don't forget to "**Stop My Server**" after you are done to free resources



The JupyterLab Interface
------------------------
By default, you will get the web-based user interface for Project Jupyter that is called [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/).

Menu Bar
--------

The menu bar at the top of JupyterLab has top-level menus that expose actions available in JupyterLab with 
their keyboard shortcuts. The default menus are:

- **File**: actions related to files and directories
- **Edit**: actions related to editing documents and other activities
- **View**: actions that alter the appearance of JupyterLab
- **Run**: actions for running code in different activities such as notebooks and code consoles
- **Kernel**: actions for managing kernels, which are separate processes for running code
- **Tabs**: a list of the open documents and activities in the dock panel
- **Settings**: common settings and an advanced settings editor
- **Help**: a list of JupyterLab and kernel help links

Left Sidebar
------------

The left sidebar contains a number of commonly-used tabs, such as a file browser, a list of running 
kernels and terminals, the command palette, and a list of tabs in the main work area:



If you move your mouse on the other icon of this left sidebar, a short information is given on its functionality.

If you click on the "stop button" icon, you can see what is currently running on your server and you can click on 
"SHUT DOWN" to stop a running Python notebook or Terminal.

### Start a new Terminal

Similarly, you can start a new Terminal by clicking on "Terminal" in the Launcher. 


Tips
----
 If the **Launcher** tab does not exist 
 anymore in your JupyterLab, you can start a new one in "**File** --> **New Launcher**".



Create a new python 3 notebook
------------------------------

Go back to the **File Browser** left sidebar tab and in the launcher select **Python 3** under the Notebook 
section:


By default, your new notebook is named as "**Untitled.ipynb**":

- **ipynb** is the extension for any Jupyter notebook and you should make sure all your notebooks get this extension (otherwise it is not recognized as a Jupyter notebook)
- you can rename your jupyter notebook with the tab "File --> Rename Notebook..." or 
  right click on its name.