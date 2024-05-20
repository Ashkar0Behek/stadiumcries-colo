This patch is a sound replacement for Pokémon cries in Pokémon Colosseum (US version).
It replaces all the cries for Gen 1 and 2 mons to their counterpart from the N64 Pokémon Stadium games.
Not tested for XD: Gale of Darkness and will definitely not work on Pokémon Battle Revolution.

 ===

How to patch:
 1 - Download Nintenlord's UPS patcher here: https://www.romhacking.net/utilities/606/
 2 - Double click the patcher's .EXE file and choose "Apply an UPS patch to a file"
 3 - For the "File to patch", you'll have to provide a ROM of the base Pokémon Colosseum game yourself.
 4 - For the "USP patch", choose the USP patch provide in this folder, then click "Patch". 
 5 - After waiting a few seconds, your ROM should now be set to role on Dolphin.

NOTE: this was not tested to work on ANY Pokémon Colosseum romhacks or otherwise prepatched roms of the game.

 ===

Known issues and future projects:

 For now, the only known issue is the inevitable fact that Colosseum is programmed to play Pokémon cries
very quietly, which can make them hard to hear especially while the battle music is blasting at peak 
volume. I tried my best to amplify the sounds as much as I could without altering them beyond 
recognition to variable degrees of success. I'm afraid that as long as I don't learn of a way to alter 
the game's sound volume parameter, that's the best result possible. If only this game had volume control
in the options, huh...

In the future, I do plan to apply my patch to XD as well and perhaps explore the possibility of doing it
in PBR. I'm hoping that PBR will be a bit nicer to me with memory and sound resolution cuz I had to drop
the cries down to 16khz, losing a bit of the original sound's quality to fit in.

 ===

Credit:

The work of finding the sounds in the rom and replacing all of them, as well as testing until the game
plays everything as best as it can, is all done by me, FrankBlack22. (discord: frankblack22)

Tools used include,
 - Nintenlord's USP patcher, of course, to make everything into a patch.
 - StarsMmd's Pokémon XD and Colosseum tool pack, to extract and reimport files from Colosseum's rom
 - Nitso's musyx-extract, to unpack samp packages into individual DSP sound files and repackage them
 - AxioDL's amuse build, which gave me the most reliable way to convert workable WAV files into 
compressed DSP files for packing.
 - Lastly the stadium cries used were found on Sr. Bullet Bill's youtube channel.