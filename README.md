# ACOS Apps
A repository containing all the available ACOS softwares.

## What is it ?
This repository is used by the ACOS app browser to let you download and install apps for the ACOS.

## How do I download apps ?
There are multiple ways of doing it.

### Downloading from App Browser
Simply go in the App Browser app on the ACOS, select the app you want, and click the "*Download*" button.

### Downloading from the `app_adder` script
Run the `app_adder.py` script.

Then, you can just select to *Install an app*, type in the name of the app you want to install, and here you go !

### Downloading manually the zip for the `app_adder` script
Download the ZIP of the software you want to install.

Run the `app_adder.py` script.

Select the *Install local app* button. Then, browse your files and look for the ZIP you downloaded. Double-click on it.

Your app is now installed !

### Downloading manually the zip and installing it manually
Download the ZIP of the software you want to install.

Go in your ACOS folder, then to `ROOT`, and you should find the `softwares` folder.

Paste the ZIP here, and extract it in place.

A new folder containing at least a Python file with the same name as the folder should appear.

## Uninstalling an app
### Uninstalling automatically, from the App Browser
Go in the *Installed apps* section in the app browser.

Find the app you want to uninstall, and click the *Uninstall* button.

### Uninstall from the `app_adder` script
Run the `app_adder.py` script.

Click on the *Uninstall an app* button.

Select the app you want to uninstall, then press *Confirm uninstall*.

### Uninstalling manually
***This type of uninstall is not recommended.***

Go in your ACOS folder, then to `ROOT`, and you should find the `softwares` folder.

Delete the folder with the name of your app.

*If your app is in ANY taskbar* :
Find the `.userdata.json` file for each user, and in the key `taskbar`, remove the app you just remove.

***If you know nothing about JSON in general, I recommend not using this uninstall type.***

## Updating an app
Just uninstall and reinstall the app.

## How do I publish my app ?
You can submit apps on my [Discord server](https://discord.gg/MBuKcUn), or create a pull request for this repository.

## How do I create an app ?
See the wiki.
