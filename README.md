# Adv-2024

## CVPR2024
| Title | Link | Abstract |
| --- | --- | --- |
| Robust Image Denoising through Adversarial Frequency Mixup | [paper](https://openaccess.thecvf.com/content/CVPR2024/html/Ryou_Robust_Image_Denoising_through_Adversarial_Frequency_Mixup_CVPR_2024_paper.html) | Image denoising approaches based on deep neural networks often struggle with overfitting to specific noise distributions present in training data. This challenge persists in existing real-world denoising networks which are trained using a limited spectrum of real noise distributions and thus show poor robustness to out-of-distribution real noise types. To alleviate this issue we develop a novel training framework called Adversarial Frequency Mixup (AFM). AFM leverages mixup in the frequency domain to generate noisy images with distinctive and challenging noise characteristics all the while preserving the properties of authentic real-world noise. Subsequently incorporating these noisy images into the training pipeline enhances the denoising network's robustness to variations in noise distributions. Extensive experiments and analyses conducted on a wide range of real noise benchmarks demonstrate that denoising networks trained with our proposed framework exhibit significant improvements in robustness to unseen noise distributions. The code is available at https://github.com/dhryougit/AFM.|
| Towards Robust 3D Pose Transfer with Adversarial Learning | [paper](https://openaccess.thecvf.com/content/CVPR2024/html/Chen_Towards_Robust_3D_Pose_Transfer_with_Adversarial_Learning_CVPR_2024_paper.html) | 3D pose transfer that aims to transfer the desired pose to a target mesh is one of the most challenging 3D generation tasks. Previous attempts rely on well-defined parametric human models or skeletal joints as driving pose sources. However to obtain those clean pose sources cumbersome but necessary pre-processing pipelines are inevitable hindering implementations of the real-time applications. This work is driven by the intuition that the robustness of the model can be enhanced by introducing adversarial samples into the training leading to a more invulnerable model to the noisy inputs which even can be further extended to directly handling the real-world data like raw point clouds/scans without intermediate processing. Furthermore we propose a novel 3D pose Masked Autoencoder (3D-PoseMAE) a customized MAE that effectively learns 3D extrinsic presentations (i.e. pose). 3D-PoseMAE facilitates learning from the aspect of extrinsic attributes by simultaneously generating adversarial samples that perturb the model and learning the arbitrary raw noisy poses via a multi-scale masking strategy. Both qualitative and quantitative studies show that the transferred meshes given by our network result in much better quality. Besides we demonstrate the strong generalizability of our method on various poses different domains and even raw scans. Experimental results also show meaningful insights that the intermediate adversarial samples generated in the training can successfully attack the existing pose transfer models. |
| Structure-Guided Adversarial Training of Diffusion Models | [paper](https://openaccess.thecvf.com/content/CVPR2024/html/Yang_Structure-Guided_Adversarial_Training_of_Diffusion_Models_CVPR_2024_paper.html) | Diffusion models have demonstrated exceptional efficacy in various generative applications. While existing models focus on minimizing a weighted sum of denoising score matching losses for data distribution modeling their training primarily emphasizes instance-level optimization overlooking valuable structural information within each mini-batch indicative of pair-wise relationships among samples. To address this limitation we introduce Structure-guided Adversarial training of Diffusion Models (SADM). In this pioneering approach we compel the model to learn manifold structures between samples in each training batch. To ensure the model captures authentic manifold structures in the data distribution we advocate adversarial training of the diffusion generator against a novel structure discriminator in a minimax game distinguishing real manifold structures from the generated ones. SADM substantially outperforms existing methods in image generation and cross-domain fine-tuning tasks across 12 datasets establishing a new state-of-the-art FID of 1.58 and 2.11 on ImageNet for class-conditional image generation at resolutions of 256x256 and 512x512 respectively. |
| Adversarial Text to Continuous Image Generation | [paper](https://openaccess.thecvf.com/content/CVPR2024/html/Haydarov_Adversarial_Text_to_Continuous_Image_Generation_CVPR_2024_paper.html) | Existing GAN-based text-to-image models treat images as 2D pixel arrays. In this paper we approach the text-to-image task from a different perspective where a 2D image is represented as an implicit neural representation (INR). We show that straightforward conditioning of the unconditional INR-based GAN method on text inputs is not enough to achieve good performance. We propose a word-level attention-based weight modulation operator that controls the generation process of INR-GAN based on hypernetworks. Our experiments on benchmark datasets show that HyperCGAN achieves competitive performance to existing pixel-based methods and retains the properties of continuous generative models. |
| ASAM: Boosting Segment Anything Model with Adversarial Tuning | [paper](https://openaccess.thecvf.com/content/CVPR2024/html/Li_ASAM_Boosting_Segment_Anything_Model_with_Adversarial_Tuning_CVPR_2024_paper.html) | In the evolving landscape of computer vision foundation models have emerged as pivotal tools exhibiting exceptional adaptability to a myriad of tasks. Among these the Segment Anything Model (SAM) by Meta AI has distinguished itself in image segmentation. However SAM like its counterparts encounters limitations in specific niche applications prompting a quest for enhancement strategies that do not compromise its inherent capabilities. This paper introduces ASAM a novel methodology that amplifies SAM's performance through adversarial tuning. We harness the potential of natural adversarial examples inspired by their successful implementation in natural language processing. By utilizing a stable diffusion model we augment a subset (1%) of the SA-1B dataset generating adversarial instances that are more representative of natural variations rather than conventional imperceptible perturbations. Our approach maintains the photorealism of adversarial examples and ensures alignment with original mask annotations thereby preserving the integrity of the segmentation task. The fine-tuned ASAM demonstrates significant improvements across a diverse range of segmentation tasks without necessitating additional data or architectural modifications. The results of our extensive evaluations confirm that ASAM establishes new benchmarks in segmentation tasks thereby contributing to the advancement of foundational models in computer vision. Our project page is in https://asam2024.github.io/. |
| Adversarial Score Distillation: When score distillation meets GAN | [paper](https://openaccess.thecvf.com/content/CVPR2024/html/Wei_Adversarial_Score_Distillation_When_score_distillation_meets_GAN_CVPR_2024_paper.html) | Existing score distillation methods are sensitive to classifier-free guidance (CFG) scale manifested as over-smoothness or instability at small CFG scales while over-saturation at large ones. To explain and analyze these issues we revisit the derivation of Score Distillation Sampling (SDS) and decipher existing score distillation with the Wasserstein Generative Adversarial Network (WGAN) paradigm. With the WGAN paradigm we find that existing score distillation either employs a fixed sub-optimal discriminator or conducts incomplete discriminator optimization resulting in the scale-sensitive issue. We propose the Adversarial Score Distillation (ASD) which maintains an optimizable discriminator and updates it using the complete optimization objective. Experiments show that the proposed ASD performs favorably in 2D distillation and text-to-3D tasks against existing methods. Furthermore to explore the generalization ability of our paradigm we extend ASD to the image editing task which achieves competitive results. The project page and code are at https://github.com/2y7c3/ASD |
| ACT-Diffusion: Efficient Adversarial Consistency Training for One-step Diffusion Models | [paper](https://openaccess.thecvf.com/content/CVPR2024/html/Kong_ACT-Diffusion_Efficient_Adversarial_Consistency_Training_for_One-step_Diffusion_Models_CVPR_2024_paper.html) | Though diffusion models excel in image generation their step-by-step denoising leads to slow generation speeds. Consistency training addresses this issue with single-step sampling but often produces lower-quality generations and requires high training costs. In this paper we show that optimizing consistency training loss minimizes the Wasserstein distance between target and generated distributions. As timestep increases the upper bound accumulates previous consistency training losses. Therefore larger batch sizes are needed to reduce both current and accumulated losses. We propose Adversarial Consistency Training (ACT) which directly minimizes the Jensen-Shannon (JS) divergence between distributions at each timestep using a discriminator. Theoretically ACT enhances generation quality and convergence. By incorporating a discriminator into the consistency training framework our method achieves improved FID scores on CIFAR10 and ImageNet 64x64 and LSUN Cat 256x256 datasets retains zero-shot image inpainting capabilities and uses less than 1/6 of the original batch size and fewer than 1/2 of the model parameters and training steps compared to the baseline method this leads to a substantial reduction in resource consumption. Our code is available: https://github.com/kong13661/ACT |

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
