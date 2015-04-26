Author:   Yashied

Script Function:
	    (Control Viewer v1.1) AutoIt Window Information Tool

Control Viewer (CV) is a alternative of AutoIt Window Info with a number of advantages. I tried to stick to the interface of the last, so you almost do not have to be retrained. During testing, I never managed to find any controls that could not be identified by CV (on the contrary, shows a lot of hidden controls, especially for the system windows). The all program settings are stored in the following registry key:

HKEY_CURRENT_USER\Software\Y's\Control Viewer

The main differences CV from AWI

Shows the complete list of all existing controls for the window that are interested (visible, hidden and deleted controls are displayed with different colors that can be changed to any other).
Dynamically changing information during search for the windows and their controls.
Ability to quickly switch between controls in the list.
Ability to show/hide any controls from the list (useful for the overlaping controls).
Information for the Style and ExStyle parameters shown in the form of hexadecimal values??, and as its flags.
Added the PID and Path parameters in the Window tab and ability to quickly open a folder that containing the process file.
Added the coordinate system relative to the selected control.
Shows a color of the selected pixel in RGB and BGR formats.
Shows an example fill of the selected color.
Ability to select the text encoding (affects the Text parameter in the Control tab).
The complete change the appearance of pop-up frame for the selected controls.
Simple and convenient tool to get a screenshot of the part screen of interest for publication on the forum (Capture tab).
Create a report in the clipboard or a text file for subsequent publication on the forum.
Search all running AutoIt scripts and their windows in the system (AutoIt tab).
User-friendly interface.

Used shortcuts:
Ctrl+Alt+T - Enable/Disable "Always On Top" mode (also available from the menu).

Ctrl+Alt+H - Enable/Disable highlight selected controls (also available from the menu).

Ctrl+A - Select all text (works in any input field).

Ctrl - Hold down when moving the mouse to scroll the screenshot (Capture tab).

Shift - Hold down when stretching/compression of the contour frame for an equilateral resizing screenshots (Capture tab).

DoubleClick (on the screenshot) - Save the image to a file (Capture tab).

DoubleClick (on any list item) - Open a folder with the file of the process or AutoIt script (AutoIt tab).

Del (on any list item) - Close process (AutoIt tab).

F5 - Updating the list (AutoIt tab).