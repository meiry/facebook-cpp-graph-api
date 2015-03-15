# Introduction #

easy steps to compile the source code on windows xp using visual studio express
and Qt gui framework


# Details #

to compile do this simple steps:<br>
1. download latest Qt sdk i used version 4.6.1 for windows xp.<br>
2. open cmd ,point it to this directory.<br>
3. type in the cmd : qmake -tp vc FB_GraphApi.pro<br>
<blockquote>it will create the visual studio c++ project files .<br>
4.load the created vc solution file.<br>
5.open the file "FBApi.cpp" in the top fill your developer id and application id you got from facebook.<br>
5 hit f5 to compile and run the code.<br>
<br>
<b>remember this is only mocap application to learn how to implement fb api in c++</b><br>