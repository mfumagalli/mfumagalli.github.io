
# Efficient Detection and Characterization of Targets of Natural Selection Using Transfer Learning

Natural selection leaves detectable patterns of altered spatial diversity within genomes, and identifying affected regions is crucial for understanding species evolution. Recently, machine learning approaches applied to raw population genomic data have been developed to uncover these adaptive signatures. 

Convolutional neural networks (CNNs) are particularly effective for this task, as they handle large data arrays while maintaining element correlations. However, shallow CNNs may miss complex patterns due to their limited capacity, while deep CNNs can capture these patterns but require extensive data and computational power. 

Transfer learning addresses these challenges by utilizing a deep CNN pretrained on a large dataset as a feature extraction tool for downstream classification and evolutionary parameter prediction. This approach reduces extensive training data generation requirements and computational needs while maintaining high performance. 

In this study, we developed TrIdent, a tool that uses transfer learning to enhance detection of adaptive genomic regions from image representations of multilocus variation. We evaluated TrIdent across various genetic, demographic, and adaptive settings, in addition to unphased data and other confounding factors. TrIdent demonstrated improved detection of adaptive regions compared to recent methods using similar data representations. 

![](/assets/Trident.png)

We further explored model interpretability through class activation maps and adapted TrIdent to infer selection parameters for identified adaptive candidates. Using whole-genome haplotype data from European and African populations, TrIdent effectively recapitulated known sweep candidates and identified novel cancer, and other disease-associated genes as potential sweeps.

The open-source software is available [here](https://www.github.com/sandipanpaul06/TrIdent).

The paper is available [here](/assets/Trident_paper.pdf).


