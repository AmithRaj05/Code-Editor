# dyte-amith
This repo contains the "Code Editor" react app developed for Dyte, by Amith Raj

Steps to access files and website:
1. All the app files are in Master branch
2. The github link to website is: https://amithraj05.github.io/dyte-amith/
3. In Master branch:
        a. All the files except "src" are default react, git, and node required files
        a. The "src" file has "index.js", "index.css" files and "components" folder
        b. The "index.js" file consists of the default react code
        c. The "index.css" file consists of the CSS functionalities of entire project
        d. The "components" folder consists of 3 files and 1 folder:
                i. "App.js" is the main file which contains the body of the project
                ii. "Editor.js" contains the code that is used to call the libraries required for syntax highlighting
                iii. "FileExplorer.js" contains the code required for creating the file explorer pane
                iv. The "hooks" folder contains a file called "useLocalStorage.js" which stores the code on the broswer. This prevents the code from 
                    vanishing even when the page is reloaded.
