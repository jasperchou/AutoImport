# AutoImport
AutoImport, handy Xcode plugin to import heaer file automatically.
Because sometimes you are on 999th line of code and scrolling up just to add an import is a waste of time. 

# Support
AutoImport is a Xcode Source Editor Extension, supports Xcode 8 and above.
Replacements of [Peckham](https://github.com/markohlebar/Peckham), as  decided to drop support for Xcode plugins in Xcode 8. 
## AutoImport by Menu

![Usage](AutoImport3.gif)

## AutoImport Key Binding

![Usage](AutoImport2.png)

## AutoImport by Quick Key 

![Usage](AutoImport1.gif)
## Credits

I am using some helper functions to deal with the filtering out source text from[CleanHeaders-Xcode](https://github.com/insanoid/CleanHeaders-Xcode) and [xTextHandler-objc](https://github.com/cyanzhong/xTextHandler-objc), thanks for the awesome class.



Installation
------------

1. On OS X 10.11 El Capitan, run the following command and restart your Mac:

        sudo /usr/libexec/xpccachectl

1. Open ``AutoImport.xcodeproj``
1. Enable target signing for both the Application and the Source Code Extension using your own developer ID
1. Product > Archive
1. Right click archive > Show in Finder
1. Right click archive > Show Package Contents
1. Drag ``AutoImport.app`` to your Applications folder
1. Run ``AutoImport.app`` and exit again.
1. Go to System Preferences -> Extensions -> Xcode Source Editor and enable the extension
1. The menu-item should now be available from Xcode's Editor menu.
