MatrixEater3D
=============

A Warcraft III MDL-file loader, importer, and vertex editor written in JAVA.
Created by Eric "Retera" to have the features that other similar freeware
programs lacked, and then eventually expanded to be a generally useful editor.

Credits:

Shadow Daemon: This guy provided me with a fantastic BLP to TGA converter, BLP Lab command line version,
that allows the texture loader to convert BLPs to something Java can understand. Many thanks to this guy!

Oracle/Sun: Thanks to Oracle/Sun for the Java language! Also, thanks to the Javadocs for documenting Java
in an understandable way for users

Terai Atsuhiro and Jay Warrick: Thanks to Terai Atsuhiro and Jay Warrick for the Drag and Drop Tabbed Pane
java class code, which was hprovided in online Java elp forums
(java-swing-tips.blogspot.com/2008/04/drag-and-drop-tabs-in-jtabbedpane.html).
I modified it a little bit to meet my needs, but they created it almost in its entirety.

LWJGL: This library, (the "Light-Weight Java Gaming Library"), provided me with the OpenGL bindings required
to display 3D. The "Perspective" display wouldn't have been possible without them! See LWJGL license for details:
http://www.lwjgl.org/license.php

Slick2D: This library has been included in several of the MatrixEater builds in case I ever want to use it,
but I don't think I have actually used it yet. Either way, it's a great library for 2D stuff overtop of LWJGL.
You can read their license here:
https://github.com/slick/slick/blob/master/LICENSE.txt

ZZ Coder and Whome on StackOverflow: These users posted various forms of a TGA-loading library that allows
the MatrixEater to open TGA image files. Many thaks to them for their work!
(stackoverflow.com/questions/1514035/java-tga-loader)

Ladislav Zezula: This guy made the StormLib library that was wrapped into the JStormLib system, which is
awesome of him. Many thanks to him! (See below for information about JStormLib.)

TimoHanisch, Deaod, and contributors to JStormLib on GitHub: JStormLib is the system that wrapped the
StormLib .dll into something that JAVA could use, so that the MatrixEater could open MPQ files. Many
thanks to these guys for that conversion!
