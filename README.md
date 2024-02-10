[Try it here](https://speff.github.io/tw-speff/)

# EdgeScribe
### **Original description/plugin from twMat [here](https://sideeditor.tiddlyhost.com/)**
EdgeScribe floats a tiddlers editor by the story river side.

You see the changes live in the tiddler and you can scroll to, and reference, stuff from other tiddlers while you edit.

## Usage

* Activate EdgeScribe by clicking the tiddler tool or page tool
* Re-size it via the "handle bars" at upper-right and lower-left corner
* Switch focus between the River and EdgeScribe by hovering

## Split-out window

* Distraction free authoring by maximizing the window __(Do test it!)__
* Stick window by using 3'd party software (e.g) to easily collect data from other applications and tabs into your wiki

Mat von TWaddle <:-)

------------------

## —Changes + Updates—

* Now able to open+edit multiple tiddlers in their own popped out windows
^my main motivation for the refactor^
* Ctrl+Enter while editing a tiddler saves/closes the editor
* Cursor focuses on EdgeScribe window when the editor is created
* Added logic to prevent a tiddler from being overwritten
    * Default behavior is to ignore the user-provided title on name clash
    * This can be changed in the new Settings menu (under $:/ControlPanel -> Settings -> EdgeScribe)
* Added the ability to change the default tiddler type when making a new one through the Add button (also in the Settings menu)
* Added new ViewToolbar and PageToolbar buttons to directly open tiddler editor in a new
    * Enable them in the $:/ControlPanel (Appearance -> Toolbars -> Page|View Toolbar)

### Removed functionality

* Cannot edit tiddlers tagged as `$:/tags/Macror` or `$:/tags/Global`
* Sidebar does not appear in front of EdgeScribe on hover

Speff

