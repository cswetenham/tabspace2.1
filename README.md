TabSpace port for Twiddler 2.1
==============================

The TabSpace Layout
-------------------

The TabSpace layout was originally written by Brandon Craig Rhodes for an earlier version of the Twiddler, with a different set of modifier keys and a different config file format. It is intended to optimise access to frequent characters and character combinations. This port is based on the following documents.

Description: http://rhodesmill.org/brandon/projects/tabspace-guide.pdf
Reference: http://rhodesmill.org/brandon/projects/tabspace-ref.pdf
Config file: http://rhodesmill.org/brandon/projects/tabspace.ini

Files
-----

PDF and CFG files are provided for each variant of the layout: US and UK keyboard (UK just swaps " and @), with letter pair and triple chords enabled or disabled.

Caveats
-------

* The original TabSpace layout uses the FN key as a modifier; since the Twiddler 2.1 doesn't have this key, I have used NUM instead.

* I have left out the NUL and LF characters from the orginal TabSpace layout as I couldn't find a way to enter them.

* I left out the extra Emacs keys in the original TabSpace layout (see tabspace.ini)

* The Twiddler 2.1 mouse mode, upgrade, and mass storage keys are unchanged

* Twiddler firmware versions earlier than 122 have some issues with the multi-character chords. To upgrade your firmware, see handykey.com/support.html

* I haven't defined chords yet for Application, GUI Left, GUI Right, which I assume are equivalent to the Windows keys and aren't included in the original TabSpace layout. I am still investigating how these work with the Twiddler 2.1
