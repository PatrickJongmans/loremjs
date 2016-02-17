Lorem.js Dummy Text/Image Generator for Appcelerator / Titanium
========================================================
A Lorem Ipsum creator service written on JavaScript.


Implementation
--------------

Implementation of Lorem.js is so simple,

You just add lorem to your lib folder, add it for your convience to your globals

Alloy.js:

    Alloy.Globals.Lorem = require('lorem');

'Controller'.js:

    var lorem = new Alloy.Globals.Lorem();
    lorem.type 	= lorem.TEXT;
    lorem.query = "5p";
    var paragraphs = lorem.createLorem();

Querying
--------

Lorem.js has a simple query language: "how many?, what?"

    2p = 2 paragraphs
    5s = 5 sentences
    6w = 6 words
    1-6w = between 1 and 6 words

That's it.

Dummy Images
------------

And Lorem.js uses lorempixum.com for images for now.

Usage:

    NOT YET IMPLEMENTED FOR ALLOY/APPCELERATOR

And watch what happens :)

