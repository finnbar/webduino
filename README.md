webduino
========

Arduino online (without USB)! This is the frontend of an IDE that uses sound to transfer data.

features
========

* All the syntax highlighting you will (probably) ever need (please tell me if it's missing something)
* Find (but not replace yet)
* Compilation (using Codebender's online compiler)
* Board selection!
* A pretty Bootstrap (with Bootbox) interface!
* Mobile compatability! (sort of)
* Basic syntax checking! (you need a semicolon etc.)

using the compiled output
========

The compiled output is currently console logged, although if you want to use it elsewhere you'll find the code in the compile function in index.html (YES, it's a one-file thing (except the dependencies)), inside the XMLHttpRequest's onstatechange callback function.

sources
========

Most content is taken from Codebender (compiler), Twitter (Bootstrap), Bootbox and Arduino (a local version of the actual compiler for the server to run)