# Upcoming

Fixed broken lights optimization system causing massive amount of lag.

# January 3rd 2025 (Version 0.3.47 V2) - Playtest

* Added a new achievement
* Added new lights and characters culling system, performance should see significant improvements
* Added sparks on train when braking
* Fixed NullReference error spam about lightcontrollers
* Fixed hotel beds not remembering being rented out (issue [#3353](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3353))
* Fixed sky not updating (issue [#3356](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3356))
* Fixed start package showing wrong item amount
* Fixed broken start package after saving and loading in border checkpoint (issue [#2718](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2718))
* Fixed Hank Möbelman alias Reijo Rautakaivos (issue [#3358](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3358))
* Fixed bribery (issue [#3361](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3361))
* Fixed money exchange UI money not being 2 decimal digits (issue [#3351](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3351))
* Fixed footstep sounds playing while driving minitrain (issue [#3350](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3350))

## Tasks

* Fixed Seamus Liepa not unlocking the door (issue [#3369](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3369))
* Fixed Max Masher standing after kicking the door (issue [#3374](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3374))

## Items

* Picking up items doesn't instantly mix liquids of different qualities
* Fixed insta eating all the fish (issue [#3357](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3357))
* Fixed items resetting their properties on failed drag
* Fixed player pouring liquids on ground when transfering between bottles (issue [#3352](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3352))

## Furniture

* Fixed Makeshift Toilet bucket having only 4 slots (issue [#3373](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3373))
* Fixed Bathroom Cabinet's description (issue [#3372](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3372))

## Tenement System

* Fixed not being able to enter building mode in canal saunas
* Fixed not being able to enter building mode in stairwell (issue [#3027](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3027))
* Fixed fine courtyard grill ownership and recipes
* Fixed ownerships of items in sauna upgrades
* Fixed weird railing collisions in IV mine
* Saunas III and IV now requires water and heating upgrades

## Mines

* Fixed Hanss' glowsticks (issue [#3367](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3367))

## Kolhola

* Fixed A7 mold issues (issue [#3338](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3338))
* Fixed lights being rendered when not required
* Fixed lights popping in laundry

## Gatehouse

* Added soap dispensers
* Fixed TV loop (issue [#3358](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3358))
* Fixed guard not caring about trespassing
* Fixed Cell 2 not respawning food (issue [#3363](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3363))

## Pharmacy

* Fixed wrong owner on antidepressant pack

## O-Market

* Fixed stuff spoiling in refrigerators (issue [#3371](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3371))

# January 1st 2025 (Version 0.3.47) - Playtest

* Fixed police tapes (issue [#3315](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3315))
* Fixed Seamus hanging with Malone at the start (issue [#3317](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3317))
* Fixed Pet Carrier appearing always (issue [#3318](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3318))
* Fixed void sky (issue [#3314](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3314))
* Fixed getting previously achieved achievements from steam (issue [#3320](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3320))

## Furniture

* Fixed multiple dismantle items

## Tenement System

* Fixed shabby greenhouse hose ownership
* Fixed decent courtyard grill ownership and recipes

## Mines

* Fixed that one ring not having a master (issue [#3313](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3313))

# December 31st 2024 (Version 0.3.46) - Playtest

* Added braking sound to trains
* Added warning message to notes if they're owned
* Added navigation data to pharmacy, canal saunas and some shacks
* Prison now gives a bit more food
* Fixed orechutes not saving and loading properly (issue [#3253](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3253))
* Fixed prison bugging out when you land there 'innocent' (issue [#2606](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2606))
* Fixed police not saving state properlty
* Fixed market packet goods not changing owner when paying (issue [#2996](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2996))
* Fixed dishwasher duplicating empty items (issue [#3251](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3251))
* Fixed train couplers not saving and loading correctly (issue [#3178](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3178))
* Fixed post-reload infinite flashlight battry (issue [#2065](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2065))
* Fixed esc not working after saving a game (issue [#3265](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3265))
* Fixed game not pausing correctly during autosaves (potentially fixing other related issues)
* Fixed minitrain not playing engine sound after loading a save
* Fixed prison ignoring part of the sentence (issue [#3157](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3157))
* Fixed collectible packages not saving
* Fixed new achievements not being achievable in old saves (issue [#3084](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3084))
* Fixed trains reseting their position and becoming non-functional when loaded a save where they've been left at player mine depot
* Fixed thunder not being linked to audio mixers (issue [#3271](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3271))
* Fixed water rendering over particles
* Fixed player falling asleep when watching TV (issue [#3270](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3270))
* Fixed RMB drag overwriting liquids
* Fixed player thinking that empty bottles still have some liquid after just drank them emtpy (issue [#2650](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2650))
* Fixed player thinking that empty trash still have some food despite just eat it (issue [#2940](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2940))
* Fixed icon of the first collected recipe always being broken (issue [#3019](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3019))
* Fixed paranormal NPCs (issue [#2979](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2979))
* Fixed being able to glitch into things while uncrouching
* Fixed growing many mushrooms in single growing workbench causing a lot of lag
* Fixed not being able to swim (issue [#3299](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3299))
* Fixed picking up dropped store items being a crime (issue [#3308](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3308))
* Reduced xp gain on medium&large distilleries (issue [#2938](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2938))
* Improved performance

## Tasks

* Fixed Pia's head regrowing (issue [#2929](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2929))
* Fixed not being able to report bodies (issue [#3224](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3224))

## Items

* Added grilled salmon/perch/pike
* Added smoked fish
* Fixed glowing fish item group (issue [#3259](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3259))
* Fixed IC magazine giving farming recipes (issue [#3232](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3232))
* Fixed shroom fish not glowing
* Fixeds news being sad (issue [#2252](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2252))

## Recipes

* Added grilled salmon/perch/pike
* Added smoked fish
* Fixed being unable to craft saline (issue [#3250](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3250))
* Fixed multigrain Doug recipe (issue [#3229](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3229))
* Fixed empty plastic filament spool recipe giving full plastic filament spools (issue [#3223](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3223))
* Fixed malting not using malting skill (issue [#3268](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3268))
* Mouse traps now take more time to make (issue [#3280](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3280))

## Furniture

* Added pet carrier
* Liquid storages now belong to their own category (issue [#3287](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3287))
* Fixed dismantling chainsaw giving planks and nails
* Union flags are now in flag category (issue [#3267](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3267))

## Tenement System

* Player cat now comes in pet carrier
* Late balcony upgrades now need rebar
* Fixed fine player bathroom shower missing collisions
* Fixed flickering lights in mine upgrades
* Fixed mine upgrades having broken collisions
* Fixed phantom paper roll (issue [#3140](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3140))
* Fixed doorway missing collisions (issue [#3263](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3263))
* Fixed deposit payments (issue [#3284](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3284))
* Fixed kitchen upgrade barrier missing collisions (issue [#3292](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3292))
* Fixed being able to access work in progress basement from the mines (issue [#3277](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3277))
* Fixed Malone's chair (issue [#3266](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3266))
* Locked Mine lvl4 elevator door

## Outside

* Eija renewed her supplier contract (issue [#3261](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3261))
* Fixed trash rendering through fog (issue [#2939](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2939))

## Mines

* Added some OSRAT stuff
* Improved mine map
* Drop-off machine now has note regarding mining permits and cashing out receipts
* Fixed gas station not giving correct amount of crime (issue [#3242](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3242))
* Fixed furniture shop UI being culled (issue [#3260](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3260))
* Fixed ore drop-off not giving out receipts if drop ownersless items (issue [#3273](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3273))
* Fixed ore drop-off receipt sound playing every time game is loaded
* Fixed waste depository gate not remembering powered state (issue [#3278](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3278))
* Fixed flatbed bed car
* Emil's duct is now solid (issue [#3115](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3115))

## Bank

* Fixed cameras rotating oddly (issue [#2969](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2969))

## Gatehouse

* Prison will now spawn a trash bag with your old stuff, if your cell gets changed (issue [#1803](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1803))
* Player can now request a can opener from the guard
* Fixed guard not telling you're free if you get released during sleep
* Fixed the call the guard button not starting correct dialogue when the player is already released
* Fixed TV power (issue [#2224](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2224))
* Fixed player not landing in prison when starting to talk with the guard before guard notices player

## Tenement A

* Added dish drying cabinet (issue [#3293](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3293))

## Tenement B

* Fixed ??? exit (issue [#2800](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2800))

## Mine Market

* Fixed player stealing not being fully succesful (issue [#2994](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2994))

## Player Tenement

* Fixed lights flickering on staircase

# December 23rd 2024 (Version 0.3.45) - Playtest

* Added new sleep event
* Train jumping out of train damage now happens after small delay (issue [#3176](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3176))
* Fixed NPCs no longer being lazy asses and standing up (issue [#3173](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3173))
* Added change level triggers to the bottom of the stairs/ladders on mines tenement upgrades. (issue [#3174](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3174))
* Converted electric fireplaces to solid fuel based (issue [#3213](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3213))
* Fixed stomping policemen (issue [#3182](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3182))
* Restored prison guard's and Lönkkä's schedules (issue [#3193](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3193))
* Fixed rock pile state not saving (issue [#3085](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3085))
* Fixed autosave not saving skills (issue [#3128](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3128))
* Reduced inventory opening/closing volume (issue [#2978](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2978))

## Furniture

* Fixed copper moonsine still being impossible to place  (issue [#3180](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3180))
* Fixed cup being made of newspaper (issue [#3166](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3166))
* Fixed typo with sleeping bag
* Fixed school chair graduating as a stool (issue [#3192](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3192))
* Fixed blueprint requirement showing incorrect title if it has a furnituregroup requirement (issue [#3225](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3225))
* Fixed portable generator ownership (issue [#3201](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3201))
* Fixed plastic chair collisions (issue [#3195](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3195)
* Fixed Orange Mushroom Lantern icon (issue [#3240](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3240)
* Fixed fancy desk category (issue [#3228](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3228))
* Fixed Leather Scrap and Rag Rugs using wrong icons (issue [#3221](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3221))
* Fixed Bathroom Cup having wrong icon (issue [#3167](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3167))
* Fixed Smooth Wooden and Half variant Pillars not having object snap option (issue [#3230](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3230))

## Tasks

* Fixed changed Survive in Obenseuer "Get some soup" task to "Get some hot soup" (issue [#3220](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3220))
* Fixed Anna not marking the Sauna location on the map (issue [#3208](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3208))
* Fixed player keeping Pia's letter instead of mailing it (issue [#2829](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2829))

## Items

* Fixed plörö issues

## Tenement System

* Fixed Fine mine depot missing collisions (issue [#3191](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3191))
* Fixed Decent and Fine mine depot stairs missing collisions (issue [#3190](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3190))
* Fixed not being able to use stolen items correctly for cleaning up (issue [#3187](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3187))
* Fixed not being able to finish contract work  (issue [#3247](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3247))
* Fixed sink furniture containing items despite being empty (issue [#3210](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3210))
* Fixed not being able to remove furniture (issue [#3139](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3139))

## Mines

* Added 10min cooldown for autosaves
* Added tenement resource storage for Ken Nakahara
* Diesel stop now gives receipt
* Added dialogue for missing funds for Anders Terva
* Heska now tells the dosage when player should leave at last (issue [#3154](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3154))
* Made fuel pump comma more visible
* Made speed limit sign more visible
* Fixed Orange Heaven task not being updated when entering the mines
* Fixed potato mine doorphone
* Fixed weirdness with X-Switch
* Fixed inversion anomalies in tracks (issue [#3175](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3175))
* Fixed some gold nodes being unreachable
* Fixed fuel pump sounds
* Supressed Antero's telepathic abilities (issue [#3184](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3184))
* Fixed floating track
* Fixed Toivo throwing a backpack randomly (issue [#3058](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3058))
* Fixed radios (issue [#3059](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3059))
* Fixed Toivo's laptop being usable
* Fixed occlusion issues

## Mine Market

* Fixed AA-battery owneship (issue [#3186](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3186))

## Tenement A

* Enlarged trespassing zones on cat-breeders apartment
* Fixed coffee mug phasing through Pena's hand
* Fixed elevator note

# December 20th 2024 (Version 0.3.44) - Playtest

* Added anvil
* Chained locomotives now have lights on.
* Improved saving times
* Imprived migration times
* Player now takes damage when jumping out of moving train
* Fixed typo in yellow pages
* Fixed being able to use owned items as ammo.
* Fixed loading a save returning invisible dynamite cones  (issue [#3048](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3048))
* Fixed minitrains causing game to crash in some switches
* Fixed trains self colliding after save/load (issue [#3014](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3014))
* Fixed Train-Train crash crash (issue [#3063](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3063))
* Fixed trains with multiple locomotives behaving oddly after loading a game
* Fixed crashing trains not bouncing off properly
* Fixed shop vendors funds getting resetted (issue [#3061](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3061))
* Fixed vendor categories not working (issue [#3022](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3022))
* Fixed collision issues on plastic chairs (issue [#2488](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2488))
* Fixed collision issues on field kitchen on Redemption Milita (issue [#2554](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2554))
* Fixed collision issues on shopping carts in the O Market (issue [#2662](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2662))
* Fixed collision issues on Tenement lvl 1 scaffolding (issue [#2552](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2552))
* Ended police strike (issue [#2982](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2982))
* Fixed train bogies not orienting properly on a loaded save (issue [#3127](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3127))
* Fixed train not positioning itself properly when loaded a save where train is on a switch (dosn't apply on old saves)
* Fixed nuclear powered dosimeter (issue [#3122](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3122))
* Fixed lingering subtle subtitles (issue [#3046](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3046))
* Fixed item spawn spam (issue [#2922](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2922))

## Items

* Fixed tenement A keycard dropping into pharmacy keycard (issue [#3076](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3076))

## Recipes

* Added sheet metal
* Added steel pot
* Added steel urn
* Added steel tray
* Added steel teapot
* Added steeö vase
* Added fecal mushroom mash (from glowing turds)

## Furniture

* Added anvil
* Calendar now shows how many days you lived in Obenseuer and current weekday (issue [#3145](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3145))
* Fixed being able to place broken refigerators on walls/ceilings
* Fixed hospital table having eyes (issue [#3082](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3082))
* Fixed fancy leather chair being unable to be placed (issue [#3079](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3079))
* Fixed refrigerator ownership (issue [#3136](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3136))
* Fixed not being able to place tripod camera (issue [#3147](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3147))
* Fixed pre-(and post-) stocked wine racks (issue [#3162](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3162))

## Blueprints

* Added anvil

## Tenement System

* Decent courtyard now requires shabby facade
* Player extensions now require shabby facade
* Adjusted balcony upgrade prices
* Tenants now pay deposit when rented to
* Player now returns the deposit when evicting the tenant.
* Added functional tracks to mine upgrades (issue [#3078](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3078))
* Second mine direction signs appear only at 3rd upgrade (issue [#3052](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3052))
* Fixed fine mine upgrade requiring apartment water (not tenement water)
* Fixed fine mine upgrade missing floor
* Fixed basement mines door not being updated (issue [#3064](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3064))
* Fixed Jonne Reis breaking tenement upgrades (issue [#3077](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3077))
* Fixed Jonne Reis breaking tenement board (issue [#3100](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3100))
* Fixed Jonne Reis not being visible in tenement menu (issue [#3051](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3051))
* Fixed placing the glass flask by using building mode having wrong placement side (issue [#3081](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3081))
* Fixed tooltips not showing furniture groups (issue [#3109](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3109))
* Fixed loose items not stacking atop each others (issue [#3074](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3074))
* Fixed the void when mine is being upgraded (issue [#3073](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3073))

## Console

* Fixed console now showing Unity messages (issue [#3025](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3025))
* Fixed import_translations command (issue [#3026](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3026))

## Mines

* Added map marker for exit elevator
* Added proper map markers
* Added locks to personal house doors
* Improved performance
* Adjusted lighting
* Saunaklonkku is no longer breathing concrete fumes (issue [#2985](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2985))
* Fixed weird urinal (issue [#2988](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2988))
* Fixed exiting elevator control room dropping player under the platform (issue [#2991](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2991))
* Fixed player surviving the fall to mineshaft (issue [#2993](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2993))
* Fixed mines double gates not unlocking both (issue [#2998](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2998))
* Fixed invisible railing on catwalk (issue [#3001](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3001))
* Fixed exiting electrical room putting player between rock and a hard place (issue [#3006](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3006))
* Fixed slippery stairs (issue [#3011](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3011))
* Fixed being unable to obtain speeding ticket achievement (issue [#3015](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3015))
* Fixed weak buffer (issue [#3030](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3030))
* Fixed elevator doors opening to wrong direction (issue [#3050](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3050))
* Fixed broken shack stairs
* Fixed saunaklonkku cave mushrooms lights (issue [#3055](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3055))
* Fixed monitoring room door putting player back intro the monitoring room (issue [#3041](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3041))
* Fixed "track change 4B" (issue [#3003](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3003))
* Fixed Heska's mineshaft track ending abruptly (issue [#3009](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3009))
* Fixed Heska's dialogue (issue [#3008](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3008))
* Fixed train ramming open a switch in another switch
* Fixed X-switch acting weird
* Fixed unwell well (issue [#3098](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3098))
* Fixed diesel station stock crashing the game (issue [#2990](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2990))
* Fixed shroomfarm apartment trying to postpone itself into the next update (issue [#3108](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3108))
* Fixed speeding ticket invoices not being sent (issue [#3099](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3099))
* Fixed depository fence gate state not saving and loading properly (causing invisible wall)

## Mines Management

* Fixed dating Tanja freezing the game when player is not feeling well (issue [#3096](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3096))

## Mines office mini hub

* Fixed being unable to leave (issue [#2987](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2987))

## Mines Elevator Control Room

* Fixed stairs being a slide (issue [#2989](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2989))

## Mine Market

* Fixed refigerator being empty until interracted (issue [#2995](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2995))

## Mine Barrack House 2

* Fixed barrack house 2 being an death trap (issue [#2997](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2997))

## Mine Canteen

* Fixed player being in mine canteen for eternity (issue [#3024](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3024))
* Fixed being able to select the "You have blonde hair!" when it shouldn't be possible (issue [#3045](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3045))
* Fixed not being able to take the daily meal (issue [#3060](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3060))

## Mine Hostel

* Fixed upstairs exit door (issue [#3104](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3104))
* Fixed bed ownership management (issue [#3066](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3066))

## City Gates

* Removed mystery door (issue [#3049](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3049))

## O Market

* Removed yeasterine (issue [#3013](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3013))
* Fixed borked salt (issue [#3035](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3035))

## Deekula A

* Removed floor mug (issue [#3031](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3021))
* Fixed floor lamp being stuffed in mattress (issue [#3023](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3023))

## Kolhola

* Fixed tile mirror
* Fixed floating cashbox
* Fixed standing on Eliana's desk after cutscene (issue [#2036](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2036))
* Fixed double Eliana (issue [#2808](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2808))
* Removed poster coffee

## Greenhouse

* Fixed the thermometer having wrong value when entering the greenhouse (issue [#3102](https://github.com/loiste-interactive/Obenseuer-Issues/issues/3102))

## Tenement A

* Fixed mainteance area keys missing owner
* Fixed wall gap

# December 13th 2024 (Version 0.3.43 V2) - Playtest

* Added Mines
* Improved loading times
* Added achievement for entering the mines first time.
* Added achievements for the city gates.
* Added music skill.
* Added localization import/export console commands.
* Eating plain breads now require butter.
* Eating hearty meals can now satisfy hunger for longer time.
* Player can now subscribe to ARG and Puuhari magazines
* Fixed player getting unemployment benefits every second (issue [#2821](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2821))
* Fixed breaking unowned items counting as a crime (issue [#2936](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2936))
* Fixed button cooldown getting stuck on level change/saveload (issue [#1811](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1811))
* Fixed lava lamps not lava lamping

## items

* Added Mussel
* Added Steamed Mussels
* Added Smoked Pike
* Added Smoked Perch
* Added Smoked Salmon
* Added Butterine
* Added Mushroom version of doughes
* Added Multigrain Dough
* Added Multigrain Sawdust Dough
* Added Rebar
* Added Rail
* Added Puuhari Magazine
* Added IC Magazine
* Added ARG Magazine
* Fixed hot steel bars not glowing red
* Fixed being unable to eat pork steak with vegetables

## Recipes

* Added Steamed Mussels
* Added Smoked Pike
* Added Smoked Perch
* Added Smoked Salmon
* Added Glowing Rat
* Added Mushroom version of doughes
* Added Multigrain Dough
* Added Multigrain Sawdust Dough
* Added Rebar
* Added Rail
* Added Plörö
* Added Fecal Moonshines  (issue [#2966](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2966)) (Playtest)
* Added Multigrain Sandwiches (issue [#2950](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2950)) (Playtest)
* Sandwich recipes now require butterine

## Furniture

* Added smoker
* Added memorial candle
* Fixed shabby bed ownership (issue [#2920](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2920)) (Playtest)
* Fixed chicken coops requiring terrariums (issue [#2948](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2948)) (Playtest)
* Fixed commercial kitchen tables spawning random loot (Playtest)

## Blueprints

* Added copper moonshine still
* Added smooth half pillar to loot list (issue [#2968](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2968)) (Playtest)

## Pharmacy

* Fixed few items being un-purchaseable (issue [#2964](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2964)) (Playtest)

## O-Market

* O-Market now sells butterine

## Outside

* Added hourly bus

# November 11th 2024 (Version 0.3.43) - Playtest

* O-Market now gives detailed receipts
* Skeida now gives detailed receipts
* Mine Canteen now gives detailed receipts (Playtest)
* Fixed large spam log of npcs (issue [#2881](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2881)) (Playtest)
* Fixed change_scene command (issue [#2898](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2898)) (Playtest)
* Fixed wealth indicator not showing up properly (issue [#2906](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2906)) (Playtest)
* Fixed scene migration not working correctly (issue [#2882](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2882)) (Playtest)
* Fixed console spam (issue [#2883](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2883)) (Playtest)
* Fixed Player Cat multiplying (issue [#2891](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2891)) (Playtest)
* Fixed cats reporting crimes (issue [#2888](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2888)) (Playtest)
* Increased view distance

## Items

* Added receipt
* Fixed laundry detergents drink button (issue [#2892](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2892)) (Playtest)

## Outside

* Fixed the border road sign is levitating off the ground (issue [#2885](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2885)) (Playtest)
* Fixed minor clipping on Deekula rooftop garden (issue [#2887](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2887)) (Playtest)
* Fixed Deekula roof garden barrels (issue [#2884](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2884)) (Playtest)
* Fixed Deekula rooftop garden occlusion (issue [#2886](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2886)) (Playtest)

## Canteen

* Fixed bag changing owned items to stolen (issue [#2902](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2902)) (Playtest)

## Greenhouse

* Fixed greenhouse barrel stove not having fuel at start (issue [#2895](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2895)) (Playtest)

# November 8th 2024 (Version 0.3.42 V4) - Playtest

* Added player character skills menu
* Added ability to swim
* Added trader's wealth level indicator (issue [#2844](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2844))
* Fixed new achievements not triggering (issue [#2798](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2798)) (Playtest)
* Fixed item spawners spawning new items when hidden (issue [#2793](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2793)) (Playtest)
* Fixed people spotting player doing crimes when they shouldn't (issue [#2617](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2617)) (Playtest)

## Crafting

* Fixed manufacturing output value increasing when using a container that already contains liquid (issue [#2803](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2803)) (Playtest)
* Fixed not being able to open manufacturing UI after recipe was enabled but not activated (issue [#2781](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2781)) (Playtest)
* Fixed crafting not always removing correct items (issue [#2815](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2815)) (Playtest)

## Items

* Added Glowing Pike
* Added Glowing Perch
* Added Glowing Salmon
* Added Pike
* Added Perch
* Added Salmon
* Added Pike Eggs
* Added Perch Eggs
* Added Salmon Eggs
* Laundry detergent can now be drank
* Fixed Chicken Wheat Sandwich having rye bread when dropped/placed (issue [#2874](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2874))
* Fixed liquids disappearing from some containers placed in the world (issue [#2740](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2740))
* Fixed broken items respawning (issue [#2854](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2854))
* Fixed some glass items not being breakable in the world

## Furniture

* Large wooden chest now costs more
* Fixed being unable to place desk fan or examination bed (issue [#2797](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2797)) (Playtest)
* Fixed the broken brown refrigerator hanging on the wall on the furniture preview menu (issue [#2805](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2805)) (Playtest)
* Fixed Devils Angels Wall Flag icon (issue [#2787](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2787)) (Playtest)

## Player Tenement

* Fixed Player Cat multiplying (issue [#2769](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2769)) (Playtest)

## Tenement System

* Changed Makeshift Facade price (issue [#2873](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2873)) (Playtest)
* Fixed huge workshop price
* Fixed Crazy Neighbour automatically counts in first 3-4 renovations (issue [#2810](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2810)) (Playtest)

## Mines Canteen

* Fixed no one reacting when the cat is killed (issue [#2868](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2868)) (Playtest)
* Fixed cat not dying when sitting on it (issue [#2726](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2726)) (Playtest)
* Fixed stolen items being counted as buyable (issue [#2780](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2780)) (Playtest)

## O Market

* Fixed being able to put 10L bottles in bottle recycling (issue [#2867](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2867)) (Playtest)

## Deekula A

* Fixed diesel not counting as stealing (issue [#2805](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2805)) (Playtest)

## Deekula B

* Fixed sofa phasing through walls (issue [#2794](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2794)) (Playtest)

## City Gates

* Fixed being able to get stuck between the truck and wall (issue [#2802](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2802))

## Outside

* Added Deekula B rooftop terrace


# October 25th 2024 (Version 0.3.42 V3) - Playtest

* Added Orange Heaven outcome enhancement (issue [#2745](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2745)) (Playtest)
* Changed "eating habits" loading screen hint (issue [#2763](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2763))

## Crafting

* Fixed coffee maker making dupes of non-stackable containers (issue [#2762](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2762)) (Playtest)
* Fixed not being able to remove mash from mashing tuns (issue [#2759](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2759)) (Playtest)

## Tenement System

* Fixed vanished apartment upgrades and tenants (issue [#2764](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2764)) (Playtest)

# October 24th 2024 (Version 0.3.42 V2) - Playtest

* Fixed Orange Heaven dialogue window getting stuck (issue [#2747](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2747)) (Playtest)
* Fixed not being able to continue the Orange Heaven quest after talking to Malone (Playtest)
* Fixed furniture store UI being broken sometimes (issue [#2751](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2751)) (Playtest)

## Crafting

* Fixed animal/plant growing being broken (issue [#2752](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2752)) (Playtest)
* Fixed some crafting stations removing items (issue [#2748](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2748)) (Playtest)
* Fixed some crafting recipes not removing liquid from containers when they should (Playtest)

## Tenement System

* Fixed not being able to take/move/place furniture (issue [#2755](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2755)) (Playtest)
* Fixed furniture disappearing (issue [#2755](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2755)) (Playtest)
* Fixed radio playing music after being taken (issue [#2755](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2755)) (Playtest)

## Kolhola

* Fixed not being able to talk to the guy in the Money Extange (issue [#2754](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2754)) (Playtest)
* Fixed sofa in Kolhola A13 poking trough the roof (issue [#2753](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2753)) (Playtest)
* Fixed minor visual bug in Hostel Warehom (issue [#2743](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2743))
* Fixed Kolhola A13 light not being rendered if player is right up against the door (issue [#2232](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2232))


# October 23rd 2024 (Version 0.3.42) - Playtest

* Added Interior Mines Potato Mine (Playtest)
* Added 4 new skill achievements
* Added new stat for orange mushrooms
* Added new consumption effects for orange mushrooms
* Jonasson now sells loom
* Telemarketing job is now less soul grinding
* Safes now have different types of loot
* Residents now take their belongings with them when they get an apartment
* Fixed the crafting stations not working if there's a missing learned recipe (Playtest)
* Fixed the mines UI map not loading (Playtest)
* Fixed typos in dialogue and letters
* Fixed makeshift passport becoming real (forged) passport (issue [#2682](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2682))
* Fixed facemask having a high hygiene penalty (issue [#2686](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2686))
* Fixed pressing down key on editable signs adding new lines (issue [#2481](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2481))
* Fixed time skipping when loading game or changing scene (issue [#2705](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2705)) (Playtest)
* Fixed hatched eggs spawning a chick after loading the game (issue [#2722](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2722)) (Playtest)
* Fixed animals not spawning after loading the game (Playtest)
* Fixed not being able to sometimes to use the buttons at the bottom of the pause menu (e.g. Load Game button)

## Crafting

* Fixed not being able to wash flashlights and some other items with ammo data (issue [#2724](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2724))

## Items

* Added snus
* Added nicotine pouches
* Added glass flask
* Added Orange Mushroom Powder
* Added Pure Orange Mushroom Powder
* Fixed shroom coffee not having shroom in it (issue [#2665](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2665))

## Recipes

* Added recipes to shroomify meats
* Added Orange Mushroom Powder Recipe
* Added Pure Orange Mushroom Powder Recipe
* Coffee now has better quality on lower levels
* Fixed not being able to cook Chicken Curry Sauce with Rice (issue [#2712](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2712))

## Furniture

* Added 4 new union flags (reward)
* Added skins to various furniture
* Added License Plates
* Added Pappa-Tunturi
* Added Devil's Angels Wall Flag
* Added New Posters
* Added Egg timer
* Added Motorcycle Gang Paintings
* Added Kettle
* Added Grater
* Added multiple furniture from this list (issue [#2412](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2412))
* Fixed fermenting container blueprint giving mashing kettle (issue [#2672](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2672))
* Fixed dismantling barrel shower giving buckets (issue [#2671](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2671))
* Fixed dismantling Old Bathtub With Soil giving 0 Old Bathtubs (issue [#2739](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2739))

## Blueprints

* Added loom blueprint
* Added stone fireplace
* Added large wooden table with curtains
* Fixed pillows being very important to be considered as task items (issue [#2669](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2669))

## Tenement System

* Added ablity to change furniture style in building menu (e.g. a sleeping bag to a packed form)
* Added the reason to the rent buttons why the apartments cannot be rented
* Outsides of exterior saunas now have a weak cooldown effect
* Fixed renovation icons not being updated after starting an upgrade (issue [#2676](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2676))

## Mines Canteen

* Fixed sledgehammering rats not counting as solving the rat problem (issue [#2667](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2667))
* Fixed stuff spoiling in Anna's storage (issue [#2686](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2686))

## Mines Hotel

* Fixed room 4 not giving access to bed (issue [#2674](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2674))

## Outside

* Fixed Teuvo being an anon (issue [#2677](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2677))
* Fixed janitor going to home too early (issue [#2648](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2648))

## Tenement A

* Fredrik got his lab back into working order (issue [#2411](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2411)) (Playtest)
* Fixed Saunas being some weird blashphemous warm rooms where you're not allowed to throw water on stones (issue [#2504](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2504)) (Playtest)
* Fixed not being able to ask about Joel Hietala from Johannes Eskola (issue [#2735](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2735)) (Playtest)

# August 30th 2024 (Version 0.3.41) - Playtest

* Added Small Playtest Mines Area (Playtest)
* Added Interior Mines Barrack Hotel (Playtest)
* Added Interior Mines Canteen (Playtest)
* Added Interior Mines Management (Playtest)
* Added Interior Mines Office (Playtest)
* Added Interior Mines Shroom Farm Apartment (Playtest)
* Added loom
* Glowing rats can now randomly attack the player
* Glowing rats cause coughing when near them
* Fixed level file not being migrated when changing level (issue [#2482](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2482))

## Tenement System

* Fixed Fine Pier Sauna leading to Under Map (issue [#2645](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2645)) (Playtest)

## Recipes

* Added Bandage
* Added Tarp Roll
* Added Cloth Roll
* Added watermelon mash
* Added glowing watermelon mash
* Added watermelon wine
* Added mushroom watermelon wine
* Mesh uses now steel wire instead of cable
* Mesh is now a loom recipe
* Fixed some mashes yielding wrong amount of ruined mash
* Fixed shroom blackrurrant mash yielding wrong amount of mash

## Items

* Added watermelon moonshine
* Added watermelon mushroom moonshine
* Added watermelon wine
* Added mushroom watermelon wine
* Added steel wire
* Added watermelon mash
* Added watermelon mushroom mash
* Mushroom rollies now have quality data
* Increased watermelon price
* Increased watermelon jam price
* Fixed mason jar tooltip

## Furniture

* Added loom
* Fixed not being able to place the tripod camera (issue [#2641](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2641))
* Fixed not being able to place the chainsaw (issue [#2641](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2641))

## Pharmacy

* Fixed facemask packs not being able to be purchased (issue [#2625](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2625)) (Playtest)


# August 22nd 2024 (Version 0.3.40 V3) - Playtest

* Added shortkey for filling/unfilling liquid containers (issue [#2579](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2579)) (Playtest)
* Itemstacks can now be merged if quality label is same.
* Improved price of low quality products.
* Good mashing kettle is now 30L
* Fixed subtitles causing lag when multiple lines of dialog are displayed at the same time
* Fixed the bathtub corpse not being removed when reporting multiple corspes (issue [#2537](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2537)) (Playtest)
* Fixed calling the police to report a body softlocking the game (issue [#2592](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2592)) (Playtest)
* Fixed being able to get crime points when item is not moved to player inventory (issue [#2591](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2591))
* Fixed recipes not showing correct name (issue [#2588](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2588)) (Playtest)
* Fixed liquid quality not being set correctly after load (issue [#2583](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2583)) (Playtest)
* Fixed fermenting bucket and other manufacturing processes not having the correct capacity (issue [#2563](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2563)) (Playtest)
* Fixed getting crime points when sorting inventory (issue [#2578](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2578)) (Playtest)
* Fixed Dr. Pena MD giving an inaccurate addiction stat (issue [#2605](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2605)) (Playtest)
* Fixed brick furnace stops running after load (issue [#2608](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2608)) (Playtest)
* Fixed missing lockpicking animation (issue [#2612](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2612)) (Playtest)
* Fixed subtitles not showing names correctly (issue [#2609](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2609)) (Playtest)
* Fixed the ability to use some toilets when the lid is not up (issue [#2610](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2610)) (Playtest)
* Fixed blueprints not spawning (issue [#2616](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2616)) (Playtest)

## Crafting

* Fixed being able to fill an infinite amount of liquid at manufacturing process stations when the liquid container has the same liquid (issue [#2614](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2614))

## Tenement System

* Fixed not being able to remove furniture sometimes (issue [#2562](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2562)) (Playtest)
* Fixed missing foundation in player apartment fine extension (issue [#2565](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2565))

## Outside

* Changed decorative items stall to janitor stall
* Fixed Tenement A doorphone being broken (issue [#2581](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2581)) (Playtest)

## Deekula C

* Fixed Mobelmann's door not being open during his opening times (issue [#2570](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2570)) (Playtest)
* Fixed Homecoming quest being stuck at the first step (issue [#2573](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2573)) (Playtest)

## O-Market

* O-Market now sells blackcurrant juice concentrate

## Kohola

* Fixed occlusion issues (issue [#2575](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2575)) (Playtest)

## Furniture

* Fixed fluid containers being owned (issue [#2584](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2584)) (Playtest)

## Recipes

* Added Mushroom Blackccurant Mash
* Added Mushroom Blackcurrant Wine
* Added Mushroom Blackcurrant Liqueur
* Added Blackccurant Mash
* Added Blackcurrant Wine
* Added Blackcurrant Liqueur
* Added Blackcurrant Juice
* Added shroom water (chemical lab)
* Added sugar mash from sugar beet juice
* Updated sugar beet juice recipe to not require bucket

## Items

* Added Mushroom Blackccurant Mash
* Added Mushroom Blackcurrant Wine
* Added Mushroom Blackcurrant Liqueur
* Added Blackccurant Mash
* Added Blackcurrant Wine
* Added Blackcurrant Liqueur
* Added Blackcurrant Juice
* Added Blackcurrant Juice Concentrate
* Mason jars are now 2L
* Sugar beet juice is now liquid
* Fixed OS Energy Drink being uncaffeinated (issue [#2582](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2582))
* Fixed player eating cash box instead of breaking it (issue [#2568](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2568)) (Playtest)

# August 16th 2024 (Version 0.3.40 V2) - Playtest

* Fixed face masks not working after loading the game while the face mask is equipped (issue [#2558](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2558))
* Fixed being able to unlock a locked door when the lockpick stack deplates fully (issue [#2550](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2550))
* Fixed some dropped items, mold etc. not disappearing when they should
* Fixed not being able to talk to some NPCs (issue [#2542](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2542)) (Playtest)
* Fixed not being able to use some tools (issue [#2547](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2547)) (Playtest)
* Fixed the game getting stuck when pressing "quit to main menu" (issue [#2559](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2559)) (Playtest)
* Fixed not being able to pickup anything (issue [#2555](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2555)) (Playtest)
* Fixed not being able to fill liquid containers in manufacturing process crafting stations (issue [#2544](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2544)) (Playtest)

## Tenement System

* Changed the Crazy Neighbor to open the apartment's door when the player opens the door with lockpicks first time (issue [#2551](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2551)) (Playtest)
* Fixed the Crazy Neighbor killing the previous tenant (issue [#2556](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2556)) (Playtest)
* Fixed plants disappearing (issue [#2557](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2557)) (Playtest)
* Fixed the crazy neighbors apartment counting examination (issue [#2549](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2549)) (Playtest)
* Fixed the crazy neighbor not reacting to stealing owned items (issue [#2553](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2553)) (Playtest)

## O-Market

* Fixed some items getting moldy (issue [#2543](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2543)) (Playtest)

# August 15th 2024 (Version 0.3.40) - Playtest

* Added text wobble effect when the player is drunk
* Added missing rent payments setting to pause menu (Playtest)
* Low tier mashes and alcohols now yield better qualities (to easen the start of the game)
* Player now receives occasional fake invoice
* Changed the dialogue comment texts to be easier to read (issue [#2405](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2405))
* Fixed money UI when the player has more money than the UI can display (issue [#2528](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2528))
* Fixed crushers not having an UI image (Playtest)
* Fixed mashing/distillery/fermenters not accounting input item quality
* Fixed null spam (issue [#2438](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2438)) (Playtest)
* Fixed not being able to plant multiple plants at once (issue [#2480](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2480)) (Playtest)
* Fixed natural light sources flashing (issue [#2375](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2375)) (Playtest)
* Fixed npcs being able to give coins when playing the guitar from afar (issue [#2527](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2527)) (Playtest)
* Fixed game being laggy when filling from owned liquid container while npc sees the player (issue [#2520](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2520)) (Playtest)
* Fixed prison escape giving extreme bounties (issue [#2526](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2526)) (Playtest)
* Fixed some growing plants having wrong state at start (issue [#2186](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2186))
* Fixed being able to try read newspaper if stats are too low (issue [#2175](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2175)) (Playtest)
* Fixed Sunday coming after Monday when the month start over
* Fixed npc sit animations being bugged after loading a game (issue [#2513](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2513)) (Playtest)

## Tasks

* Changed Orange Heaven task dialogue and objectives

## Growing

* Changed how much the player gains skill level from planting (issue [#1955](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1955))

## Crafting

* Fixed washing still removing the item skin (issue [#2499](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2499)) (Playtest)
* Fixed non-stolen detergent not reducing charges on use (issue [#2510](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2510)) (Playtest)

## Items

* Added limestone rock
* Fixed some items missing use sounds
* Fixed drinking OS Energy Drink not returning an empty can (issue [#2509](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2509))
* Fixed spring water being so good, that player drinks it all (including the bottle) at once (issue [#2478](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2478)) (Playtest)
* Fixed not being able to eat one watermelon only (issue [#2523](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2523))
* Fixed Pack of Winstead Cigarettes not consuming matches or lighter (issue [#2312](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2312))
* Updated watermelon stats

## Recipes

* Added limestone
* Added a notification if the player picks up a recipe the player already has in inventory
* Fixed recipes with the same name were not being added to the inventory
* Fixed fried egg recipe using wrong egg (issue [#2531](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2531)) (Playtest)
* Fixed scrap metal recipe typo (issue [#2512](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2512)) (Playtest)
* Fixed learned or collected recipes not getting updated on older saves (issue [#2409](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2409))
* Fixed some recipes not being added to inventory (issue [#2195](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2195)) (Playtest)

## Furniture

* Changed Candle Bowl to require light
* Fixed hay bale requiring 0 yarn (Playtest)
* Fixed electronics station description (issue [#2529](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2529)) (Playtest)
* Fixed issues with White and Green Rug (issue [#2524](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2524))
* Fixed Hay Bale blueprint being listed in task items intsead of blueprint section (issue [#2516](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2516)) (Playtest)
* Fixed plank bed and shabby bed blueprints (issue [#2498](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2498))
* Fixed barrel shower liquid disappearing (issue [#2541](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2541)) (Playtest)

## Tenement System

* Added status labels to upgrade list UI (issue [#1601](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1601))
* Optimized build menu
* Increased resident rents (Playtest)
* Total rent income are now not affected by the payment schedule setting (Playtest)
* Tenement UI now shows the income in selected payment schedule
* Changed upgrade list style (issue [#1601](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1601))
* Fixed residents livign rent free (issue [#2508](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2508)) (Playtest)
* Fixed not being able to fully examine apartment 4 (issue [#2479](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2479)) (Playtest)
* Fixed crazy neighbor not showing up in apartment 4 (Playtest)
* Fixed rare bug where game crashes when looking at furniture in build mode (issue [#2525](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2525))
* Fixed there not being enough slots to display all the required materials (issue [#2511](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2511)) (Playtest)
* Fixed not being able to upgrade plumbing (issue [#2536](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2536)) (Playtest)
* Fixed animals falling through everything in placing mode (issue [#2077](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2077))
* Fixed the "ghost" toilet in Apartment 16 (issue [#2507](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2507))
* Fixed bugged fine canal sauna wall (issue [#2539](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2539))

## Gatehouse

* Fixed gatehouse storage being too small for rucksack items (issue [#2535](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2535)) (Playtest)

## O-Market

* Fixed daily newspapers not restocking (issue [#2204](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2204)) (Playtest)

## Kolhola

* Fixed the office water cooler (issue [#2515](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2515)) (Playtest)
* Fixed Eliana bugs (issue [#2519](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2519)) (Playtest)

## Tenement A

* Fixed the fan not being at right position (issue [#2062](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2062)) (Playtest)

## Tenement B

* Fixed player knowing Passmore's password before getting it (issue [#2316](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2316)) (Playtest)

## Deekula B

* Fixed not being able to use other keys to unlock storage (issue [#1413](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1413))
* Fixed Max Masher becoming un-hurt after reload (issue [#2334](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2334))
* Fixed bathtub missing collision and making the player to cough after being cleaned (issue [#2225](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2225))

## Deekula C

* Fixed missing apartment C3 sink (issue [#2483](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2483)) (Playtest)

## Makeshift House (House1)

* Fixed being able to get two heads (issue [#2506](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2506)) (Playtest)

# July 29th 2024 (Version 0.3.39 V9) - Playtest

* Fixed being able to fall asleep while opening a change level door (issue [#2328](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2328))
* Fixed doors (issue [#2472](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2472)) (Playtest)
* Fixed shake not working after loading the game from the pause menu (issue [#2321](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2321))
* Fixed not being able to sit anywhere after loading a save when player is sitting (issue [#2134](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2134))

## Blueprints

* Fixed makeshift IBC sink blueptrint (issue [#2467](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2467)) (Playtest)

## Tenement System

* Fixed the same furniture appearing multiple times in furniture shops (issue [#2470](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2470))

## Items

* Added Syringe Pack (issue [#2240](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2240))
* Added Spring Water (issue [#2465](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2465))
* Fixed 10L bottles display (issue [#2466](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2466)) (Playtest)

## Furniture

* Fixed A-Board Sign UI icon and glowing bug (issue [#2469](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2469)) (Playtest)
* Fixed pressing enter adding a new line to editable signs (issue [#2377](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2377)) (Playtest)

## Pharmacy

* Fixed some items at the pharmacy counting as stealing (issue [#2314](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2314)) (Playtest)

# July 26th 2024 (Version 0.3.39 V8) - Playtest

* Fixed older saves not having new skills (issue [#2433](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2433))
* Fixed sinks not working with old playtest saves (issue [#2443](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2443)) (Playtest)
* Fixed wieldables moving animations (issue [#2436](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2436)) (Playtest)
* Fixed hovering over stat icons crashing the game (issue [#2447](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2447)) (Playtest)

## Items

* Added 10L water bottle

## Tenement System

* Fixed crazy neighbor not showing up in player tenement (issue [#2450](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2450)) (Playtest)
* Fixed rooftop greenhouse upgrade lighting bug (issue [#2446](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2446)) (Playtest)

## Blueprints

* Added hay bale
* Added big gear
* Added Makeshift IBC Sink

## Furniture

* Added hay bale
* Added big gear
* Added Makeshift IBC Sink
* Fixed tv table not being purchaseable
* Fixed fancy sofa not being purchaseable
* Fixed toolboxes not being purchaseable
* Fixed Helm Clock, Wall Clock and Helm not being purchaseable
* Fixed electric kiln not being purchaseable
* Fixed candle bowl not being purchaseable
* Fixed picnic table not being purchaseable
* Fixed glass coffee table not being purchaseable
* Fixed unplaceable dwaring boards (issue [#2439](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2439)) (Playtest)
* Fixed blue barrel and metal barrel descriptions (issue [#2463](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2463)) (Playtest)
* Reduced price of vegetable crates (issue [#2454](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2454))
* Modular shelf pieces now snap on walls

## O-Market

* O-Market now sells 10L bottles of clean water

## Makeshift House (House1)

* Fixed Crazy neighbor collision (issue [#2444](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2444)) (Playtest)

## Deekula B

* Fixed apartment B4 sink crashing the game (issue [#2442](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2442)) (Playtest)

## Tenement A

* Fixed wrong door transition point (issue [#2434](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2434)) (Playtest)

## Console

* Added blueprint commands

## Kolhola

* Fixed Kolhola sourcing it's water from fermented septic tank (issue [#2437](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2437))
* Fixed Hostel pods being a death traps (issue [#2432](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2432))

# July 24th 2024 (Version 0.3.39 V7) - Playtest

* Added rent payment interval options
* Changed water cooler to liquid storage (Playtest)
* Changed the behavior of the police (issue [#2414](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2414)) (Playtest)
* Fixed not being able interact or open menus after showing photo to Pia (issue [#2407](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2407)) (Playtest)
* Fixed clipping rocks in jaw crusher (issue [#2380](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2380)) (Playtest)
* Fixed some NPCs thinking they were police officers (issue [#2376](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2376)) (Playtest)
* Fixed double-click/hold item move not working after interacting with liquid storage (issue [#2396](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2396)) (Playtest)
* Fixed not being able to move liquid to some empty containers (issue [#2395](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2395)) (Playtest)
* Fixed item stat tooltip when filling item (issue [#2391](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2391)) (Playtest)
* Fixed lights being too dark sometimes (issue [#2370](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2370)) (Playtest)
* Fixed metal storage not locking view when lockpicking (issue [#2386](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2386)) (Playtest)
* Fixed exception null spam in the console (issue [#2378](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2378)) (Playtest)
* Fixed dishwasher washing the skin off (issue [#2310](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2310)) (Playtest)
* Fixed wind effect causing exceptions (issue [#2281](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2281))
* Fixed biogas reactor not updating correctly when player spends time in other scenes (issue [#1954](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1954))
* Fixed dishwasher starting cleaning items that are not owned
* Fixed dishwasher creating multiple recipes of the same item
* Increased IBC Container filling and unfilling speed (issue [#2393](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2393)) (Playtest)
* Increased sinks filling and unfilling speed (issue [#2393](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2393)) (Playtest)

## Tenement System

* Added placing an odd teddy bear adds safety to the room
* Added a Plastic Barrel Shower to player's apartment makeshift bathroom upgrade (issue [#2415](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2415))
* Balanced rents of a few tenants
* Tenement upgrades are now cheaper
* Bare water and first water upgrade (basement) now has sewage tank
* Fixed Jonne Reis breaking apartment upgrades (issue [#2429](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2429)) (Playtest)
* Fixed furniture crafting crashing the game the selected category becomes empty (issue [#2342](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2342))
* Shabby canal sauna rain barrel now fills itself during rain

## Items

* Mushrooms needs to be refigerated, not frozen. (Playtest)
* Sahti, coffee and kumis spoils unless refigerated

## Furniture

* Added editable A-Board Sign (issue [#2412](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2412))
* Increased jawcrusher capacity
* Changed barrels to fluid storages (issue [#2397](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2397))
* Fixed Small Drawer having wrong icon (issue [#2366](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2366)) (Playtest)
* Fixed Mesh Wall having wrong icon (issue [#2371](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2371)) (Playtest)
* Fixed Electronics Workbench having wrong icon (issue [#2371](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2371)) (Playtest)
* Fixed Drawing Board being off-centered (issue [#2367](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2367)) (Playtest)

## Outside

* Fixed Eijas Grill benches having wrong texture (Playtest)
* Fixed Eijas Grill bench facing in the wrong direction (issue [#2421](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2421))

## City Gates

* Fixed dynamite explosion sounds having too short range (issue [#2403](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2403)) (Playtest)

## Gatehouse

* Fixed prison cell vent lockpicking (issue [#2408](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2408))

## Kolhola

* Kolhola now has clean water
* Fixed A5 kitchen missing sink

## Tenement A

* Added door to Speakeasy (issue [#2114](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2114)) (Playtest)
* Fixed top stairs not being walkable (issue [#2413](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2413)) (Playtest)
* Fixed trespassing zones at cat trader's apartment (issue [#2422](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2422)) (Playtest)
* Fixed some Tenement A issues (issue [#2223](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2223)) (Playtest)
* Fixed some lighting issues (issue [#2190](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2190)) (Playtest)
* Tenement A now has clean water (Playtest)

## Tenement B

* Tenement B now has clean water

## Deekula B

* Fixed missing sink (issue [#2430](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2430))

# July 19th 2024 (Version 0.3.39 V6) - Playtest

* Added liquid tanks
* Added crusher
* Added planning table
* Added small random variation to rotary lock 'tick' pitch (issue [#2311](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2311))
* Added exclamation mark to show new items (issue [#1091](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1091))
* Added notifications to magazine recipes and skills (issue [#1091](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1091)) (Playtest)
* Added NPCs to react when the player plays the guitar
* Changed several "The Disappearance of Alice" dialogs (Playtest)
* Changed lockpicks to require recipe for crafting (issue [#2286](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2286))
* Fixed "The Disappearance of Alice" typos (issue [#2298](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2298)) (Playtest)
* Fixed not being able to report Hietala's and Alice's bodies (issue [#2293](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2293)) (Playtest)
* Fixed not being able to report Pia's body to the police (issue [#2292](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2292)) (Playtest)
* Fixed reporting the Pia's body to the police softlocking the game (issue [#2278](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2278)) (Playtest)
* Fixed T-posing NPC model (issue [#2276](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2276)) (Playtest)
* Fixed NPC footstep sounds
* Fixed footstep sounds not playing when walking sideways/diagonally/backwards (issue [#1262](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1262))
* Fixed the direction the police look when chasing the player
* Fixed the police not chasing the player after the player goes to another level or after loading the save
* Fixed collectible items with missing item id not being removed (issue [#2323](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2323))
* Fixed typos (issue [#2313](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2313))
* Fixed Hospital Table agressive LOD
* Fixed guitar playing without the player holding click (issue [#2355](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2355))
* Fixed steep stairs having a jaggy movement (issue [#338](https://github.com/loiste-interactive/Obenseuer-Issues/issues/338))
* Fixed Malone dialogue typos (issue [#2361](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2361))
* Fixed dropping an empty backpack taking currently equipped backpacks inventory (issue [#2350](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2350)) (Playtest)
* Fixed planter modifiers not updating correctly (issue [#2123](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2123))

## Tenement System

* Added building menu to display environment dependent modifiers (issue [#349](https://github.com/loiste-interactive/Obenseuer-Issues/issues/349))
* Changed apartment electricity icon
* Changed tenement heating icon
* Changed tenement heating name to heating room
* Changed tenement water icon
* Changed tenement water name to plumbing
* Fixed not being able to open building menu when entering from the balcony/extension door (issue [#2273](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2273))
* Fixed some furniture not being highlighted correctly (issue [#2265](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2265))
* Improved furniture snap location detection
* Makeshift sinks doesn't anymore have an infinite water supply

## Recipes

* Added Urea extraction
* Added Coke (coal)
* Added Rat Trap
* Added Charcoal
* Added Copper Wire
* Added Metal Slab (from ore + charcoal + limestone)
* Added Sand
* Added Gravel
* Added Gold Ore
* Added Iron Ore
* Added Asbestos
* Added Flowerpot
* Added Detailed Blueprint
* Added Cement
* Added Brick
* Added Improved Blueprint
* Added Scam Invoice
* Added Glue
* Added Simple Blueprint
* Added Pure Water
* Added empty filament spool recipe
* Added Rat Trap Baits
* Plastic bottles can now be recycled into filament
* Fixed water purify distillery recipes requiring containers (issue [#2285](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2285)) (Playtest)

## Items

* Added Urea
* Added Fertilizer
* Added Coke (coal)
* Added Rat Trap With Bait
* Added Rat Trap Without Bait
* Added Rat Trap Baits
* Added Copper Shavings
* Added Gravel
* Added Gold Ore
* Added Iron Ore
* Added Lacquer
* Added Detailed Blueprint
* Added Clay
* Added LMAO-Tables
* Added Improved Blueprint
* Added Scam Invoice
* Added Lime(stone)
* Added Simple Blueprint
* Added Heavy Water
* Added Pure Water
* Added Odd Teddy Bear
* Added Gold Ore Rock
* Added Iron Ore Rock
* Added Asbestos Rock
* Added perishable data for mushroom items
* Fixed boiled egg giving bleeding (Playtest)
* Fixed diesel being tasty (Playtest)
* Fixed dwarf plush typo (issue [#2360](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2360))
* Increased Pure Green Mushrooms price (issue [#2348](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2348))

## Blueprints

* Added Metal Locker
* Added Wooden Stool
* Added Wooden Step Stool
* Added Dressing Room Benches
* Added Smooth Wooden Pillar
* Added Mesh Wall
* Added Fancy Wooden Table
* Added Chicken Coops
* Added Fermenting Container
* Added Mashing Kettle
* Added cottage table
* Added cottage bench
* Added coffee table blueprints
* Added modular shelf blueprints
* Added leather scrap rug blueprint
* Added rag rug blueprint
* Added pillow blueprints
* Added cat cage blueprints
* Added Half Wooden Pillar blueprint
* Added Smooth Half Wooden Pillar blueprint

## Furniture

* Added Ore Crusher
* Added IBC Container
* Added Plastic Barrel Shower
* Added safe
* Added smooth wooden pillar
* Added Mesh Wall
* Added drawing board
* Added pillows
* Added electronics workbench
* Added a small drawer
* Added leather scrap rug
* Added rag rug
* Added Half Wooden Pillar
* Added Smooth Half Wooden Pillar
* Fixed not being able to attach head lantern to ceiling chain (Playtest)
* Fixed Fancy Large Wooden Cabinet spawning new items (issue [#2308](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2308)) (Playtest)
* Fixed the private property sign being sideways in the furniture preview menu (issue [#2318](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2318))
* Fixed makeshift toilet not requiring a bucket (issue [#2351](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2351))
* Fixed fermenting barrel crafting requiring 0 blue barrels (issue [#2358](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2358))
* Fixed Half Pallet and Quater Pallet being off-centered
* Makeshift sinks doesn't anymore have an infinite water supply

## Outside

* Added missing vent (issue [#2259](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2259))
* Fixed Eijas grill table (issue [#2363](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2363)) (Playtest)

## O-Market

* Fixed being able to recycle full milk cartons from the O-Market fridge (issue [#2315](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2315))

## Tenement A

* Added tresspassing zones to cat breeder's apartment (A7) (issue [#2291](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2291)) (Playtest)
* Added more storage space to Fredrik's fume cabinet (lab) (issue [#2268](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2268)) (Playtest)
* Added more hints to Joel's apartment that someone else lives there (issue [#2307](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2307)) (Playtest)
* Fixed elevator doors not having a lock location (issue [#2274](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2274)) (Playtest)
* Fixed collision not matching the stair geometry (issue [#2299](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2299)) (Playtest)
* Fixed not being able to ask Jonne Reis about Alice (issue [#2300](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2300)) (Playtest)
* Fixed being able to tell Fredrik that "Pia is dead" when Pia is alive (issue [#2277](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2277)) (Playtest)

## Makeshift House (House1)

* Fixed Osrat spot being active when it shouldn't be (issue [#2304](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2304)) (Playtest)
* Fixed Crazy Neighbor not appearing if selected at start

## Small Storage (House4)

* Added an item that must be picked up to proceed in "The disappearance of Alice" task (issue [#2301](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2301)) (Playtest)

# June 20th 2024 (Version 0.3.39 V5) - Playtest

* Added Makeshift House (House1)
* Added Small Storage (House4)
* Right digit of rotary lock now makes slightly different sound.
* Consuming stolen foods/drinks now have small mentalhealth debuff
* Changed item use amount slot text location if item has perishable data (issue [#2169](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2169))
* Fixed a typo in phone message (issue [#2193](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2193))
* Fixed wieldable items not remembring state after level transition (issue [#2191](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2191)) (Playtest)
* Fixed not being able to interact with various objects around eye-level when dosimeter is equipped (issue [#2110](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2110)) (Playtest)
* Fixed being able to open some furniture from the wrong side (issue [#2014](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2014))
* Fixed both sides of the steel cabinet saying that they are the left side (issue [#2218](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2218))
* Fixed icon does not always appearing when checking addiction with Dr. Pena MD (issue [#2227](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2227)) (Playtest)

## Main Menu

* Improved background

## Items

* Added fried egg
* Added canister skins
* Added bobby
* Changed diesel to be liquid
* Jams and (homemade) canned foods now have mental health benefit
* Fixed ice cream stats (issue [#2196](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2196)) (Playtest)
* Fixed grey backgrounds (issue [#2196](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2196)) (Playtest)

## Recipes

* Added fried egg
* Fixed boiled egg recipes (issue [#2185](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2185)) (Playtest)

## Furniture

* Fixed Moonshine distillery requiring barrel planters (issue [#2229](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2229)) (Playtest)
* Fixed furniture crafting UI not showing and using resources inside backpack (issue [#2258](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2258)) (Playtest)

## Tenement System

* Fixed player kitchen having an owned cabinet (issue [#2206](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2206))
* Fixed respawning money box (issue [#2180](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2180)) (Playtest)
* Fixed bleach, disinfectant and cleaner not being used if they were stored in the backpack (issue [#2248](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2248)) (Playtest)
* Fixed sewing machines being owned (issue [#2244](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2244)) (Playtest)
* Fixed picking up mail in buildmode causing the mail pile to stay (issue [#2249](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2249)) (Playtest)

## Bazaar Bank

* Added a button to turn off the alarm inside the boss's house (issue [#2181](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2181)) (Playtest)
* Changed some items and storages owners (issue [#2184](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2184)) (Playtest)
* Fixed gas killing the player when hiding at the boss's house (issue [#2181](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2181)) (Playtest)
* Fixed some storages not spawning items (issue [#2178](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2178)) (Playtest)
* Fixed the lamp at the bank entrance being turned on at start (issue [#2176](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2176)) (Playtest)
* Fixed blowing bank vault up setting off the alarm system even if the alarm was disarmed already (issue [#2174](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2174)) (Playtest)
* Fixed the vault door auto closing when the player is inside the vault (issue [#2183](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2183)) (Playtest)
* Fixed the alarm disarm sound being too loud (issue [#2182](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2182)) (Playtest)

## O-Market

* Fixed "Stalburg Times" and "Evening Tidnings" showing estimate price (issue [#2250](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2250)) (Playtest)

## Tenement A

* Added cat trader
* Changed the Tenement A keycard to a regular item (issue [#2188](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2188)) (Playtest)
* Changed resident list style (issue [#2171](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2171)) (Playtest)
* Fixed resident list names not being rendered properly when viewed from smaller angles (issue [#2170](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2170)) (Playtest)

## Deekula B

* Fixed not being able to use B3 toilet after the apartment is cleaned (issue [#2208](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2208))

# June 4th 2024 (Version 0.3.39 V4) - Playtest

* Changed cats' eyes to glow in the dark (issue [#2070](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2070)) (Playtest)
* Changed Osrat arrow to be illuminated in the dark (issue [#2130](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2130))
* Changed waiting text when working (issue [#2112](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2112))
* Fixed animal breeding only produsing default breed (issue [#2160](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2160)) (Playtest)
* Fixed not being able to plant stacks correctly (issue [#2122](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2122)) (Playtest)
* Fixed hold to sprint and crouch pause menu issue (issue [#2130](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2130))
* Fixed green electrical model not having pixelization applied (issue [#2111](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2111))
* Fixed being able to take ungrown cats and rats (issue [#2153](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2153)) (Playtest)
* Fixed animal growing indicator not visually progressing (issue [#2155](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2155)) (Playtest)
* Fixed crafting process not starting when using different types of water (issue [#1126](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1126))
* Fixed vending machines not restocking (issue [#2168](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2168))

## Tenement System

* Changed the tenement blueprint to show that the first apartment is player's (issue [#2139](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2139))
* Fixed start tenement upgrades with samuel not appearing (issue [#2092](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2092)) (Playtest)
* Fixed missing rent dialogue (issue [#2124](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2124)) (Playtest)
* Fixed rotate object tooltip (issue [#2154](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2154)) (Playtest)
* Fixed respawning money box (issue [#2125](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2125)) (Playtest)

## Tasks

* Fixed "Tell passmore what you found" objective is not getting completed (issue [#2102](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2102)) (Playtest)
* Fixed "Get Dynamite for Passmore" objective is not getting completed (issue [#2079](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2079)) (Playtest)
* Fixed Passmore only giving 1 OC (issue [#2100](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2100)) (Playtest)

## Items

* Added vanilla ice cream
* Added boiled egg
* Added rock item to Tenement Resource category (issue [#2140](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2140))
* Fixed being able to stack fertile chicken eggs (issue [#2159](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2159))
* Fixed a fertile egg or chick not spawning fully grown item in the inventory (issue [#2157](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2157))

## Recipes

* Added boiled egg
* Changed 3D printer recipe icons to usb icons (issue [#2129](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2129))
* Fixed saline recipe (issue [#2149](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2149))

## Furniture

* Fixed esc not closing type mode (issue [#2057](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2057)) (Playtest)
* Fixed missing caret (issue [#2057](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2057)) (Playtest)
* Fixed new machinery having owned tags (issue [#2113](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2113)) (Playtest)
* Fixed not being able to place the firewood storage (issue [#2094](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2094)) (Playtest)
* Fixed build mode activating when editing signs (issue [#2120](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2120)) (Playtest)

## Main Menu

* Changed to be able to remove all character slots without needing to select an existing slot first (issue [#2148](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2148))
* Fixed 'remove slot' button being partially unclickable (issue [#2147](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2147))

## Bazaar Bank

* Fixed starting area being too dark (issue [#2082](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2082)) (Playtest)
* Fixed starting area collisions (issue [#2083](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2083)) (Playtest)
* Fixed shelves in the Bank sending player flying in random direction (issue [#2093](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2093)) (Playtest)
* Fixed missing sink UI image (issue [#2084](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2084)) (Playtest)
* Fixed blowing bank vault up setting off the alarm system even if the alarm was disarmed already (issue [#2091](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2091)) (Playtest)
* Fixed there's not being consequences for being in the bank after 3:00 (issue [#2101](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2101)) (Playtest)

## Tenement A

* Added lightable oil lamp to the room with recorder (issue [#2137](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2137)) (Playtest)
* Added more detail to Osrat shadow cluster room (issue [#2116](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2116)) (Playtest)
* Changed Fredrik's store to refridginated (issue [#2145](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2145)) (Playtest)
* Fixed several issues (issue [#2131](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2131)) (Playtest)
* Fixed something blocking player's movement on the green door (issue [#2117](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2117)) (Playtest)

## Tenement B

* Fixed tunnel missing details (issue [#2104](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2104))

## Kolhola

* Added catspawner to A14

## O-Market

* O-Market now sells ice cream
* Fixed hot dog weiner refigerator (issue [#2060](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2060))

# May 31st 2024 (Version 0.3.39 V3) - Playtest

* Added flies when player's hygiene is very low (issue [#2034](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2034))
* Added urination/defecation sounds slider (issue [#2050](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2050))
* Added cats to give scratches when catched if the cat is not tamed (issue [#2069](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2069)) (Playtest)
* Fixed missing Interior City Gates (issue [#2059](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2059)) (Playtest)
* Fixed player seeing breeding recipes in the cages not designated for them (issue [#2068](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2068)) (Playtest)

## Tasks

* Fixed not being able to give dynamite to Passmore (issue [#2072](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2072))

## Tenement System

* Changed "RMB) Rotate object" to "RMB) Hold and move to rotate" (issue [#2041](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2041))
* Fixed makeshift courtyard stairs collision (issue [#2054](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2054))

## Items

* Dynamite can now be detonated with an axe or sledgehammer
* Fixed diesel having "Equip" button (issue [#2024](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2024))

## Intro

* Fixed intro issues (issue [#2073](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2073))

## Player Tenement

* Fixed npc navigation (issue [#2071](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2071))

## Outside

* Added a rare thunderstorm
* Changed start weather and time (issue [#2028](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2028))
* Fixed Lönkkä Kurahaara not buying vegetables (issue [#1956](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1956))

## Tenement A

* Fixed Fredrik stealing player's money (issue [#2056](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2056)) (Playtest)
* Fixed player getting blocked on the last step of the Tenement A stairwell (issue [#2055](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2055)) (Playtest)

## Deekula A

* Fixed Dr. Pena MD not asksing for player's turn slip (issue [#1969](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1969))

## Greenhouse

* Jomppe now mentions that you can use produce to plant more of it (issue [#2042](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2042))

# May 30th 2024 (Version 0.3.39 V2) - Playtest

* Added Tenement A (Playtest)
* Added ability for Dr. Pena to check addiction levels
* Added indicator to crafting stations to show if it is manually operated
* Added possibility to subscribe to Open Sewer magazine
* Added more recipe spawners with wider range of recipes to spawn
* Added electronics skill
* Added electronics workbench
* Added sewing
* Added engineering skill achievement
* Added cat
* Added chick
* Added chicken
* Magazines and newspapers can be used to skip time
* Lifehack-Pekka now comes as an item what gives recipes upon usage
* Reading Open-Sewer magazine gives small amount of random skill.
* Fixed wrong verb used in sauna tip (issue [#1936](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1936))
* Fixed a single open sewer coin title (issue [#1935](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1935))
* Fixed vending machines missing glow (Playtest)
* Fixed Walt Bondar using wrong dialogue (issue [#2007](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2007))
* Fixed uprooting a dead plant typo (issue [#2004](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2004))
* Fixed closing the backpack closing the entire UI while recycling bottles (issue [#1998](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1998))
* Fixed the prison deleting backpack and its contents (issue [#1960](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1960)) (Playtest)
* Fixed the open option not showing after trying to unequip backpack with items (issue [#1951](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1951)) (Playtest)
* Fixed small Dr. Pena MD typo (issue [#1971](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1971))
* Fixed mashing kettle capacity showning incorrect value (issue [#1959](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1959))
* Fixed vending machines immediately restocking (issue [#2000](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2000))
* Fixed being able to drag multiple items at same time in inventory
* Fixed liquid amount not being merged correctly sometimes

## Tenement System

* Added small label blueprint
* Added industrial sign blueprint
* Added moonshine distillery blueprint
* Added Ceiling Lamp Chain Blueprint
* Added Metal Chain Blueprint
* Fixed shabby courtyard dumpster clipping (issue [#1938](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1938))
* Fixed Ilona Pettinen dialogue (issue [#1990](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1990))

## Items

* Added Mushroom Substitute Prescription
* Added Mushroom Substitute Pills
* Added Evening Tidings Newspaper
* Added Stalburg Times
* Added Open Sewer magazine
* Added Lifehack-Pekka magazine
* Added plastic parts
* Added copper wire
* Added tin wire
* Added thread
* Added feathers
* Added electric components
* Added copper bar
* Added aluminum bar
* Added small glass bottle (0.5L)
* Added description to tin cans to say they are made out of steel (issue [#2022](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2022))
* Changed dirty bandages to lower player hygiene (issue [#2020](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2020))
* Sulphuric acid is now drinkable
* Mercury is now drinkable
* Fixed leek food and quality values (issue [#1952](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1952))
* Fixed items having infinite uses sometimes (issue [#1949](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1949))
* Removed slag being burnable
* Renamed wire -> cable

## Recipes

* Added facemask
* Added wiring components
* Added electronic parts
* Added plastic parts
* Added teddy bear
* Added oven cloth
* Added aluminum recycling
* Added empty plastic container
* Added gold extraction to electronic parts and computer parts
* Fixed gold extraction recipes
* Fixed coffee not having skill assigned

## Furniture

* Added firewood pile
* Added electronics station
* Added sewing machine
* Added chicken coops
* Added cat cages
* Added editable label
* Added editable sign
* Added 3D printer
* Fixed flat screen TV price
* Jonasson now sells table saw
* Jonasson now sells gas bottles (furniture)
* Water cooler bottle is now obtainable
* Potato sack is now obtainable

## Outside

* Added lootable bird nests
* Fixed the Deekula B police tape not being removed (issue [#1942](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1942))

## Bazaar Bank

* Fixed save/loading making the cameras go crazy (issue [#1961](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1961))
* Fixed not being able to disable Bank's security if alarm is not on (issue [#1962](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1962))

## Deekula C

* Fixed Deekula C door (issue [#1957](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1957)) (Playtest)

## O-Market

* O-Market now sells daily newspapers
* O-Market now sells rice
* Changed layout

## Tenement B

* Fixed being able to start the bank task again (issue [#1945](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1945)) (Playtest)

## Gatehouse

* Player can now request medicine and shroom substitute from the guard

## City Gates

* Fixed player getting stuck on rocks (issue [#1943](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1943)) (Playtest)

## Metro

* Fixed being able to get stuck to the elevator shaft (issue [#1940](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1940)) (Playtest)
* Fixed the exit doors clipping through a black plane (issue [#1941](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1941)) (Playtest)

## Kolhola

* Added functioning dishwashers
* Added electronics station
* Fixed A7 item ownership
* Fixed A13 balcony door
* Fixed Sam Morton appearing as Colton (issue [#1937](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1937))
* Fixed subtitle showing Mirjam Freighter instead of Eliana Passmore (issue [#1939](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1939)) (Playtest)
* Fixed doorbell dialogue repeating after door is unlocked (issue [#1953](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1953)) (Playtest)

# April 23st 2024 (Version 0.3.39) - Playtest

* Added Open Sewer Metro (Playtest)
* Added Interior City Gates (Playtest)
* Added Interior Bazaar Bank (Playtest)
* Smoking addiction & smoking need now modulates mental health change speed.
* Added ability to open backpacks when they are on the ground
* Changed backpacks to have own inventory instead of global inventory
* Changed backpacks to be able to moved to the inventory only if they are empty
* Changed backpacks to count as part of the player's inventory
* Fixed empty liquid containers sometimes breaking the dishwasher
* Fixed redundant Fenella Hunt dialogue (issue [#1920](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1920))
* Fixed fuel slots not always working (issue [#882](https://github.com/loiste-interactive/Obenseuer-Issues/issues/882))

## Items

* Added slag
* Added gold nugget (high purity)
* Added mercury
* Added sulphuric acid
* Added lighter
* Added cigar
* Added pack of cigars
* Balanced soup crafting times and difficulty
* Changed empty milk carton icon (issue [#1927](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1927))
* Changed electronic waste icon and model (issue [#1926](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1926))
* Fixed homemade wheat flour dropping homemade rye flour

## Recipes

* Added high purity gold bar
* Added gold extraction (chemical lab)

## Tenement System

* Fixed fine walls player tenement door not closing automatically (issue [#1921](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1921))
* Fixed decent stairwell resident list placement (issue [#1928](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1928))
* Fixed decent player apartment walls window visual gap (issue [#1933](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1933))

## Furniture

* Added Toilet Brush
* Added Bathroom Glass
* Added Bathroom Cup
* Added Plunger
* Added Lattemaster Coffeemaker
* Fixed not being able to turn off the candle bowl (issue [#1918](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1918))
* Fixed Stolland clock placement issue (issue [#1924](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1924))

## Kolhola

* Fixed Hall Kääbus reappearing in the hostel after moving into the tenement (issue [#1922](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1922))

# March 21st 2024 (Version 0.3.38) - hotfix

* Fixed crafting stations visual state not updating when power status is changed (issue [#1913](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1913))
* Fixed the backpack being usable after being taken while sleeping (issue [#1917](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1917))
* Fixed betel palm trees giving tomato seeds (issue [#1914](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1914))

## Items

* Fixed eating canned foods not giving you an empty can

## Tenement System

* Fixed cleaning status not always updating correctly
* Fixed missing toilet in fine basement sauna upgrade

## Deekula A

* Changed Dr. Pena MD model

## Deekula C

* Fixed storage stove being a ball grill (issue [#1912](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1912))

## Kolhola

* Added ability to ask which pod player rented (issue [#1111](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1111))
* Added dialogue if all pods are rented (issue [#1122](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1122))

# March 19th 2024 (Version 0.3.37) - hotfix

* Fixed survive 7/30/365 days achievements not triggering
* Fixed broken sauna (issue [#1906](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1906))
* Fixed bucket toilets buckets not filling with products made by player
* Fixed non sellable items dissappearing when trying to sell them
* Fixed not being able to move items when using keyboard or controller

## Items

* Changed the plastic filament not to be stackable
* Changed the coffee packages not to be stackable

## Tenement System

* Added resident list to stairwell to display current residents

## Recipes

* Fixed cider yield

# March 15th 2024 (Version 0.3.36) - hotfix

* Fixed difficulty setting not saving correctly from main menu (issue [#1902](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1902))
* Fixed some crafting/growing stations not showing recipes (issue [#1899](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1899))
* Fixed resetting refresh rate

## Tenement System

* Fixed furniture storages sometimes losing all items (issue [#1900](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1900))
* Fixed not being able to use the shabby bathroom shower (issue [#1897](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1897))
* Fixed wine rack bottles remaining in the furniture store UI if the game was saved when the wine rack was last selected (issue [#1896](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1896))

## Furniture

* Fixed Open Sewer poster name (issue [#1895](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1895))

# March 14th 2024 (Version 0.3.35)

* Added difficulty settings
* Added hygiene
* Added radiation
* Added dishwasher (workbench for reseting owner of items)
* Added face slot
* Added move stacks quickly by holding down the mouse button (issue [#1769](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1769))
* Added ability to remove save slots (issue [#1885](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1885))
* Added controls to doctor UI
* Added radiation check to Dr. Pena
* Added a second autosave slot
* Added processing time for crafting furniture (issue [#1190](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1190))
* Fixed gaining drinking skill from inappropriate actions (issue [#1892](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1892))
* Fixed tooltip being able go off the screen (issue [#1886](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1886))
* Fixed the under map door teleporting player to the wrong place (issue [#1868](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1868))
* Fixed satisfaction of bowel and bladder not being registered when player is already sitting on a toilet (issue [#1873](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1873))
* Fixed gun-trap having a chance of displaying "dead by beating" on the death-screen (issue [#1875](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1875))
* Fixed plants freezing the game (issue [#1801](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1801))
* Fixed item shortcuts not working sometimes (issue [#1818](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1818))
* Fixed extra storage space in storage (issue [#1827](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1827))
* Fixed bank panel missing rounding
* Fixed heracleum plant not being centered
* Fixed SMV progression going back to 0% when god mode is on (issue [#1835](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1835))
* Fixed mushroom consumption causing the player to travel to Other Side for a few seconds (issue [#1835](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1835))
* Fixed Aleksi Kivi dialogue loop (issue [#266](https://github.com/loiste-interactive/Obenseuer-Issues/issues/266))
* Fixed not being able to navigate to inventory sort buttons when using keyboard or controller
* Fixed biogas reactor meter not updating (issue [#1848](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1848))
* Fixed doctor UI showing wrong price
* Fixed sleeping events
* Fixed connected controllers locking the mouse cursor
* Increased farming payment (issue [#1871](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1871))
* Increased mash payment (issue [#1871](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1871))
* Removed space being an action button (issue [#142](https://github.com/loiste-interactive/Obenseuer-Issues/issues/142))

## Tenement System

* Rebalanced renovation costs (issue [#1871](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1871))
* Added unique apartment decoration to Aleksi Kivi
* Changed basic income to base income (issue [#1853](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1853))
* Fixed invisible wall in medium workshop upgrade (issue [#1893](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1893))
* Fixed water upgrades under construction tarp (issue [#1887](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1887))
* Fixed the terrarium having an aquarium light when using building mode (issue [#425](https://github.com/loiste-interactive/Obenseuer-Issues/issues/425))
* Fixed apartment cleaning percentage not updating sometimes (issue [#1726](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1726))
* Fixed the apartment 14 phantom fireplace (issue [#1847](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1847))
* Fixed the apartment 14 body giving unusable mushroom item (issue [#1847](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1847))
* Fixed heating upgrade construction missing tarp (issue [#1846](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1846))
* Fixed wires clipping through the floor of the roof greenhouse (issue [#1843](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1843))
* Fixed missing foundation wall near the gazebo (issue [#1841](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1841))
* Fixed second floor large apartment windows being shifted (issue [#1862](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1862))
* Fixed Pate's balcony (issue [#1814](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1814))
* Fixed spawners not removing old items when respawning in Malone's apartment (issue [#1820](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1820))
* Fixed the basement hallway being black when the basement is under construction
* Fixed phantom sleeping bag (issue [#1823](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1823))

## Items

* Added facemask pack
* Added facemask
* Added bag of blood
* Added saline
* Added dosimeter
* Added cobalt-60
* Added iodine pills
* Added dishwasher powder
* Added owned icon for slot items
* Added quality icon for slot items
* Added to the descriptions of Osmo Olut drinks that they are beer (issue [#1874](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1874))
* Fixed unpickable hamburgers (issue [#1839](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1839))
* Fixed Mason Jars breaking when trying to drink (issue [#1821](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1821))
* Fixed dropping the last bottle causing bottles reappear after breaking them (issue [#1863](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1863))
* Fixed original stack amount to changing to 1 when one item is dragged to a slot that does not accept it (issue [#1845](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1845))
* Fixed splitting stacks causing several issues with liquids (issue [#1834](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1834))
* Increased spoilage times
* Removed quality background from slot items

## Recipes

* Added missing cider recipe
* Added missing mushroom cider recipe
* Added saline
* Reduced fail chance of canned foods to almost 0
* Fixed some canned food recipes not requiring can opener (issue [#1850](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1850))
* Fixed some canned food recipes not returning empty cans (issue [#1850](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1850))

## Furniture

* Added dishwasher
* Fixed green dumpster having wrong price
* Fixed chemical lab blueprint using an aquarium insread of a terrarium (issue [#1645](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1645))

## Console

* Added difficulty commands
* Added command to manipulate hygiene
* Added command to manipulate radiation dose
* Fixed console kicking you out of the command line every time you press enter (issue [#840](https://github.com/loiste-interactive/Obenseuer-Issues/issues/840))

## Main Menu

* Changed character remove to mention that it removes all slots (issue [#1885](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1885))
* Removed press any key flash effect

## Outside

* Added police respawn to their original positions (issue [#1788](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1788))
* Fixed letter lights being only illuminated while in field of view (issue [#900](https://github.com/loiste-interactive/Obenseuer-Issues/issues/900))
* Fixed getting more than one pea soup a day (issue [#1826](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1826))

## Pharmacy

* Pharmacy now sells facemasks
* Pharmacy now sells iodine pills

## O-Market

* O-Market now sells dishwasher powder
* Fixed rats and animals being stuck

## Tenement B

* Fixed blue barrels not having collision (issue [#1817](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1817))

## Speakeasy

* Fixed betel palm causing invisible wall (issue [#1805](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1805))

# February 2nd 2024 (Version 0.3.33) - hotfix

* Fixed Pentti not paying for mash (issue [#1804](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1804))
* Fixed characters' stretched lips
* Removed flicker effect from super flashlight

## Tenement System

* Fixed not being able to take 24 pack from the stairwell
* Fixed moving not having correct furniture with items selected in migrated saves
* Fixed sometimes moved furniture with items duplicating when saving and loading (issue [#1799](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1799))

## Furniture

* Fixed hospital bed and table being too big

## Items

* Fixed drinking tea destroying tea cup

# February 1st 2024 (Version 0.3.31) - hotfix

* Fixed some saves getting stuck on the loading screen after migrating
* Fixed storage and backpack inventory getting combined (issue [#1791](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1791))

## Tenement System

* Fixed all furniture disappearing when taking furniture with items (issue [#1792](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1792))

# January 31st 2024 (Version 0.3.30)

* Added save migration if save has missing reference ids
* Added modifiers to show capacity
* Changed saving and loading menu (issue [#112](https://github.com/loiste-interactive/Obenseuer-Issues/issues/112))
* Changed blueprint spawner behavior
* Changed backpack button to backpack slot and button
* Increased growing skill gain 2 times (issue [#1768](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1768))
* Fixed player getting stuck if he falls asleep when working (issue [#1469](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1469))
* Fixed items getting stuck in crafting stations (issue [#1785](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1785))
* Fixed item sorting not working correctly sometimes
* Fixed phone script saving all dialogue data
* Fixed some saves crashing constantly (issue [#1644](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1644))
* Fixed tutorial move buttons when using arrow keys (issue [#1738](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1738))
* Fixed can openers clogging up lathes (issue [#1741](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1741))
* Fixed gas bottle drain/fill rate being orders of magnitude smaller when player is skipping time
* Fixed some item spawners spawning items without deleting previous items and causing lag
* Fixed NaN mushroom need addiction value (issue [#1764](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1764))
* Fixed bank customer service typo (issue [#1754](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1754))
* Fixed closing backpack closing the bottle recycling machine interface (issue [#1741](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1741))
* Fixed missing inflatable pool icon
* Fixed purchasing liquid removing random amounts (issue [#1736](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1736))
* Fixed Pentti stealing mash (issue [#1756](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1756))
* Fixed wieldable items not disappearing when being sent to jail (issue [#1749](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1749))
* Fixed liquid amounts changing when stacking liquid containers (issue [#1733](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1733))
* Fixed disappearing stairs when upgrading to huge workshop
* Fixed missing backside barriers during workshop upgrade (issue [#1739](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1739))
* Fixed apartment not being cleaned when the construction blocks entry (issue [#1763](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1763))
* Fixed Samuel reacting negatively to stolen items of they are inside player's inventory when renovating (issue [#1717](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1717))

## Tenement System

* Added unique apartment decoration to Pate Rantanen
* Added unique apartment decoration to Amanda Korhonen
* Biogas reactor gauge now shows the filled precentage in UI
* Biogas reactor compressor now automatically runs when the vat is full with gas
* Fixed a bug that caused furniture to disappear
* Fixed duplicating furniture (issue [#1782](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1782))
* Fixed balcony construction tarps being at the wrong balcony (issue [#1787](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1787))
* Fixed category buttons not working correctly (issue [#1779](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1779))

## Furniture

* Added new magazines
* Added new posters
* Added hospital bed
* Added hospital table

## Recipes

* Fixed can openers crafting instantly

## Items

* Changed Mason Jars to be breakable

## Outside

* Fixed yard porta-potty graphical (issue [#1760](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1760))

## Greenhouse

* Fixed Jomppe not buying hops
* Fixed Jomppe not buying watermelons (issue [#1742](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1742))

## Kolhola

* Fixed betel palms causing invisible walls
* Fixed elevator light (issue [#1740](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1740))

## Mr. Duck's House

* Fixed items spawning in the chest when returning to the house

## Deekula C

* Fixed C1 bucket toilet being backwards (issue [#1473](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1473))

## Tenement B

* Fixed seeing the bank ladder not updating the task ([#1751](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1751))
* Fixed Under Map teleporting player to infront of entrance to the small mine cave ([#1765](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1765))

# January 17th 2024 (Version 0.3.29)

* Betel palms now yield multiple harvests
* Biogas reactor now builds up gas into the vat and compressor is needed to run only for short period of time
* Changed main menu to show first the character that has the latest save (issue [#309](https://github.com/loiste-interactive/Obenseuer-Issues/issues/309))
* Fixed storages not working on Swiss-German locales (issue [#1124](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1124))
* Fixed chemical lab getting stuffed (issue [#1570](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1570))
* Fixed police arresting player when player moves to another area clearing crime and making time fast.
* Fixed liquid sorting duplicating liquids (issue [#1613](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1613))
* Fixed prison food getting moldy when player is asleep (issue [#1513](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1513))
* Fixed sometimes entering Speakeasy sending player straight to wasteland (issue [#1699](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1699))
* Fixed union flags being broken for the first time (issue [#1677](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1677))
* Fixed crafting not returning containers if the game is saved and loaded while crafting is in progress (issue [#1706](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1706))
* Fixed growing green mushrooms not hurting when being near them (issue [#1659](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1659))
* Fixed Unity logo appearing sometimes when booting up the game (issue [#1629](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1629))
* Fixed negative mashing process (issue [#1691](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1691))
* Fixed apartments upgrade achievements (issue [#1652](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1652))
* Fixed wood debris collision not being disabled when the wood debris is gone (issue [#1684](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1684))
* Fixed being able to start a crafting process even if not having the required items (issue [#1680](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1680))
* Fixed lockpicking keeping player in locked position too long when depleting lockpicks stack (issue [#1668](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1668))
* Fixed harvesting quality varying between in-world and UI (issue [#1682](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1682))

## Tenement System

* Added barriers and sounds to apartments when they are being renovated
* Added text to show what items the trash will give if the inventory is full (issue [#1663](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1663))
* Fixed apartments showing not being cleared when they should (issue [#1726](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1726))
* Fixed decent player extension windows
* Fixed renovation timer getting stuck at 0s when passing time (issue [#1620](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1620))
* Fixed some initial upgrades having required resources (issue [#1704](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1704))
* Fixed cleaning mode triggering when walking out of roof greenhouse (issue [#1663](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1663))
* Fixed not being able to always place some rugs on the floor (issue [#1649](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1649))
* Fixed fine basement sauna pool room benches
* Fixed not being able to pick up items in the basement (issue [#1669](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1669))
* Some furniture can now be mounted also on walls

## Items

* Added juniper trees
* Added hop seeds
* Added hop plant
* Added box of tea
* Added tea
* Betel palm nuts are now stackable
* Fixed pearl earings not being able to be picked up
* Fixed drinking kumis, rice wine, milk moonshine and shochu also eating the bottle
* Fixed not being able to move liquids between some containers (issue [#1675](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1675))
* Fixed merging stacks multiplying liquids (issue [#1678](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1678))
* Updated guitar animations and sounds

## Recipes

* Added tea recipe
* Yeast can now be extracted from milk and rice mashes

## Furniture

* Added jack-o-turnip
* Added grain mill to shop lists
* Added waiting functionality to player owned televisions
* Added mushroom lamps to shop lists
* Fixed bathtub ownership
* Fixed fancy wooden desk name (issue [#1703](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1703))
* Fixed grain mill missing icon and slots
* Fixed bathtubs (growing) not having correct modifiers (issue [#1676](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1676))

## Outside

* Fixed being able to take pea soup when inventory is full (issue [#1305](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1305))

## Deekula C

* Fixed Möbelmann door (issue [#1655](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1655))

## Kolhola

* Changed lighting
* Changed telemarketing hourly rate to be the minimum hourly rate
* Changed telemarketing job to not increase thrist or toilet
* Fixed hotel rooms always being rented for one day only (despite paying for multiple)
* Fixed hotel toilet locking player in if player's reservation expires (issue [#1670](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1670))
* Fixed sitting on the apartment A3 bench at the left of the entrance making player facing wall (issue [#1698](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1698))
* Fixed apartment A20 curtains disappearing depending on the viewing angle (issue [#1697](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1697))
* Fixed Sam Morton not having dialogue

## Tenement B

* Fixed selling items not converting RM to OC amount in Passmore's money pool
* Fixed Passmore having stolen item prices in every item

## O-Market

* O-Market now sells tea

## Redemption Militia

* Player can now volunteer at redemption militia

# December 29th 2023 (Version 0.3.28)

* Disabled broken eye adaption
* Fixed several issues with manufacturing UI (issue [#1596](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1596))
* Fixed supernova sun (issue [#1548](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1548))
* Fixed weather effects delay (issue [#1552](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1552))
* Fixed Lively Tenement achievement (issue [#1587](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1587))
* Fixed shop money not replenishing in some old saves (issue [#1583](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1583))
* Fixed Makeshift Sink blueprint name (issue [#1617](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1617))
* Removed sun and moon flare that draws above everything (issue [#700](https://github.com/loiste-interactive/Obenseuer-Issues/issues/700))

## Tenement System

* Added furniture descriptions (issue [#1193](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1193))
* Fixed cleaning counter resetting to 0% (issue [#1592](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1592))
* Fixed not being able to use building menu when entering the tenement from outside (issue [#1573](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1573))
* Fixed furniture parenting not working (issue [#1591](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1591))
* Fixed some furniture giving multiple furniture
* Fixed apartment 11 bear trap not being removable
* Fixed not being able to remove firewood basket (issue [#1573](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1573))
* Fixed moving resitent showing 0s when there is less than hour left (issue [#1589](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1589))
* Fixed income field not updating when tab is open and resident moving is done (issue [#1589](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1589))
* Fixed upgrade panel tenement upgrades being circles (issue [#1576](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1576))
* Fixed storages with items being in the sky (issue [#1616](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1616))

## Items

* Added tiny candle
* Changed paint buckets to be stackable (issue [#1430](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1430))
* Fixed dropped items not despawning

## Tasks

* Fixed Homecoming Celebration missing gift and bottle (issue [#1574](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1574))

## Greenhouse

* Fixed Jomppe not buying cabbage (issue [#1590](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1590))

## Deekula B

* Fixed police tape not despawning (issue [#1598](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1598))

## O-Market

* O-Market now sells tiny candles
* Fixed matches, glue and cleaning spray not being sold as full (issue [#1580](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1580))

# December 22nd 2023 (Version 0.3.27) - hotfix

* Fixed traders money not respawning
* Fixed building mode showing text that player apartment is not examined when walls are upgraded

# December 22nd 2023 (Version 0.3.26)

* Added map markers
* Added 3 new achievements
* Added menu navigation keys to key bindings menu
* Added flashlight reload hint to show when out of batteries
* Added "drinking" skill
* Added "drinking" skill achievement
* Fixed weather not saving correctly
* Fixed mushrooms plants not spoiling
* Fixed plants staying at 0% when planting fails
* Fixed trader money resetting after loading the game
* Player can now turn themselves for the police
* Player can now work for the Telemarketing company in Kolhola
* Fixed loading save in prison leaving skipping tools disabled
* Fixed Canal Sauna, Kolhola, Redemption Militia and Deekula C not having a map (issue [#936](https://github.com/loiste-interactive/Obenseuer-Issues/issues/936))
* Fixed coffee causing imsomnia (issue [#1395](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1395))
* Fixed guitar (issue [#1264](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1264))
* Fixed being able to override items in other inventories  (issue [#1342](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1342))
* Fixed getting stuck on toilet when the toilet bucket is full (issue [#1417](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1417))
* Fixed harvesting vine plants counting as crime (issue [#1407](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1407))
* Fixed vine plants not being harvestable at 100% (issue [#1416](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1416))
* Fixed being able to sit on Keijo (issue [#1517](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1517))
* Fixed lockpicking achievement
* Fixed cooking achievement
* Fixed sitting while being arrested freezing player (issue [#1447](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1447))
* Fixed being able to talk to police when police is chasing you
* Fixed loading a save crashing the game (issue [#1533](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1533))
* Fixed canal sauna area not covering whole sauna (issue [#1479](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1479))
* Fixed refresh rate resetting after re-launch (issue [#1477](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1477))
* Fixed not being able to rent an apartment to Jesper Kumpula after renting an apartment to Ingrid Claesson
* Fixed vendors closing an hour later than they should (issue [#1426](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1426))
* Fixed items spawning in random points

## Tasks

* Added a hint about the printer and mailbox to "Missing debitcard" task description
* Changed renovation tasks to move to separate bar (issue [#1333](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1333))
* Changed renovation task to not be visible in task panel when completed (issue [#1333](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1333))
* Changed the descriptions of some tasks (issue [#1530](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1530))
* Fixed being able to give 5 rubber ducks again to Mr. Duck (issue [#1415](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1415))
* Fixed "Start 5 renovations" not counting renovations started before getting the objective (issue [#1116](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1116))

## Items

* Added milk mash
* Added rice mash
* Added kumis
* Added rice wine
* Added milk moonshine
* Added shochu
* Macaroni casseroles now have two uses
* Pies now have multiple uses
* Pizzas now have multiple uses
* Fixed tomato soups turning into vegetable soups when dropped, fixed peasoup changing type (issue [#1145](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1145))

## Furnitures

* Added posters
* Added new paintings
* Added magazines
* Added signs
* Added Old Bathtub
* Added Shabby Bed Frame
* Added Broken Payphone
* Added boots
* Added Cardboard Boxes
* Added Fire Extinguisher
* Added Old Small Folder
* Added Metal Chain
* Added Portable Ladder
* Added Red Barrel with Fire
* Added Shopping Basket
* Added Traffic Cone
* Added Camera Tripod
* Added Laptop
* Added Kitchen Drawer
* Added Brown Refrigerator
* Added Candle Bowl
* Added Ceiling Lamp Chain
* Added Table Lamp
* Added Car Wheel
* Added Bathroom Cabinet
* Added Potato Sack
* Added Old Cottage Table
* Added Pan
* Added Cafeteria Bucket
* Added Red Bucket
* Added Broom
* Added Blue Plastic Barrel Sink
* Added Makeshift Toilet
* Added Blue Plastic Barrel Sink Blueprint
* Added Makeshift Toilet Blueprint
* Added Makeshift Sink Blueprint
* Added Shabby Bed Blueprint
* Added Tarp Wall furniture and blueprint
* Added Wooden Pillar furniture and blueprint
* Added wall hook furniture and blueprint (issue [#1314](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1314))
* Added bathtub with soil furniture and blueprint (issue [#1314](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1314))
* Added bathtub with soil and support furniture and blueprint (issue [#1314](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1314))
* Fixed Stolland clock being rotated 180 degrees (issue [#1491](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1491))
* Fixed kitchen tools interactable area (issue [#1499](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1499))
* Fixed flowerboxes not updating modifiers when turned on/off (issue [#1476](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1476))

## Recipes

* Fixed not being able to craft some soups (issue [#1424](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1424))
* Fixed cooking oil and some other items not being red in recipe when missing (issue [#1425](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1425))

## Tenement System

* Added ability to decorate stairwell
* Added ability to clean other apartments and other places in the tenement
* Added new furnishings for tenants
* Changed apartments to require cleaning before being able to renovate (issue [#1494](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1494))
* Changed tenement and apartment utility names (issue [#1287](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1287))
* Changed tenement upgrade icon shapes (issue [#1287](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1287))
* Fixed Stairwell Lights causing lag
* Fixed renovation sound playing when changing map or loading game (issue [#1353](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1353))
* Fixed taking a furniture crashing the game sometimes (issue [#1418](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1418))
* Fixed greenhouse upgrades not giving sun modifier (issue [#1443](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1443))
* Fixed Malone's toilet paper being in the greenhouse on the roof
* Fixed furniture parenting not working with start furniture (issue [#1523](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1523))
* Fixed wall of text (issue [#1391](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1391))
* Fixed manufacturing process furniture saying containing items when it's not (issue [#1391](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1391))
* Fixed the doors of large apartments not closing automatically (issue [#1242](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1242))

## Open Sewer Tenement

* Added gift shop stall
* Added Kurahaara sign above the greenhouse door
* Optimized market square area a little
* Fixed wall near Kolhola doors missing collision

## Interior O-Market

* O-Market now sells flashlights
* O-Market now sells take away coffee
* Fixed O-market cigarette packs not being full

## Interior Deekula A

* Fixed not being able to enter doctor's office when saving and loading after taking the doctor's ticket (issue [#1531](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1531))

## Interior Kolhola

* Added new dialogue to Jörge Af Guldskjöld
* Fixed Liouba Bennet being called Fenella Hunt in dialogue (issue [#1518](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1518))
* Fixed Jörge Af Guldskjöld being called Fenella Hunt in dialogue (issue [#1518](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1518))

## Interior Gatehouse

* Fixed saving and loaded after being released from prison putting player again to prison (issue [#1106](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1106))
* Fixed switching prison cells causing issues (issue [#1100](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1100))

# December 7th 2023 (Version 0.3.23)

* Added O-Market and pharmacy to map
* Changed items to move to the nearest slot when dragged into a gap between slots instead of returning to the slot it was moved from
* Changed movement keys to affect menu navigation keys
* Fixed not being able to enter hotel reservation menu, order drink from Pentti, buy cigarettes from Mirjam.
* Fixed filling multiple containers at once from fermenters and alike multiplying liquid amount (issue [#1359](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1359))
* Fixed player being able to smuggle contraband to prison (issue [#1278](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1278))
* Fixed sauna temperature meters breaking on saveloads (issue [#1247](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1247))
* Fixed bank account being re-initialized (thus being empty) every safeload (issue [#1283](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1283))
* Fixed wonky drillhead (issue [#1340](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1340))
* Fixed furnace not loading state properly (issue [#1303](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1303))

## Tenement System

* Fixed some manufacturing tools showing containing items when a recipe is selected (issue [#1083](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1083))
* Fixed doors not loading states correctly after load (issue [#1350](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1350))
* Fixed spawning two items in the same spot in the apartments
* Fixed kitchen cutting boards being owned
* Fixed disappearing bucket toilet bucket

## Furniture

* Added microscope to vendors furniture list
* Increased how many different furnitures vendors have on sale

## Items

* Fixed slaughtering rats missing sound

## Gatehouse

* Added authorized personnel only sign to the door and also sign to warn about the camera (issue [#1372](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1372))

## Speakeasy

* Fixed Pentti selling mash back to player (issue [#1300](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1300))

# December 5th 2023 (Version 0.3.22)

* Added biogas reactor
* Adjusted brewing skill gain
* Tooltip now shows item owner (if not generic owner)
* Added hint that tells what key to press when using lockpick
* Added plants to show growing/spoiling status when looking at them outside the UI
* Added hold to press to uproot plants (issue [#1179](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1179))
* Fixed achievements triggering when starting a new game
* Fixed player passing through geometry
* Fixed recipes telling about missing item if recipe requires item with ammo
* Fixed loading save the second time would sometimes cause errors requiring a restart
* Fixed furniture preview icons not loading inside inventory (issue [#1299](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1299))
* Fixed Deekula B unlocking only when player gets "Me Mash!" task (issue [#1259](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1259))
* Fixed fermenting barrel being capped to 10L (should be 100L)
* Fixed not being able to offer fungicide prescription for Mona Hall
* Fixed not being able to pick up fully grown fruits
* Fixed plant sizes changing when loading game
* Fixed plants giving coins sometimes
* Fixed cucumbers disappearing after load
* Fixed some sounds not respecting volume setting (issue [#1323](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1323))
* Fixed furnace being too loud (issue [#1332](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1332))
* Fixed SMV rate calculation (fungicide increasing SMV rate, not reducing it)
* Fixed not being able to use Osrat (issue [#1365](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1365))
* Fixed some dialogue getting stuck when using keyboard (issue [#1368](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1368))

## Options Menu

* Added sprint and crouch toggle setting to controls menu (issue [#1181](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1181))
* Added bordeless windowed setting to display menu
* Added run in background setting to display menu
* Changed to be able to re-assign movement keys (AZERTY) (issue [#1006](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1006))

## Tenement System

* Fixed furniture starting disappear sometimes when item is removed
* Fixed not being able to farm in shabby extensions (issue [#1315](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1315))
* Fixed basement bullet time (issue [#1321](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1321))

## Recipes

* Added composting recipe what also uses ash
* Added yeast extraction recipe for chemical lab
* Fixed pasta showing empty tin can and returning can opener (issue [#1363](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1363))

## Items

* Added plant matter
* Fixed some items in enviroment not geting added to inventory when picked up (issue [#1357](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1357))

## Furniture

* Added biogas reactor
* Added kitchen set
* Added electric mashing kettle
* Added fermenting bucket
* Added fermenting container
* Added malter
* Added malter blueprint
* Added helm clock

## Tenement B

* Fixed dead Mike's mushrooms causing player getting stuck to the other side

## O-Market

* Fixed vegetable shelf items spoiling and breaking the storage

## Kolhola

* Changed blue duck to normal duck

# November 29th 2023 (Version 0.3.21)

* Added malting
* Added chemistry skill achievement
* Added bribery skill achievement
* Added rewards when reaching skill level 10
* Added double clicking save slot to load save (issue [#110](https://github.com/loiste-interactive/Obenseuer-Issues/issues/110))
* Doctor now offers fungicide
* Increased Passmore's budget
* Fixed skill not affecting meat grinder output
* Fixed overloaded ash slots, dropping ash on player location issue [#1234](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1234))
* Fixed attempting to use owned items complain about missing can opener issue [#1121](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1121))
* Fixed stealing coins, recipes and blueprints not counting as a crime [#1134](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1134))
* Fixed ball grills having furnace recipes instead of stove recipes
* Fixed being able to transfer liquids from stolen containers. (issue [#1263](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1263))
* Fixed fruit growh states not saving (issue [#1265](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1265))
* Fixed wardrobe having small space (issue [#1241](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1241))
* Fixed just planted grains missing any visible indicator (issue [#1117](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1117))
* Fixed bank exchange value calculation (issue [#1131](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1131))
* Fixed Passmore restocking RM balance every reload (issue [#1290](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1290))
* Fixed decorative plants giving OC coins on harvest
* Fixed Passmore restocking RM balance every reload (issue [#1290](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1290))
* Fixed sounds remaining muted after loading save in underwater (issue [#1301](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1301))
* Fixed the "Yellow Pages" not showing up when using the payphone (issue [#1284](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1284))
* Fixed the toll bridge doors not always closing (issue [#1243](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1243))
* Fixed process manufacturing UI bug with long names (issue [#1267](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1267))
* Fixed doors not being closed when they're relocked

## Tenement System

* Facade upgrades (mid tier) now needs asbestos
* High tier facade upgrade now needs insulation wool 
* Increased stack merging margin for perishables and quality values
* Changed apartment income to show much more or less apartment income would be when renting
* Changed the surgery damage to be proportional of player health
* Fixed disappearing items (issue [#1228](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1228))
* Fixed tenement upgrade storages not saving items (issue [#1271](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1271))
* Fixed item duplication bug (issue [#1228](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1228))
* Fixed moving furniture placed by upgarade causing the furniture to vanish on save load (issue [#1255](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1255))
* Fixed decent walls having balcony door (issue [#1257](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1257))
* Fixed some visual bugs in the player apartment (issue [#1245](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1245))
* Fixed moving container with items moving wrong container (issue [#1231](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1231))
* Fixed black lines around apartment doors with decent stairwell (issue [#1288](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1288))
* Fixed old television collision
* Fixed chairs still being occupied after renting apartment to NPC (issue [#1214](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1214))
* Fixed Leon Borg acting as he was living on the street when he has an apartment (issue [#1204](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1204))
* Fixed (Contains Items!) text duplicating
* Fixed Electric I and II upgrades having flipped prices
* Reduced apartment electricity installation cost
* Reduced apartment water installation cost

## Furniture

* Added trade union flags
* Added plastic storage chest
* Fixed previewing barrel planters colliding with player
* Reduced wooden chest price and updated blueprint

## Items

* Added stainless steel
* Added fungicide
* Added insulation wool
* Added asbestos
* Fixed double clicking to move items not working sometimes
* Fixed gold and silver mechanical watches missing quality data
* Fixed picking up dracaena plant seeds giving snakeplant seeds
* Fixed picking up soleirolia plant seeds giving aralia seeds
* Fixed picking up aralia plant seeds giving heraclium seeds
* Fixed septi low and weiners not being stackable

## Recipes

* Added negative effects for fungicides
* Fixed yarn not being burnable
* Pipes can now be crafted in furnace
* Fixed pizza recipes not returning jars (issue [#1226](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1226))

## Tasks

* Changed the Poison bottle objective to mention leaving the place

## Open Sewer Tenement

* Fixed Eija's refigerator only accepting bottles (issue [#1270](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1270))

## O-Market

* Fixed bread spoiling and breaking bread shelf (issue [#1269](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1269))
* Fixed not being able to talk to Mirjam Freighter

## Skeida Pharmacy

* Pharmacy now sells fungicide
* Pharmacy now sells syringes

## Interior tenement kolhola

* Fixed pod 8 being unsafe
* Fixed pod door opening directions
* Fixed some items having pharmacy as owner

# November 23th 2023 (Version 0.3.20)

* Fixed mushrooms causing laggy mold infestation in Kolhola (issue [#1221](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1221))
* Fixed not being able to pickup those laggy mushroom
* Fixed freezing in main menu (issue [#1222](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1222))
* Fixed mental health tooltip showing wrong value (issue [#1208](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1208))
* Fixed Hank Möbelmann not paying his electricity bill (issue [#1209](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1209))
* Fixed available process and grow slots not being being shown properly (issue [#1206](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1206))
* Fixed some residents breaking tenement upgrades in scene (issue [#1210](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1210))
* Fixed item info displaying wrong item sometimes in the inventory (issue [#1211](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1211))
* Fixed item duplication while in shop interface (issue [#1223](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1223))
* Fixed bird looking like a cat in a bird calendar (issue [#1212](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1212))
* Fixed Johan Wider changing appearance (issue [#1219](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1219))
* Fixed clipping through stairs to the basement door (issue [#1225](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1225))

# November 22th 2023 (Version 0.3.19)

* Failed lockpicking attempts now also increase skill level (issue [#1158](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1158))
* Changed Hank Möbelmann to sell rugs
* Changed Mental Health percentage to show in reverse in the stat tooltip (issue [#1176](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1176))
* Fixed the police arresting the player when the police is not chasing the player (issue [#1189](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1189))
* Fixed moldy waste never disappearing from scenes
* Fixed new moldy waste spawning everytime the game is saved/loaded
* Fixed missing power slot icons
* Fixed prosess manufacturing getting stuck at 100% (issue [#1170](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1170))
* Fixed process manufacturing not updating process when the fuel has run out when the player has been in another scene
* Fixed Martta Lapinjoki having Ville and Mirjam part of the family (issue [#1180](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1180))
* Fixed sentence count down ignoring the 100h cap (issue [#1167](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1167))
* Fixed Lönkkä Kurahaara being at three different places at the same time (issue [#1178](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1178))
* Fixed stall vendors not disappearing when the stalls are closed

## Tenement System

* Added notification when item is picked up (issue [#1183](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1183))
* Fixed dropped items vanishing randomly (issue [#1163](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1163))
* Fixed residents staying on the streets when rented (issue [#1175](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1175))
* Fixed (Clone) written after the residents' name
* Fixed that no other residents are spawned if there are several residents in the same apartment
* Fixed building system playing a sound when looking at an object that requires an item
* Fixed not being able to drop items to the player's apartment when the player doesn't have the tenement blueprint
* Fixed Shabby Facade entrance hole

## Tasks

* Fixed (again) not being able to talk to the toll bridge owner about buying the bridge (issue [#1171](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1171))
* Fixed being able to give blue duck twice (issue [#1172](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1172))
* Fixed Jomppe Kurahaara accepting seeds as returnable vegetables (issue [#1169](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1169))

## Furniture

* Fixed flower pot marked as owned (issue [#1202](https://github.com/loiste-interactive/Obenseuer-Issues/issues1202))
* Fixed tiny cage graphical/animation issues (issue [#1177](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1177))

## O-Market

* Fixed items not showing the market price (issue [#1101](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1101))

## Skeida Pharmacy

* Fixed being able to bypass keycard doors (issue [#1185](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1185))

# November 20th 2023 (Version 0.3.18)

* Increased player lockpicking skill gain
* Player can now ask Samuel about furniture crafting.
* Player can now ask Malone about chopping and selling wood.
* Sleep now gives small mental health recovery.
* Fixed being unable to start crafting on mashing tuns/fermenters/distilleries (issue [#1106](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1106))
* Fixed some doors being locked automatically, when they shouldn't (issue [#1125](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1125))
* Fixed an issue where sometimes going to prison leaves timescale to 150
* Fixed camera breaking (mostly in Kolhola) (issue [#1128](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1128))
* Fixed Mr.Bag not being fixed (issue [#1108](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1108))
* Fixed being able to transfer items without paying (issue [#1140](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1140))
* Fixed low health from preventing player from sleeping.
* Fixed green mushrooms causing lag
* Fixed player's receiving alcohol addiction cured achievement at start
* Reduced start depression target

## Tasks

* Fixed not being able to talk to the toll bridge owner about buying the bridge (issue [#1107](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1107))

## Items

* Fixed double clicking to move items not working sometimes
* Fixed the amount slider not being at the maximum value at start

## Building System

* Player apartment now starts with a sawbuck.
* Fixed item duplication exploit when placing items as furniture and taking them (issue [#1110](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1110))
* Fixed dropped items changing size when dropped to placeable furniture (issue [#1137](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1137))
* Fixed two calendars having wrong image

## Tenement System

* Changed the apartment to show if the size requirement is met or not
* Fixed apartment fine balcony textures clipping (issue [#1143](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1143))
* Fixed makeshift balcony gap at outside (issue [1141](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1141))
* Fixed residents not spawning to right positions (issue [#1142](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1142))
* Fixed resident rent ignoring tenement upgrades (issue [#1135](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1135))
* Fixed invisible obstacle in the makeshift yard (issue [#1147](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1147))

## Furniture

* Fixed sink furniture being 'owned' (issue [#1105](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1105))

## Open Sewer Tenement

* Improved outdoor environment lighting
* Fixed hardware stall being open on fridays despire sign stating otherwise (issue [#1115](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1115))
* Removed debit card accidentally left over from tests (issue [#1139](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1139))

# November 17th 2023 (Version 0.3.17)

* Increased the initial duck need amount from 0.1 to 0.5
* Reduced farming skill gain on large fields
* Reduced skill gain on field kitchen
* Changed tooltip to show market price instead of estimated value (issue [#324](https://github.com/loiste-interactive/Obenseuer-Issues/issues/324))
* Fixed player getting 10pts extra for every addiction at start
* Fixed potatoes rotting in potatosack breaking its inventory
* Fixed farming skill not affecting quality of produced goods
* Fixed hoses not excluding recipes by modifiers (issue [#1062](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1062))
* Fixed payphone not displaying yellow pages (issue [#1064](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1064))
* Fixed interest breaking player bank account (issue [#1078](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1078))
* Fixed furnaces draining gas bottles even when they're off (issue [#1088](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1088))
* Fixed slots graying out on fueled but not currently processing mashing tuns (issue [#1087](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1087))
* Fixed Osrat culling issues (issue [#1086](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1086))
* Fixed NPC heads sometimes jiggling
* Fixed not being able to see notifications while sleeping (issue [#1074](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1074))
* Fixed re-lock timers not working
* Fixed inventory not updating when changing to inventory tab from other tab (issue [#935](https://github.com/loiste-interactive/Obenseuer-Issues/issues/935))
* Fixed lockpickable doors focus moving away from the doors (issue [#1098](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1098))

## Items

* Fixed low potency shrooms missing effects
* Fixed shrooms missign eating sounds

## Recipes

* Fixed crafting sometimes starts to craft wrong recipe (issue [#982](https://github.com/loiste-interactive/Obenseuer-Issues/issues/982))

## Tasks

* Added new objective to "Who lives in the basement" task (issue [#1061](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1061))
* Added Getting a Passport task description mentioning where Eliana lives (issue [#1046](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1046))
* Added dialogue for Axel Norberg for reporting a body (issue [#1058](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1058))
* Changed to be able to tell Passmores password to the Deekula B basement door (issue [#1057](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1057))
* Changed Deekula B basement door dialogue to affect Getting a Passport task (issue [#1045](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1045))
* Fixed not being able to give turnip moonshine to Pate (issue [#1066](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1066))
* Fixed task descriptions appearing in wrong order (issue [#1037](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1037))
* Fixed Locate the gang objective getting checked off when touching the gang entrance door (issue [#1026](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1026))
* Fixed not being able to buy the passport when talking to David Lund about it a second time (issue [#1026](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1026))
* Fixed not being able to ask about the passport seller when talking to Hank Möbelmann about it a second time (issue [#1026](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1026))
* Fixed being able to ask where passmore lives from Eliana when player already knows it (issue [#1048](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1048))
* Fixed Radio Signal task activating again when finding the woman in the bed (issue [#1054](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1054))
* Fixed Radio Signal task deciding not telling about the body to the police not activating new objective (issue [#1055](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1055))
* Fixed Radio Signal task not being able to tell body's name (issue [#1056](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1056))
* Fixed Priest's Debt task activating again when doing optional task after task is complete (issue [#1050](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1050))
* Fixed Me Mash! task dialogue choices after "I could if I knew how to mash" closing dialogue window with Pentti (issue [#1069](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1069))
* Fixed Buying the Toll Bridge task issues (issue [#1085](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1085))
* Fixed being able to trigger Letter for Emilie Palmer task two times (issue [#1080](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1080))
* Fixed Tunnel B2 task not completing (issue [#1094](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1094))
* Fixed Lost And Found activating again when using payphone

## Open Sewer Tenement

* Adjusted shabby and makeshift upgrade costs
* Fixed occlusion issues caused by bushes and trees

## Interior Player Tenement

* Fixed apartment 4 not having default furniture (issue [#1029](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1029))

## Interior Tenement Kolhola

* Fixed Rauha Taisto being called Fenella Hunt
* Fixed hostel keeper being naked (issue [#1015](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1015))

## Interior Tenement B

* Fixed dead Mike not having items

# November 15th 2023 (Version 0.3.16) - Playtesting branch

* Reduced addiction need baserate a little, reduced addiction reduction rate a little.
* Start package now contains can opener, matches and band-aids
* Changed debit card quest objective to trigger instantly when you send mail.
* Changed amount sliders default value to max value (issue [#983](https://github.com/loiste-interactive/Obenseuer-Issues/issues/983))
* Fixed player not always receiving mail.
* Fixed saveload reseting the amount of incoming mail
* Fixed bleeding not killing player (issue [#887](https://github.com/loiste-interactive/Obenseuer-Issues/issues/887))
* Fixed beds not being marked as safe when they infact are safe
* Fixed unsafe beds not actually being unsafe
* Fixed safety satus not saving
* Fixed tools not breaking (issue [#925](https://github.com/loiste-interactive/Obenseuer-Issues/issues/925))
* Fixed relock timers not saving (issue [#916](https://github.com/loiste-interactive/Obenseuer-Issues/issues/916))
* Fixed mashing/fermenting/distilleries and alike not giving failed result upon failure (issue [#965](https://github.com/loiste-interactive/Obenseuer-Issues/issues/965))
* Fixed mashing/fermenting/distilleries and alike process getting stuck if save/loaded power being off (issue [#973](https://github.com/loiste-interactive/Obenseuer-Issues/issues/973))
* Fixed dropping single items/half stacks destroying leftover stack in inventory (issue [#864](https://github.com/loiste-interactive/Obenseuer-Issues/issues/864))
* Fixed police breaking a lot of stuff when chasing player and player moves to another map (issue [#950](https://github.com/loiste-interactive/Obenseuer-Issues/issues/950))
* Fixed backpack allowing remote acces to shops (issue [#940](https://github.com/loiste-interactive/Obenseuer-Issues/issues/940))
* Fixed mold and other residual items duplicating (issue [#951](https://github.com/loiste-interactive/Obenseuer-Issues/issues/951))
* Fixed stealing money not counting as a crime (issue [#970](https://github.com/loiste-interactive/Obenseuer-Issues/issues/970))
* Fixed furniture crafring not using item charges (issue [#957](https://github.com/loiste-interactive/Obenseuer-Issues/issues/957))
* Fixed liquid container swap not working properly (issue [#966](https://github.com/loiste-interactive/Obenseuer-Issues/issues/966))
* Fixed rightclick dragging overriding (thus destroying) items.
* Fixed rereading notes opening wrong note (issue [#901](https://github.com/loiste-interactive/Obenseuer-Issues/issues/901))
* Fixed being able to avoid police by jumping just when police tries to talk with you
* Fixed police not arresting player if player stands still after selecting "(Run)"
* Fixed jittering police (issue [#833](https://github.com/loiste-interactive/Obenseuer-Issues/issues/833))
* Fixed multiple issues related to jail (issue [#1004](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1004))

## Open Sewer Tenement

* Hardware stall now sells scrap metal
* Fixed one wall section in Deekula missing collisions
* Fixed outhouses not working
* Fixed vending machine in the alley not selling shrooms (issue [#885](https://github.com/loiste-interactive/Obenseuer-Issues/issues/885))
* Fixed dumpsters and trashcans not respawning stuff

## Interior Tenement B

* Fixed tunnel flood door closing on load (issue [#855](https://github.com/loiste-interactive/Obenseuer-Issues/issues/855))

## Interior Tebement Kolhola

* Fixed hostel beds not being safe

## Tenement System

* Makeshift apartment now gives 60% safety
* Bare apartment now gives 30% safety
* Fixed light position in shit tier electricity
* Fixed RM rent being paid in OC (issue [#942](https://github.com/loiste-interactive/Obenseuer-Issues/issues/942))
* Fixed shabby yard collisions
* Fixed containers spawning items to world in tenement upgrades (issue [#878](https://github.com/loiste-interactive/Obenseuer-Issues/issues/878))
* Fixed residents not being evicted properly (issue [#998](https://github.com/loiste-interactive/Obenseuer-Issues/issues/998))
* Fixed not being able to use player apartment kitchen sinks

## Furniture

* Changed sawbuck with chainsaw price
* Added 1/4 pallet
* Fixed furniture duplicaiton (issue [#987](https://github.com/loiste-interactive/Obenseuer-Issues/issues/987))

## Items

* Can opener now has durability
* Fixed coffee not returning cup

## Recipes

* Steel/Brass/Silver/Gold items (vases and alike) can now be recycled into bars
* Sheet metal can now be scrapped into scrap metal

## Tasks

* Fixed not being able to tell to Passmore about the bank route (issue [#926](https://github.com/loiste-interactive/Obenseuer-Issues/issues/926))
* Fixed remove obstacle objective not triggering (issue [#926](https://github.com/loiste-interactive/Obenseuer-Issues/issues/926))
* Fixed Survive in Obenseuer not being completed after completing both objectives (issue [#997](https://github.com/loiste-interactive/Obenseuer-Issues/issues/997))
* Fixed objectives changing order in the objectives list (issue [#997](https://github.com/loiste-interactive/Obenseuer-Issues/issues/997))

# November 8th 2023 (Version 0.3.15) - Playtesting branch

* Added console command to destroy all items
* Added edit objective console command
* Adjusted rest rate
* Increased spawn changes of tarp
* Beds now tell you if they're unsafe to sleep
* Removed multiplicating items
* Opening console now temporarily disables achievements
* Tenement upgrade should now wait until player has woken up to actually finish (issue [#774](https://github.com/loiste-interactive/Obenseuer-Issues/issues/774))
* Changed stat arrows colors and directions (issue [#794](https://github.com/loiste-interactive/Obenseuer-Issues/issues/794))
* Changed status descriptions (issue [#818](https://github.com/loiste-interactive/Obenseuer-Issues/issues/818))
* Reduced axe and sledgehammer durability: (issue [#853](https://github.com/loiste-interactive/Obenseuer-Issues/issues/853))
* Reduced sledgehammer swing range (issue [#850](https://github.com/loiste-interactive/Obenseuer-Issues/issues/850))
* Fixed moving stolen items around in player inventory generating more crime: (issue [#767](https://github.com/loiste-interactive/Obenseuer-Issues/issues/767))
* Fixed beer crates spawning items into world (issue [#729](https://github.com/loiste-interactive/Obenseuer-Issues/issues/729))
* Fixed water footstep sound sometimes staying on after leaving water (issue [#447](https://github.com/loiste-interactive/Obenseuer-Issues/issues/447))
* Fixed dropping items from equipment slots getting stuck on HUD (issue [#738](https://github.com/loiste-interactive/Obenseuer-Issues/issues/738))
* Fixed growing turnips being uneconomical (issue [#782](https://github.com/loiste-interactive/Obenseuer-Issues/issues/782))
* Fixed growing sugar beets being uneconomical
* Fixed grains not spoiling (issue [#780](https://github.com/loiste-interactive/Obenseuer-Issues/issues/780))
* Fixed grains not fitting in growing box
* Fixed mashing, fermenting and distilleries not working (issue [#784](https://github.com/loiste-interactive/Obenseuer-Issues/issues/784))
* Fixed some recipes loading data of other recipes (also fixes potential spawning issues)
* Fixed some keys and task items loading data of other keys and taskitems (also fixes potential spawning issues)
* Fixed mashing machines and alike giving infinite mash/product
* Fixed cleaning your tenement opening inventory first for it to work
* Fixed furniture shop not updating money amount (issue [#803](https://github.com/loiste-interactive/Obenseuer-Issues/issues/803))
* Fixed overfilled manufacturing tools dropping stuff at player location (issue [#802](https://github.com/loiste-interactive/Obenseuer-Issues/issues/802))
* Fixed Möbelmann telling that passmore resides in tenement A
* Fixed finished tenement upgrades sometimes breaking stats, sleep and time in general
* Fixed some typos in dialog and tasks (issue [#790](https://github.com/loiste-interactive/Obenseuer-Issues/issues/790))
* Fixed being able to call bank and order a new debit card without the quest
* Fixed virtual keyboard opening in "press any key" menu (issue [#731](https://github.com/loiste-interactive/Obenseuer-Issues/issues/731))
* Fixed grey slots on Eija's grill.

## Tasks

* Fixed Start editing the apartment task not working (issue [#793](https://github.com/loiste-interactive/Obenseuer-Issues/issues/793))
* Fixed not being able tell Pentti you will make mash yourself (issue [#789](https://github.com/loiste-interactive/Obenseuer-Issues/issues/789))
* Fixed Max Masher's model is not aligned with collision when kicking in his door (issue [#825](https://github.com/loiste-interactive/Obenseuer-Issues/issues/825))
* Fixed visiting Speakeasy optional objective not being checked off (issue [#796](https://github.com/loiste-interactive/Obenseuer-Issues/issues/796))
* Fixed Ville's quest not being able to complete  (issue [#705](https://github.com/loiste-interactive/Obenseuer-Issues/issues/785))
* Fixed Priest Debt task getting reactivated (issue [#847](https://github.com/loiste-interactive/Obenseuer-Issues/issues/847))
* Fixed debit card quest never sending the forms

## Tenement System

* Changed tenants standards (issue [#815](https://github.com/loiste-interactive/Obenseuer-Issues/issues/815))
* Fixed tenants RM income
* Fixed collisions of courtyard and sauna upgrades
* Fixed heating icon showing wrong status when renting (issue [#814](https://github.com/loiste-interactive/Obenseuer-Issues/issues/814))
* Fixed sauna collisions
* Fixed rented NPCs reappearing in their original location after a reload (issue [#842](https://github.com/loiste-interactive/Obenseuer-Issues/issues/842))

## Furniture

* Fixed chest freezer giving random junk on first placement
* Fixed storages emptying themselves and spawning random junk afterwards

## Items

* Made rye breads more durable
* Fixed multigrain breads not spoiling (issue [#738](https://github.com/loiste-interactive/Obenseuer-Issues/issues/738))
* Fixed loose cigarettes not being stackable (issue [#837](https://github.com/loiste-interactive/Obenseuer-Issues/issues/837))
* Fixed perishable food items not perishing

## Open Sewer Intro

* Fixed intro

## Open Sewer Tenement

* Fixed oclusion culling
* Fixed Kurahaara stall collisions (issue [#807](https://github.com/loiste-interactive/Obenseuer-Issues/issues/807))
* Fixed being able to lockpick a door to a house not yet in game (issue [#808](https://github.com/loiste-interactive/Obenseuer-Issues/issues/808))
* Fixed hardware stall not being open on sundays (issue [#809](https://github.com/loiste-interactive/Obenseuer-Issues/issues/809))

## Interior Tenement Gatehouse

* Fixed prison lockers spawning random loot (and removing player stuff)

## Interior Tenement Greenhouse

* Fixed not being able to uproot plants in barrel planter (issue [#844](https://github.com/loiste-interactive/Obenseuer-Issues/issues/844))

## Interior Tenement Kolhola

* Added photocopier to hostel
* Fixed missing collisions on cabinets
* Fixed cabinet slots and not spawning loot
* Made pods unlockpickable (theres nothing iside anyway) (issue [#828](https://github.com/loiste-interactive/Obenseuer-Issues/issues/828))
* Fixed Meri Haka

## Interior Tenement O Market

* Fixed prepared foods having wrong owner (issue [#781](https://github.com/loiste-interactive/Obenseuer-Issues/issues/781))

## Interior Tenement Deekula A

* Fixed Jonasson's furniture UI being unlit (issue [#802](https://github.com/loiste-interactive/Obenseuer-Issues/issues/802))

# November 3th 2023 (Version 0.3.14) - Playtesting branch

* Added loading screen tip about sauna
* Added arrows to indicate stat changes
* Added expectation level what modifies depressiveness of things
* General Store now rarely sells fish eggs
* Reduced lag caused by rain
* Reduced base hunger and thirst gain
* Added maximum value for current duck need
* Added descriptions to stats tooltips (issue [#708](https://github.com/loiste-interactive/Obenseuer-Issues/issues/708))
* Added the name of the stat to be displayed when the stat is visible first time (issue [#708](https://github.com/loiste-interactive/Obenseuer-Issues/issues/708))
* Fixed VSync not saving (issue [#702](https://github.com/loiste-interactive/Obenseuer-Issues/issues/702))
* Fixed windowed mode (issue [#706](https://github.com/loiste-interactive/Obenseuer-Issues/issues/706))
* Fixed weather not being saved correctly (issue [#701](https://github.com/loiste-interactive/Obenseuer-Issues/issues/701))
* Fixed item spawners not working correctly (issue [#717](https://github.com/loiste-interactive/Obenseuer-Issues/issues/717))
* Fixed elevator positions not saving (issue [#703](https://github.com/loiste-interactive/Obenseuer-Issues/issues/703))
* Fixed claw trap state not saving properly (issue [#695](https://github.com/loiste-interactive/Obenseuer-Issues/issues/695))
* Fixed adding too much money at once crashing or freezing the game (issue [#734](https://github.com/loiste-interactive/Obenseuer-Issues/issues/734))
* Fixed vines not producing fruits
* Fixed some items saving their state globally and thus affecting other items (issue [#727](https://github.com/loiste-interactive/Obenseuer-Issues/issues/727))
* Fixed breakable doorways scrap colliding with player (issue [#736](https://github.com/loiste-interactive/Obenseuer-Issues/issues/736))
* Fixed some items listed as perishable when they shouldn't be (issue [#733](https://github.com/loiste-interactive/Obenseuer-Issues/issues/733))
* Fixed switching between backpack/recycler closing bottle recycler menu (issue [#724](https://github.com/loiste-interactive/Obenseuer-Issues/issues/724))
* Fixed flashlight sometimes draining battery when turned off after reloading batteries (issue [#732](https://github.com/loiste-interactive/Obenseuer-Issues/issues/732))
* Fixed buying liquids sometimes giving empty bottles (issue [#693](https://github.com/loiste-interactive/Obenseuer-Issues/issues/693))
* Fixed being able to sell and buy items without actually getting/losing the item.

## Furniture

* Added meat grinder

## Items

* Fixed item description typos (issue [#755](https://github.com/loiste-interactive/Obenseuer-Issues/issues/755))
  
## Tenement System

* Makeshift upgrades are now cheaper
* Fixed the player apartment fine extension upgrades not updating connection prefabs correctly
* Fixed missing collisions in tenement yard lvl4 (issue [#749](https://github.com/loiste-interactive/Obenseuer-Issues/issues/749))
* Fixed tenement yard lvl4 garbage shed door
* Fixed missing tenement facade lvl2-4 floor 1 windows
* Fixed multiple bugs with facades (issue [#748](https://github.com/loiste-interactive/Obenseuer-Issues/issues/748))
* Fixed guitar & cash box placement (issue [#747](https://github.com/loiste-interactive/Obenseuer-Issues/issues/747))

## Furniture

* Fixed some furniture blueprints missing icon

## Open Sewer Tenement

* Reduced fog intensity
* Tatyana now mentions about hazards of sleeping on streets and points you to the hostel
* Fixed sprinting past Tatyana allowing to avoid conversation (issue [#709](https://github.com/loiste-interactive/Obenseuer-Issues/issues/709))
* Fixed backdoor of the yellow shack (issue [#737](https://github.com/loiste-interactive/Obenseuer-Issues/issues/737))
* Fixed Deekula A second floor door (issue [#752](https://github.com/loiste-interactive/Obenseuer-Issues/issues/752))

## Interior Player Tenement

* Added Malone to mention about locked Deekula B
* Fixed start furnishing task
* Removed the sound of the non-existent rat

## Interior Tenement Greenhouse

* Fixed Jomppe taking held items (issue [#713](https://github.com/loiste-interactive/Obenseuer-Issues/issues/713))

## Interior Tenement O-Market

* Fixed not being able to put some items back to shelf (issue [#721](https://github.com/loiste-interactive/Obenseuer-Issues/issues/721))

## Interior Tenement B

* Fixed lights being off from start
* Fixed main door plywood not moving with the door

## Interior Tenement Kolhola

* Fixed puddles not rendering correctly
* Fixed Kirka Kääbus renting not working (issue [#723](https://github.com/loiste-interactive/Obenseuer-Issues/issues/723))

## Interior Tenement Deekula A

* Fixed lighting near Dr. Pena's

## Interior Tenement Deekula B

* Fixed not being able to tell the correct password at the basement door
* Fixed OSRAT instructions typo (issue [#754](https://github.com/loiste-interactive/Obenseuer-Issues/issues/754))

## Interior Tenement Deekula C

* Fixed storage C8 door not accepting keys (issue [#707](https://github.com/loiste-interactive/Obenseuer-Issues/issues/707))

# October 31th 2023 (Version 0.3.13) - hotfix

* Fixed duck addiction being present from start

## Tenement System

* Fixed being unable to remove mushroom stain (issue [#699](https://github.com/loiste-interactive/Obenseuer-Issues/issues/699))

# October 31th 2023 (Version 0.3.12)

* Stealing and getting caught doesn't generate new notification for each item stack stolen now
* Alcoholism now reduce hunger rate
* Being on mushrooms now give boost to crafting results
* Improved performance in Deekulas, Kolhola, Tenement B, Player Tenement and Gatehouse
* Changed SMV progression food damage/health gain to scale better.
* Changed the game to not run in the background (issue [#205](https://github.com/loiste-interactive/Obenseuer-Issues/issues/205))
* Fixed some materials missing emission
* Fixed some materials not rendering fog correctly
* Fixed resolution and refresh rate not saving
* Fixed some start settings having wrong values (issue [#579](https://github.com/loiste-interactive/Obenseuer-Issues/issues/579))
* Fixed not setting gender value correctly (issue [#642](https://github.com/loiste-interactive/Obenseuer-Issues/issues/642))
* Fixed '0-crimes' when stealing low value items (issue [#649](https://github.com/loiste-interactive/Obenseuer-Issues/issues/649))
* Fixed Pharmacy not restocking daily (issue [#650](https://github.com/loiste-interactive/Obenseuer-Issues/issues/650))
* Fixed Debit Card achievement being unobtainable
* Fixed prison not working (issue [#639](https://github.com/loiste-interactive/Obenseuer-Issues/issues/639))
* Fixed talking with NPCs softlocking the game
* Fixed load menu not showing the current character first if character name has '-'letter (issue [#648](https://github.com/loiste-interactive/Obenseuer-Issues/issues/648))
* Fixed weather not saving (issue [#666](https://github.com/loiste-interactive/Obenseuer-Issues/issues/666))
* Fixed fire icon on stoves showing as on when loading if the stove is turned off and has fuel.
* Fixed saving of items and machines inside tenement upgrades (issue [#683](https://github.com/loiste-interactive/Obenseuer-Issues/issues/683))
* Fixed crafting result texts showing color code (issue [#677](https://github.com/loiste-interactive/Obenseuer-Issues/issues/677))
* Fixed antialiasing setting (issue [#4](https://github.com/loiste-interactive/Obenseuer-Issues/issues/4))
* Fixed tarp door saving
* Rediced addiction gain (issue [#663](https://github.com/loiste-interactive/Obenseuer-Issues/issues/663))
* Reduced start addictions

# Items

* Added shroom water
* Changed Osmo-Olut stats

# Tasks

* Fixed missing title on debit card quest objective
* Fixed returning bottles not marking objective as complete (issue [#654](https://github.com/loiste-interactive/Obenseuer-Issues/issues/654))

## Open Sewer Tenement

* Optimized lights
* Changed Kurahaara stall to sell seeds
* Fixed the toll bridge task
* Fixed multiple locations where player can get stuck
* Fixed invisible box near Kurahaara farm
* Fixed "black boxes"
* Fixed Jesper Kumpula animation (issue [#632](https://github.com/loiste-interactive/Obenseuer-Issues/issues/632))
* Fixed Jesper's Soup turning into mold
* Fixed fence missing collision
* Fixed police not policing
* Fixed collision issue on main street
* Fixed lights flickering
* Fixed route to out of bounds
* Fixed the player tenement occlusions and being inaccessible (issue [#662](https://github.com/loiste-interactive/Obenseuer-Issues/issues/662))
* Fixed collision issues near player tenement
* Fixed having to crouch to enter shroom outhouse (issue [#675](https://github.com/loiste-interactive/Obenseuer-Issues/issues/675))
* Fixed tent woman's head being backwards (issue [#673](https://github.com/loiste-interactive/Obenseuer-Issues/issues/673))
* Player yard toilet is now usable

## Interior Start

* Fixed some typos in dialogue

## Interior O-Market

* Fixed the bottle recycling machine not saving money value (issue [#661](https://github.com/loiste-interactive/Obenseuer-Issues/issues/661))
* Fixed not being able to put candy backs back into the self (issue [#689](https://github.com/loiste-interactive/Obenseuer-Issues/issues/689))

## Interior Tenement Kolhola

* Fixed elevator breaking on save/scene load (issue [#664](https://github.com/loiste-interactive/Obenseuer-Issues/issues/664))
* Fixed main door not having sounds
* Fixed A9 balcony door
* Fixed typo on pod 23
* Fixed pod rent status not loading properly (issue [#692](https://github.com/loiste-interactive/Obenseuer-Issues/issues/692))

## Interior Tenement Deekula A

* Added dialogue where you can ask Samuel what you should renovate first and where to get the materials
* Changed doctor's number ticket being valid until you leave the room (issue [#251](https://github.com/loiste-interactive/Obenseuer-Issues/issues/251))
* Fixed doctor having blank page at physical health measurement (issue [#614](https://github.com/loiste-interactive/Obenseuer-Issues/issues/614))
* Fixed not opening the task panel before talking to Jonasson breaking sometimes the dialogue (issue [#651](https://github.com/loiste-interactive/Obenseuer-Issues/issues/651))

## Interior Tenement Deekula B

* Fixed several issues in the Radio signal task (issue [#90](https://github.com/loiste-interactive/Obenseuer-Issues/issues/90))

## Interior Tenement Deekula C

* Fixed David Lund dialogue (issue [#645](https://github.com/loiste-interactive/Obenseuer-Issues/issues/645))
* Fixed not being able to pickup blueprints (issue [#652](https://github.com/loiste-interactive/Obenseuer-Issues/issues/652))

# October 26th 2023 (Version 0.3.11)

* Added Interior Tenement Deekula C
* Added Interior Tenement Kolhola
* Added task given by ATM
* Added backpack model
* Implemented tenement achievements
* Updated the backpack icon to match the new model
* Increased start addiction values
* General trader now sells more goods
* Increased likelyhood of hardware stall having nails and gas bottles
* Reduced lockpicking skill gain
* Reduced backpack storage capacity (issue [#607](https://github.com/loiste-interactive/Obenseuer-Issues/issues/607))
* Some lockpicked doors lock after time with increased difficulty
* Fixed crafting station sounds playing after saveload, even when the device itself is off
* Fixed mail skipping days
* Fixed mapchange doors not unlocking after successful lockpick (issue [#596](https://github.com/loiste-interactive/Obenseuer-Issues/issues/596))
* Fixed stalls and shops with opening times opening and closing erratically (issue [#606](https://github.com/loiste-interactive/Obenseuer-Issues/issues/606))
* Fixed ingredients with charges consuming item instead of charge (issue [#617](https://github.com/loiste-interactive/Obenseuer-Issues/issues/617))
* Fixed moving items between backpack and the inventory considered as buying and selling when trade is open (issue [#615](https://github.com/loiste-interactive/Obenseuer-Issues/issues/615))
* Fixed dialogue variables not saving globally
* Fixed some doors 'vanishing' when opening (issue [#594](https://github.com/loiste-interactive/Obenseuer-Issues/issues/594))
* Fixed drills working effect on save loads
* Fixed loading screen typo

## Open Sewer Tenement

* Added Tatyana to give bottle recycling and pea soup quest at the beginning
* Added Redemption Militia to give pea soup every day
* Improved occlusion ( = better fps)
* Some traders now have more stock
* Changed Deekula B to be closed at start
* Changed to use list panel instead of dialogue (issue [#598](https://github.com/loiste-interactive/Obenseuer-Issues/issues/598))
* Fixed clouds being too fast (issue [#600](https://github.com/loiste-interactive/Obenseuer-Issues/issues/600))
* Fixed One stop shop not opening
* Fixed Kurahaara stall not opening
* Fixed getting stuck on player canal toilet
* Fixed not being able to get inside speakeasy when malone gives the objektive

## Interior Tenement LotShack3

* Fixed toilet

## Interior Tenement Redemption Militia

* Added dialogue
* Fixed Npcs appearance

## Interior Tenement Caravan

* Fixed player spawning inside the wall

## Interior Tenement O-Market

* O-Market now sells matches
* Fixed conveyor belt breaking upon save loads (issue [#529](https://github.com/loiste-interactive/Obenseuer-Issues/issues/529))

## Interior Tenement Deekula A

* Removed forgotten test door
* Fixed Samuel being overly bright

## Items

* Adjusted backpack price
* Disinfectant now has multiple uses
* Cleaning spray now has multiple uses
* Fixed item missing datavalues (issue [#605](https://github.com/loiste-interactive/Obenseuer-Issues/issues/605))
* Fixed coin items collisions
* Fixed wrong effects on shroomed foods (issue [#616](https://github.com/loiste-interactive/Obenseuer-Issues/issues/616))

## Furniture

* Fixed flags not being in addressable lists
* Fixed plank furniture not being in addresable lists
* Changed the large cuppoard slots amount (issue [#604](https://github.com/loiste-interactive/Obenseuer-Issues/issues/604))

## Tenement System

* Cleaning biohazard bags doesn't consume full bottle of disinfectant
* Cleaning graffiti and dirt doesn't consume full bottle of cleaning spray
* Fixed small apartments missing walls
* Reduced time required for early bathroom upgrades
* Moved chest blueprint to more easily accessable location

## Recipes

* Increased lockpic recipes fail change

# October 19th 2023 (Version 0.3.10)

* Added Open Sewer Tenement
* Added Interior Tenement Bus
* Added Interior Tenement Caravan
* Added Interior Tenement House3
* Added Interior Tenement LotShack1
* Added Interior Tenement LotShack2
* Added Interior Tenement LotShack3
* Added Interior Tenement Player Canal Saunas
* Added Interior Tenement Redemption Militia
* Added opening animations (more than just the latch) for map change doors.
* Added door closing sound when player enters the map via door.
* Added prison escape/released achievements
* Added pickaxe animations (issue [#13](https://github.com/loiste-interactive/Obenseuer-Issues/issues/13))
* Mr. Bag's goods are now refigerated
* Changed pickaxe model and textures
* Kitchen sink now allows concurrent crafting
* Fixed failed sort removing all items from inventory (issue [#555](https://github.com/loiste-interactive/Obenseuer-Issues/issues/555))
* Fixed crimes repeating by moving stolen goods in inventory (issue [#556](https://github.com/loiste-interactive/Obenseuer-Issues/issues/556))
* Fixed eating stuff straight from owned containers not counting as a crime (issue [#545](https://github.com/loiste-interactive/Obenseuer-Issues/issues/545))
* Fixed getting prespiction medicine being a crime
* Fixed pause menu brightness slider (issue [#551](https://github.com/loiste-interactive/Obenseuer-Issues/issues/551))
* Fixed auto farming planting new plants after load (issue [#574](https://github.com/loiste-interactive/Obenseuer-Issues/issues/574))
* Fixed vine plants uproot collision
* Fixed vine plants spawning seed items to ground if amount is 0 (issue [#569](https://github.com/loiste-interactive/Obenseuer-Issues/issues/569))
* Fixed saving causing issues in start level (issue [#580](https://github.com/loiste-interactive/Obenseuer-Issues/issues/580))
* Fixed player camera start direction not working on map change
* Fixed crafting liquids not giving correct amounts

## Tasks
* Added a task for Ville Sköldganster

## Tenement System

* Cleaning mushroom growth and graffitis now require chemicals
* Fixed original furnitures giving duplicated child furnitures
* Fixed original furnitures respawning (issue [#558](https://github.com/loiste-interactive/Obenseuer-Issues/issues/558))
* Adjusted radio sounds radius and volume (issue [#583](https://github.com/loiste-interactive/Obenseuer-Issues/issues/583))

## Interior Tenement Gatehouse

* Changed cell lockers to clear items only when you have left the prison (issue [#584](https://github.com/loiste-interactive/Obenseuer-Issues/issues/584))
* Changed it clearer where the confiscate items are (issue [#584](https://github.com/loiste-interactive/Obenseuer-Issues/issues/584))
* Fixed orange mushrooms grow states not saving when picking them up
* Fixed rat states not saving when picking them up
* Fixed the cave entrypoint being on the wrong side when coming from Tenement B
* Fixed standing up in tight place causing clipping into ceiling (issue [#573](https://github.com/loiste-interactive/Obenseuer-Issues/issues/573))
* Fixed prison locks (issue [#562](https://github.com/loiste-interactive/Obenseuer-Issues/issues/562))
* Fixed guard throwing player back to prison (issue [#560](https://github.com/loiste-interactive/Obenseuer-Issues/issues/560))

## Interior TenementDeekula B

* Harassing Jim now adds crime.

## Interior Player Tenement

* Fixed freezer texture issue (issue [#550](https://github.com/loiste-interactive/Obenseuer-Issues/issues/550))

## Interior O-Market

* Fixed being unable to buy meatballs, fixed being unable to put yeast back in to the refigerator (issue [#587](https://github.com/loiste-interactive/Obenseuer-Issues/issues/549))

## Interior Pharmacy

* Harassing Mona now gives crime

## Interior Tenement Deekula Mine Interance

* Fixed key crate state not saving (issue [#549](https://github.com/loiste-interactive/Obenseuer-Issues/issues/587))

## Interior Tenement Speakeasy

* Fixed Simppa being called Jomppe in dialog (issue [#571](https://github.com/loiste-interactive/Obenseuer-Issues/issues/571))

## Furniture

* Added decorative flags
* Added chest freezer
* Added refigerator
* Added round cafeteria table
* Added gray fancy wooden chair
* Fixed wall flag display mode (issue [#564](https://github.com/loiste-interactive/Obenseuer-Issues/issues/564))
* Fixed missing furniture asset paths (issue [#557](https://github.com/loiste-interactive/Obenseuer-Issues/issues/557))
* Fixed pricing on plastic barrels (issue [#588](https://github.com/loiste-interactive/Obenseuer-Issues/issues/588))

## Items

* Added backpack
* Added mushroom extract
* Added poisoned wine
* Added pierogi
* Added a roll of tarp
* Fixed winstead cigarettes giving alcohol addiction instead of shrooma addiction
* Fixed distilled alcohols not giving back bottle
* Fixed bread stats
* Fixed stacked pills consumption (issue [#590](https://github.com/loiste-interactive/Obenseuer-Issues/issues/590))
* Fixed not being able to pick up syringes

## Recipes

* Added pure green mushrooms recipe
* Added mushroom extract
* Added poisoned wine
* Added pierogi recipe
* Added red color to indicate missing ingredients (issue [#575](https://github.com/loiste-interactive/Obenseuer-Issues/issues/575))
* Added smashed potatoes recipe (issue [#591](https://github.com/loiste-interactive/Obenseuer-Issues/issues/591))
* Fixed milk coffee recipe
* Changed pies to use milk cartons
* Changed recipes to accept dirty water
* Fixed recipes with liquids not working (issue [#575](https://github.com/loiste-interactive/Obenseuer-Issues/issues/575))
* Fixed learned recipes not working sometimes (issue [#575](https://github.com/loiste-interactive/Obenseuer-Issues/issues/575))
* Fixed crafting liquids overriding the liquid amount in containers (issue [#226](https://github.com/loiste-interactive/Obenseuer-Issues/issues/226))
* Fixed crafting button sometimes being grayed out after crafting (issue [#457](https://github.com/loiste-interactive/Obenseuer-Issues/issues/457))
* Fixed crafting not removing items that has empty ammo data
* Fixed items with empty ammo data being counted as one item
* Recipes are now visible in the recipe list even if required container or water is missing

# September 28th 2023 (Version 0.3.09)

* Added Interior Tenement Gatehouse
* Implemented more achievements
* Added manufacturing UI icons (issue [#7](https://github.com/loiste-interactive/Obenseuer-Issues/issues/7))
* Boosted sauna depression reduction
* Showers now cool overheat
* Optimized lighting
* Adjusted farming skill gain
* Adjusted lockpicking skill gain
* Using toilet no-longer autosaves
* Player no longer produces 0-quality items
* Halved addiction reduction rate (again)
* Compost and metal furnaces can now take mixed input
* Planting from packaged seeds now have almost 100% success rate regardless of skill.
* Added brightness slider (issue [#278](https://github.com/loiste-interactive/Obenseuer-Issues/issues/278))
* Changed flashlight movement (issue [#519](https://github.com/loiste-interactive/Obenseuer-Issues/issues/519))
* Changed uproot to the bottom of the plant (issue [#521](https://github.com/loiste-interactive/Obenseuer-Issues/issues/521))
* Fixed fog height not working in build (issue [#72](https://github.com/loiste-interactive/Obenseuer-Issues/issues/72))
* Fixed glowing things not working in some maps
* Fixed ambient color not always working in some maps (issue [#510](https://github.com/loiste-interactive/Obenseuer-Issues/issues/510))
* Fixed alcohol need turning to negative when alcohol addiction is 0 (issue [#515](https://github.com/loiste-interactive/Obenseuer-Issues/issues/515))
* Fixed being able to put any item to hand slots (issue [#511](https://github.com/loiste-interactive/Obenseuer-Issues/issues/511))
* Fixed super flashlight clipping through walls (issue [#530](https://github.com/loiste-interactive/Obenseuer-Issues/issues/530))
* Fixed money exchange income
* Fixed storage visible items spoiling corrupting the storage (issue [#517](https://github.com/loiste-interactive/Obenseuer-Issues/issues/517))
* Fixed brick furnace save issues (issue [#531](https://github.com/loiste-interactive/Obenseuer-Issues/issues/531))
* Fixed mashing ignoring multiples of certain items (issue [#533](https://github.com/loiste-interactive/Obenseuer-Issues/issues/533))
* Fixed machines not outputting more than 1 type of liquid (issue [#252](https://github.com/loiste-interactive/Obenseuer-Issues/issues/252))
* Fixed wheat not giving harvest (issue [#541](https://github.com/loiste-interactive/Obenseuer-Issues/issues/541))
* Fixed being able to clip trhough walls by doing jump-uncrouch (issue [#85](https://github.com/loiste-interactive/Obenseuer-Issues/issues/85))

## Items

* Added effect to evil bear bag.
* Added eggs
* Added plywood
* Added bag of mold
* Added plate of mold
* Added french fries
* Added frozen french fries
* Added tablesalt
* Rye and wheat are now stackable
* Fixed player burning all cigarettes from a pack at once
* Fixed Carl Fatler chocolate (issue [#537](https://github.com/loiste-interactive/Obenseuer-Issues/issues/537))
* Fish eggs are now edible
* Fixed leather and cloth scraps being unpickupable

## Recipes

* Added collectable recipes for meals
* Added plywood recipe
* Added french fries recipe
* Added fish 'n chips recipe
* Added steak with fries
* Boiling vegetables don't need water modifer anymore
* Fixed failed bowl-meals not returning bowl (issue [#548](https://github.com/loiste-interactive/Obenseuer-Issues/issues/548))

## Tasks

* Jomppe Kurahaara now mentions about greenhouse stove and about the effect of temperature on plants
* Fixed not being able to give back a blue duck to Mr. Duck (issue [#520](https://github.com/loiste-interactive/Obenseuer-Issues/issues/520))
* Fixed Getting Started not counting completed renovations (issue [#526](https://github.com/loiste-interactive/Obenseuer-Issues/issues/526))
* Fixed final payment objectives being checked off after load (issue [#524](https://github.com/loiste-interactive/Obenseuer-Issues/issues/524))

## Furniture

* Added coat racks
* Added wall lamp
* Added wall flags
* Added vitrine
* Added nightstand
* Added gaming chair
* Added tuffet
* Added simple plank furniture set
* Fixed rat cages being off-centered (issue [#479](https://github.com/loiste-interactive/Obenseuer-Issues/issues/479))

## Tenement System 

* Added stairs to the swimmign pools
* Added apartment size texts
* Added a tooltip to explain the daily income
* Fixed redident RM income showing OC amount
* Fixed Aleksi Kivi having wrong prefab when spawning to rented apartment
* Fixed upgrade buttons not updating correctly
* Fixed npcs not disappearing after rent
* Fixed storages with items being duplicated (issue [#513](https://github.com/loiste-interactive/Obenseuer-Issues/issues/513))
* Fixed storages not showing items first time when re-placed (issue [#469](https://github.com/loiste-interactive/Obenseuer-Issues/issues/469))
* Fixed some machines showing containing items when there are none (issue [#465](https://github.com/loiste-interactive/Obenseuer-Issues/issues/465))
* Fixed collectible items disappearing (issue [#514](https://github.com/loiste-interactive/Obenseuer-Issues/issues/514))


## Interior Tenement O-market

* O-market now sells eggs
* O-Market now sells meatballs
* O-Market now sells mashed potatoes
* O-Market now sells salt
* O-Market now sells hops
* Fixed cheese not restocking
* Fixed not being able to put cheese in the cheese refigerator

## Interior Tenement Pharmacy

* Adjusted restocking

## Interior Tenement B

* Fixed crouching in the corner near the Passmore doors causing the scene to getting darker (issue [#516](https://github.com/loiste-interactive/Obenseuer-Issues/issues/516))
* Fixed various elements saving states (issue [#523](https://github.com/loiste-interactive/Obenseuer-Issues/issues/523))

## Interior Player Tenement

* Added some starting blueprints
* Fixed apartments not being marked examined (issue [#508](https://github.com/loiste-interactive/Obenseuer-Issues/issues/508))

# August 28th 2023 (Version 0.3.08)

* Added Interior Tenement B
* Added sounds to moonshine distillery
* Added modifier icons to manufacturing tools
* Added efficiency icon & tooltip to manufacturing tools
* Added loading screen tips about machine and item quality
* Pentti now sells canisters at a discount
* Halved addiction reduction rate
* Fixed Duck achievement triggering when loading saves (issue [#489](https://github.com/loiste-interactive/Obenseuer-Issues/issues/489))
* Fixed sorting occasionally dropping a ton of empty items
* Fixed RM not saving (issue [#494](https://github.com/loiste-interactive/Obenseuer-Issues/issues/494))
* Fixed process crafting (mashing) time being multipiled by amount you're making
* Fixed mashing ignoring player skill
* Fixed liquid filling containers to full even if there is less than that amount to fill (issue [#474](https://github.com/loiste-interactive/Obenseuer-Issues/issues/474))
* Fixed sorting ignoring liquids in container (issue [#458](https://github.com/loiste-interactive/Obenseuer-Issues/issues/458))
* Fixed item UI not showing correct alcohol & shroom amount
* Fixed consuming items ignoring item quality and other factors
* Fixed lightcullcontrollers spamming exceptions on console (issue [#499](https://github.com/loiste-interactive/Obenseuer-Issues/issues/499))
* Fixed save/load preventing storages from respawning (affects also O-Market and General Store)
* Fixed wieldable items not working correctly after loading (issue [#392](https://github.com/loiste-interactive/Obenseuer-Issues/issues/392), issue [#491](https://github.com/loiste-interactive/Obenseuer-Issues/issues/491))
* Fixed wieldable items making flashlight noises when flashlight is equipped (issue [#149](https://github.com/loiste-interactive/Obenseuer-Issues/issues/149))
* Fixed toilet saving not saving player position correctly (issue [#504](https://github.com/loiste-interactive/Obenseuer-Issues/issues/504))
* Fixed liquid quality to not affect container price
* Fixed RM counter
* Fixed lockpicking skill rewards
* Fixed sauna stove UI (issue [#445](https://github.com/loiste-interactive/Obenseuer-Issues/issues/445))
* Fixed items vanishing when merging stacks (issue [#444](https://github.com/loiste-interactive/Obenseuer-Issues/issues/444))

## Tasks

* Added more objectives to Getting Started task (issue [#403](https://github.com/loiste-interactive/Obenseuer-Issues/issues/403))

## Recipes

* Added väkisahti recipe
* Added sahti recipe
* Added sahti mash recipe
* Added ale recipe
* Added ale mash recipe
* Added hot dog weiner recipe
* Added glowing hot dog weiner recipe
* Added flour recipes
* Added composting recipe for ruined mash
* Added composting recipe for bottoms
* Added moonshine recipes (distillery)
* Added sugar mash
* Added sugar shroom mash
* Added apple mash
* Added apple shroom mash
* Added brewing recipes
* Changed mashes to not need sugar
* Changed shroom mashes to not need yeast
* Balanced mash prices

## Items

* Added väkisahti
* Added sahti
* Added ale
* Added ale mash
* Added sahti Mash
* Added juniper branches
* Added juniper berries
* Added model to fish eggs
* Added quality to meats
* Addded empty flowerpot
* Added meatballs
* Added smashed potatoes
* Adjusted canned vegetables prices to include the jar price
* Adjusted alcoholic beverage stats and prices
* Adjusted plant prices
* Added bottoms (distillation residue)
* Added moonshines
* Added cider
* Added mushroom cider
* Added sugar mash
* Added sugar shroom mash
* Added apple shroom mash
* Changed ruined mash price
* Fixed Septi Low price (issue [#502](https://github.com/loiste-interactive/Obenseuer-Issues/issues/502))
* Fixed some soups not giving bowl back
* Fixed disposable bowl soups decaying into bowl of mold

## Furniture

* Added flowerpot blueprint
* Changed Sawbuck price
* Reduced medium moonshine still collision area (issue [#498](https://github.com/loiste-interactive/Obenseuer-Issues/issues/498))

## Interior Player Tenement

* Fixed missing wardrobe collider (issue [#496](https://github.com/loiste-interactive/Obenseuer-Issues/issues/496))

# August 18th 2023 (Version 0.3.07)

* Added cents to RM
* Fixed blueprint and recipe spawners (issue [#381](https://github.com/loiste-interactive/Obenseuer-Issues/issues/381))
* Fixed rats and plants not growing when the player is in another map (issue [#394](https://github.com/loiste-interactive/Obenseuer-Issues/issues/394))
* Fixed trigger delays not working correctly when loading save (issue [#480](https://github.com/loiste-interactive/Obenseuer-Issues/issues/480))
* Fixed keybinding save issues (issue [#486](https://github.com/loiste-interactive/Obenseuer-Issues/issues/486))
* Fixed saved settings reseting every time game is updated
* Fixed transition doors state saving (issue [#288](https://github.com/loiste-interactive/Obenseuer-Issues/issues/288))
* Fixed manufacturing process saving (issue [#468](https://github.com/loiste-interactive/Obenseuer-Issues/issues/468))
* Fixed recipes not showing ingredients sometimes (issue [#467](https://github.com/loiste-interactive/Obenseuer-Issues/issues/467))
* Fixed duplicating tasks (issue [#204](https://github.com/loiste-interactive/Obenseuer-Issues/issues/204))
* Fixed bleeding effect going over a 100% (issue [#488](https://github.com/loiste-interactive/Obenseuer-Issues/issues/488))
* Fixed fuel not burning when outside the map (issue [#472](https://github.com/loiste-interactive/Obenseuer-Issues/issues/472))
* Fixed crafting not counting time spent outside the map
* Fixed perishable items not counting time spent outside the map

## Tasks

* Mr. Duck's blue duck rescue task is not being present on the list of tasks (issue [#390](https://github.com/loiste-interactive/Obenseuer-Issues/issues/390))

## Items

* Removed glow from RM coins (issue [#460](https://github.com/loiste-interactive/Obenseuer-Issues/issues/460))

## Furniture

* Fixed ownership of kitchen tools (issue [#466](https://github.com/loiste-interactive/Obenseuer-Issues/issues/466))
* Fixed rat cage collisions (issue [#478](https://github.com/loiste-interactive/Obenseuer-Issues/issues/478))
* Fixed beer crate snap point  (issue [#471](https://github.com/loiste-interactive/Obenseuer-Issues/issues/471))

## Interior Tenement Deekula B

* Fixed basement door showing always ??? (issue [#229](https://github.com/loiste-interactive/Obenseuer-Issues/issues/229))

## Interior Tenement Deekula Mine Enterance

* Fixed Hanss' Hideout Keys (issue [#485](https://github.com/loiste-interactive/Obenseuer-Issues/issues/485))

## Interior O-Market

* Fixed restocking issues.
* Fixed storage visual states.

## Interior General Store

* Enabled respawning of stock

# August 9th 2023 (Version 0.3.06)

* Added auto sort to traders
* Added out of space message to traders (issue [#404](https://github.com/loiste-interactive/Obenseuer-Issues/issues/404))
* Added hide hud key to the key bindings menu (issue [#426](https://github.com/loiste-interactive/Obenseuer-Issues/issues/426))
* Changed storages to select items to spawn in advance (issue [#398](https://github.com/loiste-interactive/Obenseuer-Issues/issues/398))
* Changed crafting menu behavior (issue [#137](https://github.com/loiste-interactive/Obenseuer-Issues/issues/137))
* Fixed furniture selling, crafting, dismantle (issue [#385](https://github.com/loiste-interactive/Obenseuer-Issues/issues/385), issue [#384](https://github.com/loiste-interactive/Obenseuer-Issues/issues/384))
* Fixed O-market price rounding  (issue [#413](https://github.com/loiste-interactive/Obenseuer-Issues/issues/413))
* Fixed spoilage of snakeplants (issue [#407](https://github.com/loiste-interactive/Obenseuer-Issues/issues/407))
* Fixed noclip not working correctly (issue [#415](https://github.com/loiste-interactive/Obenseuer-Issues/issues/415))
* Fixed disappearing trade slots every second use (issue [#404](https://github.com/loiste-interactive/Obenseuer-Issues/issues/404))
* Fixed beer mash recipe (issue [#405](https://github.com/loiste-interactive/Obenseuer-Issues/issues/405))
* Fixed mail receiving (issue [#409](https://github.com/loiste-interactive/Obenseuer-Issues/issues/409))
* Fixed max depression not drinking random alcohol from inventory
* Fixed premature triggering of achievements on save load caused by pre-initialized achievement manager (issue [#391](https://github.com/loiste-interactive/Obenseuer-Issues/issues/391))
* Fixed key bindings not showing correctly (issue [#340](https://github.com/loiste-interactive/Obenseuer-Issues/issues/340))
* Fixed (again) issues with consumable items causing an error (issue [#419](https://github.com/loiste-interactive/Obenseuer-Issues/issues/419))

## Items

* Changed sorting button to sort by categories (issue [#396](https://github.com/loiste-interactive/Obenseuer-Issues/issues/396))
* Fixed RM coins glowing too much (issue [#380](https://github.com/loiste-interactive/Obenseuer-Issues/issues/380))
* Fixed sorting button not automatically combining items (issue [#396](https://github.com/loiste-interactive/Obenseuer-Issues/issues/396))

## Tasks

* Changed kurahaara farm dialogue (issue [#414](https://github.com/loiste-interactive/Obenseuer-Issues/issues/414))
* Fixed taking Kurahaara's greenhouse plants considered as a crime (issue [#414](https://github.com/loiste-interactive/Obenseuer-Issues/issues/414))

## Tenement System

* Added message that explains why the furniture cannot be placed (issue [#429](https://github.com/loiste-interactive/Obenseuer-Issues/issues/429), issue [#342](https://github.com/loiste-interactive/Obenseuer-Issues/issues/342))
* Changed mushroom farm upgrades to require previous versions (issue [#438](https://github.com/loiste-interactive/Obenseuer-Issues/issues/438))
* Fixed placed items being removed when loading game (issue [#377](https://github.com/loiste-interactive/Obenseuer-Issues/issues/377))
* Fixed move button not working correctly when certain category is selected (issue [#424](https://github.com/loiste-interactive/Obenseuer-Issues/issues/424))
* Fixed stairwell access entrance being solid (issue [#433](https://github.com/loiste-interactive/Obenseuer-Issues/issues/433))
* Fixed tenement's greenhouse building mode area [#450](https://github.com/loiste-interactive/Obenseuer-Issues/issues/450))
* Fixed tenement upgrades getting stuck at final payment phase [#416](https://github.com/loiste-interactive/Obenseuer-Issues/issues/416))
* Fixed upgrade button message when it's upgraded to max [#442](https://github.com/loiste-interactive/Obenseuer-Issues/issues/442))
* Fixed issues with furniture indication inside inventory [#418](https://github.com/loiste-interactive/Obenseuer-Issues/issues/418))

## Furniture

* Added modular shelves
* Added katana stand
* Added plywood shelf
* Added snap points for rat cages
* Added snap point for beer crate
* Added snap points for pallets
* Added half pallet
* Added half pallet blueprint
* Sittable objects now detect if there's stuff placed on them (issue [#428](https://github.com/loiste-interactive/Obenseuer-Issues/issues/428))
* Changed name of barrel (growing) to be more clear that it is for growing plants
* Changed gas bottle holder collisions (issue [#427](https://github.com/loiste-interactive/Obenseuer-Issues/issues/427))
* Fixed bag of soil ownership (issue [#408](https://github.com/loiste-interactive/Obenseuer-Issues/issues/408))
* Fixed not being able to place a toilet paper holder to a wall (issue [#422](https://github.com/loiste-interactive/Obenseuer-Issues/issues/422))
* Fixed compost box having a placeable top (issue [#401](https://github.com/loiste-interactive/Obenseuer-Issues/issues/401))
* Fixed not being able place ashtray stand on a bare ground (issue [#421](https://github.com/loiste-interactive/Obenseuer-Issues/issues/421))
* Fixed geared head drill and angle grinder [#417](https://github.com/loiste-interactive/Obenseuer-Issues/issues/417))
  
## Console

* fixed tyiredness command (issue [#443](https://github.com/loiste-interactive/Obenseuer-Issues/issues/443))

## Interior Player Tenement

* Fixed tenement basement texture glitch at stairwell entrance (issue [#435](https://github.com/loiste-interactive/Obenseuer-Issues/issues/435))
* Fixed tenement's shabby stairwell collision problem between 3rd and 4th floor (issue [#437](https://github.com/loiste-interactive/Obenseuer-Issues/issues/437))
* Fixed decent greenhouse blocking the entrance (issue [#451](https://github.com/loiste-interactive/Obenseuer-Issues/issues/451))
* Fixed stairway fine windows (issue [#449](https://github.com/loiste-interactive/Obenseuer-Issues/issues/449))
* Fixed storages and items being owned (issue [#446](https://github.com/loiste-interactive/Obenseuer-Issues/issues/446))
* Fixed shroom room spawning shower particles in sauna (issue [#436](https://github.com/loiste-interactive/Obenseuer-Issues/issues/436))
* Removed floating items from basement (issue [#432](https://github.com/loiste-interactive/Obenseuer-Issues/issues/432))

## Interior O-Market

* Fixed O-market not restocking (issue [#412](https://github.com/loiste-interactive/Obenseuer-Issues/issues/412))

# August 3th 2023 (Version 0.3.05)

* Added Interior Tenement Greenhouse
* Added Interior Tenement Greenhouse Storage
* Added Interior Tenement House5
* Added Interior Tenement Kurahaara Home
* Added Interior Tenement Pharmacy
* Added snapping points to some furniture. Snapping can be enabled with 'c' -key
* Added random events when sleeping in unsafe bed
* Player now receives random mail once a day (currently random recipes)
* Added composting
* Added notifications for committed and detected crimes
* Added sort button to player inventory and storages (issue [#104](https://github.com/loiste-interactive/Obenseuer-Issues/issues/104))
* NPCs now react to player commiting crimes
* Added recipe for counterfeit money
* Fixed being able to drop money into player inventory as an item (issue [#337](https://github.com/loiste-interactive/Obenseuer-Issues/issues/337))
* Fixed being unable to add fuel to fuel slots (issue [#336](https://github.com/loiste-interactive/Obenseuer-Issues/issues/336))
* Fixed being able to open building menu  when console is open (issue [#334](https://github.com/loiste-interactive/Obenseuer-Issues/issues/334))
* Fixed time jumps on save loads.
* Fixed time slept and time passed not being in sync (issue [#319](https://github.com/loiste-interactive/Obenseuer-Issues/issues/319))
* Fixed noclip  (issue [#308](https://github.com/loiste-interactive/Obenseuer-Issues/issues/308))
* Fixed blueprints (and potentially other items) from instant respawning upon saveload  (issue [#300](https://github.com/loiste-interactive/Obenseuer-Issues/issues/300))
* Fixed being unable to buy more than one copy of furniture (issue [#346](https://github.com/loiste-interactive/Obenseuer-Issues/issues/346))
* Fixed item duplication exploit by placing items as furniture (issue [#359](https://github.com/loiste-interactive/Obenseuer-Issues/issues/359))
* Fixed save/load issues on player placed growing boxes  (issue [#341](https://github.com/loiste-interactive/Obenseuer-Issues/issues/341))
* Fixed lockpicking sometimes preventing from opening the pause menu (issue [#362](https://github.com/loiste-interactive/Obenseuer-Issues/issues/362))
* Fixed NPCs missing body parts (issue [#21](https://github.com/loiste-interactive/Obenseuer-Issues/issues/21))
* Fixed the furniture shop scroll position resetting after buying/selling something (issue [#354](https://github.com/loiste-interactive/Obenseuer-Issues/issues/354))
* Fixed player trigger issues (issue [#286](https://github.com/loiste-interactive/Obenseuer-Issues/issues/286))
* Fixed television noise (issue [#287](https://github.com/loiste-interactive/Obenseuer-Issues/issues/287))
* Fixed notes not being transported between the maps (issue [#189](https://github.com/loiste-interactive/Obenseuer-Issues/issues/189))
* Fixed audios being disabled after dying in sleeping (issue [#150](https://github.com/loiste-interactive/Obenseuer-Issues/issues/150))

## Intro

* Fixed looping sentence (issue [#370](https://github.com/loiste-interactive/Obenseuer-Issues/issues/370))
* Fixed mushroom lights (issue [#370](https://github.com/loiste-interactive/Obenseuer-Issues/issues/370))

## Interior Player Tenement

* Added player mailbox
* Fixed being unable to walk on smoothly without jumping on makeshift staircase ladders (issue [#364](https://github.com/loiste-interactive/Obenseuer-Issues/issues/364))

## Interior O-Market

* Mirjam now comments if player tries to leave without paying.
* Fixed liquids spawning in discount basket (issue [#332](https://github.com/loiste-interactive/Obenseuer-Issues/issues/332))
* Fixed bottle recycling (issue [#332](https://github.com/loiste-interactive/Obenseuer-Issues/issues/332))
* O-Market now sells Pekka Coffee
* O-Market now sells Glue
* O-Market now sells Paper
* O-Market now sells Envelopes
* O-Market now sells Stamps
* O-Market now sells Charcoal
* O-Market now sells Yarn

## Interior Tenement Deekula A

* Added blueprint spawnpoints

## Interior Tenement Deekula B

* Added 3D printer to hacker's apartment

## Tenement System

* Adjusted furniture amounts on traders (issue [#328](https://github.com/loiste-interactive/Obenseuer-Issues/issues/328))
* Added move button (issue [#316](https://github.com/loiste-interactive/Obenseuer-Issues/issues/316))
* Added alphabetical furniture sorting (issue [#353](https://github.com/loiste-interactive/Obenseuer-Issues/issues353))
* Added rotation modes (issue [#294](https://github.com/loiste-interactive/Obenseuer-Issues/issues/294))
* Fixed placed items being removed when loading game (issue [#313](https://github.com/loiste-interactive/Obenseuer-Issues/issues/313))
* Changed building menu to remember the current category when the menu is closed (issue [#358](https://github.com/loiste-interactive/Obenseuer-Issues/issues/358))
* Fixed not being able to pay the final payments (issue [#363](https://github.com/loiste-interactive/Obenseuer-Issues/issues/363))
* Fixed build menu legend (issue [#337](https://github.com/loiste-interactive/Obenseuer-Issues/issues/337))
* Fixed pre-placed storage furnitures resetting position after load (issue [#298](https://github.com/loiste-interactive/Obenseuer-Issues/issues/298))
* Fixed pressing TAB opening menu when closing building menu (issue [#294](https://github.com/loiste-interactive/Obenseuer-Issues/issues/294))
* Fixed disappearing storage items after saving (issue [#314](https://github.com/loiste-interactive/Obenseuer-Issues/issues/314))

## Furniture

* Added toolcart
* Added wooden desk blueprint
* Added wooden desk
* Added cottage table
* Added cottage bench
* Added metal desk
* Added Metal Table With White Tablecloth
* Added Metal Table With White Tablecloth blueprint
* Added wooden table blueprint
* Added fancy wooden square table
* Added round coffee table
* Added fancy wooden desk
* Added fancy leather chair
* Added fancy large wooden cabinet
* Added banker's lamp
* Added large flowerpot with support blueprint
* Added large flowerpot with support
* Added large flowerpot
* Added barrel with support (growing) blueprint
* Added barrel (growing) blueprint
* Added barrel with support (growing)
* Added barrel (growing)
* Added tincan (growing) blueprint
* Added tincan (growing)
* Added flowerbox with lamp
* Added flowerbox with lamp blueprint
* Added flowerbox with supports blueprint
* Added rusty barrel
* Added flowerbox with supports (can grow vines)
* Added rat cage blueprints
* Added rat cages
* Added compost blueprint
* Added compost
* Added Stolland clock blueprint
* Added Stolland clock
* Added terrarium
* Added terrarium blueprint
* Added bag of soil blueprint
* Added flowerbox blueprint
* Added aquarium blueprint
* Addded sawbuck (chainsaw version) blueprint
* Added sawbuck blueprint.
* Added saw
* Added chainsaaw
* Added brick furnace blueprint.
* Adjusted furniture crafting costs.
* Adjusted vegetable crate collisions (issue [#329](https://github.com/loiste-interactive/Obenseuer-Issues/issues/329))
* Added icons for furnace furnitures
* Fixed floating brick furnace
* Fixed growing box modifiers not being lacation dependant (issue [#348](https://github.com/loiste-interactive/Obenseuer-Issues/issues/348))
* Fixed wine racks not displaying bottles after load (issue [#356](https://github.com/loiste-interactive/Obenseuer-Issues/issues/356))
* Fixeed flowerbox ownership
* Fixed inflatable pool ownership
* Changed wine racks to accept other bottles and cans (issue [#361](https://github.com/loiste-interactive/Obenseuer-Issues/issues/361))

## Items

* Added yarn
* Added mesh
* Added charcoal
* Added glue
* Added fake money
* Metal bars are now stackable
* Addded red hot steel bar item (can be converted into sheetmetal by hitting it with sledgehammer)
* Hitting wood log with axe (few times) now converts it into firewood
* Hitting glass pane, glass bottle and pint with anything now converts it into glass shards
* Fixed pills giving paper trash on each use, also the cans spawning is not a thing anymore (issue [#320](https://github.com/loiste-interactive/Obenseuer-Issues/issues/320))


# July 2th 2023 (Version 0.3.04)

* Added Interior Tenement Speakeasy
* Added get arrested achievement
* Added crime amount achievements
* Added burglary achievements
* Changed unlock text to green (issue [#322](https://github.com/loiste-interactive/Obenseuer-Issues/issues/322))
* Fix to a crash caused by finalizer of playerdetector
* Fixed bottle recycling machine giving back bottles (issue [#284](https://github.com/loiste-interactive/Obenseuer-Issues/issues/284))
* Fixed item crafting cost check if craft uses "ammo"
* Fixed Drill working effect (issue [#307](https://github.com/loiste-interactive/Obenseuer-Issues/issues/307))
* Fixed stats loading skipping time (issue [#318](https://github.com/loiste-interactive/Obenseuer-Issues/issues/318))

## Items

* Fixed mämmi being unpickupable (issue [#299](https://github.com/loiste-interactive/Obenseuer-Issues/issues/299))
* Changed name of Plastic filament -> Plastic Filament
* Fixed used sleeping pills giving metal cans (issue [#320](https://github.com/loiste-interactive/Obenseuer-Issues/issues/320))

## Tenement System

* Fixed player bed(s) marked as owned (issue [#293](https://github.com/loiste-interactive/Obenseuer-Issues/issues/293))
* Fixed placeable crafting stations being marked as owned
* Fixed deleting trash bag not deleting it's LOD (issue [#311](https://github.com/loiste-interactive/Obenseuer-Issues/issues/311))
* Fixed Drill furniture rotation (issue [#312](https://github.com/loiste-interactive/Obenseuer-Issues/issues/312))
* Fixed the light is still being emitted after picking up shrooms (issue [#301](https://github.com/loiste-interactive/Obenseuer-Issues/issues/301))

## Furniture

* Added sawbuck furniture
* Added angle grinder furniture
* Added brick furnace furniture
* Added gas furnace furniture
* Added electric kiln furniture
* Fixed drill being unplaceable

## Interior Tenement Deekula B

* Added Hank Möbelmann for testing

## Interior O-Market

* O-Market now sells batteries and can openers
* O-Market now sells buckets and empty jars
* O-Market now sells weiners and hotdog buns
* Fixed stacked item prices on checkout (issue [#305](https://github.com/loiste-interactive/Obenseuer-Issues/issues/305))
* Fixed lenkkis being free to take

# June 30th 2023 (Version 0.3.03)

* Added Interior Player Tenement
* Added Interior Tenement O Market
* Increased Axe, Slegehammer and Pickaxe durability
* Improved drill textures
* Added animations to some crafting stations
* Some crafting stations and recipes now show items being crafted on worldspace.
* Rats can now be killed with axe and sledgehammer
* Added renewable sources for resources, what can be worked on tools such as axes to produce wood
* Added 3D printing
* Added smelting
* Added addiciton related achievements
* Added current item amount to the tenement upgrade UI (issue [#208](https://github.com/loiste-interactive/Obenseuer-Issues/issues/208))
* Added the building schematics buttons to the tenement panel UI (issue [#208](https://github.com/loiste-interactive/Obenseuer-Issues/issues/208))
* Added crafted recipes saving to the crafting machine UI  (issue [#223](https://github.com/loiste-interactive/Obenseuer-Issues/issues/223))
* Changed depression behavior
* Changed Osrat walking animation (issue [#119](https://github.com/loiste-interactive/Obenseuer-Issues/issues/119))
* Changed threshold of drunk effect to be higher (issue [#247](https://github.com/loiste-interactive/Obenseuer-Issues/issues/247))
* Changed reload tutorial behaviour [#238](https://github.com/loiste-interactive/Obenseuer-Issues/issues/238)
* Changed pause menu button to cancel lockpicking [#167](https://github.com/loiste-interactive/Obenseuer-Issues/issues/167)
* Changed default mouse sensitivity to 9 [#202](https://github.com/loiste-interactive/Obenseuer-Issues/issues/202)
* Fixed stoves missing audio
* Fixed camera jitter (issue [#259](https://github.com/loiste-interactive/Obenseuer-Issues/issues/259))
* Fixed rats converting into coins when harvesting from cages (issue [#215](https://github.com/loiste-interactive/Obenseuer-Issues/issues/215))
* Fixed lock location of certain type of doors (issue [#193](https://github.com/loiste-interactive/Obenseuer-Issues/issues/193))
* Fixed lights sometimes incorreclty turning off (issue [#196](https://github.com/loiste-interactive/Obenseuer-Issues/issues/196))
* Fixed controls not working in current Main Menu character creation (issue [#1](https://github.com/loiste-interactive/Obenseuer-Issues/issues/1))
* Fixed controls: can't select character in Main Menu (issue [#2](https://github.com/loiste-interactive/Obenseuer-Issues/issues/2))
* Fixed breakables making sound on map load (issue [#231](https://github.com/loiste-interactive/Obenseuer-Issues/issues/231))
* Fixed possibility of having >100% depression (issue [#220](https://github.com/loiste-interactive/Obenseuer-Issues/issues/220))
* Fixed container slots becoming grey and unusable (issue [#203](https://github.com/loiste-interactive/Obenseuer-Issues/issues/203))
* Fixed showers not turning off when uses (issue [#228](https://github.com/loiste-interactive/Obenseuer-Issues/issues/228))
* Fixed TVs and showers not saving their state (issue [#230](https://github.com/loiste-interactive/Obenseuer-Issues/issues/230))
* Fixed pickable objects intantly respawning on save load (issue [#213](https://github.com/loiste-interactive/Obenseuer-Issues/issues/213))
* Fixed locks not regocnizing key item after save load (issue [#190](https://github.com/loiste-interactive/Obenseuer-Issues/issues/190))
* Fixed main menu issues [#165](https://github.com/loiste-interactive/Obenseuer-Issues/issues/165)
* Fixed missing controls in payment machine [#8](https://github.com/loiste-interactive/Obenseuer-Issues/issues/8)
* Fixed Osrat issues [#227](https://github.com/loiste-interactive/Obenseuer-Issues/issues/227)
* Fixed recipes with multiple liquid outputs taking only one container [#225](https://github.com/loiste-interactive/Obenseuer-Issues/issues/225)
* Fixed controls: can select hidden clothes panel slots [#5](https://github.com/loiste-interactive/Obenseuer-Issues/issues/5)
* Fixed controls: can't select phone call or clear buttons [#6](https://github.com/loiste-interactive/Obenseuer-Issues/issues/6)
* Fixed beaker texture rendering issue (issue [#261](https://github.com/loiste-interactive/Obenseuer-Issues/issues/261))
* Fixed plants not saving (issue [#279](https://github.com/loiste-interactive/Obenseuer-Issues/issues/279))
* Fixed pressing interact button at the end of a dialogue restarting it (issue [#194](https://github.com/loiste-interactive/Obenseuer-Issues/issues/194))
* Fixed X and Y inverting options being swapped (issue [#282](https://github.com/loiste-interactive/Obenseuer-Issues/issues/282))
* Fixed missing models and icons of blueprinted items in workshop (issue [#191](https://github.com/loiste-interactive/Obenseuer-Issues/issues/191))

## Items

* Aded gold shavings item.
* Aded silver shavings item.
* Added electronic waste item
* Added junk wood item
* Added crafting recipe for gold mechanical watch
* Added crafting recipe for silver mechanical watch
* Added crafting recipe for steel mechanical watch
* Added crafting recipe for brass mechanical watch
* Aded brass shavings item.
* Added crafting recipe for OS coins.
* Added crafting recipe for can opener.
* Added fertile soil.
* Added plastic filament.
* Added gas bottle.
* Added boiled rice
* Added boiled macaroni
* Added Osmo Lonkero
* Added Stollandia Vodka
* Added crafting recipes for axe and sledgehammer.
* Added metal shavings item.
* Added metal slab item.
* Added mechanical parts item.
* Added furniture parts item.
* Added wiring components item.
* Added Osrat battery type to description [#238](https://github.com/loiste-interactive/Obenseuer-Issues/issues/238)
* Changed pure green mushrooms to act similar way as other mushrooms
* Fixed chemical lab water purifying recipe
* Fixed glass shards being un-pickupable
* Fixed missing eating sounds on baked foods

## Console

* Added command to modify player skill levels
* Developer console history should now persist 
* Fixed closing console via "esc" opening pause menu (issue [#209](https://github.com/loiste-interactive/Obenseuer-Issues/issues/209))

## Main Menu

* Changed the character limit from 10 to 15 (issue [#98](https://github.com/loiste-interactive/Obenseuer-Issues/issues/98))

## Interior Start

* Added task menu tutorial (issue [#237](https://github.com/loiste-interactive/Obenseuer-Issues/issues/237))
* Fixed load menu not working correctly (issue [#270](https://github.com/loiste-interactive/Obenseuer-Issues/issues/270))
* Fixed the interviewer screen animation (issue [#183](https://github.com/loiste-interactive/Obenseuer-Issues/issues/183))

## Interior Tenement Deekula A

* Fixed sauna not being functional
* Fixed being able to enter storage area without breaking boxes (issue [#212](https://github.com/loiste-interactive/Obenseuer-Issues/issues/212))
* Fixed collision issue (issue [#211](https://github.com/loiste-interactive/Obenseuer-Issues/issues/211))
* Fixed rat not saving (issue [#214](https://github.com/loiste-interactive/Obenseuer-Issues/issues/214))
* Fixed Samuel not dropping coffee when inventory is full (issue [#218](https://github.com/loiste-interactive/Obenseuer-Issues/issues/218))
* Fixed the mine entrance transition door lock state saving (issue [#192](https://github.com/loiste-interactive/Obenseuer-Issues/issues/192))
* Fixed the apartment A8 keys (issue [#216](https://github.com/loiste-interactive/Obenseuer-Issues/issues/216))
* Fixed collisions.

## Interior Tenement Deekula B

* Added emergency number poster to B3 (issue [#178](https://github.com/loiste-interactive/Obenseuer-Issues/issues/178))
* Changed priest's name to Tobias (issue [#201](https://github.com/loiste-interactive/Obenseuer-Issues/issues/201))
* Fixed light culling on B3 and B4 set on wrong doors (issue [#198](https://github.com/loiste-interactive/Obenseuer-Issues/issues/198))
* Fixed new objectives not appearing in Priest's debt task (issue [#199](https://github.com/loiste-interactive/Obenseuer-Issues/issues/199))
* Fixed cupboards being drawers (issue [#234](https://github.com/loiste-interactive/Obenseuer-Issues/issues/234))
* Fixed missing collisions (issue [#241](https://github.com/loiste-interactive/Obenseuer-Issues/issues/241))
* Fixed Max's toilet rotation (issue [#254](https://github.com/loiste-interactive/Obenseuer-Issues/issues/254))
* Fixed incorrect ownership on some items.
* Fixed broken occlusion on door (issue [#264](https://github.com/loiste-interactive/Obenseuer-Issues/issues/264))

## Interior Tenement Deekula Mine Enterance

* Fixed being able to get stuck between desk and wall (issue [#256](https://github.com/loiste-interactive/Obenseuer-Issues/issues/256))

## Interior Tenement General Store

* Fixed Mr. Bag's state save (issue [#207](https://github.com/loiste-interactive/Obenseuer-Issues/issues/207))

# May 13th 2023 (Version 0.3.02)

* Added Interior Tenement General Store
* Added Interior Tenement Deekula A
* Added some achievements.
* Added ability to craft lockpicks.
* Added comfort level text on beds.
* Added visible current time for alarm clock item object.
* Added eating sounds for macaroni casseroles (issue [#12](https://github.com/loiste-interactive/Obenseuer-Issues/issues/12))
* Changed closing console with "esc" to not pause the game (issue [#81](https://github.com/loiste-interactive/Obenseuer-Issues/issues/81))
* Changed scene change doors unlock behavior (issue [#77](https://github.com/loiste-interactive/Obenseuer-Issues/issues/77))
* Changed shit to edible (issue [#132](https://github.com/loiste-interactive/Obenseuer-Issues/issues/132))
* Fixed mental health not working properly
* Fixed hold interaction bug when pause menu is opened (Winch)
* Fixed issues on taking money from containers (issue [#79](https://github.com/loiste-interactive/Obenseuer-Issues/issues/79))
* Fixed going back to main menu remembering last save (issue [#82](https://github.com/loiste-interactive/Obenseuer-Issues/issues/82))
* Fixed scene change doors red unlock text (issue [#83](https://github.com/loiste-interactive/Obenseuer-Issues/issues/83))
* Fixed loading of some adressables (task items) failing
* Fixed trying to enter non-existing map causes game to freeze and autosaves to corrupt (issue [#73](https://github.com/loiste-interactive/Obenseuer-Issues/issues/73))
* Fixed rightclicked inventory slots staying highlighted
* Fixed pressing "R" multiple times on item stack causing inventory screen getting stuck
* Fixed crash on quit game (issue [#27](https://github.com/loiste-interactive/Obenseuer-Issues/issues/27))
* Fixed pressing interact button at the end of a dialogue restarting it (issue [#84](https://github.com/loiste-interactive/Obenseuer-Issues/issues/84))
* Fixed container inventory breaking (issue [#99](https://github.com/loiste-interactive/Obenseuer-Issues/issues/99))
* Fixed recursive serialization issue.
* Fixed dropping rats  (issue [#128](https://github.com/loiste-interactive/Obenseuer-Issues/issues/128))
* Fixed lathe audio
* Fixed fail chance calculation
* Fixed not always being able to drag items to inventories
* Fixed dropped items sometimes getting stuck on screen (issue [#134](https://github.com/loiste-interactive/Obenseuer-Issues/issues/134))
* Fixed toilet lid animations
* Fixed coal (not charcoal) being un-pickupable (issue [#139](https://github.com/loiste-interactive/Obenseuer-Issues/issues/139))
* Fixed culling lights, this should improve performance
* Fixed defecation on floor (issue [#152](https://github.com/loiste-interactive/Obenseuer-Issues/issues/152))
* Fixed cursor vanishing after using some equipment (issue [#146](https://github.com/loiste-interactive/Obenseuer-Issues/issues/146))
* Fixed filled wine bottles (issue [#145](https://github.com/loiste-interactive/Obenseuer-Issues/issues/145))
* Fixed dropped items not saving (issue [#135](https://github.com/loiste-interactive/Obenseuer-Issues/issues/135))
* Fixed fish breeding (issue [#157](https://github.com/loiste-interactive/Obenseuer-Issues/issues/157))
* Fixed a typo (issue [#175](https://github.com/loiste-interactive/Obenseuer-Issues/issues/175))
* Fixed logpile visual state not updating at start (issue [#170](https://github.com/loiste-interactive/Obenseuer-Issues/issues/170))
* Fixed shroom mash recipes not using mushrooms (issue [#140](https://github.com/loiste-interactive/Obenseuer-Issues/issues/140))
* Fixed negative addictions (issue [#133](https://github.com/loiste-interactive/Obenseuer-Issues/issues/133))
* Fixed item stacks not merging correctly (issue [#28](https://github.com/loiste-interactive/Obenseuer-Issues/issues/28))
* Fixed chair look around not working correctly sometimes (issue [#129](https://github.com/loiste-interactive/Obenseuer-Issues/issues/129))
* Improved lathe textures

## Console

* Added item find command.
* Added command to get player stats.
* Added command to set health directly.
* Added console to remember previous commands.
* Added unlock command to now work on change level doors.
* Fixed Noclip and godmode behaviour on saves (issue [#65](https://github.com/loiste-interactive/Obenseuer-Issues/issues/65))

## Tasks

* Fixed being able to bypass objective in "Priest's debt" (issue [#141](https://github.com/loiste-interactive/Obenseuer-Issues/issues/141))

## Interior Start
* Fixed hallucinations spell mistake (issue [#136](https://github.com/loiste-interactive/Obenseuer-Issues/issues/136))
* Fixed interviewer screen animation (issue [#153](https://github.com/loiste-interactive/Obenseuer-Issues/issues/153))

## Interior Tenement Deekula B

* Fixed missing geometry on 3rd floor (issue [#87](https://github.com/loiste-interactive/Obenseuer-Issues/issues/87))
* Fixed windows missing collisions (issue [#101](https://github.com/loiste-interactive/Obenseuer-Issues/issues/101))
* Fixed save issues on rollup door (issue [#95](https://github.com/loiste-interactive/Obenseuer-Issues/issues/95))
* Fixed save issues on light switch (issue [#78](https://github.com/loiste-interactive/Obenseuer-Issues/issues/78))
* Fixed toilet lid not closing (issue [#82](https://github.com/loiste-interactive/Obenseuer-Issues/issues/82))
* Fixed missing map (issue [#92](https://github.com/loiste-interactive/Obenseuer-Issues/issues/92))
* Fixed interaction with Adam (issue [#97](https://github.com/loiste-interactive/Obenseuer-Issues/issues/97))
* Fixed occlusion culling issues (issue [#122](https://github.com/loiste-interactive/Obenseuer-Issues/issues/27)) and (issue [#116](https://github.com/loiste-interactive/Obenseuer-Issues/issues/116))
* Fixed a typo, stool and item ownership in B11 (issue [#115](https://github.com/loiste-interactive/Obenseuer-Issues/issues/115))
* Fixed Amanda dialogue typo (issue [#177](https://github.com/loiste-interactive/Obenseuer-Issues/issues/177))
* Fixed being able to interact the shadows after the dialogue has ended (issue [#100](https://github.com/loiste-interactive/Obenseuer-Issues/issues/100))
* Fixed low FPS in hacker apartment (issue [#22](https://github.com/loiste-interactive/Obenseuer-Issues/issues/22))
* Fixed Max's shroom farm to have correct modifiers 

## Interior Tenement Deekula Mine Enterance

* Added clipping (issue [#94](https://github.com/loiste-interactive/Obenseuer-Issues/issues/94))
* Changed Anya dialogue (issue [#91](https://github.com/loiste-interactive/Obenseuer-Issues/issues/91))
* Fixed phone on the table not being interactable
* Fixed missing map (issue [#92](https://github.com/loiste-interactive/Obenseuer-Issues/issues/92))

# April 20th 2023 (Version 0.3.01)

* Added new scene to testing
* Added reload tutorial/hint
* Added refresh rate setting
* Added cooked minced meat
* Added indicator when dialogue has ended
* Changed gold, silver and brass item prices.
* Changed Osrat to only work when it's in hand and visible (issue [#39](https://github.com/loiste-interactive/Obenseuer-Issues/issues/39))
* Fixed several saving issues
* Fixed resolution change bug
* Fixed some dialogue problems
* Fixed recipes loading bug
* Fixed hand slots saving
* Fixed too slow sitting animation (issue [#14](https://github.com/loiste-interactive/Obenseuer-Issues/issues/14))
* Fixed toilet and chair save bug (issue [#32](https://github.com/loiste-interactive/Obenseuer-Issues/issues/32))
* Fixed task items loading bug (issue [#42](https://github.com/loiste-interactive/Obenseuer-Issues/issues/42))
* Fixed being able to choose the bottom dialogue option by accident when pressing continue (issue [#55](https://github.com/loiste-interactive/Obenseuer-Issues/issues/55))
* Fixed crafting fail chance (issue [#61](https://github.com/loiste-interactive/Obenseuer-Issues/issues/61))
* Fixed being able to talk when being mid-air (issue [#67](https://github.com/loiste-interactive/Obenseuer-Issues/issues/67))
* Fixed mold overlay not appearing on items after loading a save.
* Fixed liquids not showing after loading a save.
* Fixed current soundscape saving
* Fixed issues on ctrl+double click taking money from inventories (issue [#47](https://github.com/loiste-interactive/Obenseuer-Issues/issues/47))
* Increased door close range
* Several flashlight fixes and improvements (issue [#58](https://github.com/loiste-interactive/Obenseuer-Issues/issues/58))
* Several small fixes
* Mushrooms no longer damage player when other side is enabled

## Console
* Fixed console not being able to spawn large id number items
* Fixed tiredness commands changing thirst instead of tiredness

## Main Menu
* Changed first and last name input field content types to 'name'
* Fixed loading menu not working correctly (issue [#23](https://github.com/loiste-interactive/Obenseuer-Issues/issues/23))

## Interior Start
* Fixed interaction tutorial (issue [#54](https://github.com/loiste-interactive/Obenseuer-Issues/issues/54))
* Start package now gives some basic food items

## Interior Tenement Deekula B
* Added some unpickable shrooms and other stuff to bathroom scene (issue [#64](https://github.com/loiste-interactive/Obenseuer-Issues/issues/64))
* Changed some objects to be interactive (issue [#50](https://github.com/loiste-interactive/Obenseuer-Issues/issues/50))
* Fixed map not being visible
* Fixed bookcase door clipping with wall
* Fixed B4 toilet
* Fixed apartment B3 bathroom scene problems (issue [#45](https://github.com/loiste-interactive/Obenseuer-Issues/issues/45))
* Fixed some occlusion issues (issue [#56](https://github.com/loiste-interactive/Obenseuer-Issues/issues/56))
* Fixed apartment B7 bathroom door (issue [#60](https://github.com/loiste-interactive/Obenseuer-Issues/issues/60))
* Fixed Max Masher not giving recipe (issue [#66](https://github.com/loiste-interactive/Obenseuer-Issues/issues/66))
