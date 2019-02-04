PCD-E57 [ ![Codeship Status for blackibiza/PCD-E57](https://codeship.com/projects/d3f6ed00-55dd-0132-aaf0-0a29efabe26e/status)](https://codeship.com/projects/49395)
=======

Converter PointCloud Library &lt;---> E57 file format

Library used: [libE57Format](https://github.com/asmaloney/libE57Format)

Description: E57 reader and converter of point clouds, which are downscaled and saved back on hard drive.

This is a fork of [madduci/PCD-E57](https://github.com/madduci/PCD-E57) to use libE57Format instead of E57RefImpl, in order to compile on macOS.

Compiling:

    mkdir build && cd build
    LIBE57FORMAT_INSTALL_DIR="/usr/local/E57Format-2.0-x86_64-darwin" cmake ..
    make

Usage:

    ./e57_2_pcd input.e57

THIS IS ONLY A DEMONSTRATION OF CONVERSION. THE SOFTWARE IS PROVIDED "AS-IS"
