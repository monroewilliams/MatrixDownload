# Matrix

Now featured on [Awesome macOS Screensavers](https://github.com/agarrharr/awesome-macos-screensavers)! 

This is a Mac screensaver that I've been tinkering with since roughly 2002. I run it on all my personal machines, and have given copies to a few friends over the years, but hadn't made it publicly available for download.

After making some updates to it recently, I decided it was time.

<img src="Matrix.png"><img src="Matrix-config.png"><br>

Download the latest release [here](https://github.com/monroewilliams/MatrixDownload/releases/download/1.1.3/Matrix.saver.zip).

Unzip to Matrix.saver and double-click it to install, then go to System Preferences -> Desktop & Screen Saver and pick it from the list. 

The "Renderer" popup switches betewen using OpenGL and Metal for rendering. The others are all pretty self-explanatory, although you might have to wait a bit to see what "Minor Instability" does. :)

Release notes:

Version 1.1.3
- now built for both Intel and Apple Silicon

Version 1.1.2
- fixed zoom running backwards in OpenGL renderer
- changed some of the internals of how preferences are stored
- renderer selection is now a popup
- changed deployment target to include Mac OS X 10.11, and fixed some issues so it should now work on a 10.11 machine (the Metal renderer is disabled on 10.11 due to some issues there, so it's forced to OpenGL)

Version 1.1.1
- added thumbnail image for screensaver list
- fixed a graphical issue when the preview is moved between Retina and non-Retina displays

Version 1.1
- first public release
