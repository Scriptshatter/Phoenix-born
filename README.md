# You need these mods:
## https://www.curseforge.com/minecraft/mc-mods/origins
## https://www.curseforge.com/minecraft/mc-mods/fabric-api
## https://www.curseforge.com/minecraft/mc-mods/extra-origins
## https://www.curseforge.com/minecraft/mc-mods/pehkui
## https://www.curseforge.com/minecraft/mc-mods/origins-extra-keybinds

- Buffs

    - Passive
        - The warmer you are, the more powerful you get.
        - You always have elytra wings (If you have it, the migrator cape looks aesthetically nice on with this origin.)
        - You can see clearly in lava.
        - You are immune to all kinds of fire damage.
    
    - Active Ability
        - You have a fireball ability that you charge up using fire charges, and fire with heat. The hotkey for this is your quaternary key.
        - Using heat, you can launch yourself up into the air. This uses your primary key.
        - Every 10 minutes, you evade death at the cost of half your max hp. Use a blaze rod to return your hp to normal.
        - By pressing your secondary key, you can trigger an empowered mode, where at the cost of heat, every attack does more damage and lights the enemy on fire for 15 seconds.
        - By using blaze powder (50), magma cream (50), charcoal (30), coal(30), or a stick (10), you can give yourself heat.
        - By pressing your ternary key, you can activate a fire aoe aura that uses heat to light anyone in range on fire while they are in range, and for 5 seconds while out of range.

- Neutral

    - You are 0.75 times the size of a normal player.
    - You spawn in the nether (multiplayer version) or in the desert (singleplayer version)
    - Your temp is set to 250 F (no heat and no cold) whenever you die. Also, you return to full max HP when you die. but your revive cooldown does not reset upon death.

- Debuffs

    - If you start to get cold, you become slower and start to die.
    - Piglins and zombie piglins are always agresive toward you.
    - Water hurts you. need I say more.



# Whats all this temperature stuff with hot and cold about??

## Im glad you asked! Allow me to tell you!

##### This origin has a bare bones version of the tough as nails temperature system! isnt that neat?

> But what heats me up and what cools me down?

##### you might ask,
##### Well allow me to tell you! 

***DO NOT READ FURTHER IF YOU WANT PROPER "IMMERSION". THIS IS FOR PEOPLE WHO ARE WONDERING WHAT THE OPTIMAL WAY TO PLAY THIS ORIGIN IS.***

##### You have a max heat of 750 and max cold of 750.

##### this means you have a max body heat of 1000 F, since the coldest you can go (IRL mind you) is ~-500 F.

- In-game temperature. https://minecraft.fandom.com/wiki/Biome <-- has all information on which biomes have which temperature
    - 2.0 temp gives 20 heat per second (this is the entirety of the nether)
    - 1.2 temp gives 8 heat per second
    - 1.1 temp gives 4 heat per second
    - 1.0 temp doesnt do anything
    - 0.95 and 0.9 temp take 4 heat per second
    - 0.8 temp takes 8 heat per second
    - 0.7 temp and 0.6 temp take 12 heat per second
    - 0.5 temp, 0.3 temp and 0.25 temp take 20 heat per second (this is the entirety of the end)
    - 0.2 temp takes 24 heat per second
    - 0.05 temp and 0 temp take 28 heat per second
    - -0.2 temp takes 32 heat per second
    - -0.3 temp takes 36 heat per second
    - -0.5 temp takes 40 heat per second
    - -0.7 temp takes 48 heat per second  

- Environment

    - Giving heat
        - Lava pools (being surrounded and in 6 lava source blocks or more) give 100 heat per second
        - Being around lava or in 1-5 source blocks of lava takes 4 cold per second and gives 8 heat per second
        - normal torches give 3 heat every 5 seconds
        - soul torches give 1 heat every 5 seconds
        - normal campfires give 4 heat per second (while lit)
        - soul campfires give 2 heat per second (while lit)
        - jack-o-lanterns give 2 heat every 5 seconds
        - candles give 1 heat every 5 seconds (while lit)
        - (being around) fire gives 2 heat every second
        - (being around) soul fire gives 1 heat every second
        - (being around) a blaze gives 4 heat every second
        - (being around) a magma cube gives 8 heat every second
        - (being around) any entity on fire gives 1 heat every second
        - Daytime gives 3 heat per second

    - Takes away heat
        - (being around) strays take away 4 heat every second
        - (being in) rain takes away 100 heat every second (dont be in rain)
        - (being in) water takes away 140 heat every second (you know what, just dont touch water in general.)
        - Nighttime takes 5 heat every second
        - ??? takes away 4 heat every second

## You can use the heat system! just take cold.json, heat.json, coldlink.json, heatlink.json, and torch_temp_change.json and plug them into your file! tempstats.json is an example of what diffrent temps can do! Just give me credit if you use it in a origin you post.

###### hey! psst! down here!

###### Ill make origins for people! DM me at The Stoat (Flux)#4993 for details!
