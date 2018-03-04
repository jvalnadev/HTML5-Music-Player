This is a basic HTML5 music player<br/>
This was made to have the basic features in a music player as well as have a mobile friendly layout<br/>

Setup:<br/>
1. Add the index.html, player,js, player,css, and playlist.php files to a folder on your web server<br/>
2. Create a folder called library in that folder, this folder should contain your music<br/>
this folder can be a symlink to your main music folder<br/>

Any files/folders starting with a "." will be ignored<br/>
Cover images should be named cover (not case sensitive), they should be in png, jpg/jpeg, or gif format, basically anything a web browser can display<br/>
Cover images are optional<br/>
Any file not called cover will be treated as a audio file<br/>
All files should have a file extension (eg .png, .mp3, .ogg, etc)<br/>
This uses 3 icons from the apache web server, if you are using a different web service, grab these icons and save them as the following:<br/>
<a href="http://www.apache.org/icons/open.folder.png" target="_blank">/icons/open.folder.png</a><br/>
<a href="http://www.apache.org/icons/folder.png" target="_blank">/icons/folder.png</a><br/>
<a href="http://www.apache.org/icons/sound2.png" target="_blank">/icons/sound2.png</a><br/>

Overview:<br/>
<img src="https://raw.githubusercontent.com/GM-Script-Writer-62850/HTML5-Music-Player/master/overview.png"/>

Features:<br/>
Loop: Play the current track over and over again.<br/>
Shuffle: Play tracks at random instead of in order.<br/>
Repeat: Allow tracks to repeat (When un-checked every track much be played once before it can be played again; saved between sessions; Played tracks are marked as &#x2714; in the playlist)<br/>
Next/Back: This feature now uses a play history log, this is not saved between sessions (max length is the size of your playlist)<br/>
Note: Changing the number of tracks in the playlist will reset session data<br/>
Note: Pressing next will not mark a track as played unless it is at least 15% complete<br/>
Bug: When navagating away from tracks via the playlist will bypass history and will not mark the previous track as played (Maybe I will fix this one day, knowing it exist will bug me)
Keyboard shortcuts:<br/>
<pre>
pause          - Spacebar
volume up      - Plus on the number keypad
volume down    - Minus on the number keypad
next song      - Left arrow key
previous song  - Right arrow key
skip 5s        - Up arrow key
rewind 5s      - Down arrow key
toggle shuffle - S key
toggle repeat  - R key
toggle loop    - L key</pre>
