# Autobox

## Dependencies

### NVIDIA Jetson TX2

### ZED

- [ZED SDK 2.4 TX2](https://www.stereolabs.com/developers/release/2.4/)
- [ZED OpenCV Github](https://github.com/stereolabs/zed-opencv)

### OpenCV

- OpenCV4Tegra should be pre-installed from the NVIDIA Jetson TX2 Developer Kit

### Cmake

- [Cmake 3.11](https://cmake.org/download/)

## Build the program

Open a terminal in the sample directory and execute the following command:

    cd build
    cmake ..
    make

## Run the program

- Navigate to the build directory and launch the executable file
- Or open a terminal in the build directory and run the sample :

        ./ZED_with_OpenCV

- You can optionally provide an SVO file path (recorded stereo video of the ZED)

        ./ZED_with_OpenCV [path to SVO file]
        
### Features

- Click on depth window to receive the distance of the clicked location.

### Keyboard shortcuts

This table lists keyboard shortcuts that you can use in the sample application.

Parameter             | Description                   |   Hotkey
---------------------|------------------------------------|-------------------------------------------------
Save         | Save depth and normal image.      | 's'
Exit         | Quit the application.             | 'q'
