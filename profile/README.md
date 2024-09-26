![ENIGMA BANNER](https://raw.githubusercontent.com/ENIGMA-git/.github/main/Assets/ENIGMA_BANNER.png "ENIGMA")

# ENIGMA GIT


The ENIGMA Consortium is an international effort by leaders worldwide. The Consortium brings together researchers in imaging genomics, neurology and psychiatry, to understand brain structure and function, based on MRI, DTI, fMRI, genetic data and many patient populations.

The ENIGMA Consortium has several goals:
- to create a network of like-minded individuals, interested in pushing forward the field of imaging genetics
- to ensure promising findings are replicated via member collaborations, in order to satisfy the mandates of most journals
- to share ideas, algorithms, data, and information on promising findings or methods
- to facilitate training, including workshops and conferences on key methods and emerging directions in imaging genetics.

Image processing protocols and genetic analysis protocols for various ENIGMA projects are listed below.

## Protocols

<details>
  <summary><h3>ENIGMA sMRI Imaging</h3></summary>
  
> Detailed structural MRI imaging analysis protocols, including subcortical VOLUME extraction, subcortical SHAPE analysis, cortical thickness and surface area, and sulci measure analysis. 
  
  - [ENIGMA-FreeSurfer-protocol](https://github.com/ENIGMA-git/ENIGMA-FreeSurfer-protocol)
  - <details>
    <summary>Sub-segmentation of amygdalar, hippocampal and thalamic nuclei</summary>

    > Container allowing for sub-segmentation of amygdalar, hippocampal and thalamic nuclei using T1-weighted images. 

      - [docker://cvriend/enigma_subthal](https://hub.docker.com/r/cvriend/enigma_subthal)
    </details>
  - <details>
    <summary>Cerebellar and Spinal Cord Pipelines</summary>

    > Cerebellar and Spinal Cord Pipelines from ENIGMA-Ataxia. 

      - [ENIGMA Cerebellum Volumetrics Pipeline](https://forms.gle/N4rcZYfZhiNrh7ri8)
      - [Brain Voxel Based Morphometry](https://github.com/Harding-Lab/enigma-ataxia/tree/master/BrainVoxelBasedMorphometry)
      - [SpinalCord](https://github.com/Harding-Lab/enigma-ataxia/tree/master/SpinalCord)
    </details>
  - <details>
    <summary><a href="https://drive.google.com/drive/folders/0BwYbl1cTDCImck5DTy15UTMwRXc?usp=sharing">ENIGMA Sulci Protocol</a></summary>

    > This protocol allows you to segment, label, and visually inspect 123 cortical sulci/subject using FreeSurfer, BrainVISA, R and ImageMagick.
    > 
    > Development: [Fabrizio Pizzagalli](mailto:fpizzagalli@gmail.com)
    
    </details>
  - <details>
    <summary>ENIGMA Subcortical Shape</summary>

    > Streamlined tool to perform fine-grained analysis of deep gray matter morphometry using standard brain MRI.
      - [Shape Protocol](https://enigma.ini.usc.edu/ongoing/enigma-shape-analysis/)
    </details>
  - <details>
    <summary>Voxel Based Morphometry</summary>
    
      - <details>
        <summary><a href="https://sites.google.com/view/enigmavbm">ENIGMA VBM Tool </a></summary>
    
        > 	The ENIGMA Voxel Based Morphometry (VBM) tool is a fully automated pipeline that performs DARTEL VBM and a number of QC steps and sensitivity analyses. The tool packages up the group data for easy transfer to the coordinating site that performs the voxel-wise meta-analysis.
        >
        > Development: Matthew Kempton, King’s College London. 
        </details>
      - <details>
        <summary><a href="https://neuro-jena.github.io/enigma-cat12/">ENIGMA Computational Anatomy Toolbox (CAT12)</a></summary>
    
        > 	These protocols use [CAT12](https://neuro-jena.github.io/cat/)  to process voxel- and surface-based morphometry, but also enable region-based measures for volume and surface data. CAT12 includes various QC options and covers the entire analysis workflow, from cross-sectional or longitudinal data processing, to the statistical analysis, and visualization of results.
        >
        > Development: Christian Gaser, Jena University Hospital. 
        </details>
    </details>
</details>
<!--   - [PlaceHolder]()
  - [PlaceHolder]() -->

<details>
  <summary><h3>ENIGMA DTI Imaging</h3></summary>
  
> Detailed diffusion tensor imaging protocols for the ENIGMA DTI based projects.
  
  - [ENIGMA-DTI: Preprocessing Guidelines](https://github.com/ENIGMA-git/ENIGMA-DTI-Preprocessing-Guidelines)
  - [ENIGMA-DTI: TBSS Protocol](https://github.com/ENIGMA-git/ENIGMA-DTI-TBSS-Protocol)
  - [ENIGMA-DTI: eHarmonize](https://github.com/ahzhu/eharmonize)
</details>

<!--
<details>
  <summary><h3>ENIGMA Subcortical Shape</h3></summary>

> Detailed protocols for ENIGMA Shape analyses.
  
  - [PlaceHolder]()
  - [PlaceHolder]()
  - [PlaceHolder]()
</details>
-->


<details>
  <summary><h3>ENIGMA Genetics Protocols</h3></summary>
  
> Genetic analysis protocols for ENIGMA1, ENIGMA2 and ENIGMA-Cortex and DTI.

  - [ENIGMA-GWAS: ICV, Subcortical, Cortical](https://github.com/ENIGMA-git/Genetics)
  - [ENIGMA-GWAS: DTI](https://github.com/ENIGMA-git/ENIGMA_DTI_GWAS)
  - [ENIGMA-CNV](https://github.com/ENIGMA-git/ENIGMA-CNV)
  - [GCLUST Phenotype Extraction Protocol](https://github.com/ENIGMA-git/GCLUST)
</details>

<details>
  <summary><h3>ENIGMA Functional Imaging</h3></summary>

> Detailed functional MRI imaging analysis protocols for the ENIGMA resting state and task based fMRI based projects.
  
- [ENIGMA HALFpipe](https://github.com/HALFpipe)
  - [ENIGMA HALFpipe](https://github.com/halfpipe/halfpipe)
  - [Quality Control manual](https://github.com/HALFpipe/QualityCheck)
</details>

<details>
  <summary><h3>ENIGMA Statistical Protocols</h3></summary>
  
  - <details>
    <summary><a href="https://github.com/ENIGMA-git/coMAPR">coMAPR</a></summary>
    
    >  A database-backed set of routines for linear modelling and meta-analysis of Neuroimaging data.
    </details>
  - <details>
    <summary><a href="https://github.com/ENIGMA-git/ENIGMADiseaseWorkingGroupStats">ENIGMADiseaseWorkingGroupStats</a></summary>
    
    >  The script is intended for the batch processing of multiple linear models, and the results can easily be carried forward to meta-analysis with provided scripts. 
    </details>
  - <details>
    <summary>ComBat for ENIGMA</summary>
    
    >  ComBat is a function that allows for removal of known batch effects. This modified version (written in R) of the function for the ENIGMA Consortium also allows to separate functions for fitting and applying the harmonization, and allows missings and constant rows and minor changes in the arguments of the functions to facilitate their use.
    >
    > Please cite “Increased power by harmonizing structural MRI site differences with the ComBat batch adjustment method in ENIGMA” ([Radua et al., NeuroImage 2020](https://www.sciencedirect.com/science/article/pii/S1053811920304420)).
    >
    > [R package can be downloaded here](https://cran.r-project.org/package=combat.enigma) or installed with the command: `install.packages("combat.enigma")`.
    </details>
  - <details>
    <summary>Estimation of multisite accuracy</summary>
    
    >  The effects of the site may severely bias the accuracy of a multisite machine-learning model, even if the analysts removed them when fitting the model in the ‘training set’ and when applying the model in the ‘test set’. This simple R package estimates the accuracy of a multisite machine-learning model unbiasedly. It currently supports the estimation of sensitivity, specificity, balanced accuracy, the area under the curve, correlation, mean squared error, and hazard ratio for binomial, multinomial, gaussian, and survival (time-to-event) outcomes.
    >
    > Please cite “Biased accuracy in multisite machine-learning studies due to incomplete removal of the effects of the site” ([Solanes et al., Psychiatry Res Neuroimaging 2021](https://www.sciencedirect.com/science/article/abs/pii/S0925492721000652?via%3Dihub)).
    >
    > [R package can be downloaded here](https://cran.r-project.org/package=multisite.accuracy) or installed with the command: `install.packages("multisite.accuracy")`. [Browser-based GUI can be accessed here](https://www.imardgroup.com/multisite.accuracy/) (this option does not require installation or any knowledge about R). 
    </details>
<!--  - [coMAPR](https://github.com/ENIGMA-git/coMAPR)
  - [ENIGMADiseaseWorkingGroupStats](https://github.com/ENIGMA-git/ENIGMADiseaseWorkingGroupStats)
  - [ComBat for ENIGMA](https://enigma.ini.usc.edu/wp-content/uploads/2021/07/combat_for_enigma.R.zip)
  - [Estimation of multisite accuracy]() -->

</details>
<details>
<summary><h3>ENIGMA Visualization tools</h3></summary>

  - <details>
    <summary><a href="http://enigma-toolbox.readthedocs.io">ENIGMA Toolbox </a></summary> 
    
    > A Python/Matlab ecosystem for (i) accessing 100+ ENIGMA datasets, facilitating cross-disorder analysis, (ii) visualizing data on brain surfaces, and (iii) contextualizing findings at the microscale (postmortem cytoarchitecture and gene expression) and macroscale (structural and functional connectomes). The ENIGMA Toolbox equips scientists with tutorials to explore molecular, histological, and network correlates of noninvasive neuroimaging markers of brain disorders. Moreover, the ENIGMA Toolbox bridges the gap between standardized data processing protocols and analytic workflows and facilitates cross-consortia initiatives.<br/><br/>
    > Development and support: Sara Larivière & Boris Bernhardt (MICA Lab – Montreal Neurological Institute).

    </details>
</details>
