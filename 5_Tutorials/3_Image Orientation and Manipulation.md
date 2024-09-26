# Image Orientation and Manipulation

Interpretation of the orientation
The orientation of the DICOM images is displayed by one or more uppercase letters in the middle on the top and left of the view.

If Anatomical Orientation Type (0010,2210) attribute is absent or has a value of BIPED, anatomical direction is:

A: anterior
P: posterior
R: right
L: left
H: head
F: foot
If Anatomical Orientation Type (0010,2210) attribute has a value of QUADRUPED (since Version4.1.0), anatomical direction is designated by:

LE: Left
RT: Right
D: Dorsal
V: Ventral
CR: Cranial
CD: Caudal
R: Rostral
M: Medial
L: Lateral
PR: Proximal
DI: Distal
PA: Palmar
PL: Plantar

## Zooming, Panning, Rotating

The zoom tool can be associated with one of three mouse actions . In the image below the zoom tool  is associated with the middle mouse button. See also zoom preferences.

The zoom factor can be modified from different locations:

By dragging the cursor over the image with the configured mouse button
By scrolling the mouse wheel when configured
By selecting an item in the zoom dropdown button in the toolbar
From the context menu: right-click on the image > Zoom
Form the slider in the image tool panel
Using Keyboard Shortcuts (Ctrl + Plus (+), Ctrl + Minus (-) and Ctrl + Enter) on the selected view
The context menu and the toolbar button allows you to select different zoom factor:

Actual pixel size  : display the image at a 1:1 ratio, where each pixel in the image corresponds to one pixel on the screen
Real world (see below) 
Resize to best fit  : scaling the image to make it fit the view area as closely as possible
 Note
The zoom function always zooms in/out to the center of the screen regardless of where the cursor is. This mode provides greater positional accuracy in particular situations.

Since “Resize to best fit” is the default mode for a view, the image will be centered when scrolling to the next image. You need to change the mode or the zoom factor to keep the image off center when scrolling.


## Adjusting Window/Level (Brightness & Contrast)



## Histogram