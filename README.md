# Deep Optimized Broad Learning System for Large-scale Tabular Data Analysis
## Abstract:

The broad learning system is one type of effective method for tabular data analysis. However, as the demand for processing large-scale datasets, the original broad learning system ma not be effective in handling big data. In this paper, two broad learning system-based algorithms, OBLS and DOBLS have been proposed. The main contributions of the paper are: i) the OBLS uses an effective and efficient learning scheme for big data analysis, where a parameter refinement strategy is proposed to fine-tune the weights in the model, and ii) the DOBLS is built with multiple OBLS, having a robust network connection topology to boost the efficiency of the data transformation within the model. Here, two types of shortcut are utilized. One connects the input layer to each OBLS, while the other one has a direct propagation between every OBLS to the output laer. Experimental results validate the effectiveness of the proposed models. 


## Contributions:
* I. Architecture side - Two novel analytic learning algorithms called OBLS and DOBLS are proposed. Specifically, i) a refinement learning strategy is proposed to boost the perofrmance of the original BLS on the big data analysis, ii) to enhance the discriminitively of the latent space features, a new network connection topology is proposed. 

* II. Application side - The key contribution of this paper in terms of its application is the usage of OBLS and DOBLS, which harnesses high-level abstract features to handle large-scale datasets with more than 500 K samples. Furthermore, the cross-domain validations (multi-view feature embedding, one-class classification, and camera model identification) verify the effectiveness of the proposed methods. 

## Learning Structure:

<img src="https://github.com/1027051515/OBLS_DOBLS/blob/main/f2.png" width="1050" height="400" />

## Related Work:

[1] Zhang, W. (2022). Deep Optimized Broad Learning System for Large-scale Tabular Data Analysis. IEEE Transactions on Cybernetics.

### Caltech-101 (Visual Image Classification Domain)
* Caltech-101 dataset: [Caltech-101 DATASET](http://www.vision.caltech.edu/Image_Datasets/Caltech101/)
* Caltech-101 (Inception-v3) features: [Caltech-101 (GoogLe Drive)](https://drive.google.com/file/d/1utcKTwC5dftDGcvLG5ABCTFWGvvObcDz/view?usp=sharing)
* Source code for Caltech-101: [Caltech-101](https://github.com/1027051515/PHSNN-RPHSNN/blob/main/Demo.rar)

### Caltech-256 (Visual Image Classification Domain)
* Caltech-256 dataset: [Caltech-256 DATASET](http://www.vision.caltech.edu/Image_Datasets/Caltech101/)
  * Caltech-256 (ResNet-50) features: [Caltech-256 (GoogLe Drive)](https://drive.google.com/file/d/1utcKTwC5dftDGcvLG5ABCTFWGvvObcDz/view?usp=sharing)
* Source code for Caltech-256: [Caltech-256](https://github.com/1027051515/PHSNN-RPHSNN/blob/main/Demo.rar)

## Dependancies
* Matlab version 2022a,
* A workstation with a 256GB memory and an E5-2650 processor.

## Reproduce the Experimental Results

Run script "Coding_M.m" for reproduciility.

#The code is released in content-obscured version (p files). After acceptance of the manuscript (if decided so), the source code will be made public.
