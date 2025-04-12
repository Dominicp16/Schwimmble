installation and update instructions are made for Chromebooks and are assuming you downloaded the zip file<br/><br/>
  
### TO INSTALL: ###
STEP 1:
find the downloaded .zip file in "My Drive" and drag it to "Downloads". go to downloads

STEP 2:
fin the file in Downloads and right-click (click with two fingers) on the file and from the menu, click "Extract All". there should be a folder in Downloads that shares a name with the zip file.

STEP 3:
go to chrome://extensions and enable developer mode

STEP 4:
click "Load Unpacked" and go inside the folder that is inside the previously extracted folder

STEP 5:
click the puzzle piece next to the search box and find Schwimmble in the menu that opens, and click the pin button next to it.

<br/>

### TO UPDATE: ###
STEP 1:
install the new version and perform the first 2 steps

STEP 2:
return to chrome://extensions and find Schwimmble, then press remove

STEP 3: 
perform installation steps 4 and 5 again with the new version folder<br/>

or:<br/>

STEP 1:
unzip the downloaded .zip file (see step 2)

STEP 2:
go to the old schwimmble folder and rename the folder called "Schwimmble" to something else, preferably the version number

STEP 3:
drag the folder in the newly unzipped folder into the old schwimmble folder</br>
  </br>
  </br>


### HOW TO USE STYLIZATION MENU: ###
you press the buttons while having text in the message box selected (or just having your navigator somewhere in the box). when the message is sent, it parses the stylization and shows the formatted text.</br>

B: bolds the selected text

I: italicizes the selected text

U: underlines the selected text

S: strikesthrough the selected text

H: adds a custom hyperlink to the selected text (makes it clickable to send you to a website), which you input in the alert

SP: turns the selected text into superscript (makes it small and towards the top)

SB: turns the selected text into subscript (makes it small and towards the bottom)

SM: turns the selected text small

BIG: turns the selected text big

C: colours the selected text (you can input a hex code or one of <a href="https://www.w3schools.com/cssref/css_colors.php">these</a>

O: overlines the selected text

CODE: turns the selected text into code format

L: adds a line break/enter (instead of pressing enter/return)

HL: highlights the selected text (you can input a hex code or one of <a href="https://www.w3schools.com/cssref/css_colors.php">these</a>

TT: adds a tooltip to the selected text (shows a message when you hover over the text)

CC: gives a custom cursor to the selected text (changes your cursor when you hover over the text, you can choose one of <a href="https://www.w3schools.com/cssref/pr_class_cursor.php">these (except 'url' and including 'vertical-text'</a>, or choose a custom schwimmble cursor (default-custom, pointer-custom, threat)

USR: the resulting tag acts as the username section of Schwimmble messages, so you can apply formatting to the username

TH: thins the selected text

DA: adds a custom discreet hyperlink to the selected text (a hyperlink without all the underlining and colour and such)

SMR: turns the selected text extra-small

BIGR: turns the selected text extra-big</br>

### EMOJIS: ###
to use emojis, you put the emoji name between two colons (some names have slashes, DO NOT type the slashes when putting the emoji in Schwimmble). you can hover over an emoji in someone's message to see the name of it

:\cool:

:eyeroll:

:frown:

:\grin:

:hmm:

:laugh:

:mad:

:melting:

:mild:

:schwimmble:

:\smile:

:\tongue:

:\wink:

:yikes:

:gooberflab:

:devil:

:nazi:

:hitler:

:disgusted:

:blank:

:\no_mouth:

:ahh:

:glod:

  </br>
  </br>

### MODS: (not yet implemented) ###

create a folder, and in it put a file called "mod.config", and two folders called "img" and "modules"

BASIC CONFIG:</br>
put a [basic] tag at the top of your mod.config file

put a "name" element under that, and after it put an equal sign, and then the name of your mod with two underlines instead of spaces
supports any string.
<code>
[basic]
name=Schwimmble__Mod__Example
</code> would name the mod "Schwimmble Mod Example"

you can add a "desc" element (optional), with the value set to the description of your mod
supports any string.
<code>
[basic]
name=Schwimmble__Mod__Example
desc=This__is__the__description__of__this__Schwimmble__mod.
</code> would set the description of the mod to "This is the description of this Schwimmble mod."

you can add an "imgPath" element (optional), with the value set to the path of the image of your mod (when not set the default is \img\picture.png, if that doesn't exist then it uses Schwimmble Bronson-Jazz's head.
supports image paths
<code>
[basic]
name=Schwimmble__Mod__Example
desc=This__is__the__description__of__this__Schwimmble__mod.
imgPath=\img\modPicture.png
</code> would set the image for the mod to the file at <folder_where_mod.config_is>\img\profile.png

you can add a "ver" element (optional), with the value set to the version of the mod (defaults to 0.0.1)
supports up to four integers (could have -alpha or -beta after one number, but only one of each) separated by periods
<code>
[basic]
name=Schwimmble__Mod__Example
desc=This__is__the__description__of__this__Schwimmble__mod.
imgPath=\img\modPicture.png
version=1.1.1
</code> would set the version of the mod to v1.1.1
