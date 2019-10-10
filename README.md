# Copy notes

Copies can share the same intervals, ease, etc. as the original note, but they can also be set as new notes (i.e., the intervals, ease, etc. do not copy over). [verify this is correct]


To copy a note:
1. Open the card browser
2. Select the desired notes (at least one card by note)
3. Go to "Edit > Copy and set to new" their shortcuts are configurable by default (Ctrl+C)

The copy preserves the original fields, tags, and remains in the same deck.

##Copy Note Instructions

The copy can have only new cards. Or they can have exactly the same
intervals, ease, etc... than the original card.

To copy a note: 
1. Open the card browser 
2. Select the desired notes
(at least one card by note) 
3. Go to "Edit > Copy and set to new" [shortcuts are configurable by default (Ctrl+C)]

The copy preserves the original fields, tags, and remains in the same
deck.
# Bug Warning

## 26 September 2019
In earlier versions of this add-on, a bug affected shared and imported decks.
If the decks contained one original note and one or more copies of that original note, 
only one of the multiple notes would be imported.

This add-on does two things to correct this bug.
### Correcting your collection
The first time you open a profile with this add-on installed, it'll
check whether your collection contains the bug and ask
whether you want to correct it or not. It only performs this check once. [Verify this is correct] 
You must synchronize the collection after the check 
and update any other devices that use Anki. [verify this is correct]

## Warning

### Bug in previous version Before the 26th of september 2019, there
was a bug in this add-on that affected shared and imported decks. If
the decks contained one original note and one or more copies of that
original note,  only one of the multiple notes would be imported.

This add-on does two things to correct this bug. 
### Correcting your collection 
The first time you open a profile with this add-on installed, it'll check whether 
your collection contains the bug and ask whether you want to correct it or not. 
It only performs this check once. You must synchronize the collection after the check and 
update any other devices that use Anki. [verify this is correct]

### Correcting imports with this bug 
Anki will try to detect when this bug exists in a deck you import and correct the issue. 
In this case, it will also tell you to notify the decks' author that they should update their deck. 
Since this changes the Anki's default import function, a part of Anki which should not be touched by an add-on whose purpose is only to copy notes, you can deactivate it in the configurations. [Verify -- This section is unclear. Why would it recommend that the deck's author update it? Do you mean that the add-on alters Anki's default importer, so it throws an error?]

### Empty cards Empty cards are not copied by this add-on. 
If you don't know what it means, you probably doesn't need to worry about this.

### Incompatibilites This add-on is currently incompatible with: 
* add-on [Show duplicates](https://ankiweb.net/shared/info/865767531)

## Configuration Using the add-on configuration, you can: 
* change the shortcut. 
* decide whether you keep creation time or set it to current time. 
* decide whether you keep interval, due date, number of lapse, etc...

## Configuration "Preserve creation time": 
if set to true [verify this is correct], the card and note's creation time are preserved.
Otherwise, it is set to the copy's creation time.

## Links, licence and credits

Key         |Value
------------|-------------------------------------------------------------------
Copyright   |Arthur Milchior <arthur@milchior.fr> Based on    |Kealan
Hobelmann's addon 396494452 (for anki 2.0) Based on    |Anki code by
Damien Elmes <anki@ichi2.net> License     |GNU AGPL, version 3 or
later; http|//www.gnu.org/licenses/agpl.html Source in  
|https://github.com/Arthur-Milchior/anki-copy-note Addon number|
[1566928056](https://ankiweb.net/shared/info/1566928056) Support me
on|
[![Ko-fi](https://ko-fi.com/img/Kofi_Logo_Blue.svg)](Ko-fi.com/arthurmilchior)
or
[![Patreon](http://www.milchior.fr/patreon.png)](https://www.patreon.com/bePatron?u=146206)


### Correcting imports with this bug
Anki will try to detect when this bug exists in a deck you import. In
this case, it'll correct it and tell you to tell to the decks' author
that it should update this deck. Since this change the importer, a
part of anki which should not be touched by an add-on whose purpose is
only to copy notes, you can deactivate it in the configurations.


### Empty cards
Empty cards are not copied by this add-on. If you don't know what it means, you probably doesn't need to worry about this.


### Incompatibilites
This add-on is currently incompatible with:
* The add-on [Show duplicates](https://ankiweb.net/shared/info/865767531)


## Configuration
Using the add-on configuration, you can:
* change the shortcut.
* decide whether you keep creation time or set it to current time.
* decide whether you keep interval, due date, number of lapse, etc...

## Configuration
"Preserve creation time": if set to true [verify this is correct], the card and note's creation time are preserved. Otherwise, it is set to the copy's creation time.

## Links, licence and credits

Key         |Value
------------|-------------------------------------------------------------------
Copyright   |Arthur Milchior <arthur@milchior.fr>
Based on    |Kealan Hobelmann's addon 396494452 (for anki 2.0)
Based on    |Anki code by Damien Elmes <anki@ichi2.net>
License     |GNU AGPL, version 3 or later; http|//www.gnu.org/licenses/agpl.html
Source in   |https://github.com/Arthur-Milchior/anki-copy-note
Addon number| [1566928056](https://ankiweb.net/shared/info/1566928056)
Support me on| [![Ko-fi](https://ko-fi.com/img/Kofi_Logo_Blue.svg)](Ko-fi.com/arthurmilchior) or [![Patreon](http://www.milchior.fr/patreon.png)](https://www.patreon.com/bePatron?u=146206)
