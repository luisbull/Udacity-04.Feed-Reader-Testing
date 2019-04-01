# Feed Reader Testing Project


## Table of Contents

* [How game was built](#how-game-was-built)
* [App installation](#app-installation)
* [How to check all tests implemented](#how-to-check-all-tests-implemented)
* [External sources](#external-sources)

## Tests implementation

The starter project given by Udacity [link](https://github.com/udacity/frontend-nanodegree-feedreader.git) or download original files directly by clicking [here](https://github.com/udacity/frontend-nanodegree-feedreader/archive/master.zip) There are 4 folders (CSS = 3 files, FONTS = 4 files, JASMINE/SPEC = 1 file JS = 1 file) a HTML and two README files.

I started by reading and analysing the notes inside all .JS files but specially APP.JS and FEEDREADER.JS files as per instructions.  All the tests for this project were implemented in FEEDREADER.JS file.

## App installation

Go to: https://github.com/luisbull/udacity-feed-reader-testing.git
  - Click on: Clone or Download.  (green color tab)
  - Download Zip file.
  - Load index.html in browser.
  

## How to check all tests implemented

RSS feeds

Test 'All URL defined and all URL not empty'  

	To verify that test was implemented and works accurately, user can open 'js/		app.js' file in a text editor, delete a 'url' line of code, save the file and 		refresh the index.html file in the browser. 


Test 'All name defined and all name not empty'

	To verify that test was implemented and works accurately, user can open 'js/		app.js' file in a text editor, delete a 'name' line of code, save the file and 		refresh the index.html file in the browser.



The menu

Test 'The menu is hidden by default'

	To verify that test was implemented and works accurately, user can open 'jasmine/	spec/feedreader.js' file in a text editor, change line of code: 

	expect(body.classList.contains('menu-hidden')).toBe(true);
	to
	expect(body.classList.contains('menu-hidden')).toBe(false);

	save the file and refresh the index.html file in the browser.


Test 'Menu is shown when is clicked. Menu is hidden when is clicked again'

	To verify that test was implemented and works accurately, user can open 'jasmine/	spec/feedreader.js' file in a text editor, change line of code: 

	expect(body.classList.contains('menu-hidden')).toBe(false);
	to
	expect(body.classList.contains('menu-hidden')).toBe(true);

	save the file and refresh the index.html file in the browser.



Initial Entries

Test 'At least one loadFeed entry inside feed container when loadFeed is called'

	To verify that test was implemented and works accurately, user can open 'jasmine/	spec/feedreader.js' file in a text editor, change line of code: 

	expect($('.feed .entry').length >0).toBe(true);
	to
	expect($('.feed .entry').length >0).toBe(false);

	save the file and refresh the index.html file in the browser.



New Feed Selection

Test 'Content changes when loadFeed is loaded'

	To verify that test was implemented and works accurately, user can open 'jasmine/	spec/feedreader.js' file in a text editor, change line of code:

	expect(feedOne === feedTwo).toBe(false);
	to
	expect(feedOne === feedTwo).toBe(true);

	save the file and refresh the index.html file in the browser.

## External sources

https://fonts.googleapis.com/css?family=Roboto:400,100,300,700.
https://cdnjs.cloudflare.com/ajax/libs/jasmine/3.3.0/jasmine.min.css
https://cdnjs.cloudflare.com/ajax/libs/jasmine/3.3.0/jasmine.min.js
https://cdnjs.cloudflare.com/ajax/libs/jasmine/3.3.0/jasmine-html.min.js
https://cdnjs.cloudflare.com/ajax/libs/jasmine/3.3.0/boot.min.js
https://cdnjs.cloudflare.com/ajax/libs/jquery/3.3.1/jquery.min.js
https://cdnjs.cloudflare.com/ajax/libs/handlebars.js/4.0.12/handlebars.min.js
http://google.com/jsapi





