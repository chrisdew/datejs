This NPM package is a zombie.  I cannot afford the time to maintain it, as I am no longer using it.

If anyone would like to take over maintenance, please contact me via GitHub.

I have left the datejs package in the NPM repo, in order to not break other packages which depend on it.

Have a look at https://npmjs.org/package/moment as an alternative.

Apologies,

Chris.


DateJS is not working in 0.4.x+ - I'm not investigating it.
===========================================================

DateJS
------

This is a simple NPM wrapper around the excellent datejs client-side library.

It modifies the Date prototype - this technique is looked down upon, but it's
a very useful library.

See [the datejs site](http://www.datejs.com/) for more information.

Usage
-----

In the shell:

    npm install datejs

In your app:

    require('datejs');

Notes
-----

NPM package datejs v0.0.1 corresponds to datejs Alpha1.  It hasn't changed for 
three years, so hopefully it won't be too much of a maintenance nightmare.

I've just included all of the non-US locales in lib - I've not written any way 
to access them yet.

What I'll probably do is create a wrapper which defaults to en-US, but can be
called with other locales.

I am not the author of datejs.  I'm just maintaining an NPM package of it, as I
needed one.
