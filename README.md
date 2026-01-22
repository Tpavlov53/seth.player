# seth.player 0.53

An **AI generated** mp3/mp4 player, based on TeamSESH and VHS culture. Includes many functions (just imagine that it's a stereo tape recorder).
! This player is designed for audio/video playback, optimized for capturing via external software (like OBS) and subsequently recording onto authentic VHS tape. So it doesn't have any vhs filters like ntsc-qt or -rs (i might add one?)

To start:
retro_player.exe file to launch, search.exe to search multiple tracks(loads in dedicated terminal!)
alternatively .py files in bin folder (python written)

Bindings:
Space - to start/stop; 
Left&Right arrow - to **REWIND OR FAST-FORWARD** the tracks; 
T - to skip the song and move to the last 5 seconds of the track (debug, to see if features work)

How to use:
If you want to customize the TeamSESH logo, you can change the logos (logos folder) and use reference of the source files. The video must have a dark background and be in mp4 format for the logo to be transparent)
To add songs, you need to go at music folder, and create a folder and name it **with playlist title**, then add the song with the metadata included, as in, it should have: album cover, title, contributing artists. 
It won't matter how the file is called. Same for the video, title and contributing artists.

Features: 
It will show you the exact playlist, artist, title of the song.
Has a song timer.
Has a stereo volume bar.
Has three TeamSESH logos on the bottom, that will appear after program will show the metadata's of the song.
Preloads the previous or next file 1.5 seconds after the start of the song, no matter it is a music file or a video file.
Jitters the UI like a real VHS player with it's heads. 
The album cover is a background that goes down like a tape. It slows down when the songs ends, and starts when the song goes. Fades in and out if there's video next to it.
Stops the player and "ejects the tape" if there's none of the songs left.

Bugs:
Is slow while launching, and might be slower in that regard, if there's too many songs.
Will crash if you skip songs too fast.
Might crash if you use pause frequently.
Keep in mind that it is beta and not serious project.

Tested on:
W11	10.0.26200 Build 26200

Credits:
fonts by MrManet / RUS: Daymarius / VHS icons: DENIRO_pro
 
