## VEMF Changelog

#### `v1.0727.9`
**[ADDED]** Option to disable/enable mission announcements <br />
<br />

#### `v1.0727.3`
**[CHANGED]** Exile_VEMF is now called Exile_VEMF_Reloaded because the original creator of VEMF is proceeding on VEMF <br />
**[ADDED]** S.W.A.T. AI <br />
**[ADDED]** Option to send kill messages only to the killer (@KillingRe) <br />
<br />

#### `v1.0725.6`
**[NEW]** Option to control deletion of .50 cals when mission done <br />
**[IMPROVED]** Respect reward system <br />
**[FIXED]** Players getting respect if AI kill other AI <br />
<br />

#### `v1.0724.1`
**[NEW]** Option to control distance between each mission <br />
**[CHANGED]** Server-side folder is now called Exile_VEMF <br />
<br />

#### `v1.0723.1 HOTFIX`
**[FIXED]** fn_aiKilled.sqf: error Undefined variable in expression unit <br />
<br />

#### `v1.0722.15`
**[NEW]** Player now get reputation for killing AI. Dynamically increases depending on kill distance <br />
**[FIXED]** Unstable fn_random.sqf <br />
<br />

#### `v1.0721.15`
**[NEW]** AI will now spawn in houses <br />
**[NEW]** Mounted (bipod) .50 cals in/on houses if enabled <br />
**[ADDED]** Option to enable/disable AI "Cop mode" <br />
**[CHANGED]** fn_spawnAI.sqf to allow spawning in houses <br />
**[TWEAKED]** fn_loadInv.sqf <br />
<br />
#### `v1.0721.1`
**[FIXED]** fn_spawnAI.sqf: Suspending not allowed in this context, line 72 <br />
<br />

#### `v1.0720.6`
**[NEW]** Automatic removal of loot crate marker when player gets close <br />
**[ADDED]** Option to enable/disable mission markers <br />
**[ADDED]** Ability to put `maxGlobalMissions` on -1. Disables the mission limit <br />
**[ADDED]** Exile default safe zones to mission blacklist positions <br />
**[ADDED]** Option to enable/disable loot crate markers <br />
**[ADDED]** Option to enable/disable loot crate parachute spawn <br />
**[ADDED]** Option to enable/disable loot crate visual smoke/chemlights <br />
**[ADDED]** Option to enable/disable loot crate spawn sound (once) <br />
**[ADDED]** Logging of successfull removal/exploding of mines <br />
**[ADDED]** Code changes to fn_missionTimer.sqf to allow ignoring of global mission count <br />
**[ADDED]** Code changes to DLI mission to prevent removal of non-existing mission marker <br />
**[CHANGED]** several config options from negative to positive <br />
**[CHANGED]** Default debug mode from 2 to 0 (errors only) <br />
**[CHANGED]** AI difficulty config now less lines <br />
**[CHANGED]** AI Veteran and Harcore difficulty increased <br />
**[CHANGED]** Mines are now switched off by default <br />
**[CHANGED]** Default mine removal mode is now explode <br />
**[CHANGED]** fn_loadLoot.sqf: now empties the crate instead of the mission itself <br />
**[FIXED]** Error in expression fn_findPos.sqf <br />
**[FIXED]** Error in expression fn_loadInv.sqf with specific set of config settings <br />
<br />

#### `v1.0719.10`
**[ADDED]** Option to enable/disable the placement of a marker on the loot crate <br />
**[ADDED]** Attempt to fix the floating crate problem <br />
**[ADDED]** Fail-safety for fn_checkPlayerPresence.sqf <br />
**[ADDED]** Fail-safety for fn_placeMines.sqf <br />
**[ADDED]** Fail-safety for fn_spawnAI.sqf <br />
**[CHANGED]** Default value of `validateLoot` from 1 to -1 <br />
**[REMOVED]** Option to enable/disable sound on the loot crate <br />
**[FIXED]** Mines not removing or exploding <br />
**[FIXED]** Structure error in fn_findPos.sqf <br />
<br />
#### `v1.0718.11`
**NOTE:** VEMFclient code has been changed! <br />
**[ADDED]** AI difficulty presets<br />
**[CHANGED]** Default cleanMines setting changed from 2 to 1 <br />
**[CHANGED]** fn_broadCast.sqf for new broadcast system <br />
**[CHANGED]** fn_loadLoot.sqf: fail-safety removed <br />
**[CHANGED]** fn_spawnAI.sqf: implementation of AI difficulty presets <br />
**[CHANGED]** Veteran AI difficulty lowered. Too close to aimbots <br />
**[FIXED]** Duplicate spawns on locations <br />
**[FIXED]** Player getting side ENEMY for attacking AI <br />
**[FIXED]** Loot crate not falling down <br />
**[FIXED]** Loot crate not making a sound <br />
<br />
#### `v1.0717.7`
**[FIXED]** No loot in crate <br />
**[FIXED]** AI not shooting at player <br />
<br />

#### `v1.0716.14`
**[NEW]** VEMF ported to Exile :) <br />
<br />
