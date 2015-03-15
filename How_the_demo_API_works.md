# Introduction #

Example on how to use the facebook graph api framework to invoke api.<br>
i used the api to extract music from my favorite music group wall feeds,<br> then i just collected the data i needed exported it to svc file and uploaded to google docs (also pragmatically ) for using the music clips.<br>
basically so the data wont get lost!<br>
<br>
<br>
<br>
<br>
<h1>Details</h1>

The steps :<br>
<ul><li>open the file <b><code>MainWindowContainer.cpp</code></b> look for the <b>TestAPIs</b> function this is where the api start to invoke<br>
</li><li>in the same file look for <b>GetGroupWallFeeds</b> function,this is where all the feeds from current date back to the first feed in collected.<br>
</li><li>now in the <b><code>FBApi.cpp</code></b> file look at the top for <b><code>GROUP_PING_ID</code></b> variable this is where the group id should be. but your favorite group you wish to extract its data.</li></ul>
