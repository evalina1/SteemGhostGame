
### A mobile game that can post to Steem

## Introduction
A playable game on android platform made with [AppInventor2](http://ai2.appinventor.mit.edu) and JavaScript.
This would be the first of its kind since it can post the high score to Steem at the end of the game depending on user request.

## Features
1. Initial screen :
Game has an initial screen that asks for Steem user name and posting key at the first run.

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1514265467/rre8hrpsjtycyv6ozhpb.png)

2. Play screen :
After initial screen player is forwarded to play screen

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1514265562/rdzigmhxgrv8kmieiz77.png)

This screen has 3 buttons :

Start : Goes to game

Send to Steem : Send high score to steem

Steem icon : Change user and posting key

3. Game screen :

This is where game is played.

4. Score sending screen :

When user press the "Send Score to Steem" button, a screen for score sending opens.

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1514265981/tytfgdl6g8zkcjxaudkp.png)

Here the users pre-defined user name, key and high score appear in the text boxes by default.
When the user press "Post It" button score is sent automatically to the tag "steemghostgame"

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1514303471/q7mq8fn6omzcqk2rxui1.png)

If another score is sent, it is send to the same post as update so spam is prevented.

## Source Code : How to review and contribute
* Download the SteemGhost.aia from [this link](https://github.com/firedreamgames/SteemGhostGame)

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1514299954/a9ho91zfskkxiqte12x0.png)

* Download the latest index.html from [this link](https://github.com/firedreamgames/SteemGhostGame)

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1514300140/ec3zideyt9llh00aspjk.png)

* Go to AppInventor2 web page from [this link](http://ai2.appinventor.mit.edu)
* Sign up with your Google account and accept the terms

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1514300922/khhvyrvd8srei56snkds.png)

* If you wish you can take the survey or skip.

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1514300969/rlebvy9hbllpyxstwjbg.png)

* From projects tab choose "import project (.aia) to my computer"

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1514301141/ni7qnvzhahu7j6mopfaa.png)

* From your files choose "SteemGhost.aia" that you previously downloaded

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1514301297/szzliyysbwcv4knvhnfi.png)

* You will see the project screen open with all the files included in it.
First screen is the designer view where you design the User Interphase ( UI )

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1514301528/leagke7nwgfqepum8r2u.png)

In this project there are 3 screens

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1514301930/hssw2eyllqg5fkj5pypz.png)

 _PlayScreen_
This is where all the game mechanics occurs

_Screen1_
This is the main screen where the index.html also executed

_Steem_
This screen is initialized at first, to enter your Steem data ( user + posting key ) and when you click the steem icon in the game if you want to change the data.

* To see the code screen you can click on "BLOCKS" and this will take you to the code relevant to this screen.

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1514302320/xifcqupkqbtsfjx3qrkc.png)

The code is block form.
You can change the code if you need.

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1514302394/unu3cxt0npaxh6equx6k.png)

* To use the latest updated index.html file press the _upload file_ button on media section in the "BLOCK" screen

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1514302576/z13jvhohy9odrwbzsaut.png)

* Upload the latest _index.html_ to the AppInventor since this file may be contributed and updated seperately.

Change the current file.

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1514302879/f5z8llu0qt5ggcikv5va.png)

* To test the program, the .aia file must be converted into .apk. The AppInventor does it automotically.
Clicking on the build button, you can either save the .apk to your drive or provide a square code for .apk to be downloaded to your phone.

![image.png](https://res.cloudinary.com/hpiynhbhq/image/upload/v1514303020/gqh9qeguynakrzsky2ss.png)

* [index.html](https://github.com/firedreamgames/SteemGhostGame/blob/master/index.html) is the main file that makes the comminucation with Steem. 
Any contribution on this file is much appreciated since there are many open points.
example :
_How to post not only text but picture from file to Steem_ 
 
### Executable for the game
The game is placed on the [Google Play](https://play.google.com/store/apps/details?id=appinventor.ai_3rtuncnese.SteemGhost)
Also the apk is in the [GitHub](https://github.com/firedreamgames/SteemGhostGame/blob/master/SteemGhost.apk)

## GitHub Link
https://github.com/firedreamgames/SteemGhostGame




## Files in the repostiory
Readme - explanation

steemghost.aia - AppInventor2 source file

steemghost.apk - Install file - download it to Android and install

steemghost-hi.mp4 - Video tutorial on gameplay
