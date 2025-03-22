# Digital Music for LeonardoTheMutant's Murder Mystery add-on

## What can you find in this repository?
This repository contains several Digital Soundtrack packs for [LeonardoTheMutant's Murder Mystery](https://github.com/LeonardoTheMutant/SRB2-Murder-Mystery) add-on created by our community members. I know you have some questions about our music choice so let's run throught them...

### Why the main add-on (& repository) has only MIDI?
There are several reasons for that. One of them is the filesize of an average MIDI file. One music file in formats like MP3 or OGG is about 1-10 Megabytes average, MIDI one the other hand, ranges from 10 to 50 Kilobytes per file. We did not want to make the main add-on/repository huge because of the presense of digital music. Another reasons is that MIDI lets you do things which are hard or nearly impossible to do with digital music.

### But MIDI sounds horrible!
I will make this clear: it does not sound bad. In fact, **MIDI file has no sound or soundwave information whatsoever**. MIDI file is a sequence of notes and commands meant to be interpreted and played by the *MIDI synthesizer*, which can be both in hardware or software forms. I am sure for 99.9% that you make such statement because you never tried other synthesizer solutions other than the default one that comes with your OS or Media Player which are often indeed terrible. **It is up to your synthesizer to produce the sound of the commands that MIDI file contains**.

### Okay, nerd, but I don't want to mess with synthesizers or have the ability to set them up
This is the reason we have created the Digital Music Packs and this repository. We understand what some of you won't like or have the ability to mess with with MIDI Synthesizers. If you want to have more control over the music and how it sounds we still recommend to get a (software-based) synthesizer because the MIDI Digitalizations "Flavours" (packs) that we have are made using strict parametres and/or soundfonts that not everyone will like.

### How to I use the files from this repository anyway?
In the root folder of the repository you'll find folders each dedicated to one of the Digital Music Packs. Once you choose your Flavour you are able to make a working PK3 add-on by following these steps:
1. Create a new *ZIP* archive;
2. Add the contents of the Digital Pack folder to the archive;
3. Change the extension of the *ZIP* archive to *PK3*;
4. If you want the newly created *PK3* add-on to not trigger the "Game Modified" state in SRB2 the add-on **must include only the music files** (prefixed as `O_` for digital formats or `D_` for MIDI) - any other file that is not music will trigger the "Game Modified" state. Things like *TXT* readmes and *SF2* soundfont files have to be removed too!
5. Connect your *PK3* add-on to SRB2 as the regular add-on

You may not create the *PK3* file and force SRB2 to load the add-on contents directly from the folder instad (with `addfolder` console command in game or `-folder` command line parameter at launch). You still need to make sure there are only music files in the folder to not trigger the "Game Modified" state.

***Posting music-only add-ons on the SRB2 Message Board (mb.srb2.org) is PROHIBITED!***

Each music pack folder will also contain its own README file and the list of tracks present in the pack

# List of available Digital Music Packs

| Name | Description | Author(s) | Folder | Size | Complete? |
| --- | --- | --- | --- | --- | --- |
| **General Murder Music** | A mixture of the digitalized MIDI tracks and the original digital versions of the songs in high quality. | @LeonardoTheMutant, @Troplucky | [GMM](./GMM/) | 296 MB | ***Yes*** |
| **The Murderer's CD** | A remake of the "General Murder Music" pack aiming to be more compact in size | MinusMario (@mm8573) | [TMCD](./TMCD/) | 45.6 MB | ***Yes*** |
| **Yamaha's Mysterious Music 2612** | Digitalized MIDI soundtrack using FM samples taken from Sonic 1, 2, 3&K and 3D Blast | @Lamonite | [YMM2612](./YMM2612/) | 243 MB | Lacks the Intermission themes |
| **Square Saw a Triangle Knife Noise** | A chiptune variation of the soundtrack based on PSG chips like NES APU, Commodore SID and others<br>**This pack is not recommended for sensitive users as it might cause headaches** | MinusMario (@mm8573), @LeonardoTheMutant | [SSATKN](./SSATKN/) | 48.8 MB | ***Yes*** |
