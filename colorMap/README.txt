1. Prerequisites
    1.1 Apache - Download and install a stable version of Apache from https://httpd.apache.org/download.cgi. 
        It is an open source HTTP server which is compatible with all platforms (Windows, Linux and MacOS). 
        It's completely fine to install XAMPP, VertrigoServ or other HTTP servers
    1.2 Pick a good IDE (e.g Sublime, Notepad++, Atom, Visual Studio Code).

2. Directory Layout
.
├── css                         # Style Sheets folder
│   ├── style.css               # ADD YOUR CUSTOMIZED STYLE TO THIS FILE
|
├── js                          # Javascript folder
│   ├── Assignment_2.1.js       # The assignment script. EDIT/ADD YOUR CODE HERE 
|   ├── plyLoader.js            # The library to load PLY files. EDIT THIS FILE FOR THE ASSIGNMENT 2
│   ├── dat.gui.min.js          # The library for GUI menu. Don't edit it!
│   └── three.module.js         # The THREEJS module library. Don't edit this one!
|
├── models                      # Store PLY model files
|
├── index.html                  # The HTML index file. You can change the content of this file if you want, but you're not allowed to add additional libraries without our permision.
├── README.txt                  # It's me! The readme file

3. How to run?

Step 1: Run Apache
Step 2: Copy this whole folder to the web root directory
Step 3: Open a web browser (e.g Chrome) and type: http://localhost/cosc6344/
        Add your code to Assignment_2.1.js and plyLoader.js

4. References

4.1 Javascript
    https://www.w3schools.com/js/

4.1 WebGL References:
    https://webglfundamentals.org
    https://developer.mozilla.org/en-US/docs/Web/API/WebGL_API/Tutorial
    https://threejs.org/examples/

4.2 HTML Style Tutorial
    https://www.w3schools.com/bootstrap4/
    https://bootswatch.com/lumen/
