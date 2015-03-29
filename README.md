Yahoo! KeyKey
===
[Yahoo! Keykey](http://tw.media.yahoo.com/keykey/) is a Traditional Chinese IME（繁體字／老體字／正體字 拼音輸入法）designed for Taiwan, but can be modified into a Cantonese Input IME （粵語／廣東話 拼音輸入法）with a Cantonese dictionary. 

Yahoo! KeyKey is open source under a BSD licence since 2013/01/15. Although it was originally hosted as [KeyKey](https://github.com/Yi-Kai/KeyKey), it is no longer maintained.

This repository serves for non-developers to download and use the IME. 

##Installation on Mac OSX

The installer disk image cannot be directly opened or downloaded. However, together with the whole repository, it can be done in no time.

1. In Terminal, run the following command to make a copy of the repo. If you don't know where terminal is, simply type 'Terminal' on Spotlight (^ + Space).
   
   ```
   $ git clone https://github.com/kctong529/YahooKeyKey.git
   ```

2. The location of the repo copy depends on your previous step. If you have no idea about it, run this command and you'll be fine with it.

   ```
   $ open ./
   ```

3. Open `YahooKeyKey-OSX-Leopard-1.1.2535.dmg` in the repo root directory.
4. Open `Install Yahoo! KeyKey.app` and run through the installer.

##Cantonese Input IME

_m sik gwok yue m sik chong kit m sik but wak dan hai yiu da jung mun_? I know that feel bro. Wouldn't it be nice to _hor yi yung gwong dung wa da jung mun_, like this?

![Cantonese Input IME](http://blog.theoryspace.com/wp-content/uploads/2009/01/input_method.jpg "Cantonese Input IME")

**Prepare the Cantonese Data File Folder:**

1. Create a new folder called “DataTables” on your desktop (or wherever).
2. Within the 'DataTables' folder, create another folder called 'Generic'.
3. Copy canton.cin to the 'Generic' folder.

![DataTables > Generic > canton.cin](http://blog.theoryspace.com/wp-content/uploads/2009/01/DataTables.jpg "DataTables > Generic > canton.cin")

**Install the Cantonese Data File into Yahoo! KeyKey:**

1. Now locate “Yahoo! KeyKey.app” in /Library/Input Methods.
2. Right-click on it and choose “Show Package Contents”.
3. Go inside Contents/Resources.
4. Drag the entire “DataTables” folder from your desktop (or wherever you made it) into the “Resources” folder.
5. It might ask you to type your admin password to authenticate the copying process. (Note: If there are multiple users on your computer wanting to use this input method, make sure you add read and write access rights to the “DataTables” folder for everyone by right-clicking on the folder, choose “Get Info”, then do it under “Sharing & Permissions”.)
6. Now log out and log back in.

![Show Package Contents](http://blog.theoryspace.com/wp-content/uploads/2009/01/ShowPackageContents.jpg "Show Package Contents")

**Final Setup:**

1. Switch to the Yahoo! KeyKey input method and click on the input method icon on the menu bar.
2. You should see “Canton” as one of the choices. Check it.
3. Also remember to turn on “Associated Phrases” (this is very useful).
4. Congratulations! You can start typing away!

![Canton](http://blog.theoryspace.com/wp-content/uploads/2009/01/Canton.jpg "Canton")

**Advanced Tweaking:**

1. You can turn off all the other input methods by going to Yahoo! KeyKey’s preferences under the General tab.
2. In preferences, under the Generic tab, check “Put recently chosen candidates in front” to make frequently typed characters appear further in the front of the character selection pages.
3. If you want to add new characters, modify pinyin (pingyum), or adjust the character position in the selection bar, you can just open up `canton.cin` in a Unicode text editor like _**TextWrangler**_ (or _**Sublime**_) and edit it yourself. It should be pretty self explanatory, but do it at your own risk! If you want the data file’s formatting documentation, [read this](https://docs.google.com/document/d/1ew408138FCRivleknnw5IRnFqSFH3bHnDyammmiasDo/preview).

Thanks to [Theoryspace](http://blog.theoryspace.com/2009/01/05/how-to-type-chinese-on-a-mac-with-cantonese-pinyin/) for the original article!


