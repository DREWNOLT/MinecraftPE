# MinecraftPE
This is a Minecraft PE I programmed in scratch, converted to .html using sheeptester.github.io/words-go-here/htmlifier

NOTE:
IF YOU WANT TO PLAY IT OR USE IT IN ANY WAY, WHEN YOU DOWNLOAD IT, DOWNLOAD ALL THE FILES IN A .ZIP FILE. IF YOU DO NOT DO SO, THE GAME WILL NOT WORK CORRECTLY. 
The reason for this is that all the files other than the .json and .html files are assets.

Gameplay
There is only 3 items, 1 entity, and 1 placeable block but there is a command line(info can be found inside the book) and there is a decent gui. The menu grapics are pretty good, and the game itself is very similar to minecraft. You can play both on PC and Mobile, to activate PC edition, just toggle the PC switch in Options in the menu. Another way you can make the game pc edition is if you press any key on your keyboard, as long as it is a letter, number, or space key.

How it Works

This uses basic 3D pen and images for the block rendering. The save codes use all the info needed for the world; inventory, entities/blocks, and their coordinates. When you enter the code, it splits it into different lists and then uses those lists to run the game. Beta Features, unlike the regular program, uses individual pixels with individual programs, making it very unstable and unpredictable (It is not recommended). Each block in the game equals 1 item per list in 4 different lists because the lists for the blocks/entities ask for:

-What type of item is it?

-What is its x, y, and z coordinates?

The program constantly renders the world using the lists. The loading part is just for loading list data and adding items to the lists, which is why it is so fast when its loading the world. The assets in the "render" sprite(In my scratch project) are for the block images.

Known Bugs

-Beta features are unstable and super glitchy.

-sometimes 1 or even 2 blocks doesn't show up on startup.

-on the first time you try to break a block, it may go slowly.

-Sometimes the pig flickers but doesn't show.

-The hotbar doesn't always have the best sensitivity.

You can view the bare source in the json file or you can read it online at: https://projects.scratch.mit.edu/425526234/
The original project in scratch is at: https://scratch.mit.edu/projects/425526234/

P.S: There is over 125 assets, so it has a LOT of files! ;)

