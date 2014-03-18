headstart
=========

new website boilerplate

This is the boilerplate I've been working on to give me a headstart. It sets up a basic website directory: index.html, and the following folders: images, css, js, and grunt. 

The INDEX.HTML file has a few things that I like... 

1 - preferred meta tags like charset and viewport
2 - link to the favicon and retina size apple touch icon which can be used for ALL apple devices
3 - section for web fonts
4 - link to style sheet
5 - older browser fixes: clearfix for ie6/7, and html5 shiv so html5 elements get created in older browsers
6 - large html comments denoting sections of html i.e. Header, Body, Footer, Scripts
7 - Speaking of "scripts" the scripts are at the bottom. Normally I use jquery and my own script file. ALWAYS BE SURE TO CHECK FOR A LATER VERSION OF JQUERY

The STYLE.CSS file has a few things that I like...

1 - Eric Meyer's CSS Reset at the top
2 - I've added to his reset the micro clear fix to ensure floats clear properly
3 - I also include a section to define the site's color palette and standard fonts (if I'm not using SASS) i.e. primary red color = #xxxyyy, secondary color = #yyyxxx, link color = yyxxyy. 
4 - Big CSS comments to break up sections of the document
5 - Basic OOCSS styles like .float-left and .hidden for easy styling
5 - two media query examples 
