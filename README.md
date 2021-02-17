# odtconfigurations
Collection of configuration XML files for the Office Deployment Tool

How to use:
Install the Office Deployment Tool (ODT): https://www.microsoft.com/en-us/download/details.aspx?id=49117

This should create a C:\ODT directory.  Place the XML file that matches your license in this directory.  

Right-click and 'Edit' the XML file.  Replace the PIDKEY with your Product/MAK Key and save.

Open a CMD as an administrator and navigate to C:\ODT.

To download the full installer (if you've never done this before), run this (substituting <configuration.xml> with the filename of your configuration file)

setup /download <configuration.xml>

Once the installer has downloaded (or if you've already downloaded the exact version before and have copied it into the ODT folder), run:

setup /configure <configuration.xml>

Descriptions of XML files:

Install Office 2019 Professional Plus x64 English Volume License = office2019proplusen64vol.xml

Install Office 2019 Standard x64 English Volume License = office2019standarden64vol.xml

Remove Office 365 Click-To-Run for languages en-us, es-es-, fr-fr (often preloaded on Windows 10) = remove.xml
