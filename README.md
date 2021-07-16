# Notepad-_Syntax
A few visual syntaxis for Notepad++. E.g. IFC files, (Revit) JOURNAL files and a syntax for NOTES

I use 'Deep Black' theme as a basic Theme

NOTES:

![image](https://user-images.githubusercontent.com/7262482/125967327-5d27ae05-c043-4a11-89b3-d7260e953fbc.png)

IFC:

![image](https://user-images.githubusercontent.com/7262482/125968730-2fe615d1-a9a2-490d-81a7-aa03cebe4e20.png)

JOURNAL: (Revit)

![image](https://user-images.githubusercontent.com/7262482/125970900-c4863394-1e1c-47ba-ba5f-ba1fd60c429d.png)


Revit Journals files are the place where you could trace possible problems with a Revit file.
This file is probably also (partly) sent to Autodesk if Revit crashes.
But a Journal file is primarily a gray and poorly documented area.
Below is a short summary with some links to places, if you need to dive into them.


The Journal files are located in a local user folder per Revit version. E.g:
C:\Users\**USER**\AppData\Local\Autodesk\Revit\Autodesk Revit (version)\Journals

You can find some piece of documentation in the Wiki and via the ReadingList on the Github of Andreas Diekman (developer of the Journalysis Package).

https://github.com/andydandy74/Journalysis/wiki/JournalLine-types

https://github.com/andydandy74/Journalysis/wiki/Reading-list


.
I made a Syntax for NotePad++ that can help you to check a Journal file visualy. A few notes:

• Yellow are date and time formats.

• Purple are 'commands' and such.

• Blue (SLOG) are contact moments of the LOCAL file with the CENTRAL file. 
The combination of Journal File and SLOG file is sometimes used by Autodesk to detect problems problemen

• Red are notifications of possible 'problems'

• Orange is the beginning and the end of an Audit report. 
With references to specific objects (IDs) in blue. 
If you open a Revit file with Audit, an extra report is written with the reference to the problem objects.
