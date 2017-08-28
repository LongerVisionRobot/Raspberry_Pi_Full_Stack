# 2.4 Install Packages from Source

To install packages from source, we of course need to get the source code first. A lot open source code nowadays are hosted on github. Therefore, we need to make sure the code can be ```git clone``` from github repositories. In our course [**DIY Linux**](http://www.longervisionrobot.com/en/courses/linux-lfs.html), we elaborate how to use github in detail. Here, we won't talk about it, but the **Github Help** on [Adding a new SSH key to your GitHub account](https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/) is strongly recommended  for students to follow.


## 2.4.1 Some C/C++ Packages

Actually, the author's most often used packages are:

* **Video Streaming**: [**FFmpeg**](http://ffmpeg.org/), [**live555**](http://www.live555.com/), [**VLC**](https://www.videolan.org/index.html), [**gstreamer**](https://gstreamer.freedesktop.org/), etc.
* **Computer Vision**: [**OpenCV**](http://opencv.org/), [**PCL**](http://pointclouds.org/), [**OpenNI**](https://structure.io/openni), [**NiTE**](http://openni.ru/files/nite/index.html), etc.
* **Image Processing**: [**CImg**](http://cimg.eu/), [**ImageJ**](https://imagej.net/), [**ImageMagick**](https://www.imagemagick.org), etc.
* **GIS**: [**OSGeo**](http://www.osgeo.org/), [**GRASS**](https://grass.osgeo.org/), etc.
* **Robotics**: [**Mrpt**](https://www.mrpt.org/), [**Orocos**](http://www.orocos.org/), etc.


## 2.4.2 Some Python Packages

[Anaconda Python](https://www.continuum.io/) [Virtual Environment](https://conda.io/docs/user-guide/tasks/manage-environments.html) is strongly recommended as the Python working environment. In fact, we've got a course [Anaconda Python](http://www.longervisionrobot.com/en/courses/pl-python.html) focusing on Python language programming under Anaconda virtual environment. Here in this course, we ignore Anaconda Python but **ONLY** work without a virtual environment.

To install a python package, in general, there are 3 ways:
* install the package directly from **Synaptic Package Manager**
* install the package by ```pip install```. 
>**Pip** is used to support the use of Python in cloud web hosting, such as by Heroku.(Cited from [Wikipedia](https://en.wikipedia.org/wiki/Pip_(package_manager)) )
    - ```pip install packagename```
    - ```pip install git+git://github.com/xxxxx/packagename.git```
* install the package from source. From within the source directory, run command line ```python setup.py install```.
