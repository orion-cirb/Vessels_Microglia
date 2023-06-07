# Vessels_Microglia

* **Developed for:** Nicolas
* **Team:** Garel
* **Date:** June 2023
* **Software:** Fiji

### Images description

3D images taken with a x60 objective

4 channels:
  1. IB4/lectine vessels
  2. ERG endothelial cells
  3. IB1 microglia cells
  4. DAPI nuclei

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
