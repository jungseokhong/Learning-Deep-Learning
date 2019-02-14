# Paper notes
This repository contains my paper reading notes on deep learning and machine learning. **New year resolution for 2019: read at least one paper a week!**

## Summary of Topics

| Topics                                                  | Description                 |
| ------------------------------------------------------------ | --------------------------- |
| <kbd>DRL</kbd>                                               | Deep Reinforcement Learning |
| <kbd>CLS</kbd>                                                | Classification               |
| <kbd>OD</kbd>                                                | Object Detection            |
| <kbd>InsSeg</kbd>, <kbd>SemSeg</kbd>, <kbd>PanSeg</kbd> | Instance/Semantic/Panoptic Segmentation |
| <kbd>Video</kbd> | Video understanding |
| <kbd>MI</kbd> | Medical Imaging |
| <kbd>GAN</kbd> | Generative Adversarial Network |
| <kbd>NIPS</kbd>, <kbd>CVPR</kbd>, <kbd>ICCV</kbd>, <kbd>ECCV</kbd>, etc | Conference papers           |


## 2019-02
- [Quo Vadis, Action Recognition? A New Model and the Kinetics Dataset](https://arxiv.org/pdf/1705.07750.pdf) (I3D) [[Notes](paper_notes/quo_vadis_i3d.md)]<kbd>Video</kbd> <kbd>CVPR 2017</kbd>
- [Initialization Strategies of Spatio-Temporal Convolutional Neural Networks](https://arxiv.org/pdf/1503.07274.pdf) [[Notes](paper_notes/quo_vadis_i3d.md)]
- [Detect-and-Track: Efficient Pose Estimation in Videos](https://arxiv.org/pdf/1712.09184.pdf) [[Notes](paper_notes/quo_vadis_i3d.md)] <kbd>ICCV 2017</kbd>
- [Deep Learning Based Rib Centerline Extraction and Labeling](https://arxiv.org/pdf/1809.07082) [[Notes](paper_notes/rib_centerline_philips.md)] <kbd>MI</kbd> <kbd>MICCAI 2018</kbd>
- [SlowFast Networks for Video Recognition](https://arxiv.org/pdf/1812.03982.pdf) [[Notes](paper_notes/slowfast.md)]


## 2019-01
- [Human-level control through deep reinforcement learning (Nature DQN paper)](https://storage.googleapis.com/deepmind-media/dqn/DQNNaturePaper.pdf) [[Notes](paper_notes/nature_dqn_paper.md)] <kbd>DRL</kbd>
- [Retina U-Net: Embarrassingly Simple Exploitation of Segmentation Supervision for Medical Object Detection](https://arxiv.org/pdf/1811.08661.pdf) [[Notes](paper_notes/retina_unet.md)] <kbd>MI</kbd>
- [Panoptic Segmentation](https://arxiv.org/pdf/1801.00868.pdf) [[Notes](paper_notes/panoptic_segmentation.md)] <kbd>PanSeg</kbd>
- [Panoptic Feature Pyramid Networks](https://arxiv.org/pdf/1901.02446.pdf) [[Notes](paper_notes/panoptic_fpn.md)] <kbd>PanSeg</kbd> 
- [Attention-guided Unified Network for Panoptic Segmentation](https://arxiv.org/pdf/1812.03904.pdf) [[Notes](paper_notes/AUNet_panoptic.md)] <kbd>PanSeg</kbd>
- [Bag of Tricks for Image Classification with Convolutional Neural Networks](https://arxiv.org/pdf/1812.01187.pdf) [[Notes](paper_notes/bag_of_tricks_cnn.md)] <kbd>CLS</kbd>
- [Deep Reinforcement Learning for Vessel Centerline Tracing in Multi-modality 3D Volumes](https://link.springer.com/chapter/10.1007/978-3-030-00937-3_86) [[Notes](paper_notes/drl_vessel_centerline.md)] <kbd>DRL</kbd> <kbd>MI</kbd>
- [Deep Reinforcement Learning for Flappy Bird](http://cs229.stanford.edu/proj2015/362_report.pdf) [[Notes](paper_notes/drl_flappy.md)] <kbd>DRL</kbd>
- [Long-Term Feature Banks for Detailed Video Understanding](https://arxiv.org/pdf/1812.05038.pdf) [[Notes](paper_notes/long_term_feat_bank.md)] <kbd>Video</kbd> 
- [Non-local Neural Networks](https://arxiv.org/pdf/1711.07971.pdf) [[Notes](paper_notes/non_local_net.md)] <kbd>Video</kbd> <kbd>CVPR 2018</kbd>


## 2018
- [Mask R-CNN](https://arxiv.org/pdf/1703.06870.pdf)
- [Cascade R-CNN: Delving into High Quality Object Detection](https://arxiv.org/pdf/1712.00726.pdf)
- [Focal Loss for Dense Object Detection](https://arxiv.org/pdf/1708.02002.pdf) (RetinaNet)
- [Squeeze-and-Excitation Networks](https://arxiv.org/pdf/1709.01507)
- [Progressive Growing of GANs for Improved Quality, Stability, and Variation](https://arxiv.org/pdf/1710.10196.pdf)
- [Deformable Convolutional Networks](https://arxiv.org/pdf/1703.06211.pdf)
- [Learning Region Features for Object Detection](https://arxiv.org/pdf/1803.07066.pdf)

## 2017 and before
- [Learning notes on Deep Learning](Learning_notes.md)
- [List of Papers on Machine Learning](List_of_Machine_Learning_Papers.md)
- [Notes of Literature Review on CNN in CV](paper_notes/cnn_papers.md) This is the notes for all the papers in the recommended list [here](papers_and_books_to_start.md)
- [Notes of Literature Review (Others)](misc.md)
- [Notes on how to set up DL/ML environment](ML_DL_environment_Setup.md)
- [Useful setup notes](installation_log.md)

## Papers to Read
Here is the list of papers waiting to be read. 
### Deep Learning in general
- [Aggregated Residual Transformations for Deep Neural Networks](https://arxiv.org/pdf/1611.05431.pdf) (ResNeXt)
- [Accurate, Large Minibatch SGD: Training ImageNet in 1 Hour](https://arxiv.org/pdf/1706.02677.pdf)
- [ImageNet-trained CNNs are biased towards texture; increasing shape bias improves accuracy and robustness](https://openreview.net/forum?id=Bygh9j09KX)
- [Approximating CNNs with Bag-of-local-Features models works surprisingly well on ImageNet](https://openreview.net/forum?id=SkfMWhAqYQ) (BagNet) [blog](https://blog.evjang.com/2019/02/bagnet.html)

### Object detection
- [Training Region-based Object Detectors with Online Hard Example Mining](https://arxiv.org/pdf/1604.03540.pdf)

### Instance and Panoptic Segmentation
- [Path Aggregation Network for Instance Segmentation](https://arxiv.org/pdf/1803.01534.pdf)

### Video Understanding
- [Learning Spatiotemporal Features with 3D Convolutional Networks](https://arxiv.org/pdf/1412.0767.pdf) (C3D)  <kbd> Video </kbd><kbd> ICCV 2015 </kbd>
- [AVA: A Video Dataset of Spatio-temporally Localized Atomic Visual Actions](https://arxiv.org/pdf/1705.08421.pdf)
- [Spatiotemporal Residual Networks for Video Action Recognition](https://arxiv.org/pdf/1611.02155.pdf) (decouple spatiotemporal) <kbd>NIPS 2016</kbd>
- [Learning Spatio-Temporal Representation with Pseudo-3D Residual Networks](https://arxiv.org/pdf/1711.10305.pdf) (P3D, decouple spatiotemporal) <kbd> ICCV 2017 </kbd>
- [A Closer Look at Spatiotemporal Convolutions for Action Recognition](https://arxiv.org/pdf/1711.11248.pdf) (decouple spatiotemporal) <kbd>CVPR 2018</kbd>
- [Rethinking Spatiotemporal Feature Learning: Speed-Accuracy Trade-offs in Video Classification](https://arxiv.org/pdf/1712.04851.pdf) (decouple spatiotemporal) <kbd>ECCV 2018</kbd>

### Medical Imaging
- [nnU-Net: Self-adapting Framework for U-Net-Based Medical Image Segmentation](https://arxiv.org/pdf/1809.10486.pdf)
- [Foveal fully convolutional nets for multi-organ segmentation](https://www.dropbox.com/s/zcmqheb0cbwsxq0/Foveal%20fully%20convolutional%20nets%20for%20multi-organ%20segmentation.pdf?dl=0)
- [Evaluation of deep learning methods for parotid gland segmentation from CT images](https://www.spiedigitallibrary.org/journals/Journal-of-Medical-Imaging/volume-6/issue-1/011005/Evaluation-of-deep-learning-methods-for-parotid-gland-segmentation-from/10.1117/1.JMI.6.1.011005.pdf)
- [DeepMedic for Brain Tumor Segmentation](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/02/kamnitsas2016brats.pdf)
- [Attention U-Net: Learning Where to Look for the Pancreas](https://arxiv.org/pdf/1804.03999.pdf)
- [Attention-Gated Networks for Improving Ultrasound Scan Plane Detection](https://arxiv.org/pdf/1804.05338.pdf)
- [3D Context Enhanced Region-based Convolutional Neural Network for End-to-End Lesion Detection](https://arxiv.org/pdf/1806.09648.pdf)

### Orthoganal architecture improvements
- [Concurrent Spatial and Channel Squeeze & Excitation in Fully Convolutional Networks](https://arxiv.org/pdf/1803.02579.pdf)
- [CBAM: Convolutional Block Attention Module](https://arxiv.org/pdf/1807.06521.pdf)

### GAN

### Reinforcement Learning
- [Playing Atari with Deep Reinforcement Learning](https://www.cs.toronto.edu/~vmnih/docs/dqn.pdf) <kbd> NIPS 2013 </kbd>
- [Multi-Scale Deep Reinforcement Learning for Real-Time 3D-Landmark Detection in CT Scan](http://comaniciu.net/Papers/MultiscaleDeepReinforcementLearning_PAMI18.pdf)
- [An Artificial Agent for Robust Image Registration](https://www.aaai.org/ocs/index.php/AAAI/AAAI17/paper/download/14751/14296)
