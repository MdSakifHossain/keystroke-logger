# wanna change the apps name....?

you need to understand some things...
actually 2 files...

1. The /AndroidManifest.xml
2. The res/values/strings.xml

if u want to change the apps name from "Keystroke Logger" to whatever u desire.
You need to go to the "AndroidManifest.xml" file and change its name....
requirements:
    The "mt manager" app can modify the "xml" file but im "gorib"....
    so ....
    1. apk editor pro app.
        it can modify or change the stuff inside the xml file....
        you dont need to login....
    2. mt manager app.
        it can also change the xml file but you have to login first... (for xml editing...)
        and im "gorib".
        so, im using apk editor pro app.
steps:
    1. goto "APK Editor Pro" app.
    2. click on the "Keystroke Logger" app.
    3. click on the "Full Edit (RESOURCE RE-BUILD)" option.
    4. click "Decode All Files" option.
    5. at very bottom... click on the "Files" option.
    6. click on the "AndroidManifest.xml" file.
    7. goto line no. 20
    8. there is only 2 things. The app name and the package name.
    9. just change the app name.
    10. save that file and go back.
    11. click on the "build" button at the top right.
    12. click on the "install" button and install the app.
    13. and the apps name is changed.
        but when u are setting up the keyboard app..
        its not showing "the name" you saved.
        its showing "Keystroke Logger".
        but that is not what we want..
        right...?
        we want to torally change its name totally to whatever we want....
    14. goto the "APK Editor Pro" app again.
    15. select the app.
    16. click on the "Full Edit (RESOURCE RE-BUILD)" option.
    17. click "Decode All Files" option.
    18. at very bottom... click on the "Files" option.
    19. click on the "res" folder.
    20. click on the "values" folder.
    21. click on the "strings.xml" file.
    22. goto line no. 196
    23. change to name from "Keystroke Logger" to what ever you desire...
    24. save that file and go back.
    25. click on the "build" button at the top right.
    26. click on the "install" button and install the app.
        the apps name is changed "everywhere".


# wanna change the app icon.....?

then we are gonna use the "MT Manager" app.
you need to change 5 image files.

    thoes are at:
        1. /res/drawable-hdpi-v4/ic_launcher.png
        2. /res/drawable-ldpi-v4/ic_launcher.png
        3. /res/drawable-mdpi-v4/ic_launcher.png
        4. /res/drawable-xhdpi-v4ic_launcher.png/ic_launcher.png
        5. /res/drawable-xxhdpi-v4/ic_launcher.png
    
    requirements:
        1. the "MT Manager" app.
        2. the icon.
    
    steps:
        1. change the icon file name as "ic_launcher.png"
        2. replace all the default icons by the new icon at the locations below:
            1. /res/drawable-hdpi-v4/
            2. /res/drawable-ldpi-v4/
            3. /res/drawable-mdpi-v4/
            4. /res/drawable-xhdpi-v4ic_launcher.png/
            5. /res/drawable-xxhdpi-v4/
        
