# Super-Video-Player
Super Video Player is a video player for Resonite with some more features

# Public Folders
Just copy the links and paste them into Resonite. Then save the folders to your inventory to access them.

 * Main Public Folder
   * `resrec:///U-Jackson/R-C2B81CE0AAA5A37FB73491560AE0A276AE55929229D1D83D2E8365E911441C61`
 * Super Video Player Folder
   * `resrec:///U-Jackson/R-837640E394447D50B2FEF08AB13055CB41B2D291E5039918F2C58AC5335CAFF3`
# Features

 * Video URL input
 * Local volume control
 * Global mute support
 * Subtitle support (multiple languages, locally selectable)
 * Stereo 3D playback support
 * Local audio track selection
 * Loading indicator (shows how many people are still loading)

# Settings

## Basic

* Grabbable
* Loop Video
	* Loops the video
* Local UI Lock
	* Display a lock at the bottom that can locally disable the UI, useful for watching movies with people
* Spatialize
	* Sets audio to spatialized or global
* Global Mute
	* Mutes the player for everyone
	* Useful when you put the player into another audio solution
## Video
* Steam
	* Sets the player to streaming mode
	* Video files will be streamed instead of fully downloaded before you can watch it
* Video Engine
	* Shows current engine
	* Lets you force engine
		* May not work depending on video
* Stereo
	* For Stereo 3D settings
* Subtitles (local)
	* Locally enables subtitles 
		* Every user that wants to see subtitles has to enable them themselves and select the subtitle
	* Drag and drop an imported .srt file into the drop zone to add (URLs are also supported)
	* Select subtitle from list
* Audio Track (local)
	* Change the audio track locally
	* Used to change audio language
   
# Hidden Settings

```
For these you need an inspector (sorry)
They are in the green slots on the player
``` 
  
* URLOveride
	* Override the URL for different people
* Only useful if you want people to download from different servers
	* Should use the same movie for everyone, otherwise unexpected things might happen
* SubtitlesUserOverride
	* Can set different subtitle languages for different people
* AudioUserOverride
	* Override the audio channel for different people
* StreamUserOverride
	* User override for the stream setting 
