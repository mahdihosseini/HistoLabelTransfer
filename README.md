# HistoLabelTransfer

This is the official **Keras** implementations of our ECCV 2020 paper [*"On Transferability of Histological Tissue Labels in Computational Pathology"*](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123740443.pdf)

### 1. Brief Introduction

#### 1.1 Backgrounds

- Current deep learning models in Computational Pathology are limited to particular diagnostic task for tissue/cancer classificaiton
- Development of each task requires expensive investment for creation of data labels done by pathologists

#### 1.2 Contributions

- We introduce a new label transferring solution in computational pathologyfrom the ADP source domain to different target domain based on diagnostically relevant labels for tissue type and cancer grade classification
- We introduce efficient CNN i.e. **HistoNet** that is robust and optimized toward color disparities and pixel-resolution for tissue recognitionin in WSI scans.

#### 1.4 Citation

Please cite our paper if you find our models useful.
```
@InProceedings{hosseini2020histo_label_transfer,
    title={On Transferability of Histological Tissue Labelsin Computational Pathology},
    author={Hosseini, Mahdi and Chan, Lyndon and Huang, Weimin and Wang, Yichen and Hasan, Danial and Rowsell, Corwyn and Damaskinos, Savvas and Plataniotis, Konstantinos},
    booktitle={European Conference on Computer Vision -- ECCV 2020},
    year={2020},
    publisher="Springer International Publishing"
}
```

### 2. Python Codes, Models and Dataset

#### 2.1 [ADP Database](http://www.dsp.utoronto.ca/projects/ADP/)

  - **Download**: The dataset is available on Atlas Project webpage under the EULA form you will sign during the registration from [ADP Website](http://www.dsp.utoronto.ca/projects/ADP).
  - **Content**: Contains **17,668** supervised annotated pathological images across multi-label tissue classes.

#### 2.2 [Keras Codes for CNN Training](https://github.com/mahdihosseini/ADP)

You can access the Keras implementation for CNN training from this [GitHub](https://github.com/mahdihosseini/ADP)


#### 2.2 [HistoNet Pre-Trained Models](https://zenodo.org/record/3991085#.XzyL8TUpCUk)

   - **Download**: The pre-trained CNN models are available on Zenodo under a Creative Commons Attribution license: [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3991085.svg)](https://doi.org/10.5281/zenodo.3991085)

   - **Content**: Contains pre-trained CNN models for histological tissue classification in different Pixel-Resolution, Color Augmentation technique, and CNN architectures.


### 5. License

FocusLiteNN is released under [The Prosperity Public License 3.0.0](LICENSE).
