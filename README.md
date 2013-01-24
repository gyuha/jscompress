jscompress
==========
Uses closure-compiler to minimize multiple JavaScript files.

Requirements
------------

* Linux or Mac OSX
* [Google's Closure Compiler](http://code.google.com/p/closure-compiler/)


Installation
------------

Download the latest Closure Compiler from the Google Code page, and place the [compiler.jar](http://closure-compiler.googlecode.com/files/compiler-latest.zip) file somewhere on your computer (typically ~/bin).


Usage
-----------

Uses closure-compiler to minimize multiple JavaScript files.

Usage: `jscompress [-h] [-all] [-o out] [-l level] file1 file2 ...`

	-all : All sub directory .js files to each Compress. Sub in file options are ignore.
	
	-o   : Output file. using -o followed by its name. If no output file is specified, to each compress files.
	
	-l   : Compilation Level
		1 : Whitespace only
		2 : Simple (default)
		3 : Advanced

Uses closure-compiler to minimize multiple JavaScript files and concatenate them into a single file. 
The files are concatenated in the order they are received as parameters.


