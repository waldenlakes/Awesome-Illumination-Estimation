# Awesome-Illumination-Estimation  ![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)
A curated list of illumination estimation papers and resources.

## Table of Contents
+ [Papers](#Papers)
+ [Datasets](#Datasets)
+ [Challenges](#Challenges)

## Papers
SV:Spatially-Varying, ID:Indoor, OD:Outdoor, E:Editable

### Learning-based Methods
Indoor Scenes:
|Year|Venue|Paper|Repo|Data|SV|ID|OD|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|2022|ECCV|[Stylelight: Hdr panorama generation for lighting estimation and editing](https://arxiv.org/pdf/2207.14811.pdf)|[Code](https://github.com/Wanggcong/StyleLight)|[LavalIndoorHDR](http://indoor.hdrdb.com/)||&#10003;||
|2022|ECCV|[Editable indoor lighting estimation](https://arxiv.org/pdf/2211.03928.pdf)|[Proj](https://lvsn.github.io/EditableIndoorLight/)|[LavalIndoorHDR](http://indoor.hdrdb.com/)||&#10003;||
|2021|ICCV|[Sparse needlets for lighting estimation with spherical transport loss](http://openaccess.thecvf.com/content/ICCV2021/papers/Zhan_Sparse_Needlets_for_Lighting_Estimation_With_Spherical_Transport_Loss_ICCV_2021_paper.pdf)|[Code](https://github.com/fnzhan/EMLight/tree/master/Needlets)|[LavalIndoorHDR](http://indoor.hdrdb.com/)||&#10003;||
|2021|CVPR|[HDR environment map estimation for real-time augmented reality](https://openaccess.thecvf.com/content/CVPR2021/papers/Somanath_HDR_Environment_Map_Estimation_for_Real-Time_Augmented_Reality_CVPR_2021_paper.pdf)|[Code](https://github.com/apple/ml-envmapnet)|[LavalIndoorHDR](http://indoor.hdrdb.com/)||&#10003;||
|2021|AAAI|[Emlight: Lighting estimation via spherical distribution approximation](https://ojs.aaai.org/index.php/AAAI/article/download/16440/16247)|[Code](https://github.com/fnzhan/EMLight)|[LavalIndoorHDR](http://indoor.hdrdb.com/)||&#10003;||
|2020|ECCV|[PointAR: Efficient Lighting Estimation for Mobile Augmented Reality](https://arxiv.org/pdf/2004.00006.pdf)|[Code](https://github.com/cake-lab/PointAR)|[Matterport3D](https://niessner.github.io/Matterport/)|&#10003;|&#10003;||
|2020|CVPR|[Lighthouse: Predicting lighting volumes for spatially-coherent illumination](https://openaccess.thecvf.com/content_CVPR_2020/papers/Srinivasan_Lighthouse_Predicting_Lighting_Volumes_for_Spatially-Coherent_Illumination_CVPR_2020_paper.pdf)|[Code](https://github.com/pratulsrinivasan/lighthouse)|[InteriorNet](https://interiornet.org/)|&#10003;|&#10003;||
|2019|ICCV|[Deep parametric indoor lighting estimation](http://openaccess.thecvf.com/content_ICCV_2019/papers/Gardner_Deep_Parametric_Indoor_Lighting_Estimation_ICCV_2019_paper.pdf)|[Proj](https://lvsn.github.io/deepparametric/)|[LavalIndoorHDR](http://indoor.hdrdb.com/)|&#10003;|&#10003;||
|2019|CVPR|[Fast spatially-varying indoor lighting estimation](http://openaccess.thecvf.com/content_CVPR_2019/papers/Garon_Fast_Spatially-Varying_Indoor_Lighting_Estimation_CVPR_2019_paper.pdf)|[Proj](https://lvsn.github.io/fastindoorlight/)|[LavalIndoorSVHDR](http://indoorsv.hdrdb.com/)|&#10003;|&#10003;||
|2019|CVPR|[Deeplight: Learning illumination for unconstrained mobile mixed reality](http://openaccess.thecvf.com/content_CVPR_2019/papers/LeGendre_DeepLight_Learning_Illumination_for_Unconstrained_Mobile_Mixed_Reality_CVPR_2019_paper.pdf)|[Proj](https://augmentedperception.github.io/deeplight/)|Capture||&#10003;|&#10003;|
|2019|CVPR|[Neural illumination: Lighting prediction for indoor environments](https://openaccess.thecvf.com/content_CVPR_2019/papers/Song_Neural_Illumination_Lighting_Prediction_for_Indoor_Environments_CVPR_2019_paper.pdf)|[Proj](https://illumination.cs.princeton.edu/)|[Matterport3D](https://niessner.github.io/Matterport/)|&#10003;|&#10003;||
|2017|SIGGRAPH|[Learning to predict indoor illumination from a single image](https://arxiv.org/pdf/1704.00090.pdf)|[Proj](http://vision.gel.ulaval.ca/~jflalonde/projects/deepIndoorLight/)|[LavalIndoorHDR](http://indoor.hdrdb.com/)|&#10003;|&#10003;||

Ourdoor Scenes:
|Year|Venue|Paper|Repo|Data|SV|ID|OD|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|2022|ECCV|[Neural Light Field Estimation for Street Scenes with Differentiable Virtual Object Insertion](https://arxiv.org/pdf/2208.09480.pdf)|[Proj](https://nv-tlabs.github.io/outdoor-ar/)||||&#10003;|
|2022|ECCV|[Estimating Spatially-Varying Lighting in Urban Scenes with Disentangled Representation](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136660445.pdf)|[Code](https://github.com/ChemJeff/SOLD-Net/)||&#10003;||&#10003;|
|2021|ICCV|[Hierarchical disentangled representation learning for outdoor illumination estimation and editing](https://openaccess.thecvf.com/content/ICCV2021/papers/Yu_Hierarchical_Disentangled_Representation_Learning_for_Outdoor_Illumination_Estimation_and_Editing_ICCV_2021_paper.pdf)|||&#10003;||&#10003;|
|2021|CVPR|[Spatially-varying outdoor lighting estimation from intrinsics](http://openaccess.thecvf.com/content/CVPR2021/papers/Zhu_Spatially-Varying_Outdoor_Lighting_Estimation_From_Intrinsics_CVPR_2021_paper.pdf)|[Video](https://www.youtube.com/watch?v=O1M1k6JncoA)||&#10003;||&#10003;|
|2019|CVPR|[Deep Sky Modeling for Single Image Outdoor Lighting Estimation](https://openaccess.thecvf.com/content_CVPR_2019/papers/Hold-Geoffroy_Deep_Sky_Modeling_for_Single_Image_Outdoor_Lighting_Estimation_CVPR_2019_paper.pdf)|[Proj](https://lvsn.github.io/deepskymodel/)||||&#10003;|
|2019|CVPR|[All-weather deep outdoor lighting estimation](https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhang_All-Weather_Deep_Outdoor_Lighting_Estimation_CVPR_2019_paper.pdf)|[Proj](https://lvsn.github.io/allweather/)||||&#10003;|
|2017|ICCV|[Learning high dynamic range from outdoor panoramas](http://openaccess.thecvf.com/content_ICCV_2017/papers/Zhang_Learning_High_Dynamic_ICCV_2017_paper.pdf)|[Proj](http://vision.gel.ulaval.ca/~jflalonde/publications/projects/learningHDR/)||||&#10003;|

Inverse-rendering based Methods:
|Year|Venue|Paper|Repo|Data|SV|ID|OD|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|2022|SIGGRAPH Asia|[Learning-based Inverse Rendering of Complex Indoor Scenes with Differentiable Monte Carlo Raytracing](https://arxiv.org/abs/2211.03017)|[Proj](https://jingsenzhu.github.io/invrend/) & [Code](https://github.com/jingsenzhu/IndoorInverseRendering)|[InteriorVerse](https://interiorverse.github.io/)|&#10003;|&#10003;||
|2022|ECCV|[Physically-Based Editing of Indoor Scene Lighting from a Single Image](https://arxiv.org/pdf/2205.09343.pdf)|[Proj](https://vilab-ucsd.github.io/ucsd-IndoorLightEditing/) & [Code](https://github.com/ViLab-UCSD/IndoorLightEditing)|[OpenRoom](https://vilab-ucsd.github.io/ucsd-openrooms/)|&#10003;|&#10003;||
|2022|CVPR|[IRISformer: Dense Vision Transformers for Single-Image Inverse Rendering in Indoor Scenes](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhu_IRISformer_Dense_Vision_Transformers_for_Single-Image_Inverse_Rendering_in_Indoor_CVPR_2022_paper.pdf)|[Code](https://github.com/ViLab-UCSD/IRISformer)|[OpenRoom](https://vilab-ucsd.github.io/ucsd-openrooms/)|&#10003;|&#10003;||
|2022|CVPR|[PhyIR: Physics-based Inverse Rendering for Panoramic Indoor Images](https://openaccess.thecvf.com/content/CVPR2022/papers/Li_PhyIR_Physics-Based_Inverse_Rendering_for_Panoramic_Indoor_Images_CVPR_2022_paper.pdf)|[Proj](https://lzleejean.github.io/PhyIR)|[FutureHouse](https://github.com/LZleejean/FutureHouse)|&#10003;|&#10003;||
|2021|ICCV|[Learning indoor inverse rendering with 3d spatially-varying lighting](http://openaccess.thecvf.com/content/ICCV2021/papers/Wang_Learning_Indoor_Inverse_Rendering_With_3D_Spatially-Varying_Lighting_ICCV_2021_paper.pdf)|[Proj](https://nv-tlabs.github.io/inverse-rendering-3d-lighting/)|[InteriorNet](https://interiornet.org/)|&#10003;|&#10003;||
|2020|CVPR|[Inverse rendering for complex indoor scenes: Shape, spatially-varying lighting and svbrdf from a single image](https://openaccess.thecvf.com/content_CVPR_2020/papers/Li_Inverse_Rendering_for_Complex_Indoor_Scenes_Shape_Spatially-Varying_Lighting_and_CVPR_2020_paper.pdf)|[Code](https://github.com/lzqsd/InverseRenderingOfIndoorScene)|[OpenRoom](https://vilab-ucsd.github.io/ucsd-openrooms/)|&#10003;|&#10003;||

### Capture-based Methods
|Year|Venue|Paper|Repo|Data|SV|ID|OD|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|2023|ArXiv|[Accidental Light Probes](https://arxiv.org/pdf/2301.05211.pdf)|[Proj](https://kovenyu.com/ALP)|Capture||&#10003;|&#10003;|
|2022|ArXiv|[ORCa: Glossy Objects as Radiance Field Cameras](https://arxiv.org/pdf/2212.04531.pdf)|[Proj](https://ktiwary2.github.io/objectsascam/)|[Polarimetric](https://akshatdave.github.io/pandora/index.html)||&#10003;|&#10003;|
|2021|ICCV|[Objects as cameras: Estimating high-frequency illumination from shadows](https://openaccess.thecvf.com/content/ICCV2021/papers/Swedish_Objects_As_Cameras_Estimating_High-Frequency_Illumination_From_Shadows_ICCV_2021_paper.pdf)||[hdrihaven.com](https://hdrihaven.com) & Capture||&#10003;|&#10003;|
|2021|CVPR|[Indoor lighting estimation using an event camera](https://openaccess.thecvf.com/content/CVPR2021/papers/Chen_Indoor_Lighting_Estimation_Using_an_Event_Camera_CVPR_2021_paper.pdf)||Capture|&#10003;|&#10003;||
|2020|ECCV|[Object-based illumination estimation with rendering-aware neural networks](https://arxiv.org/pdf/2008.02514.pdf)|[Proj](https://yuedong.shading.me/project/lightest/lightest.htm)|Collect||&#10003;||


## Datasets
+ Laval Outdoor HDR Dataset [[link]](http://outdoor.hdrdb.com/)
+ Laval Indoor HDR Dataset [[link]](http://indoor.hdrdb.com/)
+ Laval Indoor Spatially Varying HDR Dataset [[link]](http://indoorsv.hdrdb.com/)
+ Laval Face & Lighting HDR Dataset [[link]](http://faces.hdrdb.com/)
+ OpenRooms Dataset [[link]](https://vilab-ucsd.github.io/ucsd-openrooms/)

## Challenges
+ AIM 2020: Scene Relighting and Illumination Estimation Challenge @ECCV [[link]](https://data.vision.ee.ethz.ch/cvl/aim20/) [[Paper]](https://arxiv.org/abs/2009.12798)
+ Illumination Estimation Challenge 2019, 2020 @ISPA [[link]](https://nightimaging.org/index.html) [[Paper]](https://onlinelibrary.wiley.com/doi/abs/10.1002/col.22675)
