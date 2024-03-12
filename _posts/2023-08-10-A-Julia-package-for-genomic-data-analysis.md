
# ngsJulia: population genetic analysis of next-generation DNA sequencing data with Julia language

A sound analysis of DNA sequencing data is important to extract meaningful information and infer quantities of interest. Sequencing and mapping errors coupled with low and variable coverage hamper the identification of genotypes and variants and the estimation of population genetic parameters. Methods and implementations to estimate population genetic parameters from sequencing data available nowadays either are suitable for the analysis of genomes from model organisms only, require moderate sequencing coverage, or are not easily adaptable to specific applications. 

To address these issues, we introduce ngsJulia, a collection of templates and functions in Julia language to process short-read sequencing data for population genetic analysis. We further describe two implementations, ngsPool and ngsPloidy, for the analysis of pooled sequencing data and polyploid genomes, respectively. Through simulations, we illustrate the performance of estimating various population genetic parameters using these implementations, using both established and novel statistical methods. 

![](/assets/ngsJulia_figure.gif)

These results inform on optimal experimental design and demonstrate the applicability of methods in ngsJulia to estimate parameters of interest even from low coverage sequencing data. ngsJulia provide users with a flexible and efficient framework for ad hoc analysis of sequencing data.ngsJulia is available from: https://github.com/mfumagalli/ngsJulia.

The paper is available for download [here](/assets/ngsJulia_paper.pdf).


