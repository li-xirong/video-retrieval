# video-retrieval
Deep Learning for Video Retrieval by Natural Language

![image](overview.jpg)


## [Dataset](https://github.com/li-xirong/avs)

### Frame-level features
| CNN feature | Dimensionality | Downloads |
|:----- | -----:|:----- |
| ResNext-101 | 2,048 | [IACC.3 (27GB)](http://39.104.114.128/avs/iacc.3_ResNext-101.tar.gz), [MSR-VTT (2GB)](http://39.104.114.128/avs/msrvtt10k_ResNext-101.tar.gz), [TGIF (7GB)](http://39.104.114.128/avs/tgif_ResNext-101.tar.gz), [MSVD (288M)](http://39.104.114.128/avs/msvd_ResNext-101.tar.gz), [TV2016VTT-train (42M)](http://39.104.114.128/avs/tv2016train_ResNext-101.tar.gz) |
| ResNet-152 | 2,048 | [IACC.3 (26GB)](http://39.104.114.128/avs/iacc.3_ResNet-152.tar.gz), [MSR-VTT (2GB)](http://39.104.114.128/avs/msrvtt10k_ResNet-152.tar.gz), [TGIF (7GB)](http://39.104.114.128/avs/tgif_ResNet-152.tar.gz), [MSVD (283M)](http://39.104.114.128/avs/msvd_ResNet-152.tar.gz), [TV2016VTT-train (42M)](http://39.104.114.128/avs/tv2016train_ResNet-152.tar.gz) |

### Video-level features
* [Google drive](https://drive.google.com/drive/folders/1XiCudpjZVAUUg41TSB-u_HZE6qVnJpxC)

### Sentences 
* [MSR-VTT (3MB)](http://39.104.114.128/avs/msrvtt10k_textdata.tar.gz)
* [TGIF (2MB)](http://39.104.114.128/avs/tgif_textdata.tar.gz) 
* [MSVD (945K)](http://39.104.114.128/avs/msvd_textdata.tar.gz)
* [TV2016VTT-train (11K)](http://39.104.114.128/avs/tv2016train_textdata.tar.gz)


## Methods
[W2VV](https://github.com/danieljf24/w2vv)
[W2VV++](https://github.com/li-xirong/w2vvpp)
[Dual encoding](https://github.com/danieljf24/dual_encoding)

## References
```
@article{dong2018predicting,
  title={Predicting visual features from text for image and video caption retrieval},
  author={Jianfeng Dong and Xirong Li and Cees G. M. Snoek},
  journal={IEEE Transactions on Multimedia},
  volume={20},
  number={12},
  pages={3377-3388},
  year={2018},
  doi = {10.1109/TMM.2018.2832602},
}
```

```
@inproceedings{mm19-w2vvpp,
title = {{W2VV}++: Fully Deep Learning for Ad-hoc Video Search},
author = {Xirong Li and Chaoxi Xu and Gang Yang and Zhineng Chen and Jianfeng Dong},
year = {2019},
booktitle = {ACMMM},
}
```

```
@inproceedings{cvpr2019-dual-dong,
title = {Dual Encoding for Zero-Example Video Retrieval},
author = {Jianfeng Dong and Xirong Li and Chaoxi Xu and Shouling Ji and Yuan He and Gang Yang and Xun Wang},
booktitle = {IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
year = {2019},
}
```