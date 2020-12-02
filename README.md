# nickiminajclock
This is an alarm clock that can be programmed to play any custom mp3 using customized sound libraries for Arduino. The current design plays Nicki Minaj shouting WAKE UP.

<h3>Instructions for Nicki Minaj Clock</h3>
<ul>
<li>Download All Files</li>
<li>Get the PCM library for Arduino</li>
<li>Upload code to Arduino</li>
</ul>
<h3>Instructions for Uploading Custom Sounds</h3>
<ul>
<li>Download All Files</li>
<li>Get the PCM library for Arduino</li>
<li>Get audacity <a href="https://www.audacityteam.org/download/">LINK TO AUDACITY</a></li>
<li>Download this <a href="https://cdn.hackaday.io/files/1691377236357408/Arduino%20MP3.zip">file</a> it allows you to convert mp3 to raw code</li>
<li>Import your audio file into audacity, change it to 8000khz, export as force mono mp3</li>
<li>In the folder you downloaded, run the script. You may need to get java</li>
<li>Select the file exported from audacity</li>
<li>A file will be copied to your clipboard. Replace the string of numbers in playback.ino with this. You can have 2 1-2 second clips max</li>
<li>Upload to Arduino</li>
</ul>
