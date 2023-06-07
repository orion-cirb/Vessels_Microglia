# Vessels_Microglia

* **Developed for:** Nicolas
* **Team:** Garel
* **Date:** June 2023
* **Software:** Fiji

### Images description

3D images taken with a x60 objective

2 channels:
  1. Vessels
  2. Endothelial cells
  3. Microglia cells
  4. Nuclei

With each image should be provided *.zip* file containing one or multiple ROI(s).

### Plugin description

* Normalize images with quantile-based normalization
* Detect vessels with Weka + Huang thresholding + median filtering
* Detect microglia cells with Weka
* Compute distance between each microglia cell and its nearest vessel
* Compute vessels mean diameter and number of branches, end points, junctions, etc

### Dependencies

* **3DImageSuite** Fiji plugin

* **Weka pixel classifier** + *vessels.model* and *microglia.model* models 

### Version history

Version 1 released on June 2, 2023.
