---
title: update history
---

## What is this page?
- this page shows you all of the updates in the lifespan of ores.rng, going all the way from release to where we are now.
- ores.rng updates are **signified with letters of the greek alphabet**
    - the first public release of the game was **beta (β)**, and the pre-release was **alpha (α)**
- the version with its dropdown already opened is the **latest version of ores.rng**

## Notation:
```diff
+ brand new content
+= significant addition made to existing content
= change
- removal
! bugfix
# explanation of change
```

## Update history:

### gamma (γ)

<!--γ3 - turbowarped-->
<details open>
<summary>γ3 - turbowarped</summary>

**Published:** 14/01/2026

> ```diff
> Changes:
> + added saving and loading (holy moly it’s about time)
> + added many new buttons in the settings for saving and loading
> # autosave config, save data, and load data
> += improved all ui yet again as i was not satisfied with the ui made in the original γ update
> = ported the entire game from scratch to an application in turbowarp, downloadable from this notion page
> ! fixed a bug where buttons in the settings menu would sometimes appear behind the menu itself for reasons i can’t work out
> - removed the requirement to press the spacebar to prove you’re on mobile, as it is no longer necessary
> - removed the detector to see if you’re on turbowarp or not, as it is no longer necessary
> ```

</details>

<!--γ2 - the little things-->
<details closed>
<summary>γ2 - the little things</summary>

**Published:** 16/12/2025

> ```diff
> Changes:
> + added info modes to the index:
> # press E to change modes while inside of the index
> # info mode 0 (default): shows the rarity of the ore and how many you have
> # info mode 1: shows on what roll you last got the ore, with the adjusted rarity and the base rarity
> # when you have 0 of an ore, no data will show on info mode 1 when you click it
> = made TurboWarp a requirement to play the game, as it runs much better when playing on it!
> = changed the index to display VANITY instead of RARITY when clicking on an ore (basically, it displays the ore’s rarity with commas now!)
> = changed the way rarity is handled whenever 25x or 2500x luck rolls adjust the rarity
> # instead of round(rarity/luck) it is now ceiling(rarity/luck)
> = changed the required key to verify you are on PC from E to Spacebar
> ```

</details>

<!--γ1.1 - hotfix-->
<details closed>
<summary>γ1.1 - hotfix</summary>

**Published:** 16/12/2025

> ```diff
> Changes:
> = added a verification system that verifies that you are on pc before playing - mobile is not supported in ores.rng!
> ! fixed a bug that set the roll number to 1 upon the first launch of the game
> # i’m pretty sure this is at the fault of me, i saved the game when i had rolled once, so everything broke 😭
> ```

</details>

<!--γ - index and inventory update-->
<details closed>
<summary>γ - index and inventory update</summary>

**Published:** 16/12/2025

> ```diff
> Changes:
> + added the INDEX
> # shows info about all ores in the game. shows their name, tier, rarity and how many you have (so it also couples as an inventory system!)
> # ores are darkened in the list until you get 1 of them, where it then becomes lighter
> # ores currently use rarity instead of vanity in the index, meaning no commas. this will be changed in a hotfix
> + new rarity: MULTIVERSAL (1/5B+)
> + 11 new ores
> + added custom spawn messages for Unfathomable+ ores
> + added 2500x luck rolls that occur every 10,000 rolls
> += complete ui overhaul, making everything look a lot nicer
> # including: new button styles, new animations for opening/closing menus and some info being pushed to the top left corner
> # for clarification: there will NEVER be a tier greater than Multiversal in the game
> = made it so inputting no value in the autoroll config keeps the same value as before
> = changed 10x luck rolls to 25x luck rolls
> ! fixed a bug where you could multi press the settings button and bug out the UI very easily
> ! removed herobrine
> ```
>
> <pre>Ores added:</br></br>Surreal: Purpurite, Satistine, Caeruleum</br>Mythic: Retronium, Luminite</br>Transcendent: Aether</br>Unfathomable: Exdeus</br>Otherworldly: SCARLET, VANTABLACK</br>Multiversal: SPYWARE LXXII, OBLIVION</pre>

</details>