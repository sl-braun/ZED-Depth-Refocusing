# ZED-Depth-Refocusing

This sample demonstrates how to grab and process images/depth on a CUDA kernel for a depth-based focusing application.
It creates a simple layered depth-of-filed rendering based on a gaussian blur effect where the kernel size depends on the actual depth.

It is based on the separable convolution CUDA samples to provide optimal performances.


## Build the program

#### Build for Windows

- Create a "build" folder in the source folder
- Open cmake-gui and select the source and build folders
- Generate the Visual Studio `Win64` solution
- Open the resulting solution and change configuration to `Release`
- Build solution

#### Build for Linux

Open a terminal in the sample directory and execute the following command:

    mkdir build
    cd build
    cmake ..
    make

## Run the program

- Navigate to the build directory and launch the executable file
- Or open a terminal in the build directory and run the sample :

        ./ZED_Depth_Refocusing