# Dark Mode Forms

This is a customized version of the [Dark-Mode-Forms](https://github.com/BlueMystical/Dark-Mode-Forms) project by @BlueMystical for use with [Game Backup Monitor](https://mikemaximus.github.io/gbm-web/).  

This project is based on v1.8.12 of Dark-Mode-Forms.

Key Changes:
	- Dark mode no longer removes borders from label controls.
	- Changed the reversed button order on the dark mode message boxes.
		- Ex.  "Yes, No instead of "No, Yes".
	- Changed the look of the dark mode input boxes to fit my needs.
		- Prompt dialogs can now be two lines and will now auto-ellipse when too long.
		- Input boxes no longer display labels for fields and use entire form size for input control.
	- Dark mode input boxes now always give first input field focus when the form opens.
	- Removed the value changed delay on dark mode input box controls.
		- Caused issues with values not being updated before the form closes for fast typers/keyboard only users.
	- Other visual changes to dark mode message/input boxes, such as text alignments.

Usage:

Build the DLL and add it to your project.