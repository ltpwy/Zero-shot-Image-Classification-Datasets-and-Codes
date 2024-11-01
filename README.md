**This document presents a comprehensive collection of commonly used models and datasets in the field of zero-shot image classification. The "TZSL&GZSL Models" folder contains open-source models for traditional/generalized zero-shot image classification, while the "TZSL&GZSL Datasets" folder includes commonly used datasets for these approaches. The "CZSL Models" folder holds open-source models for compositional zero-shot image classification, with frequently used datasets for this task stored in the "CZSL Datasets" folder. Additionally, links to relevant papers are provided in the readme.md files.**

# Traditional Zero-shot Image Classification/Generalized Zero-shot Image Classification


## Datasets
Below is a summary of commonly used datasets for traditional/generalized zero-shot classification.


| **Relevant Information**                             | **AWA** | **AWA2** | **aPY** | **SUN** | **CUB** |
|-------------------------------------------|---------|----------|---------|---------|---------|
| **Number of images**                      | 30,475  | 37,322   | 15,339  | 14,340  | 11,788  |
| **Number of classes**                     | 50      | 50       | 32      | 717     | 200     |
| **Number of seen classes**                | 40      | 40       | 20      | 645     | 150     |
| **Number of unseen classes**              | 10      | 10       | 12      | 72      | 50      |
| **Number of attribute labels per class**  | 85      | 85       | 64      | 102     | 312     |
| **Dataset Links**                         | [AWA](https://cvml.ist.ac.at/AwA/) | [AWA2](https://cvml.ist.ac.at/AwA/) | [aPY](https://vision.cs.uiuc.edu/attributes/) | [SUN](http://cs.brown.edu/~gmpatter/sunattributes.html) | [CUB](https://www.vision.caltech.edu/datasets/cub_200_2011/) |


## Models

| **Models**                | **Source**  | **Paper Link** | **Code Link** |
|---------------------------|-------------|-----------------|----------------|
| DAP                       | CVPR2009    |[PDF](https://ieeexplore.ieee.org/abstract/document/5206594)| [Link](#) |
| IAP                       | CVPR2009    | [PDF](https://ieeexplore.ieee.org/abstract/document/5206594)| [Link](#) |
| DEVISE                    | NeurIPS2013 | [PDF](https://proceedings.neurips.cc/paper/2013/hash/7cce53cf90577442771720a370c3c723-Abstract.html)  | [Link](#)      |
| ALE                       | CVPR2013    | [PDF](https://www.cv-foundation.org/openaccess/content_cvpr_2013/html/Akata_Label-Embedding_for_Attribute-Based_2013_CVPR_paper.html)      | [Link](#)      |
| CMT                       | NeurIPS2013  |[PDF](https://proceedings.neurips.cc/paper/2013/hash/2d6cc4b2d139a53512fb8cbb3086ae2e-Abstract.html)      | [Link](#)      |
| RT-ZSL                    | NeurIPS2014 | [PDF]( https://proceedings.neurips.cc/paper/2014/hash/1f1baa5b8edac74eb4eaa329f14a0361-Abstract.html)| [Link](#)      |
| HAP                       | CVPR2015    | [PDF](https://www.cv-foundation.org/openaccess/content_cvpr_2015/html/Huang_Learning_Hypergraph-Regularized_Attribute_2015_CVPR_paper.html) | [Link](#)      |
| SJE                       | CVPR2015    | [PDF](https://openaccess.thecvf.com/content_cvpr_2015/html/Akata_Evaluation_of_Output_2015_CVPR_paper.html)       | [Link](#)      |
| ESZSL                     | ML2015      | [PDF](https://proceedings.mlr.press/v37/romera-paredes15.html)       | [Link](#)      |
| SSE                       | CVPR2015    | [PDF](https://www.cv-foundation.org/openaccess/content_iccv_2015/html/Zhang_Zero-Shot_Learning_via_ICCV_2015_paper.html)       | [Link](#)      |
| SYNC                      | CVPR2016    | [Link](#)       | [Link](#)      |
| LATEM                     | CVPR2016    | [Link](#)       | [Link](#)      |
| SAE                       | CVPR2017    | [Link](#)       | [Link](#)      |
| RN                        | CVPR2018    | [Link](#)       | [Link](#)      |
| DLF                       | CVPR2019    | [Link](#)       | [Link](#)      |
| AREN                      | CVPR2019    | [Link](#)       | [Link](#)      |
| TVN                       | TIP2019     | [Link](#)       | [Link](#)      |
| DAZLE                     | CVPR2020    | [Link](#)       | [Link](#)      |
| ALS                       | TIP2020     | [Link](#)       | [Link](#)      |
| TEDE                      | TCSVT2020   | [Link](#)       | [Link](#)      |
| TEDE*                     | TCSVT2020   | [Link](#)       | [Link](#)      |
| AAW                       | MLWA2020    | [Link](#)       | [Link](#)      |
| AAW*                      | MLWA2020    | [Link](#)       | [Link](#)      |
| ZIC-LDM                   | Sensors2021  | [Link](#)      | [Link](#)      |
| Trans-zero                | AAAI2022    | [Link](#)       | [Link](#)      |
| SRSA                      | PR2022      | [Link](#)       | [Link](#)      |
| MSDN                      | CVPR2022    | [Link](#)       | [Link](#)      |
| I2dformer                 | NeurIPS2022  | [Link](#)      | [Link](#)      |
| VT-ZSL                    | PRMVIA2023  | [Link](#)       | [Link](#)      |
| DFAN                      | BMVC2023    | [Link](#)       | [Link](#)      |
| PSVMA                     | CVPR2023    | [Link](#)       | [Link](#)      |
| $ \mathrm{DUET}^{(1)} $   | AAAI2023    | [Link](#)       | [Link](#)      |
| CC-ZSL                    | TCSVT2023   | [Link](#)       | [Link](#)      |
| I2mvformer                | CVPR2023    | [Link](#)       | [Link](#)      |
| CVAE-ZSL                  | NeurIPS2015 | [Link](#)       | [Link](#)      |
| f-CLSWG                   | CVPR2018    | [Link](#)       | [Link](#)      |
| c-CLSWG                   | ECCV2018    | [Link](#)       | [Link](#)      |
| LisGAN                    | CVPR2019    | [Link](#)       | [Link](#)      |
| F-VG-D2                   | CVPR2019    | [Link](#)       | [Link](#)      |
| F-VG-D2*                  | CVPR2019    | [Link](#)       | [Link](#)      |
| TF-VG                     | ECCV2020    | [Link](#)       | [Link](#)      |
| TF-VG*                    | ECCV2020    | [Link](#)       | [Link](#)      |
| LISEC                     | ECCV2020    | [Link](#)       | [Link](#)      |
| E-PGN                     | CVPR2020    | [Link](#)       | [Link](#)      |
| IZF                       | ECCV2020    | [Link](#)       | [Link](#)      |
| VCGF                      | CVPR2020    | [Link](#)       | [Link](#)      |
| Zero-VG                   | TIP2020     | [Link](#)       | [Link](#)      |
| SDGZSL                    | ICCV2021    | [Link](#)       | [Link](#)      |
| SCGZSL                    | ICCV2021    | [Link](#)       | [Link](#)      |
| DAA                       | TRL2023     | [Link](#)       | [Link](#)      |
| DAA&SPOT                  | CVPR2023    | [Link](#)       | [Link](#)      |
| $ \mathrm{DUET}^{(2)} $   | TIP2019     | [Link](#)       | [Link](#)      |
| CADA-V                    | CVPR2019    | [Link](#)       | [Link](#)      |
| CE-GZSL                   | CVPR2021    | [Link](#)       | [Link](#)      |
| DCA-V                     | Cybern2022  | [Link](#)       | [Link](#)      |
| ESA*                      | ICASSP2023  | [Link](#)       | [Link](#)      |
















