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

<t style="background-color:#b6ff96;">+ brand new content</t><br>

<t style="background-color:#b6ff96;">+= significant addition made to existing content</t><br>

<t style="background-color:#ebebeb;">= change</t><br>

<t style="background-color:#faaaaa;">- removal</t><br>

<t style="background-color:#ffd096;">! bugfix</t><br>

<t style="color:grey;">> more information about a change</t>

</body>

## Update history:

### gamma (γ)

<!--γ3 - turbowarped-->

<details open>
<summary><b>γ3</b> - turbowarped</summary>
<br>
<b>Published:</b> 14/01/2026<br><br>

Changes:<br>
<t style="background-color:#b6ff96;">+ added saving and loading (holy moly it’s about time)<br>
+ added many new buttons in the settings for saving and loading</t><br>

<t style="color:grey;">> autosave config, save data, and load data</t><br>

<t style="background-color:#b6ff96;">+= improved all ui yet again as i was not satisfied with the ui made in the original γ update</t><br>

<t style="background-color:#ebebeb;">= ported the entire game from scratch to an application in turbowarp, downloadable from this notion page</t><br>

<t style="background-color:#faaaaa;">- removed the requirement to press the spacebar to prove you’re on mobile, as it is no longer necessary<br>
- removed the detector to see if you’re on turbowarp or not, as it is no longer necessary</t><br>

<t style="background-color:#ffd096;">! fixed a bug where buttons in the settings menu would sometimes appear behind the menu itself for reasons i can’t work out</t><br>

<br>
</details>

<!--γ2 - the little things-->

<details>
<summary><b>γ2</b> - the little things</summary>
<br>
<b>Published:</b> 16/12/2025<br><br>

Changes:<br>
<t style="background-color:#b6ff96;">+ added info modes to the index:</t><br>

<t style="color:grey;">> press E to change modes while inside of the index<br>
> info mode 0 (default): shows the rarity of the ore and how many you have<br>
> info mode 1: shows on what roll you last got the ore, with the adjusted rarity and the base rarity<br>
>> when you have 0 of an ore, no data will show on info mode 1 when you click it</t><br>

<t style="background-color:#ebebeb;">= made TurboWarp a requirement to play the game, as it runs much better when playing on it!<br>
= changed the index to display VANITY instead of RARITY when clicking on an ore (basically, it displays the ore’s rarity with commas now!)<br>
= changed the way rarity is handled whenever 25x or 2500x luck rolls adjust the rarity</t><br>

<t style="color:grey;">> instead of round(rarity/luck) it is now ceiling(rarity/luck)</t><br>

<t style="background-color:#ebebeb;">= changed the required key to verify you are on PC from E to Spacebar</t><br>

<br>
</details>

<!--γ1.1 - hotfix-->

<details>
<summary><b>γ1.1</b> - hotfix</summary>
<br>
<b>Published:</b> 13/12/2025<br><br>

Changes:<br>
<t style="background-color:#ebebeb;">= added a verification system that verifies that you are on pc before playing - mobile is not supported in ores.rng!</t><br>

<t style="background_color:#ffd096;">! fixed a bug that set the roll number to 1 upon the first launch of the game</t><br>

<t style="color:grey;">> i’m pretty sure this is at the fault of me, i saved the game when i had rolled once, so everything broke 😭</t><br>

<br>
</details>

<!--γ - index and inventory update-->

<details>
<summary><b>γ</b> - index and inventory update</summary>
<br>
<b>Published:</b> 10/12/2025<br><br>

Changes:<br>
<t style="background_color:#b6ff96;">+ added the INDEX</t><br>

<t style="color:grey;">> shows info about all ores in the game. shows their name, tier, rarity and how many you have (so it also couples as an inventory system!)<br>
> ores are darkened in the list until you get 1 of them, where it then becomes lighter<br>
> ores currently use rarity instead of vanity in the index, meaning no commas. this will be changed in a hotfix</t><br>

<t style="background-color:#b6ff96;">+ new rarity: MULTIVERSAL (1/5B+)<br>
+ 11 new ores<br>
+ added custom spawn messages for Unfathomable+ ores<br>
+ added 2500x luck rolls that occur every 10,000 rolls</t><br>

<t style="background-color:#b6ff96;">+= complete ui overhaul, making everything look a lot nicer</t><br>

<t style="color:grey;">> including: new button styles, new animations for opening/closing menus and some info being pushed to the top left corner<br>
> for clarification: there will NEVER be a tier greater than Multiversal in the game</t><br>

<t style="background-color:#ebebeb;">= made it so inputting no value in the autoroll config keeps the same value as before<br>
= changed 10x luck rolls to 25x luck rolls</t><br>

<t style="background-color:#ffd096;">! fixed a bug where you could multi press the settings button and bug out the UI very easily<br>
! removed herobrine</t>
<br>

<pre>
Ores added:

Surreal: Purpurite, Satistine, Caeruleum
Mythic: Retronium, Luminite
Transcendent: Aether
Unfathomable: Exdeus
Otherworldly: SCARLET, VANTABLACK
Multiversal: SPYWARE LXXII, OBLIVION
</pre>

<br>
</details>