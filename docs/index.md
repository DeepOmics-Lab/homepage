# Welcome to DeepOmics Lab

We are a multidisciplinary research team at the intersection of **omics analysis and artificial intelligence**, 
dedicated to developing and utilizing machine learning, deep learning, and bioinformatics algorithms 
to address the challenges of deciphering the structure and function of biomolecules in life omics.

Our research focuses on the core scientific challenge of **deciphering unknown small molecule structures and functions 
based on mass spectrometry technology**. Using chemometrics and AI as core approaches, we systematically develop 
methodologies for MS information analysis, forming distinctive analytical frameworks and algorithmic tools.

![Research Overview](images/fig1-research-overview.png)

## News

- **2025**: DeepMASS web server ([http://deepmass.cn](http://deepmass.cn)) launched, attracting 300+ registered users
- **2025**: Invited as Guest Editor for *"Deep Learning in Metabolomics"* special issue in *Metabolites*
- **2024–2025**: Multiple papers published in *Analytical Chemistry*, *Patterns*, *Analytica Chimica Acta*, *Talanta*
- **2023**: Two major papers published in *Nature Communications* and *Cell Chemical Biology*

The research group plans to recruit 1-2 master's and joint doctoral students each 
year and is actively seeking postdoctoral fellows and research assistants with 
backgrounds in chemistry, computer science and/or bioinformatics. Contact: jihongchao@caas.cn

## PI

**Ji Hongchao**, Associate Researcher, Master's Supervisor, Ph.D. in Science from Central South University. 
Joined the Shenzhen Agricultural Genomics Institute in 2022. He has received funding from 
the National Natural Science Foundation of China (General Program & Youth Project), the Shenzhen City 
Outstanding Young Scientist Training Project, and other projects.   

He has published over 20 papers in international academic journals such as *Nature Communications*, 
*Cell Chemical Biology*, *Analytical Chemistry*, *Patterns*, and *Briefings in Bioinformatics*. 
He has applied for 2 national invention patents and 2 PCT international patents. 
He serves as a reviewer for journals such as *Briefings in Bioinformatics*, *Journal 
of Chemical Information and Modeling*, *Analytical and Bioanalytical Chemistry*, and 
*Chemometrics and Intelligent Laboratory Systems*, and as guest editor for *Metabolites*.
He is a youth committee member of the Metabolomics Society of the Chinese Biophysical Society.

## Research Directions

### 1. Structure Elucidation of Unknown Compounds

We develop algorithms for processing complex LC-MS and GC-EI/MS data, including:
- **KPIC**: Pure ion chromatogram extraction via dynamic programming clustering, improving feature extraction accuracy and low-abundance signal detection
- **AutoMS**: Deep learning-based continuous peak quality scoring for objective false positive rate control
- **DeepMASS**: Chemical space positioning strategy for library-free structure annotation, achieving state-of-the-art accuracy on multiple benchmarks
- **Biosynthesis-aware structure generation**: Graph-sequence enhanced Transformer for predicting biologically plausible novel structures

> Our methods outperform leading tools: 97.1% feature extraction accuracy (vs. 95.8% XCMS, 93.8% MS-DIAL); 
> 57.7% Top-1 annotation accuracy on CASMI (vs. 44.7% SIRIUS, 36.1% MS-Finder).

[More about our research](research.md)

### 2. Compound Target Deconvolution

We combine chemometrics algorithms with thermal proteomics to enable high-throughput drug target discovery:
- **MAPS**: Matrix-augmented pooling strategy increasing experimental throughput by 10–100× while reducing costs by ~90%
- **DIA-TPP**: Label-free thermal proteome profiling with exogenous standard protein enhancement
- **ProSAP**: Standardized GUI software for thermal stability data analysis (1,400+ downloads)

[More about our research](research.md)

### 3. General-Purpose Mass Spectrometry LLM (Future Direction)

We are building a general-purpose mass spectrometry large language model that treats MS spectra as a "chemical language," 
enabling joint multi-task inference across structure elucidation, property prediction, and functional assessment 
within a unified representation space.

[More about this vision](research.md#3-future-direction-general-purpose-mass-spectrometry-large-language-model)

## Representative Publications

1. **Ji, H.**; Xu, Y.; Lu, H.; Zhang, Z. Deep MS/MS-Aided Structural-Similarity Scoring for Unknown Metabolite Identification. *Anal. Chem*. 2019, 91 (9), 5629–5637. [link](https://pubs.acs.org/doi/10.1021/acs.analchem.8b05405)
2. **Ji, H.**; Deng, H.; Lu, H.; Zhang, Z. Predicting a Molecular Fingerprint from an Electron Ionization Mass Spectrum with Deep Neural Networks. *Anal. Chem*. 2020, 92 (13), 8649–8653. [link](https://pubs.acs.org/doi/10.1021/acs.analchem.0c01450)
3. Yang, Q.#; **Ji, H.**#; Xu, Z.; Li, Y.; Wang, P.; Sun, J.; Fan, X.; Zhang, H.; Lu, H.; Zhang, Z. Ultra-Fast and Accurate Electron Ionization Mass Spectrum Matching for Compound Identification with Million-Scale in-Silico Library. *Nat. Commun*. 2023, 14 (1), 3722. [link](https://www.nature.com/articles/s41467-023-39279-7)
4. **Ji, H.**#; Lu, X.#; Zhao, S.; Wang, Q.; Bin, L.; Huber, K. V. M.; Luo, R.; Tian, R.; Tan, C. S. H. Target deconvolution with matrix-augmented pooling strategy reveals cell-specific drug-protein interactions. *Cell Chem. Biol*. 2023, 30(11) 1478-1487. [link](https://linkinghub.elsevier.com/retrieve/pii/S245194562300274X)
5. **Ji, H.**; Lu, X.; Zheng, Z.; Sun, S.; Tan, C.S.H. ProSAP: A GUI Software Tool for Statistical Analysis and Assessment of Thermal Stability Data. *Brief. Bioinform*. 2022, 23 (3), bbac057. [link](https://doi.org/10.1093/bib/bbac057)  

[More publications](publications.md)
