---
title: update history
---

## What is this page?
- this page shows you all of the updates in the lifespan of ores.rng, going all the way from release to where we are now.
- ores.rng updates are **signified with letters of the greek alphabet**
    - the first public release of the game was **beta (β)**, and the pre-release was **alpha (α)**
- the version with its dropdown already opened is the **latest version of ores.rng**

## Notation:

<body>

<t style="background_color:#6afa5c;">+ brand new content</t><br>
<t style="background_color:#6afa5c;">+= significant addition made to existing content</t><br>
= change<br>
<t style="background_color:#ff4a4a;">- removal</t><br>
<t style="background_color:#ffa33b;">! bugfix</t><br>
<t style="color:grey;">> more information about a change</t>

</body>

## Update history:

### gamma (γ)

<!--γ3 - turbowarped-->
<details open>
<summary>γ3 - turbowarped</summary>

<b>Published:</b> 14/01/2026<br>

Changes:<br>
<t style="background_color:#6afa5c;">+ added saving and loading (holy moly it’s about time)</t><br>
<t style="background_color:#6afa5c;">+ added many new buttons in the settings for saving and loading</t><br>
<t style="color:grey;">> autosave config, save data, and load data</t><br>
<t style="background_color:#6afa5c;">+= improved all ui yet again as i was not satisfied with the ui made in the original γ update</t><br>
= ported the entire game from scratch to an application in turbowarp, downloadable from this notion page <br>
<t style="background_color:#ffa33b;">! fixed a bug where buttons in the settings menu would sometimes appear behind the menu itself for reasons i can’t work out</t><br>
<t style="background_color:#ff4a4a;">- removed the requirement to press the spacebar to prove you’re on mobile, as it is no longer necessary</t><br>
<t style="background_color:#ff4a4a;">- removed the detector to see if you’re on turbowarp or not, as it is no longer necessary</t>

</details>

<!--γ2 - the little things-->
<details closed>
<summary>γ2 - the little things</summary>

<b>Published:</b> 16/12/2025<br>

Changes:<br>
<t style="background_color:#6afa5c;">+ added info modes to the index:</t><br>
<t style="color:grey;">> press E to change modes while inside of the index</t><br>
<t style="color:grey">> info mode 0 (default): shows the rarity of the ore and how many you have</t><br>
<t style="color:grey">> info mode 1: shows on what roll you last got the ore, with the adjusted rarity and the base rarity</t><br>
<t style="color:grey">>> when you have 0 of an ore, no data will show on info mode 1 when you click it</t><br>
= made TurboWarp a requirement to play the game, as it runs much better when playing on it!<br>
= changed the index to display VANITY instead of RARITY when clicking on an ore (basically, it displays the ore’s rarity with commas now!)<br>
= changed the way rarity is handled whenever 25x or 2500x luck rolls adjust the rarity<br>
<t style="color:grey">> instead of round(rarity/luck) it is now ceiling(rarity/luck)</t><br>
= changed the required key to verify you are on PC from E to Spacebar

</details>

<!--γ1.1 - hotfix-->
<details closed>
<summary>γ1.1 - hotfix</summary>

<b>Published:</b> 16/12/2025<br>

Changes:<br>
= added a verification system that verifies that you are on pc before playing - mobile is not supported in ores.rng!<br>
<t style="background_color:#ffa33b;">! fixed a bug that set the roll number to 1 upon the first launch of the game</t><br>
<t style="color:grey;">> i’m pretty sure this is at the fault of me, i saved the game when i had rolled once, so everything broke 😭</t><br>

</details>

<!--γ - index and inventory update-->
<details closed>
<summary>γ - index and inventory update</summary>

<b>Published:</b> 16/12/2025<br>


Changes:
<t style="background_color:#6afa5c;">+ added the INDEX</t><br>
<t style="color:grey;">> shows info about all ores in the game. shows their name, tier, rarity and how many you have (so it also couples as an inventory system!)</t><br>
<t style="color:grey;">> ores are darkened in the list until you get 1 of them, where it then becomes lighter</t><br>
<t style="color:grey;">> ores currently use rarity instead of vanity in the index, meaning no commas. this will be changed in a hotfix</t><br>
<t style="background_color:#6afa5c;">+ new rarity: MULTIVERSAL (1/5B+)</t><br>
<t style="background_color:#6afa5c;">+ 11 new ores</t><br>
<t style="background_color:#6afa5c;">+ added custom spawn messages for Unfathomable+ ores</t><br>
<t style="background_color:#6afa5c;">+ added 2500x luck rolls that occur every 10,000 rolls</t><br>
<t style="background_color:#6afa5c;">+= complete ui overhaul, making everything look a lot nicer</t><br>
<t style="color:grey;">> including: new button styles, new animations for opening/closing menus and some info being pushed to the top left corner</t><br>
<t style="color:grey;">> for clarification: there will NEVER be a tier greater than Multiversal in the game</t><br>
= made it so inputting no value in the autoroll config keeps the same value as before<br>
= changed 10x luck rolls to 25x luck rolls<br>
<t style="background_color:#ffa33b;">! fixed a bug where you could multi press the settings button and bug out the UI very easily</t><br>
<t style="background_color:#ffa33b;">! removed herobrine</t>

<pre>
Ores added:<br><br>
Surreal: Purpurite, Satistine, Caeruleum<br>
Mythic: Retronium, Luminite<br>
Transcendent: Aether<br>
Unfathomable: Exdeus<br>
Otherworldly: SCARLET, VANTABLACK<br>
Multiversal: SPYWARE LXXII, OBLIVION
</pre>

</details>