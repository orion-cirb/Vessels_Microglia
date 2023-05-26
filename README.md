# Vessels_Microglia

**Developed for:** Nicolas

**Team:** Garel

**Date:** May 2023

**Software:** Fiji

### Images description

3D images taken with a x60 objective

2 channels:
  1.  Vessels
  2.  Endothelial cells
  3. Microglia
  4. Nucleus

With each image should be provided *.zip* file containing one or multiple ROI(s).

### Plugin description

* Normalize images with quantile-based normalization
* Detect Vessels with Weka (vessels.model) + Huang threshold + median
* Detect microglia cells with Weka (microglia.model)
* Compute distance microglia cells to vessel
* compute nb branches, end points, junctions, mean diameter for vessels etc ...



### Dependencies

* **3DImageSuite** Fiji plugin

* **Weka pixel classifier** 
 

### Version history

Version 1 released on May 25, 2023.
