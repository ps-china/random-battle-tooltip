Random Battle Tooltip
========================================================================

This a tooltip made to be used with Pokemon Showdown's Unrated Random Battle mode using open source code from the Pokemon Showdown server.
The tooltip provides useful data on an enemy's item, ability, moves, and stats that exceeds data found on the default tooltip.
Data is expressed in percentages. This data changes dynamically as the enemy reveals some of their information over the course of a game.

Warnings
------------------------------------------------------------------------

Use of the tooltip on anything but a Unrated Random Battle will have no effect.
In particular, the tooltip will not appear on Rated Random Battles.
As time passes, this tooltip will become slightly outdated as the data files change slightly. Use at your own risk.

How to install
------------------------------------------------------------------------

You just need a way of uploading and running a Javascript file. The best way to install is with Google Chrome:
Right-click anywhere on Pokemon Showdown, and click on "Inspect". In the tabs on the near the top, click on Sources.
This should open a tab of "Sources", "Content Scripts", and "Snippets". If you only see 1 or 2, click on the ">>".
Select the "Snippets" tab, and create a new snippet. This should open a text box on the right side of your screen.
Copy/Paste the text of the tooltip file into this textbox. Be sure to hit Ctrl+S to save it, and viola!

This probably works with other browsers but I cannot guanrantee this.

How to run
------------------------------------------------------------------------

To activate the tooltip, go to back to the snippet. Right-click the file "Script snippet #1" (or whatever you named it) and hit run.
The tooltip will remain activated for all random battle games until the Google Chrome tab is closed.
Once it is run, there is no need to reactivate it until you close the entire Google Chrome tab.
Closing the tab does not delete the snippet.

Issues
------------------------------------------------------------------------

Sometimes you will see "No viable sets found!" This is usually normal behavior if the pokemon is unconventional (like Shuckle).
However if you see this for a somewhat conventional pokemon (like Bisharp) or see an invalid number or negative number, report the issue at GitHub.