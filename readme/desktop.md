# An illustrated Guide to getting started with Joplin.  

## Why note taking at all?
It makes it easier to find small bits of information that don’t warrant a full document: the VIN number and tire air pressure for your car; Veterinary data for pets, the phone number and ordering website for a good pizza place, all the way up to major projects of any type.
 
## Why Joplin over other note managers? 
- OneNote – Too many limitations, and too many of the wrong capabilities. Learning curve is high.
- EverNote – Too buggy.
- Google Keep. Too slow, no offline/desktop app. No way to nest notes. 
- Also, these above leave you beholden to a corporate data format which may or may not be in your best interest.

Joplin features are straightforward: the features it has are pretty bulletproof.  If a feature is included, it works and does so consistently.

## Joplin the name: 
It comes from Scott, not Janice.  Scott Joplin is a favorite composer and pianist of the primary developer for the app.

![Picture1](https://user-images.githubusercontent.com/17282079/229366932-2630a7f8-263c-4702-95e9-f27ff75a33e8.png)

The top button toggles the editor layout 

The second button toggles between Rich Test Format or "RTF" editor and the Markdown editor.

![Editor Layout](https://user-images.githubusercontent.com/17282079/229366968-4d191d47-5d4a-40f2-a0e9-300ce9c2f4a6.jpg)

**A note about the markdown editor for the unfamiliar:**
If you have ever worked on a wiki, you know what it looks like and how it works.  Plain text formatting marks are translated into more advanced formatting for display. For instance, adding highlighting, bulleted lists, italics, tables etc.  The markdown editor shows you the raw text it is translating and also gives you formatting buttons at the top.

For those people who may remember the old WordPerfect “Reveal codes” button, which allowed you to directly change the text formatting behind the display, markdown works much the same way.
**Tip:** You can teach yourself Joplin's markdown by using the format buttons at the top and seeing both how markdown sets it up, and how it is rendered.
  
**Saving what you’ve written.**  It saves automatically. There is no save button.
Reverting to a previous version: Click the Info button in the note. 
 
Note history is available if you want to restore a previous version of a note.

![Note History Word](https://user-images.githubusercontent.com/17282079/229367109-5acf0a3e-c959-4a69-b558-3077846d2f1b.jpg)

Using an external editor:
In the menu “Note” is “Toggle the external Editor” which will pull the text in your current note into an external word processor. 

![Toggle External](https://user-images.githubusercontent.com/17282079/229367123-39af7d24-97f9-4dd1-af29-7a1cfd40ae99.png)

If nothing happens when you do this, it’s because an external editor is not set up in your Joplin.  This is found under Tools, Options, General.
For instance to access Wordpad, by entering the path to it:
%ProgramFiles%\Windows NT\Accessories\wordpad.exe

And clicking “Apply” and “Back” at the bottom of the page.  External editor should now work.

![External Editor 2](https://user-images.githubusercontent.com/17282079/229367163-9016f3db-0d97-4fda-9160-0598d7cef615.png)

## Other editing considerations:
- Speech recognition/dictation is not available through Joplin but Windows 10/11 has speech recognition natively for most external editors. It just needs to be programmed with your voice.  Search for "Speech" in the Windows search bar and begin setup.
Android Joplin also uses Google Voice Keyboard.


- **"Hey! clicking on links doesn't work!"** - Try pressing ctrl while clicking. Or open the markdown editor and click on the RTF.

# Organizing.
**Folders:**
Any notebook can have any number of sub-folders, as opposed to OneNote where subfolders are limited to three.
Folders and subfolders can be moved to re-arrange them in ways that fit your organizational style.  You can change the sort order from the button at the top of the page list. 

Clicking the up or down arrow changes the sort order from ascending to descending and back.

![Sort Notes](https://user-images.githubusercontent.com/17282079/229367181-b28ddadf-5660-45d9-a6bf-8687bf20930e.jpg)

## Tags:
Notes can be tagged by going to Tags at the bottom of the note page.

 ![Tags](https://user-images.githubusercontent.com/17282079/229367196-07e2c247-932e-4778-bc1b-069804c3aaf3.jpg)

Tags are useful for marking notes across folder and subfolder structures. This is the difference from folders. Multiple tags can be placed on a single note, whereas notes can have only one folder location. For instance you can create tags "Vacation" "Peninsula" "Camping" for a single note.  When viewing the tags in the left side menu, that note will show up under all three tags regardless of what folder it's in.  

It is possible to search for tags using “Tag:{tag name}

# Finding Info - Searching:
The "Search" box in Joplin may be small, but it is quite powerful.  Type in a search term and you get all instances of that term in the results underneath.

![Search location](https://user-images.githubusercontent.com/17282079/229367245-16fb0133-cad5-436d-a4b9-9e7c1beb636c.png)

You can refine your searches. The definitive guide is located here: 

https://discourse.joplinapp.org/t/search-syntax-documentation/9110

Some helpful search syntax:

`type:todo iscompleted:0 `
Finds all uncompleted tasks (this is the same as clicking on the “+” sign at the top of the folder list under “All Notebooks.” (unfinished ToDo’s are listed first). Added to a notebook or a tag, and you get all uncompleted todo's in that notebook or tag. Like this: 
`Tag: Vacation type:todo iscompleted:0`

Sometimes you don't remember what a note said but you remember when it was created or updated:

`created:202001 -created:202003` will return notes created on or after January and before March 2020.

`updated:1997-updated:2019`  will return all notes updated between the years 1997 and 2019.

`created:day-2` searches for all notes created in the past two days.

`updated:week-1` searches all notes updated lasst week.

## Organization tip for those just starting with note takers: 
It is recommended that, when you first start out, you do not worry too much about how your information is organized,  
Decide how you want to organize: Tags, or Folders. Choose one - avoid using both. It makes it easy to find needed information.
 

## Exporting and Importing: Backing up Joplin notes.
Joplin notes and folders can also be exported ***at any level*** by right-clicking the folder, you will have the option to export the selected folder and all subfolders and notes beneath it.

![Export](https://user-images.githubusercontent.com/17282079/229367268-6e7d22d7-db4f-4048-86ec-55f5fb20a418.png)

JEX is the native Joplin backup and restore, and is quick and accurate. Subfolders can be exported, moved to another profile or another copy of Joplin. Right-click the folder set, and select "Export". You then move or copy the the JEX file.  You import the result to the recipient Joplin - and presto!.
Other export/import options exist, for those who are building websites, HTML file, or directory is useful.


## Conclusion
This guide, it is hoped, will get you started using Joplin.  If you have a suggestion, please add it here.


