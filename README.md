<img src="https://github.com/kritiksoman/tmp/blob/master/cover.png" width="1280" height="180"> <br>
# Semantics for GNU Image Manipulation Program
### [<img src="https://github.com/kritiksoman/tmp/blob/master/yt.png" width="70" height="50">](https://www.youtube.com/channel/UCzZn99R6Zh0ttGqvZieT4zw) [<img src="https://github.com/kritiksoman/tmp/blob/master/inst.png" width="50" height="50">](https://www.instagram.com/explore/tags/gimpml/) [<img src="https://github.com/kritiksoman/tmp/blob/master/arxiv.png" width="100" height="50">](https://arxiv.org/abs/2004.13060) [<img src="https://github.com/kritiksoman/tmp/blob/master/manual.png" width="100" height="50">](https://github.com/kritiksoman/GIMP-ML/wiki/User-Manual) [<img src="https://github.com/kritiksoman/tmp/blob/master/ref.png" width="100" height="50">](https://github.com/kritiksoman/GIMP-ML/wiki/References) [<img src="https://github.com/kritiksoman/tmp/blob/master/wiki.png" width="100" height="30">](https://en.wikipedia.org/wiki/GIMP#Extensions)<br>
 
:star: :star: :star: :star: are welcome. New tools will be added and existing will be improved with time.<br>

Updates: <br>
[October 17] Added image enlightening. (Existing users should be able to update.)<br>
[September 27] Added Force CPU use button and minor bug fixes. <br>
[August 28] Added deep learning based dehazing and denoising. <br>
[August 25] Simplified installation and updating method. <br>
[August 2] Added deep matting and k-means. <br>
[July 17] MonoDepth and Colorization models have been updated. <br>

# Screenshot of Menu
![image1](https://github.com/kritiksoman/tmp/blob/master/screenshot.png)

# Installation Steps
[1] Install [GIMP](https://www.gimp.org/downloads/) 2.10.<br>
[2] Clone this repository: git clone https://github.com/kritiksoman/GIMP-ML.git <br>
[3] Open terminal, go to GIMP-ML/gimp-plugins and run : <br>
    ```bash installGimpML.sh```<br>
[4] Open GIMP and go to Preferences -> Folders -> Plug-ins, add the folder gimp-plugins and restart GIMP. <br>
[5] Go to Layer->GIMP-ML->update, click on ok with "update weights" set to yes and restart GIMP. (Weights ~ 1.5GB will be downloaded)<br>
Manual install description if above is not working: [Link](https://github.com/kritiksoman/GIMP-ML/blob/master/INSTALLATION.md) <br>

# Update Steps
[1] Go to Layer->GIMP-ML->update, click on ok with "update weights" set to NO and restart GIMP. <br>
[2] Go to Layer->GIMP-ML->update, click on ok with "update weights" set to YES and restart GIMP. <br>

# Citation
Please cite using the following bibtex entry:

```
@article{soman2020GIMPML,
  title={GIMP-ML: Python Plugins for using Computer Vision Models in GIMP},
  author={Soman, Kritik},
  journal={arXiv preprint arXiv:2004.13060},
  year={2020}
}
```

# Tools
| Name | License | Dataset |
| ------------- |:-------------:| :-------------:| 
| facegen | [CC BY-NC-SA 4.0](https://github.com/switchablenorms/CelebAMask-HQ#dataset-agreement) | CelebAMask-HQ |
| deblur | [BSD 3-clause](https://github.com/VITA-Group/DeblurGANv2/blob/master/LICENSE) | GoPro |
| faceparse | [MIT](https://github.com/zllrunning/face-parsing.PyTorch/blob/master/LICENSE) | CelebAMask-HQ |
| deepcolor | [MIT](https://github.com/junyanz/interactive-deep-colorization/blob/master/LICENSE) | ImageNet |
| monodepth | [MIT](https://github.com/intel-isl/MiDaS/blob/master/LICENSE) | [Multiple](https://arxiv.org/pdf/1907.01341v3.pdf) |
| super-resolution | [MIT](https://github.com/twtygqyy/pytorch-SRResNet/blob/master/LICENSE) | ImageNet |
| deepmatting | [Non-commercial purposes](https://github.com/poppinace/indexnet_matting/blob/master/Adobe%20Deep%20Image%20Mattng%20Dataset%20License%20Agreement.pdf) | Adobe Deep Image Matting |
| semantic-segmentation | MIT | COCO |
| kmeans | [BSD](https://github.com/scipy/scipy/blob/master/LICENSE.txt) | - |
| deep-dehazing | [MIT](https://github.com/MayankSingal/PyTorch-Image-Dehazing/blob/master/LICENSE) | [Custom](https://sites.google.com/site/boyilics/website-builder/project-page) |
| deep-denoising | [GPL3](https://github.com/SaoYan/DnCNN-PyTorch/blob/master/LICENSE) | BSD68 |
| enlighten | [BSD](https://github.com/VITA-Group/EnlightenGAN/blob/master/License) | [Custom](https://arxiv.org/pdf/1906.06972.pdf) |
