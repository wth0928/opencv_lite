## OpenCV: Open Source Computer Vision Library

### Resources

* Homepage: <https://opencv.org>
* Docs: <https://docs.opencv.org/master/>
* Q&A forum: <http://answers.opencv.org>
* Issue tracking: <https://github.com/opencv/opencv/issues>

### Contributing

Please read the [contribution guidelines](https://github.com/opencv/opencv/wiki/How_to_contribute) before starting work on a pull request.

#### Summary of the guidelines:

* One pull request per issue;
* Choose the right base branch;
* Include tests and documentation;
* Clean up "oops" commits before submitting;
* Follow the [coding style guide](https://github.com/opencv/opencv/wiki/Coding_Style_Guide).

# opencv_lite
* This is a lite opencv library which can be called by Android native vendor code
* The source code depended on opencv-4.3.0, compiled by Android.bp
* In this project, core/imgproc/imgcodecs was compiled to libopencv_lite
* Usage:
* 1st: copy this directory to <android_code>/external/
* 2nd: source build/envsetup.sh && lunch <project> && make libopencv_lite

