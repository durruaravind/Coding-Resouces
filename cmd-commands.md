# Change colors
You can change color using the following command in cmd. 

color <color-code>

# The following command will give you a list of all the colors you can use in cmd:
help color

# The following command will change the color of the terminal:
color 04

# Change the Prompt in CMD
You can change the prompt text in the cmd using the following command:

prompt harry@hacker$G

Here $G is a special character for the '>' symbol

# Use the following command to learn about more special characters you can use with prompt command
help prompt

# Change Title in CMD
title Hacking in progress...

# Hide a Folder
Attrib +h +s +r foldername

Once your folder is hidden, you can unhide by firing the following command:

Attrib -h -s -r foldername

# Copy Output to Clipboard
ipconfig | clip

# CMD Command History Shortcuts
You can use f7 key to see your command history in the prompt. 

# Create a Folder with reserved names (Like aux, con, etc.) 
Do you know that you cannot create a folder named aux or con in windows?

These are the reserved names that windows use for internal purposes.

You can still create a folder named con or aux by firing the following command in cmd:

md con\

md aux\ 

# View all the installed programs on your PC
You can view all the installed programs on your pc by firing the following command:

wmic product get name

# Command to open default code editor (vscode):
code .

# To know the password of connected wifi type in CMD:
netsh wlan show profile name = <Wifi Name> key = clear

# PC battery report using cmd
C:\WINDOWS\system32>powercfg /batteryreport /output "C:\battery-report.html"

Battery life report saved to file path C:\battery-report.html.
