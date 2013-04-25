# AccountChanger (Alfred v2 Workflow)

If you use more than one AppleID in iTunes App Store or Mac App Store, this is the perfect extension for you.

All you have to do is to press a keyboard shortcut when you want to switch account, this brings up a dialog window with all your AppleID's listed. Then you choose the account you would like to log in to, and press enter.

# Installation

For AccountChanger to funtion like supposed to, you have to do some preparations first.

1. Download and mount **[AccountChanger.dmg](http://cl.ly/OTXs)**
2. Run the applescript application with the strange (Norwegian) name *("Kjør denne først!!!")*
3. Open **Keychain Access** *(/Applications/Utilities/)*
4. Make a new keychain by pressing the following keyboard shortcut: **Command + Alt + N**

Give the keychain a master password and remember it.

Give the new keychain the name 'Applescript', and drag it to the top of the listed keychains, in the upper left corner of the window (like in the screenshot below).

<center><img src="https://api.monosnap.com/image/download?id=pMqtkgX9yumkXcUg45FnWOq8T" /></center>

<ol><li start="5"> For each AppleID you want to use, make one 'New password item' (Command+N). Each of the entries **must** be named 'eple'. In the 'Account' field, enter your AppleID (email address). And of course - the password in the password field.

<img src="http://cl.ly/OYud/51789258e4b0484a551c4cca.png" width=100%  /></li>

<li> Add the Alfred workflow from AccountChanger.dmg, and add a keyboard shortcut.

Congratulations! It should work now...</li></ol>

