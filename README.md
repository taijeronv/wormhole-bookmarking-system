![Image](https://i.imgur.com/Fo1WK7H.png)

**Bookmarking & Scanning Procedures**


_It's a very easy system, that's very easy to explain badly_
-Alerean

This is a guide to procedures optimal when scanning and bookmarking in EVE Online. It is expected that you follow these procedures to make life easier for all alliance members and maximize PVP opportunities! 

 If you are in the chain doing **anything** you should be on voice comms! If you find something or something finds you it can be the difference between getting kills and being killed, or missing a fight all together.

 This guide will reference  [siggy](https://siggy.borkedlabs.com), one of EVE's oldest wormhole scanning tools. However what scanning tool you use is irrelevant and you can use whichever you prefer. [Pathfinder](https://www.pathfinder-w.space/) and [Tripwire](https://tripwire.eve-apps.com/) are great alternatives!

# Bookmarking

## Labelling wormholes
- `0` is homesys
- `1` signifies a static wormhole (Never a K162)
- `2`-`9` signifies a non-static wormhole (K162 or if it is not the static listed on siggy)
- `null` signifies a hole to 0.0 (Null Sec)
- `low` signifies a hole to 0.1-0.4 (Low Sec)
- `high` signifies a hole to 0.5-1.0 (High Sec)
- `'insert letter'1` signifies a wormhole chain that branches off a k-space in the chain (EG `N1`, `H1`, `L1`, or any other letter if more than one in the chain. 

Wormholes are a passage with an entry and an exit. The entry side will have a name like `W237` or `V911`. The exit side will always be `K162`.
- Home system is always signified by `0`
- The static from home system is always signified by `1`

Each new wormhole system added to the chain is labelled by adding a digit to the label of the hole that you are currently in, depending on whether it is a static (add `1`) or a non-static (add `2` through `9`).


### Where there is more than one non-static
The first found is labelled by adding a `2` to the end of the label for your current system. 
EG. `11-112`

The next non static found in the same system adds a `3` to the end of the label and so on. 
EG. `11-113`

There is always a static hole to be found in each wormhole you enter and as long as you scan down the static chain you will eventually end in known space (k-space - null, low or high) unless you manage to loop around and reconnect to a system in your current chain.

There can also be randomly spawned k-space wormholes (null, low and/or high) in any system.

However, remember when scanning a non-static system the static is the hole that you have come into that system from so if no other holes are connected to that system it can be a dead end. If there are other holes connected to the non-static they will also be non-static or they will be randomly spawned k-space holes.

An example of a static chain: `0 - 1 - 11 - 111 - 4x1 - 5x1 - 6x1`


## Bookmarking wormholes
Wormhole bookmarks have two important parts seperated by `-`

The first part of the bookmark is the label of the system you are currently in. The second part of the bookmark is the label of the system that the wormhole leads to. 
EG. `11-111`

### There are a few other important principles: 

1. FOUR OR MORE of the same number should be abbreviated
EG. `11111` = `5x1`
2. Known space holes should be edited with the name of the system, so that multiple holes can be easily differentiated.
EG. `111-null (YKE4-3)` or `4x1-high (Ashab)` or `5x1-low (Maila)`
3. The holes that enter wormhole space from k-space don't require the extra information, the bookmarks as viewed in your "People and Places" or clicking on the system in siggy will tell you what system it is in if you can't use siggy at the time.
EG. `low-4x1`
4. If you encounter a wormhole in k-space, you start a new chain number and name the hole `X1` or `N1` or `Z1` or `whatever1`. Then the next hole you find in the `X1` system will be `X11` or `X12`, etc.

## Sites & Signatures
The standard method for bookmarking signatures is up to your corporation or alliance. Here's two popular methods.

### The first method helps to order the list by type of site but is only useful when bookmarking wormhole sites. 

`G-Bountiful-XYZ`
- `G` = Gas, `D` = Data, `R` = Relic, `A` = Anomaly 
- The name of the site removing the two words that are the same for each site type to shorten the bookmark (Gas sites remove "Perimeter Deposit/Reservoir", Data and Relic remove the "Unsecured/Forgotten Core") 
- `###` Signature as marked on siggy 

### The second is applicable to signature bookmarking in all types of space.

`G-XYZ-Bountiful Frontier Reservoir`
- `G` = Gas, `D` = Data, `R` = Relic, `A` = Anomaly, `C` = Complex 
- `###` Signature as marked on siggy
- Full name of the site (which automatically comes up when you click "Save Location") 

When clearing gas site of Sleepers you should consider bookmarking the clouds even if you don't intend to gas them (other people might have the time, even for those crappy clouds). When bookmarking gas clouds the following convention helps determine what size and type of cloud it is while also telling the user which site it is in. 

`c320-Vital-XYZ`
- Gas Type 
- Site Type 
- Signature of the Site 


# Scanning

## When first entering a system

### Before you decloak:
- Bookmark the wormhole you just came through (refer to bookmarking section) 
- Use your directional scanner (d-scan) and look for activity/structures in range of your entry wormhole. Make sure wrecks are visible on your d-scan filter so you can find targets doing sites as soon as possible!

### Before you drop probes:
1. If nothing appears to be active
- Warp around the system and look for activity
- Locate any interesting structures in system and update the Intel tab on siggy. Remove any outdated information.

2. If during this time you find activity
- Report them in an appropriate channel. Link pilot name and ship type as well as any other information like "sitting on pos at P1M3" or "on d-scan near P4"
- Report on comms if the ships appear to be moving, doing sites (wrecks on scan are a giveaway), doing logistics (haulers coming onto and off of scan).

3. Update the siggy map
- The static chain should be positioned in as straight a line as possible to the right of homesys. You can move the position of a system by clicking 'Options > Edit Map' on the bottom left hand corner of the map and dragging the systems around. 
- Update the system information by right clicking the system select 'edit'. This will bring up a window of system information. 
- Update the systems activity level. (Green = Empty = No online POS / Yellow = Occupied = Online POS but no active pilots spotted / Red = Active pilots have been reported in system) 
- If the wormhole is not part of the static chain edit the system name to help with navigation. Standard labelling with the system class EG. `11122 (C3)`

### Finally drop probes and start scanning:
**Add the signatures to siggy**
1. In the Probe Scanner window and hit `Ctrl+A` to select all of the signatures, then hit `Ctrl+C` to copy them
2. Open siggy. Click on the system you're in, scroll down to "[+] Mass Sig Reader" and click to open the input window
3. Hit `Ctrl+V` to paste the signatures you copied into the window and then click Submit. This will add all of the signatures in the system into siggy
4. Now that all the sigs are added you can hit your preferred formation button and it will reactivate the probes you have out 
5. Start scanning them down and update the Type and Description on siggy as you scan or by using the Mass Sig Reader when you're done.

### When adding wormholes to siggy
**Make sure you fill out all the appropriate siggy fields completely.**
1. 'Type' should be set to `WH`
2. Under 'Name/Description' select the correct wormhole type like `K162 (from Dangerous unknown)` from the drop down menu. In the text box add the wormhole name EXACTLY as you bookmarked it. EG. `12-122`
3. Check the wormhole status and update the wormhole information by clicking on the link between two systems on the map. The menu that pops up allows you to set the hole as EOL, mark it as a frigate wormhole and/or modifying the mass stage so that it is visible on the siggy map.
4. If you encounter a wormhole to k-space you can use a temporary label to identify it until you jump through however the optimal labelling for k-space wormholes is `11-high (Boranai)` or `11-null (H-ADOC)` or `11-low (Maila)`, NOT `11-null1`. Having systems labelled as `null1` `null2` `null3` leads to confusion when you can see the fleet in a system on siggy but don't know which bookmark to use.

### Updating the bookmark can
This only applies for wormhole alliances living in one and the same wormhole. You are not finished scanning before you've updated the bookmark can, as only your corp has the current bookmarks.
- Remove the old bookmarks and trash them
- Put in a full set of current bookmarks
- Inform about updated bookmarks in an appropriate channel.

### When moving through a chain that is already scanned. (Whether you are in a scan ship or not!)
- Check d-scan for new hostiles! 
- Use your system scanner to check for new sigs by adding the list using `Ctrl+A` to siggy. It takes no time and can be done while in warp to the next WH.

# Final words and changelog
Any thoughts, correction or additions are welcome please shoot Xtrah a message or raise an [issue](https://github.com/Xtrah/wormhole-bookmarking-system/issues) and I'll update this.

2014: Updated to include the Scanning Guide provided by Domin Ique

2016: Updated with new standards used in Overload This

2019: Updated and published publicly