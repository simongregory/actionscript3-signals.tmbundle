TextMate ActionScript 3 Signals Bundle
========================================

This Bundle provides [TextMate][tm] support for working with the ActionScript 3 [Signals][signals] Event system.

Features:

 * Templates

Installation
------------

Via download:

 * Open this [link][as3_signals_bundle_zip]
 * Unzip the download  
 * Rename the folder to 'ActionScript 3 Signals.tmbundle'
 * Double-click  
 * TextMate handles the rest!  

To install via Git:

		cd ~/"Library/Application Support/TextMate/Bundles/"
		git clone git://github.com/simongregory/actionscript3-signals.tmbundle.git "ActionScript 3 Signals.tmbundle"
		osascript -e 'tell app "TextMate" to reload bundles'

The [ActionScript 3.tmbundle][as3_bundle] is also required. Once installed it needs
be made aware of the Robotlegs bundle. This is done by adding 'ActionScript 3 Signals'
to the `TM_AS3_TEMPLATE_BUNDLES` variable of the 'Settings' preference in the
'ActionScript 3' under **Bundles > Bundle Editor > Show Bundle Editor**.

Support
-------

 * [Issue tracker][issue_tracker]
 * [Repository][repo]

For general questions please use the [TextMate Users mailing list][tm_mailing_list].
Bugs and issues should be reported via the [issue tracker][issue_tracker].
Source can be viewed and forked via the [GitHub repository][repo].

Maintainer
----------

[Simon Gregory][sg_blog]

License
-------

If not otherwise specified (see below), files in this project fall under the following license:

		Copyright 2009 Simon Gregory

		Permission is hereby granted, free of charge, to any person obtaining a copy
		of this software and associated documentation files (the "Software"), to deal
		in the Software without restriction, including without limitation the rights
		to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
		copies of the Software, and to permit persons to whom the Software is
		furnished to do so, subject to the following conditions:

		The above copyright notice and this permission notice shall be included in
		all copies or substantial portions of the Software.

		THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
		IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
		FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
		AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
		LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
		OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
		THE SOFTWARE.

An exception is made for files in readable text which contain their own license 
information, or files where an accompanying file exists (in the same directory) 
with a “-license” suffix added to the base-name name of the original file, and
an extension of txt, html, or similar.

[signals]: http://github.com/robertpenner/as3-signals
[tm]: http://macromates.com
[as3_bundle]: http://github.com/simongregory/actionscript3-tmbundle/tree/master
[as3_signals_bundle_zip]: http://github.com/simongregory/actionscript3-signals.tmbundle/zipball/master
[issue_tracker]: http://github.com/simongregory/actionscript3-signals.tmbundle/issues
[repo]: http://github.com/simongregory/actionscript3-signals.tmbundle/
[fork]: http://github.com/simongregory/actionscript3-signals.tmbundle/fork
[sg_blog]: http://blog.simonregory.com
[tm_conventions]: http://svn.textmate.org/trunk/Conventions.txt
[tm_env_vars]: http://manual.macromates.com/en/environment_variables
[tm_mailing_list]: http://lists.macromates.com/listinfo/textmate
[fx_conventions]: http://opensource.adobe.com/wiki/display/flexsdk/Coding+Conventions
[rl_knowledge]: http://knowledge.robotlegs.org/

[adobe_flash]: http://www.adobe.com/products/flashplayer/
[adobe_flash_tool]: http://www.adobe.com/products/flash/
