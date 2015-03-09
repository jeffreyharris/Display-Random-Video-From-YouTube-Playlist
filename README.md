# Display-Random-Video-From-YouTube-Playlist

<h2>What's This?</h2>
<p>A JavaScript / JQuery solution to playing a random video from a YouTube playlist.</p>

<h3>Requirements</h3>
<ul>
<li>JQuery</li>
<li>This code uses the YouTube api, so you will need to aquire an API key. (steps below)</li>
</ul>

<p>The code connects to the YouTube API and retrieves the information about the playlist. It then counts the number of items in the playlist and selects a random number between 0 and the total number of videos. That random number is then used to select a video from the playlist and the video embed code is changed to play that video.</p>

<h2>Steps for conecting to the YouTube api</h2>
<ul>
<li>Go to Google Developers console</li>
<li>Create a new project</li>
<li>go to Boost your app with Google API</li>
<li>Enable YouTube Data API v3</li>
<li>on the left, go to "Credentials"</li>
<li>Click Create new Public API Access Key</li>
<li>Click Create Browser Key</li>
<li>Add the URl of your site to the "Accept requests from these http referrers."</li>
<li>Generate the key and add it to the JavaScript code where indicated.</li>
</ul>
