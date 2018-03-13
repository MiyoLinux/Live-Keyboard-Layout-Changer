# Live-Keyboard-Layout-Changer

![alt text](http://miyolinux.weebly.com/uploads/1/3/7/0/13707080/screenshot-from-2018-03-06-18-02-18_orig.png)

The Live Keyboard Layout Changer allows a user to change keyboard layouts during a live session.

Requires: yad
          flag icons

Unfortunately, I was shortsighted when I created this application, because I pointed the code toward a MiyoLinux specific folder containing the flag icons instead of a generic folder that could easily be used on any system. Therefore, a user has two options...

Option 1: Download the flags.zip file and just use the code "as-is". This will be the least amount of hassle. Create a folder in /usr/share/ and name it miyolinux (all lowercase letters). Then extract the flags.zip file into that miyolinux folder.

Option 2: Download the flags.zip file. Create a folder in /usr/share/ and name it whatever you'd like. Extract the flags.zip file into the folder that you created. Then edit the code (to point to that specific folder that you created) by replacing each instance of miyolinux with your own folder's name.
