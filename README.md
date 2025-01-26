# farm_automation this project use for eduacation only
In this project, I learned debugging skills and the importance of a step-by-step approach

Program Limitation Considerations:
-Slow Screen Capture: The screen capture process from the Android phone may be slower due to the time it takes for the device to transmit image data over ADB.
-Template Matching Limitations: The program currently relies on template matching for image recognition, but this method might struggle with variations in lighting, screen resolution, or dynamic UI elements.
-No Root Access for Low-Level Commands: Due to the lack of root access, the program cannot perform certain low-level touch or move actions that require more direct control over the device. This limits the ability to perform gestures or other complex actions that are typically possible with root access.

Program Requirements
-ADB should be installed and properly configured in the system's PATH to allow for seamless communication between the computer and the Android device.
-Android Phone Requirements: The Android phone must have developer mode enabled, with USB debugging turned on. This allows the phone to communicate with the computer via ADB commands.
