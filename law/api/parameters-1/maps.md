---
description: Set the maps where a law module will trigger.
---

# Maps

* Separate with commas, no spaces allowed for each map name. 
* `*` __in front of a name if you want the challenge to match maps **CONTAINING** that name. Otherwise, the challenge will match maps with the exact naming. 
* `#` at the end of a map name if you want the challenge to match case-sensitively. 
* `!NOT` at the end of a map name if you don't want the challenge to track in that map.

## Mann vs Machine

* To indicate a Mann vs Machine mission, simply indicate its mission/popfile name after the map name. A mission called Ambush on mvm\_decoy, will be `mvm_decoy_Ambush`. 
* To indicate a specific wave of a mission, add `;wave<number>` behind the map \(map\_mission\) name. For example, `mvm_decoy_Ambush;wave3` to indicate the 3rd wave of Ambush mission on mvm\_decoy.

**Note that if you are indicating that a challenge can be done in any mission of a MvM map, it should include a `*` infront of the map name. Otherwise, it can only be done in the default mission of that map.**

