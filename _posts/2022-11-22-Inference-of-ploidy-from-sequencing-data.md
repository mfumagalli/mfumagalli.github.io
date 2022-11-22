
In our latest [paper](https://peercommunityjournal.org/articles/10.24072/pcjournal.178/) published in [Peer Community Journal](https://peercommunityjournal.org/), Mathematical and Computational Biology section, we present a new method, and software, to estimate ploidy from low-depth sequencing data.

The inference of ploidy levels from high-throughput sequencing data is essential to shed light onto the molecular mechanisms underpinning genome evolution. 
Current methods to estimate ploidy from sequencing data are based on allele frequency and depth variation. 
As such, they have limited power to infer ploidy levels at low- and mid-depth sequencing data, as they do not fully account for data uncertainty. 

Here we introduce __HMMploidy__, a novel method that leverages the information from multiple samples and combines the information from sequencing depth and genotype likelihoods. 

![](/assets/HMMploidy.jpg)

We demonstrate that HMMploidy outperforms existing methods in many scenarios of experimental design.
It does particularly well at low-depth with large sample sizes. 
To illustrate its applicability, we deployed HMMploidy to sequencing data from the pathogenic fungus _Cryptococcus neoformans_ and retrieved atterns of multiploidy and aneuploidy.
Results were robust when downsampling the sequencing data. 

We predict that HMMploidy will have wide applicability to low-depth sequencing data from polyploid and aneuploid species, and will be deployed to address further questions in studies of genome evolution and stability.
HMMploidy is available as open-source software on its github [repository](https://github.com/SamueleSoraggi/HMMploidy) and it is integrated with [ngsTools](https://github.com/mfumagalli/ngsTools).

We are also proud that this important piece of work has been reviewed, recommended and published by [Peer Community In](https://peercommunityin.org/) (PCI), a non-profit organisation for reviewing scientific papers.
Its journal is golden open-access, meaning that neither authors nor readers pay.
Would not signing the [PCI Manifesto](https://peercommunityin.org/pci-manifesto/) for free open access to scientific publications? 















