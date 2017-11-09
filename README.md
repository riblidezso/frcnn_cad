# Computer aided detection with Faster-RCNN


A VGG16 based Faster-RCNN detector trained to detect breast cancer lesions on mammogram images.

For more details and results please see the article on arXiv: https://arxiv.org/abs/1707.08401

---

### Model weights

Model weights can de downloaded from here, the models is licensed with Creative Commons Attribution + Noncommercial + ShareAlike license [![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
- http://dkrib.web.elte.hu/cad_faster_rcnn/vgg16_frcnn_cad.caffemodel


---

### OsiriX/Horos plugin

I wrote a plugin for the popular medical image viewer: OsiriX/Horos. This is a simplified version of the model. It is based on CoreML. In order to run it you will need:
- A mac
- High Sierra (10.13) operating system ( becase of CoreML )
- OsiriX/Horos medical image viewer.

Just download the plugin, unzip it, click on the installer, and approve it. Restart OsiriX/Horos. The plugin will appear in the menu of OsiriX/Horos: Plugins/Image Filters/CnnCAD. You can also add it to the toolbar of the 2D viewer.

Note: Now the plugin only works correctly with Horos!

The OsiriX/Horos can be downloaded from here.  The plugin is licensed with Creative Commons Attribution + Noncommercial + ShareAlike license [![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
- DISCLAIMER: NOT FOR MEDICAL USE!!! THE PLUGIN IS FOR DEMONSTRATION/RESEARCH/EDUCATION PURPUSES ONLY!
- http://dkrib.web.elte.hu/cad_faster_rcnn/CnnCAD.osirixplugin.zip



---

If you want to use the model or the plugin in your research please cite:
> Ribli, Dezső, et al. "Detecting and classifying lesions in mammograms with Deep Learning." arXiv preprint arXiv:1707.08401 (2017).
