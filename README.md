# Adv-2024

## CVPR2024
| Title | Link | Abstract |
| --- | --- | --- |
| Robust Image Denoising through Adversarial Frequency Mixup | [paper](https://openaccess.thecvf.com/content/CVPR2024/html/Ryou_Robust_Image_Denoising_through_Adversarial_Frequency_Mixup_CVPR_2024_paper.html) | Image denoising approaches based on deep neural networks often struggle with overfitting to specific noise distributions present in training data. This challenge persists in existing real-world denoising networks which are trained using a limited spectrum of real noise distributions and thus show poor robustness to out-of-distribution real noise types. To alleviate this issue we develop a novel training framework called Adversarial Frequency Mixup (AFM). AFM leverages mixup in the frequency domain to generate noisy images with distinctive and challenging noise characteristics all the while preserving the properties of authentic real-world noise. Subsequently incorporating these noisy images into the training pipeline enhances the denoising network's robustness to variations in noise distributions. Extensive experiments and analyses conducted on a wide range of real noise benchmarks demonstrate that denoising networks trained with our proposed framework exhibit significant improvements in robustness to unseen noise distributions. The code is available at https://github.com/dhryougit/AFM.|
| Towards Robust 3D Pose Transfer with Adversarial Learning | [paper](https://openaccess.thecvf.com/content/CVPR2024/html/Chen_Towards_Robust_3D_Pose_Transfer_with_Adversarial_Learning_CVPR_2024_paper.html) | 3D pose transfer that aims to transfer the desired pose to a target mesh is one of the most challenging 3D generation tasks. Previous attempts rely on well-defined parametric human models or skeletal joints as driving pose sources. However to obtain those clean pose sources cumbersome but necessary pre-processing pipelines are inevitable hindering implementations of the real-time applications. This work is driven by the intuition that the robustness of the model can be enhanced by introducing adversarial samples into the training leading to a more invulnerable model to the noisy inputs which even can be further extended to directly handling the real-world data like raw point clouds/scans without intermediate processing. Furthermore we propose a novel 3D pose Masked Autoencoder (3D-PoseMAE) a customized MAE that effectively learns 3D extrinsic presentations (i.e. pose). 3D-PoseMAE facilitates learning from the aspect of extrinsic attributes by simultaneously generating adversarial samples that perturb the model and learning the arbitrary raw noisy poses via a multi-scale masking strategy. Both qualitative and quantitative studies show that the transferred meshes given by our network result in much better quality. Besides we demonstrate the strong generalizability of our method on various poses different domains and even raw scans. Experimental results also show meaningful insights that the intermediate adversarial samples generated in the training can successfully attack the existing pose transfer models. |

## ECCV2024
| Title | Link | Abstract |
| --- | --- | --- |
| - | - | - |

## MM2024
| Title | Link | Abstract |
| --- | --- | --- |
| - | - | - |

## ICLR2024
| Title | Link | Abstract |
| --- | --- | --- |
| - | - | - |
