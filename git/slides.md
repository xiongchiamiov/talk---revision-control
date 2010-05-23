!SLIDE

# Git #

!SLIDE bullets incremental

* Fast
* Handles large repositories well
* Designed with multiple users in mind
* Powerful and flexible
* Arcane syntax

!SLIDE

## Change Control, not Version Control ##

!SLIDE

## Staging Index ##

!SLIDE incremental bullets

* hack hack hack
* add files to index
* commit changes

!SLIDE

## http://tomayko.com/writings/the-thing-about-git ##
## http://plasmasturm.org/log/gitidxpraise/ ##

!SLIDE commandline

	┌─[pearson@Bragi] - [~/Documents/talk-revision_control] - [Tue Jan 26, 06:38]
	└─[$]> git add -p showoff.json 
	diff --git a/showoff.json b/showoff.json
	index 6a561f0..f58d37d 100644
	--- a/showoff.json
	+++ b/showoff.json
	@@ -1,5 +1,6 @@
	 [
	-       {"section": "intro"},
	-       {"section": "why"},
	-       {"section": "how"}
	+       //{"section": "intro"},
	+       //{"section": "why"},
	+       //{"section": "how"},
	+       {"section": "git"}
	 ]
	Stage this hunk [y,n,q,a,d,/,e,?]?

!SLIDE

## Stash ##

!SLIDE commandline

	git stash --keep-index
	[run tests]
	git commit
	git stash pop

!SLIDE

## Cheap Branches ##

!SLIDE

## git-svn ##

!SLIDE

## Rebasing ##

!SLIDE

## http://schacon.github.com/history.html ##

!SLIDE

## Easy Self-Hosting ##
