# SoleStormCatPY

SoleStormCatPY is an app developed to help you throughout your day. Here are some of the apps that are jam-packed into this Python Distribution Package!

(Not all scripts/apps are originaly from SoleStormCat Corp. Here is a list of apps that are effected, and includes a link to the original source:
1. [Standalone App](https://www.geeksforgeeks.org/python-menu-widget-in-tkinter/)
1. [ClockTimer and Standalone App](https://www.geeksforgeeks.org/creating-tabbed-widget-with-python-tkinter/) (FOR THE TAB FEATURE ONLY)
1. [Files](https://data-flair.training/blogs/python-file-explorer-project/) (THIS IS A MODIFED VERSION OF THE PROJECT)
1. [WebOpenGUI](https://stackoverflow.com/a/64363622) (For GUI Web Viewing Only)
)
## Instaling SoleStormCatPY
To install SoleStormCatPY, you can do either of the #:

1. Install from `pip`:
To install/upgrade from `pip`, go to your terminal and enter (for Linux/Mac) `python3 -m pip install --upgrade SoleStormCatPY` or (for Windows) `py -m pip install SoleStormCatPY`

2. Install from packages:
To install/upgrade `SoleStormCatPY` from the packages, you must download the package(s) from `dist`, and after setting your terminal to the location of the downloaded files, run (For Linux/Mac) `python3 -m pip install ./{File}` or (For Windows) `py -m pip install {Path To File}`.

3. Install from SoleStormCat Corp's installer file:
To install `SoleStormCatPY` from SoleStormCat Corp's provided installer, simply download the installer (found at `Releases/Python/Installer`), and run the `.py` file that was downloaded!

## MathSolver

"MathSolver" seems just like it sounds. A calculator. A boring old calculator. You've seen many apps (the even come built in to your device) that work like this, but "MathSolver" is made to help with your daily math needs. "MathSolver" can do math ranging from Multiplication, Division, Adding, and Subtracting!

### How To Use
To Run "MathSolver" in your script, make sure to specify `num1` (Being the first number), `num2` (being your second number), and `ty` (being the type of math you require), along with the command `SoleStormCatPY.MathSolver.numPrint(num1, num2, ty)`.

You may also run `SoleStormCatPY.MathSolver.numPrint('5','8','Divide')` when running MathSolver!

Have Fun Mathing!

## WebOpen

"WebOpen" is not as it might see. It's not a web browser, but a web browser opener! You enter the URL of the website you want (including `http://`), and you'll be sent to the website. And, you also get to put in names for specific websites that lead to them with only the name!

### The Two Types of "WebOpen"

Yes, there are three versions of "WebOpen"! There is "WebGUI" (With GUI), "WebCMD" (With No GUI, Just Terminal), and "WebCMDgui" (GUI window, opens via terminal script). Here are their differences!

WebGUI:
WebGUI opens in a `tkinter` window, allowing users to enter their URL into a user-friendly box! (Requires the `tkinter`, `PyQT5`, and `PyQTWebEngine` modules)

WebCMD:
WebCMD opens in the standard terminal window, this is great for opening a website the developer wants! (THIS WILL NOT WORK WITH `.pyw` FILES!) (Requires `webbrowser` module!) (Opens in user's default browser)

WebCMDgui:
WebCMDgui allows you to input the website in the script, while opening the window in a SoleStormCat-Scripted window! (Requires `PyQT5` and `PyQTWebEngine` modules) (Does not use a user-specified browser, uses SoleStormCat-Scripted browser!)

### How To Use
To Run "WebOpen" in your script, make sure to specify `website` (being the URL (or name in some cases)) (with WebGUI Being an exeption), along with the command `SoleStormCatPY.WebOpen.webCMD(website)` (For WebCMD. Requires `webbrowser`), `import SoleStormCatPY.WebOpen.WebGUI()` (For WebGUI. Requires `PyQt5`, `PyQtWebEngine` and `tkinter`) or `SoleStormCatPY.WebOpen.webCMDgui(website)` (For WebCMDgui. Requires `PyQt5` and `PyQtWebEngine`)
Have Fun Webbing!

### Websites With Names:
This meantions the certain websites that you can access by name. The Format for this is (Name of Website with clickable URL), (Name input into App). Both WebCMD and WebGUI support this!

1. [Amazon](https://amazon.com), "Amazon"
1. [Android](https://android.com), "Android"
1. [Apple](https://apple.com), "Apple"
1. [Google Bard](https://bard.google.com), "BardAI"
1. [Microsoft Bing](https://bing.com), "Bing"
1. [ChatGPT](https://chat.openai.com), "ChatGPT"
1. [ChunkBase](https://chunkbase.com), "ChunkBase"
1. [Ebay](https://ebay.com), "Ebay"
1. [Facebook](https://facebook.com), "Facebook"
1. [Nvidia GeForce Now](https://play.geforcenow.com), "GeForceNow"
1. [GitHub](https://github.com), "GitHub"
1. [GitHub Developer](https://github.dev), "GitHubDev"
1. [Google](https://google.com), "Google"
1. [Local-Hosted Website](http://127.0.0.1), "Local"
1. [Microsoft 365](https://microsoft365.com), "Microsoft 365"
1. [Minecraft](https://minecraft.net), "Minecraft"
1. [Netflix](https://netflix.com), "Netflix"
1. [PlayStation](https://playstation.com), "PlayStation"
1. [Proton](https://proton.me), "Proton"
1. [Python](https://python.org), "Python"
1. [Snapchat](https://web.snapchat.com), "Snapchat"
1. [SoleStormCatPY - GitHub](https://github.com/solestormcat-corp/solestormcatpy), "sscPY-GitHub"
1. [SoleStormCatPY - PyPi](https://pipy.org/solestormcat-corp/solestormcatpy), "sscPY-PyPi"
1. [Twitch](https://twitch.tv), "Twitch"
1. [Twitter](https://twitter.com), "Twitter"
1. [Roblox](https://roblox.com), "Roblox"
1. [Steam](https://store.steampowered.com), "Steam"
1. [Walmart](https://walmart.com), "Walmart"
1. [Xbox](https://xbox.com), "Xbox"
1. [Xbox Cloud Gaming](https://xbox.com/play), "XBCloud"
1. [Google Voice](https://voice.google.com), "GoogleVoice"
1. [YouTube](https://youtube.com), "YouTube"

## Terminal
"terminal" is a way to easily access the user's system default terminal. So, if you want to check for an update for your package, you could easily do that! There are also two versions of "terminal": "terminal" and "terminalGUI". Here is how you can tell which each is!

### Both "Terminal" Types
There are two types of "terminal" Here they are:
"terminal":
This is the default terminal runner. Everything is done within the terminal.

"terminalGUI":
This asks the user for a command within a `tkinter` GUI. The output will be printed in the real terminal. (Requires `tkinter` module)

### How To Use
To run "terminal" in your application, here is a way to use it. As per the example above, updating your package would require the `command` string, which holds your command that you are going to run (example: `command = 'pip install tkinter'`), along with `SoleStormCatPY.terminal.terminalrun(command)` (For "terminal), or run `import SoleStormCatPY.terminal.terminalGUI()` (For "terminalGUI", does NOT require `command`).
Have Fun Running commands via Python!

## System Info
This application prints out the user's infomation onto their terminal screen. Here is a basic output of this application:

`The Current User OS is:`
`Linux`

`The Current User is:`
`root`

`The Current Version of Python is:`
`Python 3.10.6`

`The Current Wifi is:`
`MyWifiNetwork`

### How To Use
Here is how you use "System Info":

`import SoleStormCatPY.SystemInfo as SystemInfo`
`SystemInfo.systemPrint()`

## ClockTimer
This application acts as a timer. The user can set the time (in minutes (Along with seconds and hours in the GUI)), or the developer can set the timer (in seconds). Everything will be printed out into the terminal (or the GUI), and will set the timer.

### How To Use
There is four different ways to use `ClockTimer`. The First being the process where the user sets the timer, the second being where the developer sets the timer, and the third being the GUI mode.
`import SoleStormCatPY.ClockTimer as PyTimer` and `PyTimer.clockTimerCMD()`
AND (Also Terminal)
`import SoleStormCatPY.ClockTimer as PyTimer` and `seconds = 12` and `PyTimer.clockTimerManual(seconds)`
AND (GUI)
`import SoleStormCatPY.ClockTimer as PyTimer` and `PyTimer.clockTimerGUI()`
AND FINALLY (GUI in Standalone App)
Open the Standalone app, and click the `ClockTimer` Button!

## Files
Files is a basic file program, allowing you to open files/folders, to rename files, and to delete files/folders. This runs in both the terminal and GUI.

### Current Issues
SoleStormCat Corp. currently has knowledge of these issues:

1. Files has an issue when opening folders, saying "Permission Denied" (This has only been tested on Linux). There is currently no known fix to this. See more at Issue #1!

### How To Use
There are two different ways to use `files`, with the first being in the terminal, and the second being through GUI. To run the terminal version, type `import SoleStormCatPY.files` and `SoleStormCatPY.files.filesCMD()` into your terminal. For GUI, you can either run the main GUI app, or you can run `import SoleStormCatPY.files` and `SoleStormCatPY.files.filesGUI` into the terminal.

## GreeNotes
`GreeNotes` is an application that allows users to write (or read) reminders that they make. This app writes a file named `.sscGreeNotes` file to the local computer, and nothing gets uploaded online. You can even read/write your reminders from this file!

### How To Use
There are 2 ways to run `GreeNotes`, but both require interactions with the terminal. To run this application (the main method), use `import SoleStormCatPY.GreeNotes` and `SoleStormCatPY.GreeNotes.GreeNotes()` in the terminal. The other way is to run SoleStormCatPY GUI application, then change the tab to `Terminal Apps`, then click on `GreeNotes (Terminal)`.

## appOpener
`appOpener` is an application that allows users to open appplications on a computer. Not all apps will be availible for all systems, and this is due to the way that operating systems are made.

### How To Use
Here is how to run `appOpener` in your terminal:
`import SoleStormCatPY.appOpener`
`appOpener.openAppManual(appname)`

Here is how to run `appOpener` through GUI:
`import SoleStormCatPY.appOpener`
`appOpener.openAppGUI()`

You can also open `appOpener` through the standalone app!

### Currently Supported Apps
This table is set in the following way:
`#. {Common App Name}, {Name Input}, (Systems Supported)`

1. Python, Python, (Linux; Windows; Mac)
1. Minecraft, Minecraft, (Linux; Mac)
1. Visual Studio Code, vsCode, (Linux)
1. Spotify, Spotify, (Linux)
1. Nano, nano, (Linux)
1. Nano (As Root), nanoSU, (Linux)
1. Vim, vim, (Linux)
1. Vim (As Root), vimSU, (Linux)

### Issues
There are a couple issues to this app (and I require your help!):

#### Operating System Issue
Since all operating systems are differnt, some use certain apps, while some do not. Some apps are located in different locations on the systems. Windows puts the files for the app in different places due to user restrictions. This makes it impossible for all apps to be supported!

Sometimes, these systems put these files in the in the user's directory, and SoleStormCat Corp does not know how to fix this for apps on Windows machines (Linux and Mac use `~` as the home directory.)

## Interactive Shell
The Interactive Shell is an intercative terminal developed by SoleStormCat Corp. It holds custom commands, along with being able to use system commands!

### How to Use
There are two ways to open the interactive shell. The first being a blank shell, and the second opening the shell with a command.
To open a blank shell, use `SoleStormCatPY.interactiveShell.shellOpen()`. To open a command shell, use `SoleStormCatPY.interactiveShell.shellUse('command')`.

### Currently Supported commands
The commands that are custom made are below:

#### help
`help` is a command that shows all the active commands that are made by SoleStormCat. 
To find system commands, run `help --os`. 
To find help for specific modules, run `help -m name` (with name being the module name.)

#### sscpy
`sscpy` is the opener for SoleStormCatPY. To open SoleStormCatPY in GUI, run `sscpy --gui`.

#### python
`python` is a coding platform developed by the Python Software Foundation.

#### web
`web` utilizes the SoleStormCatPY `webOpen` module to use a web browser.
You can run `web --tk` to use a `tkinter` window for the URL asker.
You can run `web --df` to use your defult browser.