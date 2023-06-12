# Metaviz

Diagramming application for web browser.

## About

Metaviz is a general-purpose web-based diagramming and team productivity tool.
You can just store project ideas or use it for visual scripting.

Note this is main aggregator project which bundles everything into single small html file and loads components from CDN.

## File format

Metaviz stores data in a xml format with .mv extension.
It is iterative text file with one line assigned to one action and sectors assigned to the user's session to make the format friendly to the version control system (like git).

## Quick Start

1. Open metaviz.html in your browser.
NOTE: only Chrome, Opera and Edge are supported at the moment!

2. Right Mouse Button -> Add Node -> Text. Type "Hello World" inside.

3. Right Mouse Button -> Save. Due to security limitations in browsers this will download file for the first time. To save a file normally in a future - it must already exist.

4. Move downloaded metaviz-diagram.mv file into your project.

5. Since now you can use this file in "normal" way. Start Metaviz again and use Right Mouse Button -> Open File...
There will be no download from now on during saving.

## Component libraries

Note that always latest versions will be used through '/latest/' url in CDNs.

Metaviz Editor: https://github.com/dariuszdawidowski/metaviz-editor
Total Diagram: https://github.com/dariuszdawidowski/total-diagram
Total Text: https://github.com/dariuszdawidowski/total-text
Total Pro Menu: https://github.com/dariuszdawidowski/total-pro-menu

## Third party libraries

Emoji Picker: https://github.com/nolanlawson/emoji-picker-element

# Credits

Dariusz Dawidowski
