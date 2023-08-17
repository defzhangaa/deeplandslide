# deeplandslideDS
This is the source codebase for A Deep Evidence-theoretic Remote Sensing Landslide Image Classification Framework with A New Belief Divergence, Multi-scale Visual Saliency and An Improved Three-branched Fusion Model. 

**IMPORTANT**: The experiments of this paper can be repeated on your platform with the following steps: 

1. Download the Bijie landslide image dataset, which is avaliable in [1] at http://gpcv.whu.edu.cn/data/Bijie_pages.html . 

2. Use the source code for multi-scale visual saliency (multiscale_saliency_grad.m). Then the remote sensing images after channel-wise fusion can be avaliable.  

3. Train the deep neural networks using fused images with the source code (this paper did not make improvements on network strucures but using previous SOTA networks as simple tools) and initial weights in OpenMMLab's Image Classification Toolbox and Benchmark, which is avaliable at https://github.com/open-mmlab/mmclassification . 

4. Fuse the decisions from deep neural networks with the proposed three-branched fusion model. 

[1] Ji, S., Yu, D., Shen, C., Li, W., & Xu, Q. Landslide detection from an open satellite imagery and digital elevation model dataset using attention boosted convolutional neural networks. Landslides, 1-16, 2020. 
