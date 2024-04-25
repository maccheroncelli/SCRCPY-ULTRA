# SCRCPY-ULTRA

## Description
SCRCPY-ULTRA is a comprehensive Python-based tool designed to enhance interaction with Android devices. Leveraging advanced capabilities like screen mirroring, device control, and PDF document management, it offers extensive functionalities through a user-friendly GUI. This application integrates ADB for device communication and provides features such as real-time image processing, PDF generation, and custom event handling for efficient device management.

To leverage the full functionality of SCRCPY-ULTRA, including screen recording and mirroring, place the script in the same directory as your SCRCPY installation. 
This setup ensures that SCRCPY-ULTRA can utilize scrcpy's capabilities directly.

## Installation

### Setup
1. Download the original SCRCPY - https://github.com/Genymobile/scrcpy/releases
2. Download the `SCRCPY-ULTRA' script and place it into the SCRCPY directory.
4. Install required Python packages:
   ```sh
   pip install PyQt5 opencv-python-headless PyPDF2 pyautogui numpy pillow reportlab
   ```
   
### Android Device Setup
Before using SCRCPY-ULTRA, ensure your Android device is prepared:
- Enable **Developer Mode** by going to Settings > About phone and tapping Build number 7 times.
- Turn on **USB Debugging** in Developer options.

## Usage

### Starting the Application
Run the script using Python:
```sh
python SCRCPY-ULTRA-V1.2.py
```

## Features

- **SCRCPY Functionality**: Enables users to start SCRCPY directly through the interface without command line interaction, simplifying the process of screen mirroring and device control.
- **Screenshot Tool**: Offers the ability to take screenshots of the connected device. It supports Optical Character Recognition (OCR) to recognize text within screenshots, which can then be used to create searchable PDF documents.
- **Autoscroll**: Automates scrolling on the connected device, with customizable direction, speed, and count, ideal for capturing content.
- **OCR Capabilities**: Integrated OCR function that can be manually triggered, allowing the extraction of text from images or screenshots.
- **Image Post-Processing**: Includes options for post-processing of images, such as cropping and stitching, to refine the results before saving or utilizing them further.
- **Image Stitching**: Premier feature, provides the ability to stitch images together in a specified direction, which is particularly useful for creating a continuous image sequence from multiple screenshots.

## Contributing

Contributions to SCRCPY-ULTRA are welcome. Here are ways you can contribute:
- Reporting bugs
- Suggesting enhancements
- Submitting pull requests for new features or bug fixes

For major changes, please open an issue first to discuss what you would like to change.

## Screenshot
![image](https://github.com/maccheroncelli/SCRCPY-ULTRA/assets/154501937/2ad1eb8f-2668-481b-808d-ff9f9f9b1457)
