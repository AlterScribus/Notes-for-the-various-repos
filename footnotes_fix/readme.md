This aims to get the best of footnotes_fix branch 

this branch is one branch of the contributor's git repo that was setup and managed by malex (before github).
this branch was created by Cezary to debug footnotes

To clone the whole repo :
git clone git://git.scribus.net/scribus.git git

then switch to footnotes_fix branch :
git checkout --track -b footnotes_fix origin/footnotes_fix
or simply
git checkout footnotes_fix

Related bugs on mantis are in the "contributor's project" :
* http://bugs.scribus.net/view.php?id=10983 : Delete text doesnt update display (fixed in footnotes branch)
* http://bugs.scribus.net/view.php?id=11003 : Crash when editing notenumber reminder in note (fixed in footnotes branch)
* http://bugs.scribus.net/view.php?id=11837 : Crash when deleteing text of 2 footnotes at once (NOT fixed)
* and more...
