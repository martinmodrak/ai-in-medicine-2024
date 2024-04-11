---
title: "Lesson 5 - Task materials"
output: 
  html_document:
    number_sections: true
---


# Download data for lesson

- Download everything from http://195.113.43.46:3388/
  - File sources (for access from outside): 
    - QuPath: https://github.com/qupath/qupath/releases/download/v0.5.1/QuPath-v0.5.1-Windows.zip
    - Ki67 Slide 1: https://openslide.cs.cmu.edu/download/openslide-testdata/Hamamatsu/OS-2.ndpi
    - Ki67 Slide 2 (small): https://molecular.pathology.ufl.edu/2017/06/05/ki67-ihc-single-stain-on-human-tumor-slide/
- Save to a temporary folder (e.g. on Desktop)

# Unpack and run QuPath

# Analyzing first Ki-67 image

Will be done together with everybody

We are mostly following the tutorial at:  https://qupath.readthedocs.io/en/0.5/docs/tutorials/cell_detection.html

- Check Image (left pane) -> Pixel width
- View -> Brightness + Contrast
  - Inspect channels/stains
- Draw a small-ish rectangle ("R" key  or the rectangle icon on the main toolbar) - we want ~100-1000 cells in it
- Analyze -> Cell detection -> Positive cell detection
  - Run with default settings
- Draw a different small-ish rectangle 
  - Run cell detection on "Detection image"  = "Optical Density sum"
- Tuning other parameters
  - Cell expansion
  - Threshold 1
- Analyze a larger region - hotspot
- Can use another region and see the percent positive


# Analyze a Ki-67 image on your own
  



https://qupath.readthedocs.io/en/0.5/docs/tutorials/cell_detection.html

