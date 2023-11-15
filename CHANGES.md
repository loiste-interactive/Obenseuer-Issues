# Upcoming

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

## Interior Tebement B

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

## Interior Tenement Deekula A (issue [#802](https://github.com/loiste-interactive/Obenseuer-Issues/issues/802))

* Fixed Jonasson's furniture UI being unlit 

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
