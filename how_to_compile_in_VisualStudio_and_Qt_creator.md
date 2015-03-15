# Introduction #

easy steps to compile the source code on windows xp using visual studio express And Qt Creator
and Qt gui framework


# Details #

to compile do this simple steps:<br><br>
-- on visual studio express 2008<br>
-------------------------------------------<br>
<ol><li>download latest Qt sdk for visual studio i used version 4.7.1 for windows xp.<br>
</li><li>open cmd ,point it to this directory.<br>
</li><li>type in the cmd : qmake -tp vc <code>FB_GraphApi.pro</code> it will create the visual studio c++ project files .<br>
</li><li>load the created vc solution file.<br>
</li><li>open the file "FBApi.cpp" in the top fill your developer id and application id you got from facebook.group id if you like to use the demo example<br>
</li><li>hit f5 to compile and run the code.<br>
<br></li></ol>


-- on Qt creator 2.1<br>
-------------------------------------------<br>
<ol><li>download latest Qt sdk for mingw i used version 4.7.2 for windows xp.download the mingw in the same page , and Qt creator 2.1 for windows<br>
</li><li>open the <code>FB_GraphApi_mini.pro</code> into the Qt Creator , it supposed to configure the project.<br>
</li><li>open the file "FBApi.cpp" in the top fill your developer id and application id you got from facebook.group id if you like to use the demo example<br>
</li><li>hit ctrl+shift+B or the hammer icon to build .<br>
<br></li></ol>
