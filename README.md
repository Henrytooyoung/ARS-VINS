# ARS-VINS: Adaptive Region Selection for Robust Visual-Inertial Localization

## About
ARS-VINS is a Robust Visual-Inertial Localization Approach leveraging Adaptive Region Selection. This project enhances the state-of-the-art VINS-Mono algorithm with an Adaptive Region Selection (ARS) network that intelligently selects stable feature regions, effectively improving feature extraction in challenging environments such as underground pipelines.

**Note: The source code for this project will be made public following the publication of our research paper.**

## Abstract
Visual SLAM plays a crucial role in the automation of underground pipeline inspection. However, images captured under pipeline conditions pose a significant challenge for Visual SLAM systems due to high noise levels and weak features. Existing methods struggle to suppress noise while preserving weak features, as the denoising process often inadvertently removes useful weak feature information. On the other hand, increasing the sensitivity of feature extraction algorithms to detect weak features can lead to noise being mistakenly identified as features. 

To address these limitations, we propose ARS-VINS, a Robust Visual-Inertial Localization Approach leveraging Adaptive Region Selection. ARS-VINS enhances the state-of-the-art VINS-Mono algorithm with an Adaptive Region Selection (ARS) network that intelligently selects stable feature regions. This approach effectively reduces noise while preserving weak but critical features, improving feature extraction in challenging environments. 

We also introduce DualPipe, a specialized dataset containing visual-inertial data and semantic annotations for developing and comprehensively evaluating SLAM systems under realistic pipeline conditions. We evaluate the accuracy and computational efficiency of ARS-VINS against existing state-of-the-art SLAM algorithms on the DualPipe dataset. 

Our results show that in low-noise conditions, ARS-VINS achieves an RMSE of 0.3158, outperforming the next best method, VINS-Mono (RMSE 0.3344), by 5.6%. More significantly, in challenging high-noise environments, ARS-VINS maintains robust performance with an RMSE of 0.3245, surpassing VINS-Mono (RMSE 0.5428) by 40.2%, while maintaining comparable real-time performance at 10 Hz.

## Future Updates
- Source code will be released upon paper publication
- DualPipe dataset will be made available for research purposes
- Documentation and usage instructions will be provided

Stay tuned for updates!

## Contact
For any inquiries, please open an issue in this repository.
