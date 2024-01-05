---
title: MUG
summary: Library for **M**obile **U**nrestrained **G**azetracking
tags:
  - Gaze tracking
  - Smarttrack
  - Eye tracking
  
date: '2011-06-30T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: 'https://bitbucket.org/browatbn/mug/src/master/'

image:
  focal_point: Smart

links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
#url_code: ''
#url_pdf: ''
#url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "retinacorder-slides"` references `content/slides/retinacorder-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
This dataset contains segmented color and depth images of objects from 18 categories of common household and office objects. 
Each object was recorded using a high-resolution color camera and a time-of-flight range sensor. 
Objects were rotated using a turn table and snapshots taken every 20 degrees.

### Download
****
[PointcloudsWithBackground.7z](https://www.dropbox.com/s/3ko6elj58fbwasg/PointcloudsWithBackground.7z?dl=1) (608MB)

[//]: # (**Loading**)
### Loading
****

Color and 3D data is stored in a 3-channel PNG image each. To load a view with C++ and OpenCV use the following lines:

```C++
cv::Mat colorImage = cv::imread(FILENAME_COLOR, -1);
cv::Mat xyzImage_16U3 = cv::imread(FILENAME_XYZ, -1);
cv::Mat xyzImage;
xyzImage_16U3.convertTo(xyzImage, CV_32FC3);
cv::split(xyzImage, channels);
channels[0] -= 1000.0;
channels[1] -= 1000.0;
cv::merge(channels, xyzImage);
```



### Citation
****

If you find this dataset useful, please cite the following paper:

```
@inproceedings{Browatzki2011,
 title = {Going into depth: Evaluating 2D and 3D cues for object classification on a new large-scale object dataset},
 author = {Browatzki, Björn and Fischer, Jan and Graf, Birgit and Bulthoff, Heinrich H. and Wallraven, Christian},
 booktitle = {Proceedings of the IEEE International Conference on Computer Vision},
 doi = {10.1109/ICCVW.2011.6130385},
 pages = {1189--1196},
 year = {2011}
}
```
