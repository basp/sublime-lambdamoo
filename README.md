# sublime-lambdamoo
### LambdaMOO syntax highlighting for Sublime Text
There seems to be no LambdaMOO syntax highlighting for sublime so I hacked together this <code>LambdaMOO.tmLanguage</code> file. Unfortunately, to make good use of it, you'll need some styling for it too. That is where the <code>LambdaMOO.tmTheme</code> file comes in. 

### Note
These should work in Sublime Text 2 and probably 3 too. But they are totally untested (except on my own machine). I don't believe they are able to harm your system but in the rare case that they do I am not responsible, you are using these at your own risk. That being said, this is mainly just a bunch of XML regex declarations so I personally would be highly amazed if this is cracker material.

#### LambdaMOO.tmLanguage
This is the main syntax highlighting file. It will (hopefully) recognize a bunch of _scopes_ that are relevant to highlighting. Due to my inexperience and lack of awareness of default scopes, I had to invent some and that is also why you need to be aware of these if you wanna make full use of this definition.

This also means that if you are gonna use this definition be prepared for it to change frequently as I'm trying to find out what stuff is available already, how to best map my LambdaMOO elements onto it and what to invent myself.

#### LambdaMOO.tmTheme
This is basically a clone of the included __Sunburst__ theme. Some of the default elements might have been changed _slightly_ but it's mostly additions to make use of the extra scopes.

