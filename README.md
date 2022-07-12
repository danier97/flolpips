# FloLPIPS: A bespoke video quality metric for frame interpoation

### Duolikun Danier, Fan Zhang, David Bull


[Project](https://danielism97.github.io/FloLPIPS) | [Paper](TODO)


## Dependencies
The following packages were used to evaluate the model.

- python==3.8.8
- pytorch==1.7.1
- torchvision==0.8.2
- cudatoolkit==10.1.243
- opencv-python==4.5.1.48
- numpy==1.19.2
- pillow==8.1.2
- cupy==9.0.0


## Usage
```python
from flolpips import calc_flolpips
ref_video = '<path to the reference>.mp4'
dis_video = '<path to the distorted>.mp4'
res = calc_flolpips(dis_video, ref_video)
```


<!-- ## Citation
```
@InProceedings{Danier_2022_CVPR,
    author    = {Danier, Duolikun and Zhang, Fan and Bull, David},
    title     = {ST-MFNet: A Spatio-Temporal Multi-Flow Network for Frame Interpolation},
    booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
    month     = {June},
    year      = {2022},
    pages     = {3521-3531}
}
``` -->

## Acknowledgement
Lots of code in this repository are adapted/taken from the following repositories:

- [LPIPS](https://github.com/richzhang/PerceptualSimilarity)
- [pytorch-pwc](https://github.com/sniklaus/pytorch-pwc)

We would like to thank the authors for sharing their code.