P5 is a menu-based command line tool to emulate the functionality of P4V within a Bash shell.

Configuration:
Open p5 in an editor and set the following variables at the top of the script:

	P4DIFF - a diff program of your choice. The default is meld which is great, but requires X window forwarding (see below).
	       - leave it blank to perform a text-based diff

	P4MERGE - a merge program of your choice, used for resolving conflicts.
		Default is p4merge which requires X window forwarding

	EDITOR - a program for viewing or editing files.

	TMPDIR - a temp directory used by the script

X11 forwarding:
Allows graphical programs to be used for Diff, merge, etc.
If you are connecting via Putty, you can run an X server in Windows (Xming), and set up putty to forward to it.
Details: https://kb.iu.edu/d/bdnt   (See Putty for windows section)

Running:
p5 is menu-based and takes no arguments

		
