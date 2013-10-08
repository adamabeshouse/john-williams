To-Do:

+Crop thumbnails, get images for people in Williams house

FUNCTIONALITY:
Thumbnails:
	+ click on face, dialog comes up "in John, Williams, or Cancel"

	+ next to them, there's a info box that says "last checked in (John | Williams) at (time)

	+ after checking in, refresh the page

Info is stored in different files for each person, to avoid any thread-safety issues

When page is loaded, if last check in for any person was more than 8 hours ago, assume check-in no longer relevant and clear it


This is literally all we have to do.
