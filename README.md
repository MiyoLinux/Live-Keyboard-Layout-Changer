# Live-Keyboard-Layout-Changer

![alt text](http://miyolinux.weebly.com/uploads/1/3/7/0/13707080/screenshot-from-2018-03-06-18-02-18_orig.png)

Requires: yad and flag icons (provided as a .zip file)

The Live Keyboard Layout Changer allows a user to temporarily change the keyboard layout on the fly in a live session. The change will last until a user changes it back again with the application, or until a user logs out/in or reboots. It was created to aid non-US users while running MiyoLinux live before installation; however, it can also be useful after installation for anyone desiring more than one keyboard layout.

Unfortunately, I was shortsighted when I created this application, because I pointed the code toward a MiyoLinux specific folder containing the flag icons instead of a generic folder that could easily be used on any system. Therefore, a user has two options...

Option 1: Download the flags.zip file and just use the code "as-is". This will be the least amount of hassle. Create a folder in /usr/share/ and name it miyolinux (all lowercase letters). Then extract the flags.zip file into that miyolinux folder.

Option 2: Download the flags.zip file. Create a folder in /usr/share/ and name it whatever you'd like. Extract the flags.zip file into the folder that you created. Then edit the code (to point to that specific folder that you created) by replacing each instance of miyolinux with your own folder's name.

<p xmlns:dct="http://purl.org/dc/terms/" xmlns:vcard="http://www.w3.org/2001/vcard-rdf/3.0#">
  <a rel="license"
     href="http://creativecommons.org/publicdomain/zero/1.0/">
    <img src="http://i.creativecommons.org/p/zero/1.0/88x31.png" style="border-style: none;" alt="CC0" />
  </a>
  <br />
  To the extent possible under law,
  <a rel="dct:publisher"
     href="http://miyolinux.weebly.com/">
    <span property="dct:title">MiyoLinux</span></a>
  has waived all copyright and related or neighboring rights to
  <span property="dct:title">MiyoLinux Accessories</span>.
This work is published from:
<span property="vcard:Country" datatype="dct:ISO3166"
      content="US" about="http://miyolinux.weebly.com/">
  United States</span>.
</p>
