# Detection-App
Android Studio
![image](https://github.com/user-attachments/assets/e9637bc5-7181-4a4a-a69b-f71135684e1f)
![image](https://github.com/user-attachments/assets/1629ee72-fca1-4c37-a1c6-28644c34f808)


This repository contains the implementation of a mobile application developed for the Software for Mobile Devices course at the National University of Computer and Emerging Sciences (FAST-NUCES) in Spring 2025. The project focuses on building a feature-rich Android application with four distinct interfaces: Text Recognition (OCR), Face Detection, Barcode Scanning, and Object Detection. Each interface leverages real-time camera processing and machine learning capabilities to provide an intuitive and responsive user experience.

Project Overview

The mobile application integrates advanced computer vision functionalities using Android's camera APIs and machine learning libraries (e.g., ML Kit or TensorFlow Lite). The project is designed to meet the requirements outlined in the course rubric, which evaluates the application across four interfaces, each worth 50 marks, based on UI design, functionality, and usability.

Interfaces and Features





Text Recognition (OCR) Interface:





Displays a live camera preview for real-time text detection.



Features a capture button to extract text from the camera feed.



Draws bounding boxes around detected text for clear visualization.



Provides a scrollable, styled text output area (using TextView or RecyclerView).



Includes user-friendly copy and share buttons for extracted text.



Face Detection Interface:





Shows a smooth, real-time camera feed with face detection.



Overlays precise bounding boxes around detected faces.



Optionally marks facial features (eyes, nose, mouth) with clear indicators.



Displays face data (e.g., age, smile probability, eye status) in an accessible panel, if implemented.



Includes a styled capture button for saving the current frame.



Barcode Scanning Interface:





Offers a lag-free live preview for barcode scanning.



Features a transparent scan box guide to assist users in aligning barcodes.



Provides feedback (e.g., vibration or beep icon) upon successful scans.



Displays scanned barcode content in a readable, scrollable panel.



Includes action buttons (e.g., "Open", "Copy", "Save") for interacting with scan results.



Object Detection Interface:





Processes the camera feed to detect and label objects with bounding boxes.



Shows a dynamic list of detected objects with confidence scores.



Includes a toggle switch for enabling/disabling object tracking mode.



Features a snapshot button to freeze the current view.



Provides a settings interface for switching between object detection modes.

Technologies Used





Programming Language: Kotlin (or Java) for Android development.



Platform: Android Studio with Android SDK.



Libraries and APIs:





CameraX or Camera2 API: For real-time camera preview and capture.



Google ML Kit: For text recognition, face detection, barcode scanning, and object detection.



Android UI Components: Jetpack Compose or XML layouts for designing interfaces.



RecyclerView: For scrollable lists (e.g., text output, object labels).



Tools:





Gradle for build management.



Git for version control.

Repository Structure





app/: Contains the Android application source code.





src/main/java/: Kotlin/Java files for activities, fragments, and logic.



src/main/res/: Resources including layouts, drawables, and strings.



README.md: This file, providing an overview and instructions.

How to Run





Prerequisites:





Install Android Studio (latest version, e.g., Flamingo or newer).



Ensure an Android emulator or physical device with API level 21+ is available.



Install required dependencies via Gradle (specified in build.gradle).



Setup:





Clone the repository:

git clone <repository-url>
cd <repository-directory>



Open the project in Android Studio:





Select File > Open and choose the project folder.



Sync the project with Gradle by clicking Sync Project with Gradle Files.



Execution:





Configure a virtual device (AVD) or connect a physical Android device via USB debugging.



Build and run the app:





Click Run > Run 'app' in Android Studio.



Select the target device/emulator.



Navigate through the app's main menu to access the four interfaces:





Test the OCR Interface by pointing the camera at text and capturing.



Use the Face Detection Interface to detect faces and view optional data.



Scan barcodes using the Barcode Scanning Interface.



Detect objects in the Object Detection Interface and toggle tracking.

Sample Output





Text Recognition: Captures text from a book, displays it in a scrollable TextView, and allows copying to the clipboard.



Face Detection: Shows bounding boxes around faces in the camera feed, with optional markers for eyes/nose and a data panel showing smile probability.



Barcode Scanning: Scans a QR code, vibrates on success, and displays the URL with an "Open" button.



Object Detection: Detects objects (e.g., chair, phone) with labels and confidence scores, allowing snapshot capture.
