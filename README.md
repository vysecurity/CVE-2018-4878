Author and Credits
==================
Author: Vincent Yiu (@vysecurity)

Credits:
   - @evi1cg: Helping me test and keep me motivated
   - @smgoreli: Original Calc.exe PoC
   - @kbandla: He knows, and I know. ;)

Disclaimer
==========
Developed to encourage more Aggressor script development. Use only in authorized penetration testing!

Description
===========

Aggressor Script to launch an Internet Explorer driveby attack using CVE-2018-4878 exploit for Shockwave Flash player versions before February 2018.

Usage:
======

Video Demonstration: <https://www.youtube.com/watch?v=JhUlOIEdq0s>

* Click Host > Host CVE-2018-4878 Payload > Host
* Send link to victim or embed as part of other pages or a redirect
* Victim hits link with IE and outdated flash, you get a shell back in IE sandbox.


CobaltStrike
============

* Load CVE-2018-4878.cna