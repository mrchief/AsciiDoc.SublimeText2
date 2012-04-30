AsciiDoc Package for Sublime Text 2                    
===================================
This is an [AsciiDoc](http://www.methods.co.nz/asciidoc/) package for [Sublime Text 2 editor](http://www.sublimetext.com/).

It adds syntax highlighting and snippets for AsciiDoc language to Sublime Text 2 editor.

My work is based on the Christian Zuckschwerdt's [AsciiDoc TextMate bundle](https://github.com/zuckschwerdt/asciidoc.tmbundle).

Sublime Text 2 is compatible with Textmate editor for OS X snippets, preferences and languages file. 
However, even though it can recognize the Textmate snippets, some features such as tab completion, shortcut commands do not work out of the box.

My work is to overcome these limitations.

All the files provided here are tested in Windows 7 and OS X Lion. 

Installation
------------
To install the package, follow these steps:

 - Download the zip containing src files.
 - Extract the files to *AsciiDoc* folder (create this folder if not present already) under:
	- Windows: `%APPDATA%\Sublime Text 2\Packages\`    
	- OS X: `~/Library/Application Support/Sublime Text 2/Packages`
	- Linux: `~/.config/sublime-text-2`
	- Portable Installation: `Sublime Text 2/Data`   
 - Close all instances of Sublime Text 2 editor and relaunch the editor.  

If successful, you should see **AsciiDoc** entry under `View > Syntax` and under `Tools > Snippets`.

**Note**: Snippets may take few seconds to load under Windows.

Usage
-----
 - Create a new file, save it as `<filename>.asc`
 - Start typing AsciiDoc!

Snippets
--------
Snippets can be inserted anywhere by using the menu command `Tools > Snippets > AsciiDoc` or by typing two initial characters and hitting tab to complete.
Few tab completion examples are:

 - Comments (type `// TAB`)
 - Headings (type `h1 TAB` to `h4 TAB` for one-liner versions)
 - Table generation (type `|= TAB`) 
 - Tab expansion for blocks (type `== TAB`)  
 - Sidebar block (type `** TAB`) 

Keyboard Shortcuts
-------- 
Basic support for some handy shortcuts are now available:

 - **Bold** selection: Select some text and then press `ctrl+b`
 - _Italic_ize selection: Select some text and then press `ctrl+i`
 - Mark selection as Code literal: Select some text and then press `ctrl+k`

**Note**: `ctrl+b` overrides the standard key binding of `Tools > Build System`. If this bothers you, you can edit the `.sublime-keymap` files (based on your OS) under `Packages\AsciiDoc` folder.

Time permitting, I'll add more shortcuts but meanwhile if you come upon something useful, feel free to submit a patch!

Enhancements
------------

Following are planned enhancements for the package:

 - <strike>Add keyboard shortcuts for various commands such bold text, italics, blocks etc.</strike>
 - Adding Build system to preview as HTML or PDF.
                                                   
Your suggestions are welcome.       

Author & Credits
----------------

Created by Hrusikesh Panda. Copy left or right, as you wish.                                         

Credit goes to Christian Zuckschwerdt for his original work on AsciiDoc TextMate bundle.
