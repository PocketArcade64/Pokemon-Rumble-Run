# Pokemon-Rumble-Run

Use models from Pokemon Rumble/ Pokemon Quest

Upcoming changes
- CHECK Claude chat with previous changes I made!!!  ✅ 
- Coins are still not rending textures on their model ✅ 
- On the title screen
    - only show “Bulbasaur selected” for example above the Pokemon itself walking on the ranch after you click on it then the text disappears. ✅ 
    - center the Pokemon icon to the right of the play button vertically in the center ✅ 
    - Remove the circle behind the coin counter total and make the coin number gold and show an icon of the gold P coin ✅
- Why on mobile is there a section of the screen up top where the Dynamic Island is that changes color - it is black on the main menu and light blue in game - is that a restriction of Apple or can you remove that? - include a reference screenshot from iOS
- In Pokemon selection screen
    - Pokemon types not displaying properly on unlocked pokemon and wrong size (??? Type looks good but is blurry), ✅ 
    - Add a small gap between runs and high score, ✅ 
    - During a run, some of the hitboxes are too large or make bigger spacing with the “cars”, - look up how Crossy Road handles this issue.
    - condense the information at the top so you can see more of the small boxes at the bottom ✅ 
    - Label the boxes with 3 digits (001, 002, …) ✅ 
    - In the boxes, you can make the Pokemon icon 20% bigger and the name 20% bigger ✅ 
- Make the poke ball machine only show Pokemon you can pull. ✅ 
- You can make the text 30% bigger universally
- During a run
    - Remove the circle behind the coin counter total and make the coin number gold and show an icon of the gold P coin ✅ 
    - Redesign the pause button to be pixel art

This is a big change: completely redesigning the environment to match the aesthetic of Pokemon Rumble
- Keep all the pokemon the same but change the environment completely 
- Redo the aesthetics of the environment to be exactly like pokemon rumble
- Make the title screen not just be a flat green plane - add environmental objects to fit a cozy outdoors forest home. 
- Add gray lines between road sections (not directly on each road but in between like how Crossy Road does it)

- Implement type abilities ❌ 
- Implement megas
- Add official Pokemon music in adjacent GitHub folder
- Bulk download all models then bulk unzip into target folder ✅ 
- After you pass 100 blocks, after that there is a 1/100 chance after each block passed for you to see a pokemon ahead of you playing the game as you would and if you run into it, you catch it and can use it in the future (no legendaries can appear this way) and only 1 pokemon can be found this way per run (you have to lose then start a new run to find and acquire a pokemon this way)
- if I filter by a type, only show the unlocked Pokemon ✅ 
- Make poke ball machine only show silhouettes of the pokemon you can still pull - once one is pulled, remove it from that screen ✅ 
- Make a different map/mode for Pokemon Quest with all blocky Pokemon
    - Redo the aesthetics of of the starting screen to correspond
- Check if other coins appear normally with shiny legendaries. 
- Do not allow duplicate pokemon to be pulled from the poke ball machine - if you pulled them all then change the button to be grayed out and say “All Pokemon Owned”

- In the Pokemon selection screen
    - Make all the regions be expanded by default
    - some of the sprites are messed up
    - Make all the sprites the same size like gen 1
    - The gen 7 pokemon have extra spaces for models that do not exist - remove those
    - The gen 7 pokemon do not rotate in place
    - When playing as the gen 7 pokemon, their sprite stays in place and you play as an invisible character  
    - Make the developer code “pokemonrumblerush” also unlock all shiny pokemon

- How can I make the 5 and 10 coins appear normally with even non shiny pokemon but also have shiny legendaries have a better bonus from shiny non legendaries?

Obstacles

1. Roads / Cars
Crossy Road equivalent: Cars and trucks moving at different speeds.

Pokémon alternatives
* Cyclizar traffic (Pokémon Scarlet/Violet) riding along established routes.
* Rapidash racing lanes (Pokémon races exist throughout the anime and games).
* Dodrio courier routes (Pokémon delivery services have appeared multiple times in canon).

2. Rivers / Floating Logs
Crossy Road equivalent: Jumping across moving platforms.

Pokémon alternatives
* Lotad lily pads
* Lapras ferry routes (Kanto and Johto canon transportation).
* Wailmer migration pods.
* Mantine surfing routes (Alola Mantine Surf).

3. Trains
Crossy Road equivalent: Fast, lethal obstacles.

Pokémon alternatives
* Tauros stampedes (Pokédex frequently describes aggressive charging behavior).

To keep it feeling like classic Crossy Road, the key rule is: the player still only hops, swipes, and times movement. 

Collect coins along the way to use in a gum ball machine for 50 coins that dispenses Poke balls with new playable characters (poke ball - basic pokemon, great ball - stage 1, ultra ball - stage 3, Masterball - legendary/mythical)

While you are playing as a pokemon, if you reach 1000 score with that selected character, you unlock its shiny form which has a 50% chance to double every coin you pick up. 
Shiny Legendaries instead of having a 50% chance to double coins, there is a 1/10 chance to find a blue coin which is worth 2 coins and a 1/25 chance to find a red coin which is worth 10 (please calculate the math on this to ensure it is slightly better output than regular shinies)

Each pokemon type has a cooldown based ability that recharges based on progress steps taken forward 
- Fire – Move through one fire or lava hazard without stopping once per cooldown.
- Water – Next water section becomes safe instant hops instead of timed crossings.
- Electric – Reveals and highlights the safe timing gap in the next mechanical hazard sequence.
- Ground – Negates the next pitfall, sinkhole, or collapsing tile on contact.
- Ghost – Passes through one solid obstacle or blocked lane during cooldown.
- Grass – Automatically clears one blocked natural hazard cluster ahead into a safe path opening. (They can bypass a special obstacle that provides an easy route through an area)
- ? Poison – Delays activation of the next spore, gas, or toxic hazard on screen.
- ? Bug – Slight collision forgiveness that allows slipping through tight multi-hazard gaps.
- Rock – Pushes you back and absorbs the first impact from a hazard once per cooldown. (Long cooldown)
- Flying – Grants one extended hop that ignores ground hazards in a straight line.
- ? Psychic – Temporarily slows one selected hazard’s timing window for easier reaction.
- Ice – Stabilizes the next slippery or moving hazard into a predictable landing path.
- ? Fighting – Knocks aside one small moving obstacle on contact.
- Dark – Increases reward density but reduces hazard visibility for the next segment.
- ? Dragon – Builds momentum to briefly slow overall hazard speed after a long streak.
