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


Fileset
Patient

Study
Series
Images



이 5가지를 렌더링한 모습을 보여주는 패널

outline 은 아키텍처로 종속되지 않으며 DICOMDIR이 속해있는 폴더에 실제 존재하는 DICOM 폴더 및 파일들의 구조 및 정보를 제공
With DICOM DIR 모드로 업로드할 경우 DICOMDIR의 구조와 실제 존재하는 폴더 및 파일을 비교하여 DICOMDIR엔 포함되어 있지만 실제로 존재하지 않는 파일의 경우 해당 파일을 제외하여 DICOMDIR에 있고 실제로도 존재하는 파일만 업로드하게 했습니다. 만약 DICOMDIR의 정보와 실제 파일의 존재 여부가 동일하다면 바로 업로드됩니다. 또한 DICOMDIR


