# Screen-Webcam-Recorder-App
Need to Record your computer screen? or want to have fun? We got some fun for you. Lets build a Screen recorder using python.

There are two version of the Screen Recording App

version 1.0 : Screen Recorder + Webcamera Recorder.py
version 2.0 : Screen Recorder

1.   Download the zip file.
2.   Extract it.
3.   Run the    version 1.0 : Screen Recorder + Webcamera Recorder.py
                version 2.0 : Screen Recorder.py
     as per your requirements.
4.   Open the cmd and go to the File Source.
5.   Run the [ Screen Recorder + Webcamera Recorder.py  or Screen Recorder.py ] Files.

6.   Want to exit for the app " Press q from the keyboard "
7.   The file will be save at the source file destination.


Modules used in the Program

    *   import datetime         The datetime module supplies classes for manipulating dates and times
                                        # for fetching date and time of the system

    *   Pillow                  The Python Imaging Library adds image processing capabilities to your Python interpreter.
                                This library provides extensive file format support, an efficient internal representation, and
                                fairly powerful image processing capabilities.The core image library is designed for fast access to data
                                stored in a few basic pixel formats. It should provide a solid foundation for a general image processing tool.
                                        # for image grabing Pillow will be used done with ImageGrab method

    *   numpy                   NumPy is a Python library that provides a simple yet powerful data structure: the n-dimensional array.
                                This is the foundation on which almost all the power of Python's data science toolkit is built,
                                and learning NumPy is the first step on any Python data scientist's journey.
                                        # is used to convert the img to an array so the opencv can perform its tasks.

    *   cv2                           OpenCV (open source computer vision) is a very powerful library for image processing and
        (opencv-contrib-python)       machine learning tasks which also supports Tensorflow, Torch/Pytorch and Caffe. ...
                                      Choose only the OpenCV contrib modules you want by selecting/deselecting them as
                                      appropriate when building in Cmake.
                                         # is used to show the image an works with the image processing things

    *   pywin32                  python has the “Python for Windows Extensions” package known as pywin32 that allows us to easily
        GetSystemMetrics         access Window's Component Object Model (COM) and control Microsoft applications via python.
                                        # To get the system metrics like to fetch the height and width of the system screen from OS
