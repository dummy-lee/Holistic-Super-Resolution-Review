# Convolution Neural Network-based Methods
Model | Description | Publication | Year
:-:|:-:|:-:|:-:
[SRCNN](https://ieeexplore.ieee.org/abstract/document/7115171)|3-layer convolutional network|TPAMI|2016
[FSRCNN](https://link.springer.com/content/pdf/10.1007/978-3-319-46475-6_25.pdf)|transposed convolution|ECCV|2016
[ESPCN](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Shi_Real-Time_Single_Image_CVPR_2016_paper.pdf)|efficient sub-pixel convolution|CVPR|2016
[VDSR](https://openaccess.thecvf.com/content_cvpr_2016/papers/Kim_Accurate_Image_Super-Resolution_CVPR_2016_paper.pdf)|deep networks|CVPR|2016
[EDSR](https://openaccess.thecvf.com/content_cvpr_2017_workshops/w12/papers/Lim_Enhanced_Deep_Residual_CVPR_2017_paper.pdf)|removing the Batch Normalization layer in the residual block|CVPR|2017
[LapSRN](https://openaccess.thecvf.com/content_cvpr_2017/papers/Lai_Deep_Laplacian_Pyramid_CVPR_2017_paper.pdf)|progressively reconstruct the sub-band|CVPR|2017
[MemNet](https://openaccess.thecvf.com/content_ICCV_2017/papers/Tai_MemNet_A_Persistent_ICCV_2017_paper.pdf)|memory block, consisting of a recursive unit and a gate unit|ICCV|2017
[RDN](https://openaccess.thecvf.com/content_cvpr_2018/papers/Zhang_Residual_Dense_Network_CVPR_2018_paper.pdf)|combining residuals and dense connections|CVPR|2018
[IDN](https://openaccess.thecvf.com/content_cvpr_2018/papers/Hui_Fast_and_Accurate_CVPR_2018_paper.pdf)|information distillation blocks|CVPR|2018|
[DBPN](https://openaccess.thecvf.com/content_cvpr_2018/papers/Haris_Deep_Back-Projection_Networks_CVPR_2018_paper.pdf)|iterative up- and down- sampling layers|CVPR|2018
[ZSSR](https://openaccess.thecvf.com/content_cvpr_2018/papers/Shocher_Zero-Shot_Super-Resolution_Using_CVPR_2018_paper.pdf)|examples extracted solely from the input image itself|CVPR|2018
[CARN](https://openaccess.thecvf.com/content_ECCV_2018/papers/Namhyuk_Ahn_Fast_Accurate_and_ECCV_2018_paper.pdf)|cascading mechanism upon a residual network|ECCV|2018
[RCAN](https://openaccess.thecvf.com/content_ECCV_2018/papers/Yulun_Zhang_Image_Super-Resolution_Using_ECCV_2018_paper.pdf)|residual channel attention networks|ECCV|2018
[IMDN](https://dl.acm.org/doi/pdf/10.1145/3343031.3351084)|cascaded information multi-distillation blocks|ACMMM|2019
[SRFBN](https://openaccess.thecvf.com/content_CVPR_2019/papers/Li_Feedback_Network_for_Image_Super-Resolution_CVPR_2019_paper.pdf)|feedback network|CVPR|2019
[OISR](https://openaccess.thecvf.com/content_CVPR_2019/papers/He_ODE-Inspired_Network_Design_for_Single_Image_Super-Resolution_CVPR_2019_paper.pdf)|ordinary differential equation (ODE)-inspired design scheme|CVPR|2019
[META-SR](https://openaccess.thecvf.com/content_CVPR_2019/papers/Hu_Meta-SR_A_Magnification-Arbitrary_Network_for_Super-Resolution_CVPR_2019_paper.pdf)|arbitrary SR|CVPR|2019
[SAN](https://openaccess.thecvf.com/content_CVPR_2019/papers/Dai_Second-Order_Attention_Network_for_Single_Image_Super-Resolution_CVPR_2019_paper.pdf)|second-order attention network|CVPR|2019
[RNAN](https://arxiv.org/pdf/1903.10082.pdf)|local and non-local attention blocks|ICLR|2019
[SCN](https://ojs.aaai.org/index.php/AAAI/article/view/6706/6560)|pyramid representation via bilinear down-scaling|AAAI|2020
[MZSR](https://openaccess.thecvf.com/content_CVPR_2020/papers/Soh_Meta-Transfer_Learning_for_Zero-Shot_Super-Resolution_CVPR_2020_paper.pdf)|Meta-Transfer Learning|CVPR|2020
[DRN](https://openaccess.thecvf.com/content_CVPR_2020/papers/Guo_Closed-Loop_Matters_Dual_Regression_Networks_for_Single_Image_Super-Resolution_CVPR_2020_paper.pdf)|dual regression scheme to reduce space of the possible functions|CVPR|2020
[cutBlur](https://openaccess.thecvf.com/content_CVPR_2020/papers/Yoo_Rethinking_Data_Augmentation_for_Image_Super-resolution_A_Comprehensive_Analysis_and_CVPR_2020_paper.pdf)|data preprocessing|CVPR|2020
[RFANet](https://openaccess.thecvf.com/content_CVPR_2020/papers/Liu_Residual_Feature_Aggregation_Network_for_Image_Super-Resolution_CVPR_2020_paper.pdf)|residual feature aggregation|CVPR|2020
[HAN](https://link.springer.com/content/pdf/10.1007/978-3-030-58610-2_12.pdf)|layer attention module (LAM) and a channel-spatial attention module (CSAM)|ECCV|2020
[IRN](https://link.springer.com/content/pdf/10.1007/978-3-030-58452-8_8.pdf)|Invertible Rescaling Net|ECCV|2020
[LatticeNet](https://link.springer.com/content/pdf/10.1007/978-3-030-58542-6_17.pdf)|two butterfly structures are applied to combine two RBs|ECCV|2020
[ClassSR](https://openaccess.thecvf.com/content/CVPR2021/papers/Kong_ClassSR_A_General_Framework_to_Accelerate_Super-Resolution_Networks_by_Data_CVPR_2021_paper.pdf)|combined classification and SR in a unified framework|CVPR|2021
[FKP](https://openaccess.thecvf.com/content/CVPR2021/papers/Liang_Flow-Based_Kernel_Prior_With_Application_to_Blind_Super-Resolution_CVPR_2021_paper.pdf)|normalizing flow-based kernel prior (FKP) for kernel modeling|CVPR|2021
[SRWrap](https://openaccess.thecvf.com/content/CVPR2021/papers/Son_SRWarp_Generalized_Image_Super-Resolution_under_Arbitrary_Transformation_CVPR_2021_paper.pdf)|arbitrary image transformation|CVPR|2021
[NLSA](https://openaccess.thecvf.com/content/CVPR2021/papers/Mei_Image_Super-Resolution_With_Non-Local_Sparse_Attention_CVPR_2021_paper.pdf)|dynamic sparse attention pattern|CVPR|2021
[LUT](https://openaccess.thecvf.com/content/CVPR2021/papers/Jo_Practical_Single-Image_Super-Resolution_Using_Look-Up_Table_CVPR_2021_paper.pdf)|precomputed HR output values from the table|CVPR|2021
[SMSR](https://openaccess.thecvf.com/content/CVPR2021/papers/Wang_Exploring_Sparsity_in_Image_Super-Resolution_for_Efficient_Inference_CVPR_2021_paper.pdf)|sparse masks, sparse convolution|CVPR|2021
[AdderSR](https://openaccess.thecvf.com/content/CVPR2021/papers/Song_AdderSR_Towards_Energy_Efficient_Image_Super-Resolution_CVPR_2021_paper.pdf)|adder networks|CVPR|2021
[FAD](https://openaccess.thecvf.com/content/ICCV2021/papers/Xie_Learning_Frequency-Aware_Dynamic_Network_for_Efficient_Super-Resolution_ICCV_2021_paper.pdf)|frequency-aware dynamic network, DCT|CVPR|2021
[DFSA](https://openaccess.thecvf.com/content/ICCV2021/papers/Magid_Dynamic_High-Pass_Filtering_and_Multi-Spectral_Attention_for_Image_Super-Resolution_ICCV_2021_paper.pdf)|learning of high frequency features both locally and globally|ICCV|2021
[NASPR](https://openaccess.thecvf.com/content/ICCV2021/papers/Zhan_Achieving_On-Mobile_Real-Time_Super-Resolution_With_Neural_Architecture_and_Pruning_Search_ICCV_2021_paper.pdf)|NAS, pruning|ICCV|2021
[LIIF](https://openaccess.thecvf.com/content/CVPR2021/papers/Chen_Learning_Continuous_Image_Representation_With_Local_Implicit_Image_Function_CVPR_2021_paper.pdf)|implicit neural representation|CVPR|2021
[DCLS](https://openaccess.thecvf.com/content/CVPR2022/papers/Luo_Deep_Constrained_Least_Squares_for_Blind_Image_Super-Resolution_CVPR_2022_paper.pdf)|deconvolution module, channel-wise deblurring|CVPR|2022
[SLS](https://openaccess.thecvf.com/content/CVPR2022/papers/Oh_Attentive_Fine-Grained_Structured_Sparsity_for_Image_Restoration_CVPR_2022_paper.pdf)|pruning method|CVPR|2022
[LTE](https://openaccess.thecvf.com/content/CVPR2022/papers/Lee_Local_Texture_Estimator_for_Implicit_Representation_Function_CVPR_2022_paper.pdf)|dominant-frequency estimator|CVPR|2022
[SESR](https://proceedings.mlsys.org/paper/2022/file/ac627ab1ccbdb62ec96e702f07f6425b-Paper.pdf)|over-parameterize|MLS|2022
[HPUN](https://arxiv.org/pdf/2203.08921.pdf)|efficient and effective downsampling module|arxiv|2022

