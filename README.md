# Megaman-Super
Megaman: Super (Previously known as 30th Anniversary Mesen 16-bit HD Pack)

=======Description=======
	This HD pack aims to recreate Megaman 1's graphics in 16-bit. The driving idea behind this is a "What-if" scenario where Nintendo made the SNES not only backward compatible with the NES, but also created (and allowed third parties to create) special pass through cartridges that could reskin games. It's a crazy, out-there, parallel universe sort of idea, but it's pretty fun to think about.
	
The tiles in this pack are 99% based on the original NES designs rather than Wily Wars, however, the backgrounds mostly come from WW, albeit with some modifications and enhancements. 

=======Installing the HD Pack=======

1. Locate the folder you have installed Mesen to and inside of that, open HdPacks. If there is not a folder named that, create it.
2. Inside HdPacks, create a folder named exactly the same as your Megaman ROM.
3. Copy the entire contents of the Megaman: Super zip file into the folder you've created.
4. Open Mesen and load up your the ROM for Megaman.
5. Make sure when the game starts that there is text at the bottom stating "[Patch] Applying Patch: Megaman - Super.ips". Another way to check this is if there are white squares on the title screen, the patch is not applying. See Troubleshooting #2 for a fix.
	
=======Troubleshooting=======

1. If no new graphics are showing, in Mesen, goto Options > Video and make sure "Use HDNES HD Packs" is checked.
2. If the patch is not applying, your Megaman ROM has a different hash than required in hires.txt, located in the pack folder you created in step #2 of installation. You'll need to scan the ROM with any tool that can produce an SHA-1 hash, such as Igorware Hasher, copy the SHA-1 it produces, and paste it over the old hash found at the top of hires.txt.

=======Optional (but recommended) steps=======

=======Overclocking=======

Overclocking works perfectly with Megaman 1-6 (and for that matter, very, very much of the NES library). To enable it, go to Options > Emulation > Overclocking tab and change "Additional scanlines before NMI" to 262. This results in a 200% overclock.
	
=======Sprite Flicker=======

Mesen has the option to remove some of the NES's sprite flickering. To enable this, go to Options > Video > Advanced and check the box beside "Remove sprite limit (Reduces Flashing)". 
	
=======Overscan=======

This is the least important of these steps because HD packs mask this pretty well but some players may want to enable this. Mesen allows you to set overscan cropping for individual games. To enable it, go to Options > Video > Overscan tab > Game-Specific tab. The optimal overscan cropping for Megaman 1 is (top, right, bottom, left) 16, 8, 16, 8. This will prevent almost all sprite pop-in, cut off, and glitched background tiles from being visible.

=======Customization=======

Megaman: Super offers various graphical and music customization options.

=======Graphics=======

Inside of the Customization folder you'll find various subfolders with different options. The contents of these folders can simply be copied to the main folder for the HD Pack, overwriting the files inside. The only exceptions to this are folders named "ZZZ_Further Customization" which need to be copied to the appropriate folders. Think of these as slightly more advanced options. All default options are found in here as well, so you can simply copy them over if you want to return the pack to vanilla.

=======Music=======

If you would like to use the original NES music, inside the Customization folder are folders with the prefix "Patch" which you can use to change the music back to default. Word of caution, you cannot switch these patches mid-game and use save states to return to your progress, the reason being that the old save states will be linked to the other version.
		
You can also change out music if you edit the hires.txt file manually. Included in the pack are two remixes and also included is a txt file with the necessary loop points to paste into hires.txt.

=======Pause=======

By default, Megaman: Super removes Pause functionality to free up the use of holding down the Select button to display text boxes in-game. This is simply for consistency with how the rest of the series would handle these text boxes. You can use the "Pause Intact" patches and hires.txt files to restore the pause functionality. You'll still be able to view text boxes, but they will toggle on and off with Select rather than holding it down.
		
=======Thanks=======

mkwong98
	
- For the original HDNES emulator and pack format
		
- For continuing work on Mesen concerning HD Packs
		
Sour
	
- For creating Mesen
		
- For supporting HD packs as well as building upon the format
		
- So much more
		
kya
	
- For the music patch
		
Zynk Oxhyde
	
- For the Roll-Chan series of hacks and letting me add Roll-Chan to this
		
ACC:Xess
	
- For the Bombman and Fireman remixes used in this pack
		
TwelveDust
	
- For the Iceman remix used in the music pack
		
CosmicGem
	
- For the Cutman and Fireman chiptune remixes
		
NES Game Fan
	
- For the trailer for Megaman: Super
		
feos
	
- For making overclocking a possiblity for NES emulation in the first place
		
Dan
	
- For creating Rock and Roll editor, used for some misc edits to levels and tilesets
		
Superjustinbros/Geno on MM8BDM Resources forum
	
- For easter egg materials
		
All who have contributed to Sprites Inc. and Spriter's Resource
	
VGMaps user Revned
	
Most of all, my girlfriend
	
- For who you are and everything you do that keeps me going
		
Enjoy!
