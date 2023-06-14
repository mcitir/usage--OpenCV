# Installation
- List opencv packages: `apt list --installed | grep opencv`
- After successful build you will find libraries in the build/lib directory: `ls lib`
- And, executables (test, samples, apps) in the build/bin directory: `ls lib`
- Find out opencv installed or not: `pkg-config --modversion opencv`, uninstall guideline [link](https://www.srccodes.com/uninstall-remove-opencv-raspberry-pi-jessie-debain-make-uninstall-open-source-computer-vision-opencvlib/), [link2](https://answers.opencv.org/question/209088/how-to-completely-remove-opencv3/)
- Update dynamic links after `make install` or `make uninstall`: `sudo ldconfig`
-  
