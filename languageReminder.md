Language Reminder
=================

git status for each file
in stage
in the workspace

stdin is standard input

always use fileName, not filename
more in line with other cases like fileData, fileContents fileStatus, etc.


Helpdoc
-------

sections are: NAME SYNOPSIS DESCRIPTION OPTIONS
think about adding EXIT STATUS after options
thing about adding EXAMPLES after description or after options

order of options in SYNOPSIS
-h <- always the first
-specific <- command specific options
-cx <- cut/verbose group
-swa <- stage/worspace/all group


-D <- debug/dev/dryrun, always the last


Options
-------

-a show all matches when picking/gicking
	original from pick, later gick

-p plain path, do not pick
	original from giff
	original will be gadd

-s consider only stage files
-w consider only workspace files
	original from pick
	later gadd and all gick based commands

-c cut off status
	original from gtatus
-x show status
	original from gick

-D dryrun/debug
	original from pick