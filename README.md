# NDS Homebew Development
Welcome to my [NDS Homebrew](https://en.wikipedia.org/wiki/Nintendo_DS_homebrew) Development Resource!


The Nintendo DS has a special place in my heart and I thought it was about time to started developing on it. You'll find resources, examples and more as I learn how to program on the NDS.

This repo is designed to provide an comprehensive understanding of how to develop on the NDS with devkitpro (C & C++). The examples that come with devkitpro are excellent but in some cases are very one off. Here you'll find examples that are specific to game development. I'll also include as much commented as I see and provide resources to further the understanding of the topic.

Come join us at [/r/NDSHacks](https://www.reddit.com/r/NDSHacks/) to learn more about NDS Homebrew.

Join our Discord: https://discord.gg/JtnxnDD

# NDS Game Development Topics
This repo is broken up into high level topics and each of those topics have it's own README.md that go into more detail. For example the Graphics examples have a total of 9 examples. Each of those 9 examples will have it's own README outlining new information about the code. So this truly is a great way to learn the DevKitPro SDK.

#### 1. [Graphics](/examples/Graphics/)
###### *(Novice - Moderate) - 9 Examples*

Here we will learn how to display a basic solid square on the screen to a full basic game in 9 different examples. Each example will have it's own tutorial outlining new code and different concepts for a full understanding of the basics of graphics on the NDS. I suggest starting off here if you are new to DevKitPro and NDS homebrew development.

#### 2. [Ray Casting](/examples/Ray_Casting/)
###### *(Advance) - working progress*

Here we will learn about an advance idea that can make your game look reall awesome with Ray Casting. Each example has a comprehensive outline of new code, concepts and equations. I truly think anyone can learn how to Ray Cast from these examples because of how much information I go into. If you are looking to take everything you've learned from the `Graphics` category and take it to the next level, Ray Casting is it!

#### 3. [Basic RTS](/examples/Basic-RTS/)
###### *(Advance) - working progress*

I'm pretty interested in getting an RTS together, so I'll be breaking up the development of it into multiple parts. The code, the sprites and the entire project is free to use for your own games! If you do develop something with it let me know, I'd love to spot light it!

# Downloading and Installing
Devkitpro now starts you off with GC and Wii SDKs. To get the GBA/NDS version of devkitPro use the link below:
http://devkitpro.org/wiki/Getting_Started/devkitARM

All projects are currently compiled with 1.50.3 NDS rom tool and devkitARM r45 (latest), as of May 12, 2016.

After installing (I did through OSX perl install) it requires you to set up environment variables.
This is what my *~/.bash_profile* looks like (OSX/Linux):
```
  export DEVKITPRO=/Users/jdriselvato/devkitPro
  export DEVKITARM=${DEVKITPRO}/devkitARM
```

Then literally after that go to *~/devkitPro/examples* and type *make* in any of the example folders and it will compile the source to NDS file. It couldn't be easier.

# Emulator
I'm using DESMUME as the emulator to test out the code on OSX.
Download here: http://desmume.org

# Testing on Device
Read more [here](./tools/README.md)

# Still have questions join our communities
Come join us at [/r/NDSHacks](https://www.reddit.com/r/NDSHacks/) to learn more about NDS Homebrew.

Join our Discord: https://discord.gg/JtnxnDD


# Resources to read
1. http://devkitpro.org/wiki/Getting_Started/devkitARM - Getting Started
2. http://libnds.devkitpro.org/index.html - The libNDS documentation (the bible practically)
3. https://patater.com/files/projects/manual/manual.html - Best guide to get you really familair with developing NDS
4. https://web.archive.org/web/20150814060137/http://www.tobw.net/dswiki/index.php?title=Graphic_modes - Graphic Modes
5. https://mtheall.com/vram.html#T0=1&NT0=32&MB0=0&TB0=0&S0=0 - Tool to check VRAM
6. http://www.coranac.com/2009/02/some-interesting-numbers-on-nds-code-size/ - Some interesting numbers on NDS code size
7. http://answers.drunkencoders.com - Different segments to beginner questions
8. http://www.cc.gatech.edu/~hyesoon/spr11/lec_arm_prog1.pdf - really awesome intro to the technical size of NDS development from GA Tech!
9. http://osdl.sourceforge.net/main/documentation/misc/nintendo-DS/homebrew-guide/HomebrewForDS.html - A guide to homebrew development for the Nintendo DS
10. http://problemkaputt.de/gbatek.htm - An awesome resource on Gameboy Advance / Nintendo DS / DSi, thanks [@zecbmo](https://github.com/zecbmo)
11. https://sylvainhb.blogspot.com/2009/02/xargon-may-source-be-with-you.html - sprite collision example

# Where to find me
[Website](http://johnriselvato.com) | [Twitter](http://twitter.com/jdriselvato) | [Instagram](instagram.com/jdriselvato)
