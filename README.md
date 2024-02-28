# Dissertation

The repository contains the code that I wrote and the experients that I conducted for my dissertation with the title *Improving Convolutional Neural Network-based Image Classification by Exploiting Network Layer Information*. The dependencies of the code can be found in each Jupyter notebook.

## patch_init

The directory `patch_init` contains the code and experiments for my method *Image Patch-based Model Weight Initialization* in order to make model training more robust with respect to the choice of the learning rate parameter. This method is described in chapter 4 of my dissertation and in my corresponding publication:

```
@inproceedings{lehmann/ebner:2021a,
    author       = {Lehmann, Daniel and Ebner, Marc},
    title        = {{Are Image Patches Beneficial} for {Initializing Convolutional Neural Network Models}?},
    booktitle    = {{Proceedings} of the 16th {International Joint Conference} on {Computer Vision}, {Imaging} and {Computer Graphics Theory} and {Applications} ({VISIGRAPP} 2021) - {Volume} 5: {VISAPP}},
    year         = {2021},
    pages        = {346-353},
    publisher    = {SciTePress}, 
    organization = {INSTICC},
}
```

## scus

The directory `scus` contains the code and experiments for my method *Subclass-based Undersampling* in order to address model training using a class-imbalanced training dataset. This method is described in chapter 5 of my dissertation and in my corresponding publication:

```
@inproceedings{lehmann/ebner:2022a,
    author       = {Lehmann, Daniel and Ebner, Marc},
    title        = {{Subclass-based Undersampling} for {Class-imbalanced Image Classification}},
    booktitle    = {{Proceedings} of the 17th {International Joint Conference} on {Computer Vision}, {Imaging} and {Computer Graphics Theory} and {Applications} ({VISIGRAPP} 2022) - {Volume} 5: {VISAPP}},
    year         = {2022},
    pages        = {493-500},
    publisher    = {SciTePress}, 
    organization = {INSTICC},
}
```

## laca

The directory `laca` contains the code and experiments for the naive version of my method *Layer-wise Activation Cluster Analysis* in order to detect out-of-distribution samples at inference with respect to a trained model. This method is described in chapter 6 of my dissertation (especially in section 6.2.3) and in my corresponding publication:

```
@inproceedings{lehmann/ebner:2021b,
    author    = {Lehmann, Daniel and Ebner, Marc},
    title     = {{Layer-Wise Activation Cluster Analysis} of {CNN}s to {Detect Out-of-Distribution Samples}},
    booktitle = {{Proceedings} of the 30th {International Conference} on {Artificial Neural Networks} and {Machine Learning} - {ICANN} 2021},
    year      = {2021},
    editor    = {Farka{\v{s}}, Igor and Masulli, Paolo and Otte, Sebastian and Wermter, Stefan},
    series    = {Lecture Notes in Computer Science},
    pages     = {214-226},
    address   = {Cham, Switzerland},
    publisher = {Springer},    
}
```

## laca2

The directory `laca2` contains the code and experiments for the more sophisticated version of my method *Layer-wise Activation Cluster Analysis* in order to detect out-of-distribution samples at inference with respect to a trained model. This method is described in chapter 6 of my dissertation (especially in section 6.2.4) and in my corresponding publication:

```
@inproceedings{lehmann/ebner:2022b,
    author       = {Lehmann, Daniel and Ebner, Marc},
    title        = {{Calculating} the {Credibility} of {Test Samples} at {Inference} by a {Layer-wise Activation Cluster Analysis} of {Convolutional Neural Networks}},
    booktitle    = {{Proceedings} of the 3rd {International Conference} on {Deep Learning Theory} and {Applications} - {Volume} 1: {DeLTA}},
    year         = {2022},
    pages        = {34-43},
    address      = {Lisbon, Portugal},
    publisher    = {SciTePress},
    organization = {INSTICC}, 
}
```

## laca3

The directory `laca3` contains additional experiments for the more sophisticated version of my method *Layer-wise Activation Cluster Analysis* (see `laca2`). These experiments are described in section 6.3.4 and 6.3.5 of chapter 6 of my dissertation and in my corresponding publication:

```
@inproceedings{lehmann/ebner:2023,
    author    = {Lehmann, Daniel and Ebner, Marc},
    title     = {{Reliable Classification} of {Images} by {Calculating} their {Credibility Using} a {Layer-wise Activation Cluster Analysis} of {CNN}s},
    booktitle = {{Deep Learning Theory} and {Applications} - {DeLTA} 2022 ({Revised Selected Papers})},
    year      = {2023},
    editor    = {Fred, Ana and Sansone, Carlo and Gusikhin, Oleg and Madani, Kurosh},
    series    = {Communications in Computer and Information Science},
    pages     = {33-55},
    address   = {Cham, Switzerland},
    publisher = {Springer},
}
```

## Dissertation Citation

Coming soon.



