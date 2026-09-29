# marioswim
Mario Party 4 - Mario Medley (PAL) TAS
Files generated with Dolphin x64 2606a
ROM: MarioParty4 Europe Revision 2 (GMPP01)
sha256=622c73c9beeba2ee0068a7201b4e05d3c04d99bc3357886980d8aa1c452765cc

# Video
https://www.youtube.com/watch?v=OBX4T2mFH-g

# Youtube Description of above link
Previous known best TAS 47"91 by Freezard: https://www.youtube.com/watch?v=rtpsQApKOGg

Here's how I got a significant improvement over the previous TAS. During recovery, I use the pattern (swim)-(pass 8 frames)-(swim)-(pass 8 frames)-(swim)-(pass 32 frames). Only 1 of the 17 different phases for this pattern gives the correct synchronization that gives optimal healing, which is, gain 7 health every 17 frames. This particular pattern assures 2 of the 3 swim actions are bonified, where last TAS had 1 for 2, so basically 66% vs 50% for bonification rate. Here's a visual for the pattern:

xxxxxxxxxxxxxxxxo
xxxxxxxxoxxxxxxxx
oxxxxxxxxxxxxxxxx

Notice how this strategy only works for blocks of 17 frames, so we are kind of lucky how Nintendo chose their numbers. This strategy does not work for NTSC because healing is every 20 frames there, so Freezard tas remains the best in that version.

For the rest not much thoughts went into it, I just copied what Freezard was doing. I believe there are many ideas worth exploring, but I'm not putting more time into it. I just wanted to share this neat little discovery. I've explored the ending a little and I managed to get a 47"08, I just forgot what I did, lol.

Thanks to hahaphd for bringing to my attention Freezard's tas. Thanks to Freezard for their tas, and most importantly, all the explanation about the game's mechanics. Without this knowledge I would not have done this project. There are still much to understand about the speed dynamics, and I'm sure a better knowledge would lead to interesting mathematics. Finally, thanks to the Dolphin team and the Dolphin Memory Engine team. Incredible programs. Health value is a float at 0x80463C28 and position is a float at 0x80463C14.

Dolphin Tas movie download: github.com/falkush/marioswim

Thank you for your reading!
