kudo-localize-norwegian
=======================

Translation of Kudo into Norwegian

Howto:
 - Click on file you want to translate
 - Click on RAW and select the entire text EXCEPT the first tag (<?xml...) and copy it
 - Go to http://xmltranslate.azurewebsites.net/ (There is a help file on how to use the tool)
 - Paste inn the text, and translate up to 100 texts
 - When finished, take a note of which line number you are on.
 - Copy finished XML and go back to the RAW window and paste contents over the existing contents.
 - Commit your changes with a comment on which line number you have gotten to.
 - Repeat for next batch of lines.

Note: Check in as often as possible (at least every 100 lines) so make sure nobody are translating the same text.

To test your changes in Kodu:
 - Create a folder called NO in the folder: C:\Program Files (x86)\Microsoft Research\Kodu Game Lab\Content\Xml\Localizable
 - Download all files from GitHub into this folder
 - Right-click the Kodu Game Lab icon
 - Click Properties
 - Click the text box labeled Target and move the text cursor to the end of the line (after the close quotation mark).
 - Add a space then type /localization no (where no stands for Norwegian)
 - Press OK.
 - Start Kodu to view your changes in context of the game.

Dictionary (use this for commonly used words that might be translated in different ways):
Kodu=Kodu
Ship=Skip
Community=Samfunn
Stick=Styrespak
Blip=Blip
Bot=Bot
Tutorial=Innføring
Team=Lag
