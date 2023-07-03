# Diffusion Models in Vision: A Survey (accepted at IEEE TPAMI 2023)
Denoising diffusion models represent a recent emerging topic in computer vision, demonstrating remarkable results in the area of generative modeling. A diffusion model is a deep generative model that is based on two stages, a forward diffusion stage and a reverse diffusion stage. In the forward diffusion stage, the input data is gradually perturbed over several steps by adding Gaussian noise. In the reverse stage, a model is tasked at recovering the original input data by learning to gradually reverse the diffusion process, step by step. Diffusion models are widely appreciated for the quality and diversity of the generated samples, despite their known computational burdens, i.e. low speeds due to the high number of steps involved during sampling. This repository categorizes the papers about diffusion models, applied in computer vision, according to their target task. The classifcation is based on our survey [Diffusion Models in Vision: A Survey](https://arxiv.org/abs/2209.04747v2), which was accepted for publication in IEEE TPAMI.

## Summary

1. [Unconditional Generation](#1)
2. [Conditional Generation](#2)
3. [Text-to-Image generation ](#3)
4. [Super-Resolution ](#4)
5. [Image Editing](#5)
6. [Region Image Editing](#6)
7. [Inpainting](#7)
8. [Image-to-Image Translation](#8)
9. [Image Segmentation ](#9)
10. [Multi-Task](#10)
11. [Medical Image-to-Image Translation](#11)
12. [Medical Image Generation](#12)
13. [Medical Image Segmentation](#13)
14. [Medical Image Anomaly Detection](#14)
15. [Video Generation](#15)
16. [Few-Shot Image Generation ](#16)
17. [Counterfactual Explanations and Estimations](#17)
18. [Image Restoration](#18)
19. [Image Registration](#19)
20. [Adversarial Purification](#20)
21. [Semantic Image Generation](#21)
22. [Shape Generation and Completion](#22)
23. [Classification](#23)
24. [Point Cloud Generation](#24)
25. [Theoretical](#25)
26. [Graphs](#26)
27. [Deblurring](#27)
28. [Face Morphing Attack Detection](#28)
29. [Trajectory prediction](#29)
30. [Attacks](#30)
31. [Study on  data memorization](#31)

## Content

### Unconditional Generation <a name="1"></a>
  1. [Deep unsupervised learning using non-equilibrium thermodynamics](https://arxiv.org/pdf/1503.03585.pdf)
  2. [Denoising diffusion probabilistic models](https://arxiv.org/pdf/2006.11239.pdf)
  3. [Improved techniques for training score-based generative models](https://arxiv.org/pdf/2006.09011.pdf)
  4. [Adversarial score matching and improved sampling for image generation](https://arxiv.org/pdf/2009.05475.pdf)
  5. [Maximum likelihood training of score-based diffusion models](https://proceedings.neurips.cc/paper/2021/file/0a9fdbb17feb6ccb7ec405cfb85222c4-Paper.pdf)
  6. [D2C: Diffusion-Decoding Models for Few-Shot Conditional Generation](https://proceedings.neurips.cc/paper/2021/file/682e0e796084e163c5ca053dd8573b0c-Paper.pdf)
  7. [Diffusion Normalizing Flow](https://proceedings.neurips.cc/paper/2021/file/876f1f9954de0aa402d91bb988d12cd4-Paper.pdf)
  8. [Diffusion Schrodinger bridge with applications to score-based generative modeling](https://proceedings.neurips.cc/paper/2021/file/940392f5f32a7ade1cc201767cf83e31-Paper.pdf)
  9. [Structured denoising diffusion models in discrete state-spaces](https://proceedings.neurips.cc/paper/2021/file/958c530554f78bcd8e97125b70e6973d-Paper.pdf)
 10. [Score-based generative modeling in latent space](https://papers.nips.cc/paper/2021/file/5dca4c6b9e244d24a30b4c45601d9720-Paper.pdf)
 11. [Improved denoising diffusion probabilistic models](https://arxiv.org/pdf/2102.09672.pdf)
 12. [Denoising Diffusion Implicit Models](https://arxiv.org/pdf/2010.02502.pdf)
 13. [Non-Gaussian denoising diffusion models](https://arxiv.org/pdf/2106.07582.pdf)
 14. [Bilateral denoising diffusion models](https://arxiv.org/pdf/2108.11514.pdf)
 15. [Unleashing Transformers: Parallel Token Prediction with Discrete Absorbing Diffusion for Fast High-Resolution Image Generation from Vector-Quantized Codes](https://arxiv.org/pdf/2111.12701.pdf)
 16. [Noise estimation for generative diffusion models](https://arxiv.org/pdf/2104.02600.pdf)
 17. [Gotta go fast when generating data with score-based models](https://arxiv.org/pdf/2105.14080.pdf)
 18. [Learning to efficiently sample from diffusion probabilistic models](https://arxiv.org/pdf/2106.03802.pdf)
 19. [Deep generative learning via Schrodinger bridge](https://arxiv.org/pdf/2106.10410.pdf)
 20. [VAEs meet Diffusion Models: Efficient and High-Fidelity Generation](https://arxiv.org/pdf/2201.00308.pdf)
 21. [Variational diffusion models](https://arxiv.org/pdf/2107.00630.pdf)
 22. [Score-based generative modeling with critically-damped Langevin diffusion](https://arxiv.org/pdf/2112.07068.pdf)
 23. [Tackling the generative learning trilemma with Denoising Diffusion GANs](https://arxiv.org/pdf/2112.07804.pdf)
 24. [Heavy-tailed denoising score matching](https://arxiv.org/abs/2112.09788)
 25. [Analytic-DPM: an Analytic Estimate of the Optimal Reverse Variance in Diffusion Probabilistic Models](https://arxiv.org/pdf/2201.06503.pdf)
 26. [Learning Fast Samplers for Diffusion Models by Differentiating Through Sample Quality](https://arxiv.org/abs/2202.05830)
 27. [Truncated Diffusion Probabilistic Models](https://arxiv.org/abs/2202.09671)
 28. [Subspace Diffusion Generative Models](https://arxiv.org/abs/2205.01490)
 29. [Maximum Likelihood Training of Implicit Nonlinear Diffusion Models](https://arxiv.org/abs/2205.13699)
 30. [On Analyzing Generative and Denoising Capabilities of Diffusion-based Deep Generative Models](https://arxiv.org/abs/2206.00070)
 31. [Diffusion-GAN: Training GANs with Diffusion](https://arxiv.org/abs/2206.02262)
 32. [Accelerating Score-based Generative Models for High-Resolution Image Synthesis](https://arxiv.org/abs/2206.04029)
 33. [Soft Diffusion: Score Matching for General Corruptions](https://arxiv.org/pdf/2209.05442.pdf)
 34. [Post-Training Quantization on Diffusion Models](https://openaccess.thecvf.com/content/CVPR2023/papers/Shang_Post-Training_Quantization_on_Diffusion_Models_CVPR_2023_paper.pdf)
 35. [Lookahead Diffusion Probabilistic Models for Refining Mean Estimation](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhang_Lookahead_Diffusion_Probabilistic_Models_for_Refining_Mean_Estimation_CVPR_2023_paper.pdf)
 36. [Wavelet Diffusion Models are fast and scalable Image Generators](https://openaccess.thecvf.com/content/CVPR2023/papers/Phung_Wavelet_Diffusion_Models_Are_Fast_and_Scalable_Image_Generators_CVPR_2023_paper.pdf)
37. [All are Worth Words: A ViT Backbone for Diffusion Models](https://openaccess.thecvf.com/content/CVPR2023/papers/Bao_All_Are_Worth_Words_A_ViT_Backbone_for_Diffusion_Models_CVPR_2023_paper.pdf)
38. [Diffusion Probabilistic Model Made Slim](https://openaccess.thecvf.com/content/CVPR2023/papers/Yang_Diffusion_Probabilistic_Model_Made_Slim_CVPR_2023_paper.pdf)
### Conditional Generation <a name="2"></a>
  1. [Diffusion models beat gans on image synthesis](https://openreview.net/pdf?id=AAWuCvzaVt)
  2. [Classifier-Free Diffusion Guidance](https://openreview.net/pdf?id=qw8AKxfYbI)
  3. [On Fast Sampling of Diffusion Probabilistic Models](https://arxiv.org/pdf/2106.00132.pdf)
  4. [DiffuseVAE: Efficient, Controllable and High-Fidelity Generation from Low-Dimensional Latents](https://arxiv.org/pdf/2201.00308.pdf)
  5. [Pseudo Numerical Methods for Diffusion Models on Manifolds](https://arxiv.org/pdf/2202.09778.pdf)
  6. [Cascaded Diffusion Models for High Fidelity Image Generation](https://www.jmlr.org/papers/volume23/21-0635/21-0635.pdf)
  7. [High Fidelity Visualization of What Your Self-Supervised Representation Knows About](https://arxiv.org/abs/2112.09164)
  8. [Itô-Taylor Sampling Scheme for Denoising Diffusion Probabilistic Models using Ideal Derivatives](https://arxiv.org/abs/2112.13339)
  9. [{Dynamic Dual-Output Diffusion Models](https://openaccess.thecvf.com/content/CVPR2022/papers/Benny_Dynamic_Dual-Output_Diffusion_Models_CVPR_2022_paper.pdf)
  10. [Generating High Fidelity Data from Low-density Regions using Diffusion Models](https://openaccess.thecvf.com/content/CVPR2022/papers/Sehwag_Generating_High_Fidelity_Data_From_Low-Density_Regions_Using_Diffusion_Models_CVPR_2022_paper.pdf)
  11. [Perception Prioritized Training of Diffusion Models](https://openaccess.thecvf.com/content/CVPR2022/papers/Choi_Perception_Prioritized_Training_of_Diffusion_Models_CVPR_2022_paper.pdf)
  12. [Elucidating the Design Space of Diffusion-Based Generative Models](https://arxiv.org/pdf/2206.00364.pdf)
  13. [Progressive distillation for fast sampling of diffusion models](https://arxiv.org/pdf/2202.00512.pdf)
  14. [Denoising Likelihood Score Matching for Conditional Score-based Data Generation](https://arxiv.org/abs/2203.14206)
  15. [On Conditioning the Input Noise for Controlled Image Generation with Diffusion Models](https://arxiv.org/abs/2205.03859)
  16. [A Continuous Time Framework for Discrete Denoising Models](https://arxiv.org/abs/2205.14987)
  17. [DPM-Solver: A Fast ODE Solver for Diffusion Probabilistic Model Sampling in Around 10 Steps](https://arxiv.org/abs/2206.00927)
  18. [Compositional Visual Generation with Composable Diffusion Models](https://arxiv.org/pdf/2206.01714.pdf)
  19. [TryOnDiffusion: A Tale of Two UNets](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhu_TryOnDiffusion_A_Tale_of_Two_UNets_CVPR_2023_paper.pdf)
  20. [High-Fidelity Guided Image Synthesis with Latent Diffusion Models](https://openaccess.thecvf.com/content/CVPR2023/papers/Singh_High-Fidelity_Guided_Image_Synthesis_With_Latent_Diffusion_Models_CVPR_2023_paper.pdf)
  21. [Unite and Conquer: Plug & Play Multi-Modal Synthesis using Diffusion Models](https://openaccess.thecvf.com/content/CVPR2023/papers/Nair_Unite_and_Conquer_Plug__Play_Multi-Modal_Synthesis_Using_Diffusion_CVPR_2023_paper.pdf)
  22. [Towards Practical Plug-and-Play Diffusion Models](https://openaccess.thecvf.com/content/CVPR2023/papers/Go_Towards_Practical_Plug-and-Play_Diffusion_Models_CVPR_2023_paper.pdf)
  23. [Inversion-based Style Transfer with Diffusion Models](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhang_Inversion-Based_Style_Transfer_With_Diffusion_Models_CVPR_2023_paper.pdf)
  24. [Conditional Text Image Generation with Diffusion Models](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhu_Conditional_Text_Image_Generation_With_Diffusion_Models_CVPR_2023_paper.pdf)
  25. [Generative Diffusion Prior for Unified Image Restoration and Enhancement](https://openaccess.thecvf.com/content/CVPR2023/papers/Fei_Generative_Diffusion_Prior_for_Unified_Image_Restoration_and_Enhancement_CVPR_2023_paper.pdf)
  26. [DCFace: Synthetic Face Generation With Dual Condition Diffusion Model](https://openaccess.thecvf.com/content/CVPR2023/papers/Kim_DCFace_Synthetic_Face_Generation_With_Dual_Condition_Diffusion_Model_CVPR_2023_paper.pdf)
  27. [Controllable Light Diffusion for Portraits](https://openaccess.thecvf.com/content/CVPR2023/papers/Futschik_Controllable_Light_Diffusion_for_Portraits_CVPR_2023_paper.pdf)
  28. [LayoutDiffusion: Controllable Diffusion Model for
Layout-to-image Generation](https://openaccess.thecvf.com/content/CVPR2023/papers/Zheng_LayoutDiffusion_Controllable_Diffusion_Model_for_Layout-to-Image_Generation_CVPR_2023_paper.pdf)
  29. [Self-Guided Diffusion Models](https://openaccess.thecvf.com/content/CVPR2023/papers/Hu_Self-Guided_Diffusion_Models_CVPR_2023_paper.pdf)
### Text-to-Image generation <a name="3"></a>
  1. [Vector quantized diffusion model for text-to-image synthesis](https://openaccess.thecvf.com/content/CVPR2022/papers/Gu_Vector_Quantized_Diffusion_Model_for_Text-to-Image_Synthesis_CVPR_2022_paper.pdf)
  2. [Hierarchical text-conditional image generation with CLIP latents](https://arxiv.org/pdf/2204.06125.pdf)
  3. [Photorealistic Text-to-Image Diffusion Models with Deep Language Understanding](https://arxiv.org/pdf/2205.11487.pdf)
  4. [Fast Sampling of Diffusion Models with Exponential Integrator](https://arxiv.org/abs/2204.13902)
  5. [DiVAE: Photorealistic Images Synthesis with Denoising Diffusion Decoder](https://arxiv.org/pdf/2206.00386.pdf)
  6. [Text-Guided Synthesis of Artistic Images with Retrieval-Augmented Diffusion Models](https://arxiv.org/pdf/2207.13038.pdf)
  7. [Text2Human: Text-Driven Controllable Human Image Generation](https://arxiv.org/pdf/2205.15996.pdf)
  8. [DreamBooth: Fine Tuning Text-to-Image Diffusion Models for Subject-Driven Generation](https://arxiv.org/pdf/2208.12242.pdf)
  9. [SpaText: Spatio-Textual Representation for Controllable Image Generation](https://arxiv.org/pdf/2211.14305.pdf)
  10. [MultiDiffusion: Fusing Diffusion Paths for Controlled Image Generation](https://arxiv.org/pdf/2302.08113.pdf)
  11. [Person Image Synthesis via Denoising Diffusion Model](https://openaccess.thecvf.com/content/CVPR2023/papers/Bhunia_Person_Image_Synthesis_via_Denoising_Diffusion_Model_CVPR_2023_paper.pdf)
  12. [Uncovering the Disentanglement Capability in Text-to-Image Diffusion Models](https://openaccess.thecvf.com/content/CVPR2023/papers/Wu_Uncovering_the_Disentanglement_Capability_in_Text-to-Image_Diffusion_Models_CVPR_2023_paper.pdf)
  13. [Multi-Concept Customization of Text-to-Image Diffusion](https://openaccess.thecvf.com/content/CVPR2023/papers/Kumari_Multi-Concept_Customization_of_Text-to-Image_Diffusion_CVPR_2023_paper.pdf)
  14. [ERNIE-ViLG 2.0: Improving Text-to-Image Diffusion Model with Knowledge-Enhanced Mixture-of-Denoising-Experts](https://openaccess.thecvf.com/content/CVPR2023/papers/Feng_ERNIE-ViLG_2.0_Improving_Text-to-Image_Diffusion_Model_With_Knowledge-Enhanced_Mixture-of-Denoising-Experts_CVPR_2023_paper.pdf)
  15. [Shifted Diffusion for Text-to-image Generation](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhou_Shifted_Diffusion_for_Text-to-Image_Generation_CVPR_2023_paper.pdf)
  16. [Specialist Diffusion: Plug-and-Play Sample-Efficient Fine-Tuning of Text-to-Image Diffusion Models To Learn Any Unseen Style](https://openaccess.thecvf.com/content/CVPR2023/papers/Lu_Specialist_Diffusion_Plug-and-Play_Sample-Efficient_Fine-Tuning_of_Text-to-Image_Diffusion_Models_To_CVPR_2023_paper.pdf)
  17. [Safe Latent Diffusion: Mitigating Inappropriate Degeneration in Diffusion Models](https://openaccess.thecvf.com/content/CVPR2023/papers/Schramowski_Safe_Latent_Diffusion_Mitigating_Inappropriate_Degeneration_in_Diffusion_Models_CVPR_2023_paper.pdf)
### Super-Resolution <a name="4"></a>
  1. [Image super-resolution via iterative refinement](https://arxiv.org/pdf/2104.07636.pdf)
  2. [Score-based Generative Neural Networks for Large-Scale Optimal Transport](https://arxiv.org/pdf/2110.03237.pdf)
  3. [Implicit Diffusion Models for Continuous Super-Resolution](https://openaccess.thecvf.com/content/CVPR2023/papers/Gao_Implicit_Diffusion_Models_for_Continuous_Super-Resolution_CVPR_2023_paper.pdf)
  4. [](https://openaccess.thecvf.com/content/CVPR2023/papers/Lu_Specialist_Diffusion_Plug-and-Play_Sample-Efficient_Fine-Tuning_of_Text-to-Image_Diffusion_Models_To_CVPR_2023_paper.pdf)
### Image Editing<a name="5"></a>
  1. [SDEdit: Guided Image Synthesis and Editing with Stochastic Differential Equations](https://arxiv.org/abs/2108.01073)
  2. [Blended Latent Diffusion](https://arxiv.org/pdf/2206.02779.pdf)
  3. [SINE: SINgle Image Editing with Text-to-Image Diffusion Models (https://openaccess.thecvf.com/content/CVPR2023/papers/Zhang_SINE_SINgle_Image_Editing_With_Text-to-Image_Diffusion_Models_CVPR_2023_paper.pdf)
  4. [Imagic: Text-Based Real Image Editing with Diffusion Models](https://openaccess.thecvf.com/content/CVPR2023/papers/Kawar_Imagic_Text-Based_Real_Image_Editing_With_Diffusion_Models_CVPR_2023_paper.pdf)
  5. [Collaborative Diffusion for Multi-Modal Face Generation and Editing](https://openaccess.thecvf.com/content/CVPR2023/papers/Huang_Collaborative_Diffusion_for_Multi-Modal_Face_Generation_and_Editing_CVPR_2023_paper.pdf)
  6. [Null-text Inversion for Editing Real Images using Guided Diffusion Models](https://openaccess.thecvf.com/content/CVPR2023/papers/Mokady_NULL-Text_Inversion_for_Editing_Real_Images_Using_Guided_Diffusion_Models_CVPR_2023_paper.pdf)
  7. [DiffusionRig: Learning Personalized Priors for Facial Appearance Editing](https://openaccess.thecvf.com/content/CVPR2023/papers/Ding_DiffusionRig_Learning_Personalized_Priors_for_Facial_Appearance_Editing_CVPR_2023_paper.pdf)
  8. [RenderDiffusion: Image Diffusion for 3D Reconstruction, Inpainting and Generation] (https://openaccess.thecvf.com/content/CVPR2023/papers/Anciukevicius_RenderDiffusion_Image_Diffusion_for_3D_Reconstruction_Inpainting_and_Generation_CVPR_2023_paper.pdf)
  9. [Paint by Example: Exemplar-based Image Editing with Diffusion Models](https://openaccess.thecvf.com/content/CVPR2023/papers/Yang_Paint_by_Example_Exemplar-Based_Image_Editing_With_Diffusion_Models_CVPR_2023_paper.pdf)
### Region Image Editing <a name="6"></a>
  1. [Blended diffusion for text-driven editing of natural images](https://openaccess.thecvf.com/content/CVPR2022/papers/Avrahami_Blended_Diffusion_for_Text-Driven_Editing_of_Natural_Images_CVPR_2022_paper.pdf)
### Inpainting <a name="7"></a>
  1. [GLIDE: Towards Photorealistic Image Generation and Editing with Text-Guided Diffusion Models](https://arxiv.org/pdf/2112.10741.pdf)
  2. [RePaint: Inpainting using Denoising Diffusion Probabilistic Models](https://openaccess.thecvf.com/content/CVPR2022/papers/Lugmayr_RePaint_Inpainting_Using_Denoising_Diffusion_Probabilistic_Models_CVPR_2022_paper.pdf)
  3. [RGBD2: Generative Scene Synthesis via Incremental View Inpainting using RGBD Diffusion Models] (https://openaccess.thecvf.com/content/CVPR2023/papers/Lei_RGBD2_Generative_Scene_Synthesis_via_Incremental_View_Inpainting_Using_RGBD_CVPR_2023_paper.pdf)
  4.[SmartBrush: Text and Shape Guided Object Inpainting With Diffusion Model](https://openaccess.thecvf.com/content/CVPR2023/papers/Xie_SmartBrush_Text_and_Shape_Guided_Object_Inpainting_With_Diffusion_Model_CVPR_2023_paper.pdf)
### Image-to-Image Translation <a name="8"></a>
  1. [Palette: Image-to-Image Diffusion Models](https://arxiv.org/pdf/2111.05826.pdf)
  2. [UNIT-DDPM: UNpaired Image Translation with Denoising Diffusion Probabilistic Models](https://arxiv.org/pdf/2104.05358.pdf)
  3. [EGSDE: Unpaired Image-to-Image Translation via Energy-Guided Stochastic Differential Equations](https://arxiv.org/pdf/2207.06635.pdf)
  4. [Pretraining is All You Need for Image-to-Image Translation](https://arxiv.org/pdf/2205.12952.pdf)
  5. [VQBB: Image-to-image Translation with Vector Quantized Brownian Bridge](https://arxiv.org/pdf/2205.07680.pdf)
  6. [The Swiss Army Knife for Image-to-Image Translation: Multi-Task Diffusion Models](https://arxiv.org/pdf/2204.02641.pdf)
  7. [Unifying Diffusion Models' Latent Space, with Applications to CycleDiffusion and Guidance](https://arxiv.org/pdf/2210.05559.pdf)
  8. [BBDM: Image-to-Image Translation with Brownian Bridge Diffusion Models](https://openaccess.thecvf.com/content/CVPR2023/papers/Li_BBDM_Image-to-Image_Translation_With_Brownian_Bridge_Diffusion_Models_CVPR_2023_paper.pdf)
  9. [Plug-and-Play Diffusion Features for Text-Driven Image-to-Image Translation](https://openaccess.thecvf.com/content/CVPR2023/papers/Tumanyan_Plug-and-Play_Diffusion_Features_for_Text-Driven_Image-to-Image_Translation_CVPR_2023_paper.pdf)
### Image Segmentation <a name="9"></a>
  1. [Label-Efficient Semantic Segmentation with Diffusion Models](https://arxiv.org/abs/2112.03126)
  2. [SegDiff: Image Segmentation with Diffusion Probabilistic Models](https://arxiv.org/pdf/2112.00390.pdf)
  3. [Multi-Class Segmentation from Aerial Views using Recursive Noise Diffusion](https://arxiv.org/pdf/2212.00787.pdf)
  4. [Ambiguous Medical Image Segmentation using Diffusion Models](https://openaccess.thecvf.com/content/CVPR2023/papers/Rahman_Ambiguous_Medical_Image_Segmentation_Using_Diffusion_Models_CVPR_2023_paper.pdf)
### Multi-Task <a name="10"></a>
  1. [Generative modeling by estimating gradients of the data distribution](https://arxiv.org/pdf/1907.05600.pdf)
  2. [Score-Based Generative Modeling through Stochastic Differential Equations](https://arxiv.org/pdf/2011.13456.pdf)
  3. [ImageBART: Bidirectional Context with Multinomial Diffusion for Autoregressive Image Synthesis](https://openreview.net/pdf?id=-1AAgrS5FF)
  4. [Learning Energy-Based Models by Diffusion Recovery Likelihood](https://arxiv.org/pdf/2012.08125.pdf)
  5. [Conditional image generation with score-based diffusion models](https://arxiv.org/pdf/2111.13606.pdf)
  6. [More control for free! Image synthesis with semantic diffusion guidance](https://arxiv.org/pdf/2112.05744.pdf)
  7. [ILVR: Conditioning Method for Denoising Diffusion Probabilistic Models](https://arxiv.org/abs/2108.02938)
  8. [Global Context with Discrete Diffusion in Vector Quantised Modelling for Image Generation](https://arxiv.org/pdf/2112.01799.pdf)
  9. [High-Resolution Image Synthesis with Latent Diffusion Models](https://openaccess.thecvf.com/content/CVPR2022/papers/Rombach_High-Resolution_Image_Synthesis_With_Latent_Diffusion_Models_CVPR_2022_paper.pdf)
  10. [Diffusion Autoencoders: Toward a Meaningful and Decodable Representation](https://openaccess.thecvf.com/content/CVPR2022/papers/Preechakul_Diffusion_Autoencoders_Toward_a_Meaningful_and_Decodable_Representation_CVPR_2022_paper.pdf)
  11. [Come-Closer-Diffuse-Faster: Accelerating Conditional Diffusion Models for Inverse Problems through Stochastic Contraction](https://openaccess.thecvf.com/content/CVPR2022/papers/Chung_Come-Closer-Diffuse-Faster_Accelerating_Conditional_Diffusion_Models_for_Inverse_Problems_Through_Stochastic_CVPR_2022_paper.pdf)
  12. [DiffusionCLIP: Text-Guided Diffusion Models for Robust Image Manipulation](https://openaccess.thecvf.com/content/CVPR2022/papers/Kim_DiffusionCLIP_Text-Guided_Diffusion_Models_for_Robust_Image_Manipulation_CVPR_2022_paper.pdf)
  13. [Understanding DDPM Latent Codes Through Optimal Transport](https://arxiv.org/abs/2202.07477)
  14. [Conditional Simulation Using Diffusion Schrödinger Bridges](https://arxiv.org/abs/2202.13460)
  15. [Retrieval-Augmented Diffusion Models](https://arxiv.org/abs/2204.11824)
  16. [Accelerating Diffusion Models via Early Stop of the Diffusion Process](https://arxiv.org/abs/2205.12524)
  17. [Diffusion Models as Plug-and-Play Priors](https://arxiv.org/pdf/2206.09012.pdf)
  18. [Non-Uniform Diffusion Models](https://arxiv.org/pdf/2207.09786.pdf)
  19. [Diffusion Probabilistic Model Made Slim](https://arxiv.org/pdf/2211.17106.pdf)
  20. [Open-Vocabulary Panoptic Segmentation with Text-to-Image Diffusion Models](https://openaccess.thecvf.com/content/CVPR2023/papers/Xu_Open-Vocabulary_Panoptic_Segmentation_With_Text-to-Image_Diffusion_Models_CVPR_2023_paper.pdf)
  21. [On Distillation of Guided Diffusion Model](https://openaccess.thecvf.com/content/CVPR2023/papers/Meng_On_Distillation_of_Guided_Diffusion_Models_CVPR_2023_paper.pdf)
  22. [DiffCollage: Parallel Generation of Large Content With Diffusion Models](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhang_DiffCollage_Parallel_Generation_of_Large_Content_With_Diffusion_Models_CVPR_2023_paper.pd)
### Medical Image-to-Image Translation <a name="11"></a>
  1. [Unsupervised Medical Image Translation with Adversarial Diffusion Models](https://arxiv.org/pdf/2207.08208.pdf)
  2. [Unsupervised Denoising of Retinal OCT with Diffusion Probabilistic Model](https://arxiv.org/pdf/2201.11760.pdf)
  3. [Conversion Between CT and MRI Images Using Diffusion and Score-Matching Models](https://arxiv.org/pdf/2209.12104.pdf)
### Medical Image Generation <a name="12"></a>
  1. [Solving inverse problems in medical imaging with score-based generative models](https://arxiv.org/pdf/2111.08005.pdf)
  2. [Score-based diffusion models for accelerated MRI](https://arxiv.org/pdf/2110.05243.pdf)
  3. [Diffusion Models For Medical Image Analysis: A Comprehensive Survey](https://arxiv.org/pdf/2211.07804.pdf)
  4. [Low-Dose CT Using Denoising Diffusion Probabilistic Model for 20× Speedup](https://arxiv.org/pdf/2209.15136.pdf)
  5. [Solving 3D Inverse Problems using Pre-trained 2D Diffusion Models](https://openaccess.thecvf.com/content/CVPR2023/papers/Chung_Solving_3D_Inverse_Problems_Using_Pre-Trained_2D_Diffusion_Models_CVPR_2023_paper.pdf)
### Medical Image Segmentation <a name="13"></a>
  1. [Diffusion Models for Implicit Image Segmentation Ensembles](https://arxiv.org/pdf/2112.03145.pdf)
  2. [Accelerating Diffusion Models via Pre-segmentation Diffusion Sampling for Medical Image Segmentation](https://arxiv.org/pdf/2210.17408.pdf)
### Medical Image Anomaly Detection <a name="14"></a>
  1. [Diffusion Models for Medical Anomaly Detection](https://arxiv.org/pdf/2203.04306.pdf)
  2. [Fast Unsupervised Brain Anomaly Detection and Segmentation with Diffusion Models](https://arxiv.org/pdf/2206.03461.pdf)
  3. [AnoDDPM: Anomaly Detection With Denoising Diffusion Probabilistic Models Using Simplex Noise](https://openaccess.thecvf.com/content/CVPR2022W/NTIRE/papers/Wyatt_AnoDDPM_Anomaly_Detection_With_Denoising_Diffusion_Probabilistic_Models_Using_Simplex_CVPRW_2022_paper.pdf)
  4. [What is Healthy? Generative Counterfactual Diffusion for Lesion Localization](https://arxiv.org/pdf/2207.12268.pdf)
### Video Generation <a name="15"></a>
  1. [Video Diffusion Models](https://arxiv.org/pdf/2204.03458.pdf)
  2. [Diffusion Probabilistic Modeling for Video Generation](https://arxiv.org/pdf/2203.09481.pdf)
  3. [Flexible Diffusion Modeling of Long Videos](https://arxiv.org/pdf/2205.11495.pdf)
  4. [Diffusion Models for Video Prediction and Infilling](https://arxiv.org/pdf/2206.07696.pdf)
  5. [Dreamix: Video Diffusion Models are General Video Editors](https://arxiv.org/pdf/2302.01329.pdf)
  6. [Conditional Image-to-Video Generation with Latent Flow Diffusion Models](https://arxiv.org/pdf/2303.13744.pdf)
  7. [Diffusion Video Autoencoders: Toward Temporally Consistent Face Video Editing via Disentangled Video Encoding](https://openaccess.thecvf.com/content/CVPR2023/papers/Kim_Diffusion_Video_Autoencoders_Toward_Temporally_Consistent_Face_Video_Editing_via_CVPR_2023_paper.pdf)
  8. [DiffTalk: Crafting Diffusion Models for Generalized Audio-Driven Portraits Animation](https://openaccess.thecvf.com/content/CVPR2023/papers/Shen_DiffTalk_Crafting_Diffusion_Models_for_Generalized_Audio-Driven_Portraits_Animation_CVPR_2023_paper.pdf)
  9. [MM-Diffusion: Learning Multi-Modal Diffusion Models for Joint Audio and Video Generation](https://openaccess.thecvf.com/content/CVPR2023/papers/Ruan_MM-Diffusion_Learning_Multi-Modal_Diffusion_Models_for_Joint_Audio_and_Video_CVPR_2023_paper.pdf)
  10. [VideoFusion: Decomposed Diffusion Models for High-Quality Video Generation](https://openaccess.thecvf.com/content/CVPR2023/papers/Luo_VideoFusion_Decomposed_Diffusion_Models_for_High-Quality_Video_Generation_CVPR_2023_paper.pdf)
  11. [Video Probabilistic Diffusion Models in Projected Latent Space](https://openaccess.thecvf.com/content/CVPR2023/papers/Yu_Video_Probabilistic_Diffusion_Models_in_Projected_Latent_Space_CVPR_2023_paper.pdf)
  12. [Align your Latents: High-Resolution Video Synthesis with Latent Diffusion Models](https://openaccess.thecvf.com/content/CVPR2023/papers/Blattmann_Align_Your_Latents_HighResolution_Video_Synthesis_With_Latent_Diffusion_Models_CVPR_2023_paper.pdf)
### Few-Shot Image Generation <a name="16"></a>
  1. [Few-Shot Diffusion Models](https://arxiv.org/abs/2205.15463)
### Counterfactual Explanations and Estimations <a name="17"></a>
  1. [Diffusion Models for Counterfactual Explanations](https://arxiv.org/pdf/2203.15636.pdf)
  2. [Diffusion Causal Models for Counterfactual Estimation](https://proceedings.mlr.press/v177/sanchez22a/sanchez22a.pdf)
### Image Restoration <a name="18"></a>
  1. [Restoring Vision in Adverse Weather Conditions with Patch-Based Denoising Diffusion Models](https://arxiv.org/pdf/2207.14626.pdf)
  2. [Denoising Diffusion Restoration Models](https://arxiv.org/pdf/2201.11793.pdf)
  3. [Diffusion in the Dark: A Diffusion Model for Low-Light Text Recognition](https://arxiv.org/pdf/2303.04291.pdf)
  4. [High-resolution image reconstruction with latent diffusion models from human
brain activity](https://openaccess.thecvf.com/content/CVPR2023/papers/Takagi_High-Resolution_Image_Reconstruction_With_Latent_Diffusion_Models_From_Human_Brain_CVPR_2023_paper.pdf)
  5. [Seeing Beyond the Brain: Conditional Diffusion Model with Sparse Masked Modeling for Vision Decoding](https://openaccess.thecvf.com/content/CVPR2023/papers/Chen_Seeing_Beyond_the_Brain_Conditional_Diffusion_Model_With_Sparse_Masked_CVPR_2023_paper.pdf)
### Image Registration <a name="19"></a>
  1. [DiffuseMorph: Unsupervised Deformable Image Registration Along Continuous Trajectory Using Diffusion Models](https://arxiv.org/pdf/2112.05149.pdf)
### Adversarial Purification <a name="20"></a>
  1. [Diffusion Models for Adversarial Purification](https://arxiv.org/pdf/2205.07460.pdf)
### Semantic Image Generation <a name="21"></a>
  1. [Semantic Image Synthesis via Diffusion Models](https://arxiv.org/pdf/2207.00050.pdf)
### 3D Generation <a name="22"></a>
  1. [3D shape generation and completion through point-voxel diffusion](https://openaccess.thecvf.com/content/ICCV2021/papers/Zhou_3D_Shape_Generation_and_Completion_Through_Point-Voxel_Diffusion_ICCV_2021_paper.pdf)
  2. [RODIN: A Generative Model for Sculpting 3D Digital Avatars Using Diffusion](https://openaccess.thecvf.com/content/CVPR2023/papers/Wang_RODIN_A_Generative_Model_for_Sculpting_3D_Digital_Avatars_Using_CVPR_2023_paper.pdf)
  3. [Avatars Grow Legs: Generating Smooth Human Motion from Sparse Tracking Inputs with Diffusion Model](https://openaccess.thecvf.com/content/CVPR2023/papers/Du_Avatars_Grow_Legs_Generating_Smooth_Human_Motion_From_Sparse_Tracking_CVPR_2023_paper.pdf)
  4. [NeuralField-LDM: Scene Generation with Hierarchical Latent Diffusion Models](https://openaccess.thecvf.com/content/CVPR2023/papers/Kim_NeuralField-LDM_Scene_Generation_With_Hierarchical_Latent_Diffusion_Models_CVPR_2023_paper.pdf)
  5. [Diffusion-SDF: Text-to-Shape via Voxelized Diffusion](https://openaccess.thecvf.com/content/CVPR2023/papers/Li_Diffusion-SDF_Text-To-Shape_via_Voxelized_Diffusion_CVPR_2023_paper.pdf)
  6. [Score Jacobian Chaining: Lifting Pretrained 2D Diffusion Models for 3D Generation](https://openaccess.thecvf.com/content/CVPR2023/papers/Wang_Score_Jacobian_Chaining_Lifting_Pretrained_2D_Diffusion_Models_for_3D_CVPR_2023_paper.pdf)
  7. [DATID-3D: Diversity-Preserved Domain Adaptation Using Text-to-Image Diffusion for 3D Generative Model](https://openaccess.thecvf.com/content/CVPR2023/papers/Kim_DCFace_Synthetic_Face_Generation_With_Dual_Condition_Diffusion_Model_CVPR_2023_paper.pdf)
  8. [HOLODIFFUSION: Training a 3D Diffusion Model using 2D Images](https://openaccess.thecvf.com/content/CVPR2023/papers/Karnewar_HOLODIFFUSION_Training_a_3D_Diffusion_Model_Using_2D_Images_CVPR_2023_paper.pdf)
  9. [Dream3D: Zero-Shot Text-to-3D Synthesis Using 3D Shape Prior and Text-to-Image Diffusion Models](https://openaccess.thecvf.com/content/CVPR2023/papers/Xu_Dream3D_Zero-Shot_Text-to-3D_Synthesis_Using_3D_Shape_Prior_and_Text-to-Image_CVPR_2023_paper.pdf)
  10. [Consistent View Synthesis with Pose-Guided Diffusion Models](https://openaccess.thecvf.com/content/CVPR2023/papers/Tseng_Consistent_View_Synthesis_With_Pose-Guided_Diffusion_Models_CVPR_2023_paper.pdf)
### Classification <a name="23"></a>
  1. [Score-based generative classifiers](https://arxiv.org/pdf/2110.00473.pdf)
  2. [Diffusion-based Data Augmentation for Skin Disease Classification: Impact Across Original Medical Datasets to Fully Synthetic Images](https://arxiv.org/pdf/2301.04802.pdf)
### Point Cloud Generation <a name="24"></a>
  1. [Diffusion Probabilistic Models for 3D Point Cloud Generation](https://openaccess.thecvf.com/content/CVPR2021/papers/Luo_Diffusion_Probabilistic_Models_for_3D_Point_Cloud_Generation_CVPR_2021_paper.pdf)
### Theoretical <a name="25"></a>
  1. [A variational perspective on diffusion-based generative models and score matching](https://proceedings.neurips.cc/paper/2021/file/c11abfd29e4d9b4d4b566b01114d8486-Paper.pdf)
  2. [Sampling is as easy as learning the score: theory for diffusion models with minimal data assumptions](https://arxiv.org/pdf/2209.11215.pdf)
### Graphs <a name="26"></a>
  1. [Generative Diffusion Models on Graphs: Methods and Applications](https://arxiv.org/pdf/2302.02591.pdf)
### Deblurring <a name="27"></a>
  1. [Image Deblurring with Domain Generalizable Diffusion Models](https://arxiv.org/pdf/2212.01789.pdf)
### Face Morphing Attack Detection <a name="28"></a>
  1. [Face Morphing Attack Detection with Denoising Diffusion Probabilistic Models](https://lmi.fe.uni-lj.si/wp-content/uploads/2023/03/IWBF2023_Morphing.pdf)
### Trajectory Prediction <a nav="29"></a>
  1. [Leapfrog Diffusion Model for Stochastic Trajectory Prediction](https://openaccess.thecvf.com/content/CVPR2023/papers/Mao_Leapfrog_Diffusion_Model_for_Stochastic_Trajectory_Prediction_CVPR_2023_paper.pdf)
### Attacks <a nav="30"></a>
  1. [How to Backdoor Diffusion Models?](https://openaccess.thecvf.com/content/CVPR2023/papers/Chou_How_to_Backdoor_Diffusion_Models_CVPR_2023_paper.pdf)
  2. [TrojDiff: Trojan Attacks on Diffusion Models with Diverse Targets](https://openaccess.thecvf.com/content/CVPR2023/papers/Chen_TrojDiff_Trojan_Attacks_on_Diffusion_Models_With_Diverse_Targets_CVPR_2023_paper.pdf)
### Study on  data memorization <a nav="31"></a>
  1.[Diffusion Art or Digital Forgery? Investigating Data Replication in Diffusion Models](https://openaccess.thecvf.com/content/CVPR2023/papers/Somepalli_Diffusion_Art_or_Digital_Forgery_Investigating_Data_Replication_in_Diffusion_CVPR_2023_paper.pdf)



