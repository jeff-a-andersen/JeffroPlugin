# Overview

The Jeffro Tools Suite is an Eclipse plug-in that provides useful utilities to the users.  Once installed, you will see a new toolbar in Eclipse that looks like this:

 ![Alt text](readme_images/Toolbar.png?raw=true "Jeffro Plugin Toolbar")

The functionality provided by each button can be found below.

# Jeffro Plugin Preferences

![Alt text](readme_images/Me.ico?raw=true "Jeffro Plugin Preferences")

This button launches the Eclipse preference page for the plugin.

![Alt text](readme_images/PreferencesWindow.png?raw=true "Preference Window")

 
| Preference | Description | Used By |
| --- | --- | --- |
| Wildfly Root | Contains the root path of your Wildfly installation. | ![Alt text](readme_images/wildfly-configuration.ico?raw=true "Wildfly configuration Directory") ![Alt text](readme_images/wildfly-deployments.ico?raw=true "Wildfly deployments Directory") ![Alt text](readme_images/wildfly-standalone.ico?raw=true "Wildfly standalone Directory") ![Alt text](readme_images/wildfly-standalone-file.ico?raw=true "Wildfly standalone.xml File")|
| Wildfly Clean Script | Contains the path of your script file for deep cleaning Wildfly. | ![Alt text](readme_images/wildfly-clean.ico?raw=true "Wildfly Deep Clean")|
| Backup Utility | Contains the path to your backup utility (if you have one you want to use). | ![Alt text](readme_images/backup.ico?raw=true "Backup Utility")|


# Wildfly Deep Clean

![Alt text](readme_images/wildfly-clean.ico?raw=true "Wildfly Deep Clean")

The Wildfly Deep Clean button is used to launch your local clean script for deep cleaning Wildfly.

If you haven&#39;t defined the location of the local script file yet, clicking the button will result in an error indicating the preference hasn&#39;t been set and, after clicking Ok, opens the Jeffro Plugin Preferences dialog.

# Wildfly configuration Directory

![Alt text](readme_images/wildfly-configuration.ico?raw=true "Wildfly configuration Directory")

This &quot;Wildfly configuration Directory&quot; button will open your configuration directory in Windows File Explorer.

If you haven&#39;t defined the location of the Wildfly root, clicking the button will result in an error indicating the preference hasn&#39;t been set and, after clicking Ok, opens the Jeffro Plugin Preferences dialog.

# Wildfly deployment Directory

![Alt text](readme_images/wildfly-deployments.ico?raw=true "Wildfly deployments Directory")

This &quot;Wildfly deployment Directory&quot; button will open your deployment directory in Windows File Explorer.

If you haven&#39;t defined the location of the Wildfly root, clicking the button will result in an error indicating the preference hasn&#39;t been set and, after clicking Ok, opens the Jeffro Plugin Preferences dialog.

# Wildfly standalone Directory

![Alt text](readme_images/wildfly-standalone.ico?raw=true "Wildfly standalone Directory")

This &quot;Wildfly standalone Directory&quot; button will open your standalone directory in Windows File Explorer.

If you haven&#39;t defined the location of the Wildfly root, clicking the button will result in an error indicating the preference hasn&#39;t been set and, after clicking Ok, opens the Jeffro Plugin Preferences dialog.

# Wildfly &quot;standalone.xml&quot; File

![Alt text](readme_images/wildfly-standalone-file.ico?raw=true "Wildfly standalone File")

The &quot;Wildfly &#39;Standalone.xml&#39; File&quot; button will open your standalone.xml file in the Eclipse XML editor.

If you haven&#39;t defined the location of the Wildfly root, clicking the button will result in an error indicating the preference hasn&#39;t been set and, after clicking Ok, opens the Jeffro Plugin Preferences dialog.

# Backup Utility

![Alt text](readme_images/backup.ico?raw=true "Backup Utility")

The &quot;Backup Utility&quot; button will open the backup utility that you&#39;ve defined.

If you haven&#39;t defined the location of the backup utility, clicking the button will result in an error indicating the preference hasn&#39;t been set and, after clicking Ok, opens the Jeffro Plugin Preferences dialog.

# Open Eclipse Workspace Directory

![Alt text](readme_images/eclipse-workspace.ico?raw=true "Open Eclipse Workspace Directory")

The &quot;Open Eclipse Workspace Directory&quot; button will open your current workspace in Windows File Explorer.

# Installing

To install the plugin, simply use the following update site:

[https://raw.githubusercontent.com/jeff-a-andersen/JeffroPlugin/master/JeffroUpdateSite](https://raw.githubusercontent.com/jeff-a-andersen/JeffroPlugin/master/JeffroUpdateSite)

NOTE: You will get a 404 error if you attempt to load the URL above into your browser.  It will still work in Eclipse as depicted below:

![Alt text](readme_images/UpdateSite.png?raw=true "Update Site Preference")