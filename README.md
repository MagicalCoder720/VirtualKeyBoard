# VirtualKeyBoard
Virtual Keyboard Using ComputerVision
Virtual Keyboard with Hand Gesture Control

Developed a gesture‑controlled virtual keyboard using Python, OpenCV, and the cvzone HandTrackingModule.
Implemented real‑time hand detection via webcam to track finger landmarks and enable interactive typing without physical hardware.
Designed a custom on‑screen keyboard UI with hover and click effects using OpenCV drawing functions.
Integrated pynput keyboard controller to simulate actual key presses when the user performs a pinch gesture (index finger and thumb together).

Added visual feedback mechanisms:
Blue keys for default state
Purple highlight when hovering
Red highlight when clicked

Ensured single‑click detection by managing finger distance thresholds and preventing multiple unintended presses.
Built a responsive interface with real‑time video feed flipping and dynamic rendering for smooth user experience.
