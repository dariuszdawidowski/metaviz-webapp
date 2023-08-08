<h1 align="center">
Metaviz
</h1>
<p align="center">
Diagramming application for web browser. Distribution repository of the tool in the html file.
</p>
<p align="center">
Supported browsers: recent versions of Chrome, Opera and Edge.
</p>

[![license](https://img.shields.io/github/license/dariuszdawidowski/metaviz?color=9cf)](./LICENSE)

# About

Metaviz is a web-based team productivity tool for creating visually stunning diagrams with ease.
This application empowers you to construct diagrams using various elements, including points, labels, text and cliparts.

<img src="https://raw.githubusercontent.com/dariuszdawidowski/metaviz-editor/main/metaviz-editor-showcase.png" />

Whether you need to:

* illustrate complex concepts
* map out processes
* use visual scripting for your project
* or simply express your ideas visually

...intuitive interface and versatile set of features make it a breeze.

Important feature is the capability to develop custom plugins, providing users with the flexibility to expand its functionality and customize it according to their specific requirements.

# Important note

If you are user - you are in the right place. No code here.\
This project is bootstrap, just plain html loading all libraries from CDN to quick start for end users.
If you are looking for code see the Libraries section below.

# Quick start

Open file metaviz.html in the browser (File->Open file... or just drag&drop) and you are ready to work.

# File format

Metaviz stores data in a xml format with .mv extension.
It is iterative text file with one line assigned to one action and sectors assigned to fake user's session to make the format friendly to the version control system (like git).

# Create new project file

1. Open metaviz.html in your browser.
NOTE: due to NativeFilesystemAPI only **Chrome**, **Opera** and **Edge** are supported at the moment!

2. Right Mouse Button -> Add Node -> Text. Type "Hello World" inside.

3. Right Mouse Button -> Save. Due to security limitations in browsers this will download file for the first time. To save a file normally in a future - it must already exist.

4. Move downloaded metaviz-diagram.mv file into your project.

5. Since now you can use this file in "normal" way. Start Metaviz again (reload page) and use Right Mouse Button -> Open File...
There will be no download from now on, file will be just saved.

# Libraries

All dependencies are loaded from CDN. Note that latest versions will be found automatically through '/latest/' URL.

Metaviz Editor: https://github.com/dariuszdawidowski/metaviz-editor

Total Diagram: https://github.com/dariuszdawidowski/total-diagram

Total Text: https://github.com/dariuszdawidowski/total-text

Total Pro Menu: https://github.com/dariuszdawidowski/total-pro-menu

Emoji Picker: https://github.com/nolanlawson/emoji-picker-element

# Authors

Dariusz Dawidowski\
Jagoda Dawidowska\
Maksym Godovanets
