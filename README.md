Noc
===

Noc - Documentation generation tool based on Node.

Description
-----------

*Noc* is a project intended to run [JsDoc-Toolkit](http://code.google.com/p/jsdoc-toolkit/) under [Node](http://nodejs.org/).  

JsDoc-Toolkit normally runs under [Rhino](http://www.mozilla.org/rhino/) which is a javascript engine developed in Java.  
*Noc* has no dependency on Java and is a lot faster than the version of JsDoc-Toolkit based on Rhino.  

*Noc* uses JsDoc-Toolkit 2.4.0.


Synopsis
--------

	node app/run.js [OPTIONS] -t=<template_dir> <source_dir> <source_file> ...


Options
-------

	-a or --allfunctions
			Include all functions, even undocumented ones.

	-c or --conf
			Load a configuration file.

	-d=<PATH> or --directory=<PATH>
			Output to this directory (defaults to "out").

	-D="myVar:My value" or --define="myVar:My value"
			Multiple. Define a variable, available in JsDoc as JSDOC.opt.D.myVar.

	-e=<ENCODING> or --encoding=<ENCODING>
			Use this encoding to read and write files.

	-E="REGEX" or --exclude="REGEX"
			Multiple. Exclude files based on the supplied regex.

	-h or --help
			Show this message and exit.

	-m or --multiples
			Don't warn about symbols being documented more than once.

	-n or --nocode
			Ignore all code, only document comments with @name tags.

	-o=<PATH> or --out=<PATH>
			Print log messages to a file (defaults to stdout).

	-p or --private
			Include symbols tagged as private, underscored and inner symbols.

	-q or --quiet
			Do not output any messages, not even warnings.

	-r=<DEPTH> or --recurse=<DEPTH>
			Descend into src directories.

	-s or --suppress
			Suppress source code output.

	-S or --securemodules
			Use Secure Modules mode to parse source code.

	-t=<PATH> or --template=<PATH>
			Required. Use this template to format the output.

	-T or --test
			Run all unit tests and exit.

	-u or --unique
			Force file names to be unique, but not based on symbol names.

	-v or --verbose
			Provide verbose feedback about what is happening.

	-x=<EXT>[,EXT]... or --ext=<EXT>[,EXT]...
			Scan source files with the given extension/s (defaults to js).


Git repository
--------------

https://github.com/francoiscolas/noc

