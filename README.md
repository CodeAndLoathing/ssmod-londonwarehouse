# ssmod-londonwarehouse

SunlessSea Mod : CNL London Warehouse
=====================================

This Sunless Sea mod adds a warehouse you can purchase to Fallen London which may be used to store items via the shop interface.

This is an unofficial fan work. Fallen London and Sunless Sea are © 2015 and ™ Failbetter Games Limited: www.failbettergames.com
The artwork included with this mod is from Sunless Sea and should only be used with a licensed copy of Sunless Sea.

Installation
------------
MAKE A BACKUP OF YOUR SAVE FILE BEFORE YOU CONTINUE.

Extract the contents of the zip file and copy the cnl-warehouse folder to your addons folder.
It should end up looking like SunlessSea/addon/cnl-warehouse/entities etc. 

Then copy the images in inside SunlessSea/addon/cnl-warehouse/images to SunlessSea/images/sn/icons/

(the addons mechanism doesn't currently support images inside the /addon folder)


Removal
-------
FIRST SELL THE WAREHOUSE BEFORE YOU CONTINUE - THIS SHOULD CLEAN UP ANY PROPERTIES IN YOUR SAVE FILE ADDED FOR THE MOD.

Then just delete the cnl-warehouse folder from within the /addons folder.
If you do not sell the warehouse first, bad things can happen (tm). And by that I mean you may have to delete qualities by hand out of your save file.

Usage
-----
The mod adds a new menu item in Fallen London : Wolfstack Docks

From the Wolfstack Docks menu you can buy (or sell) your warehouse.

You can also "activate" the warehouse - this hides the regular shops and instead shows your warehouse under the shops tab.

You can re-activate the regular shops from the Wolfstack Docks menu. (alternatively, leaving London and re-docking will also restore the regular shops).

To actually store and unstore fuel for example, you would use the shop interface to sell 1 fuel for 1 "stored fuel", and buy 1 fuel at the cost of 1 "stored fuel".
Your current stored inventory can be tracked in your Hold under Curiosities.


Latest Version
--------------
For the latest version see [https://github.com/CodeAndLoathing/ssmod-londonwarehouse/releases]


JSON IDs
--------
Setting    6100000 ....... display warehouse exchange
Qualities  6100001 6100199
Exchanges  6100200 6100219
Events     6100220 6100299