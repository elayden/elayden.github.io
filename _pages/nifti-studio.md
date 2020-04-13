---
permalink: /software/nifti-studio/
title: "NIfTI Studio"
classes: smaller_font
author_profile: true
header:
  overlay_image: /assets/images/seattle-night.jpg
  caption: "Photo credit: [**Timothy Eberly on Unsplash**](https://unsplash.com/photos/h3vT1-T2nfc)"
  actions:
    - label: "Github"
      url: "https://github.com/elayden/NIfTI-Studio"
    - label: "Cite"
      url: "http://doi.org/10.5281/zenodo.3725006"
---
[NIfTI Studio](https://elliotlayden.com/nifti-studio) is an open-source Matlab toolbox for NIfTI and Analyze (img/hdr) image visualization, editing, and 3D rendering. This toolbox was used to manually trace regions of interest (ROIs) for our custom zebra finch brain template in Layden et al. (2019), and also to create figures for several papers. Below are some example use cases for the toolbox:

### 3D rendering of the human MNI brain template with regions of interest (ROIs) [[Code](https://github.com/elayden/NIfTI-Studio/blob/master/examples/human_example.m)]
![3D Human Brain](/assets/images/nifti-studio/human_brain_3d_rois_connections.jpg)

### Mosaic of slices from the human MNI brain template with segmented grey matter [[Code](https://github.com/elayden/NIfTI-Studio/blob/master/examples/human_example.m)]
![Human Brain Mosaic](/assets/images/nifti-studio/human_brain_mosaic_axial.jpg)

### A 3D rendering of a zebra finch brain template with embedded ROIs [[Code](https://github.com/elayden/NIfTI-Studio/blob/master/examples/zebra_finch_example.m)]
![Zebra Finch Brain Mosaic](/assets/images/nifti-studio/zebra_finch_brain_3d_rois_connections.jpg)
  
### Slice mosaic of zebra finch brain template with ROIs [[Code](https://github.com/elayden/NIfTI-Studio/blob/master/examples/zebra_finch_example.m)]
![Zebra Finch Example - Mosaic](/assets/images/nifti-studio/zebra_finch_brain_mosaic_coronal.jpg)
