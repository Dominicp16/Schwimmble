installation and update instructions are made for Chromebooks and are assuming you downloaded the zip file<br/><br/>
  
### TO INSTALL: (if you don't have your own chromebook) ###
STEP 1:
find the downloaded .zip file in "My Drive" and double-click it

STEP 2:
click "Extract All". there should be a folder in "My Drive" that shares a name with the zip file.

STEP 3:
go to chrome://extensions and enable developer mode

STEP 4:
click "Load Unpacked" and go inside the folder that is inside the previously extracted folder

STEP 5:
click the puzzle piece next to the search box and find Schwimmble in the menu that opens, and click the pin button next to it.

### TO INSTALL: (if you do have your own chromebook) ###
STEP 1:
find the downloaded .zip file in "My Drive" and double-click it

STEP 2:
drag the folder you see inside the archive to "Downloads" and then go there

STEP 3:
go to chrome://extensions and enable developer mode

STEP 4:
click "Load Unpacked" and navigate to "Downloads", choose the folder you added called "Schwimmble"

STEP 5:
click the puzzle piece next to the search box and find Schwimmble in the menu that opens, and click the pin button next to it.

<br/>

### TO UPDATE: ###
STEP 1:
install the new ver and perform the first 2 steps

STEP 2:
return to chrome://extensions and find Schwimmble, then press remove

STEP 3: 
perform installation steps 4 and 5 again with the new ver folder<br/>

or:<br/>

STEP 1:
unzip the downloaded .zip file (see step 2)

STEP 2:
go to the old schwimmble version folder and rename the folder called "Schwimmble" to something else, preferably the ver number

STEP 3:
drag the folder in the newly unzipped folder into the old schwimmble version folder</br>
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

CC: gives a custom cursor to the selected text (changes your cursor when you hover over the text, you can choose one of <a href="https://www.w3schools.com/cssref/pr_class_cursor.php">these (except 'url' and including 'vertical-text'</a>, or choose a custom schwimmble cursor (default-custom, pointer-custom, threat, adoring)

USR: the resulting tag acts as the username section of Schwimmble messages, so you can apply formatting to the username

TH: thins the selected text

DA: adds a custom discreet hyperlink to the selected text (a hyperlink without all the underlining and colour and such)

SMR: turns the selected text extra-small

BIGR: turns the selected text extra-big</br>

<br/>

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

:aww:

:fork:

:fork_you:

:gas:

:purples:

:911:

:isis:

:haw:

:die:

:trump:

:white:

:joel:

  </br>
  </br>

### MODS: (not yet implemented. probably scroll down to) ###

create a folder, and in it put a file called "mod.config", and two folders called "img" and "modules"
  </br>
METADATA CONFIG:</br>
put a [metadata] tag at the top of your mod.config file

put a "name" element under that, and after it put an equal sign, and then the name of your mod between double quotes ""
supports any string.
<code>
[metadata]
name="Schwimmble Mod Example"
</code> would name the mod Schwimmble Mod Example

you can add a "desc" element (optional), with the value set to the description of your mod.
supports any string.
<code>
[metadata]
name="Schwimmble Mod Example"
desc=desc="This is the description of this Schwimmble mod."
</code> would set the description of the mod to This is the description of this Schwimmble mod.

you can add an "img" element (optional), with the value set to the path of the icon of your mod (when not set the default is \img\picture.png, if that doesn't exist then it uses Schwimmble Bronson-Jazz's head.
supports image paths.
<code>
[metadata]
name="Schwimmble Mod Example"
desc="This is the description of this Schwimmble mod."
img=\img\modPicture.png
</code> would set the image for the mod to the file at <folder_where_mod.config_is>\img\profile.png

you can add a "ver" element (optional), with the value set to the ver of the mod (defaults to 0.0.1).
supports up to four integers (could have -alpha or -beta after one number, but only one of each) separated by periods.
<code>
[metadata]
name="Schwimmble Mod Example"
desc="This is the description of this Schwimmble mod."
img=\img\modPicture.png
ver=1.1.1
</code> would set the version of the mod to v1.1.1

  </br>
FUNCTIONAL CONFIG:</br>
put a [function] tag at the top of your mod.config file (typically a line break would go before it but not here for succinctness)

you can add a "background" tag under, with the value set to the path of your custom background (if the value is left blank then it defaults to \img\backgrounds\background.png).
supports image paths.
<code>
[metadata]
name="Schwimmble Mod Example"
desc="This is the description of this Schwimmble mod."
img=\img\modPicture.png
ver=1.1.1
[function]
background=\img\backgrounds\modBackground.gif
</code> would set the background picture to the image at \img\backgrounds\modBackground.gif

TAG DESCRIPTION NOTATION: (how i will describe the tags from now on because i'm lazy)
example (using the background tag):
background='type:path;image' F

_background_ is the name of the tag
_'single quotes'_ mean that the text in the single quotes is describing the input for the tag
_type:path_ means the input is a path to a file
_;image_ means that the path should be to an image file
_F_ means that it is a function tag

other notation to know:

_M_ means that it is a metadata tag </br>
_*_ means that the tag is required </br>
_D=''_ will set the default value of the string (always set no matter what) to the exact text in the single quotes </br>
_D$=''_ will set the default value of the string (only set if the tag exists and does not have an equal sign) to the exact text in the quotes </br>
_type:string_ mean that a string is to be entered there (text in double quotes) </br>
_{curly brackets}_ mean that an array of properties is to be put there (in curly brackets) </br>
_U_ at the end of an array means that you can have an unlimited amount of properties in the array (only ones where the name is customizable) </br>
 </br>
  </br>
name='type:string' M * </br>
desc='type:string' M D='My Schwimmble mod' </br>
home='type:path' M D='%home%' </br>
img='type:path;image' M D='\img\picture.png' </br>
ver='type:SemVer;-ab' M D='1.0.0' </br>
background='type:path;image' F </br>
cursor={'name'='type:path;image' U} </br>
emoji={'name'='type:path;image' U} </br>
style={'name'={ </br>
‌   name='type:string' </br>
‌   type='type:option;select/noSelect' </br>
‌   action='type:string' </br>
}} M </br>
startup='type:path;javascript' F D$='/js/mod.js'</br>
css='type:path;css' F D$='/css/mod.css'</br>
