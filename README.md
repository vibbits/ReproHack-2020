# ReproHack

*A hackaton on reproducible data analysis*

## 1. Introduction
Did you ever read a paper with insufficient documentation and poorly understandable data analysis? Or are you struggling with reproducing your own analyses? We're all cheering for researchers making their data analysis reproducible, although it's kind of a struggle to do it ourselves. On 20th October 2020, we gather for the first ReproHack organized in Belgium. ReproHack is an acronym for Reproducibility Hackaton and encourages papers to be published with reproducible code and accessible data.

## 2. What is ReproHack
During a ReproHack, participants attempt to reproduce published research of their choice from a list of proposed papers with publicly available associated code and data. This approach should provide a low-pressure environment to actually get working with other people's code and data. Besides evaluating the analysis of papers, this hackaton is also about working together, networking and learning from each other! 

*Disclaimer: It’s imperative to note that ReproHacks are by no means an attempt to criticise or discredit work. We see reproduction as beneficial scientific activity in itself, with useful outcomes for authors and valuable learning experiences for the participants and the research community as a whole.*

## 3. Participate
Participations are free of charge and we encourage everyone with some experience in bioinformatics and data analysis to register for this hackaton.

1. Nominate a paper

We accept nominations from anyone. Both researchers that have submitted a paper and would like to test whether one of their own papers is reproducible, and researchers that want to dig into the code of another paper! Either way, we encourage proponents to seek consent from the original authors for their nominations. Nominate a paper by filling in [this link](https://forms.gle/VQCkWdifUhL6EWja8)    
When selecting a paper, please keep in mind some of the following points:
- Is the data-analysis achievable in one day?
- How big is the data and should we subselect part of it on beforehand?
- Does the paper/code describes trivial topics which align with the knowledge of other people?


2. Register as participant  

Join us at the hackaton and register [here](https://training.vib.be/reprohack-hackaton-reproducible-data-analysis).

## List of proposed papers
### 1. Assessing sub-cellular resolution in spatial proteomics experiments.    
**Paper:** Assessing sub-cellular resolution in spatial proteomics experiments  
Laurent Gatto, Lisa M Breckels, Kathryn S Lilley (2019) Current Opinion in Chemical Biology, 48, pages 123-149

**Why should we attempt to reproduce this paper?** There is a github repo with documentation on how to reproduce this paper including data, code and which packages should be installed. It would be interesting if it now, 4y after submission still runs or otherwise just dive in all the information that is given in the repository.

**Paper URL:** https://doi.org/10.1016/j.cbpa.2018.11.015  
**Data URL:** https://github.com/lgatto/QSep-manuscript/  
**Code URL:** https://github.com/lgatto/QSep-manuscript/

**Tags:** `proteomics`, `R`

### 2. A single-cell atlas of mouse brain macrophages reveals unique transcriptional identities shaped by ontogeny and tissue environment  
**Paper:** Van Hove, H., Martens, L., Scheyltjens, I., De Vlaminck, K., Antunes, A. R. P., De Prijck, S., ... & Aerts, J. (2019). A single-cell atlas of mouse brain macrophages reveals unique transcriptional identities shaped by ontogeny and tissue environment. Nature neuroscience, 22(6), 1021-1035.

**Why should we attempt to reproduce this paper?** There is a nice web-interface to start using the data (www.brainimmuneatlas.org). The R codes that were used for scRNA-seq and bulk RNA-seq data analysis can be found on GitHub as well. Could be interesting to inspect. Gives us an entry point to analyze downstream analysis of sc/bulkRNA experiments.


**Paper URL:** https://www.nature.com/articles/s41593-019-0393-4  
**Data URL:** https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE128855  
**Code URL:** https://github.com/saeyslab/brainimmuneatlas/  

**Tags:** `R`, `bulkRNA-seq`, `scRNA-seq` 

### 3. Profiling peripheral nerve macrophages reveals two macrophage subsets with distinct localization, transcriptome and response to injury
**Paper:** Ydens, E., Amann, L., Asselbergh, B., Scott, C. L., Martens, L., Sichien, D., Mossad, O., Blank, T., De Prijck, S., Low, D., Masuda, T., Saeys, Y., Timmerman, V., Stumm, R., Ginhoux, F., Prinz, M., Janssens, S., & Guilliams, M. (2020). Profiling peripheral nerve macrophages reveals two macrophage subsets with distinct localization, transcriptome and response to injury. Nature neuroscience, 23(5), 676–689. https://doi.org/10.1038/s41593-020-0618-6


**Why should we attempt to reproduce this paper?** Both code and data is available in resp. GitHub and NCBI's GEO. It's possible that the analysis isn't going to work out-of-the-box and might be some issues with computing environment, etc.


**Paper URL:** https://www.nature.com/articles/s41593-020-0618-6  
**Data URL:** https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSM4294087  
**Code URL:** https://github.com/saeyslab/MFs_peripheralCentralNerveSystem  


**Tags:** `R`, `transcriptomics` 

### 4. Addressing the pooled amplification paradox with unique molecular identifiers in single-cell RNA-seq
**Paper:** Gustafsson, J., Robinson, J., Nielsen, J., & Pachter, L. (2020). Addressing the pooled amplification paradox with unique molecular identifiers in single-cell RNA-seq. BioRxiv. https://doi.org/10.1101/2020.07.06.188003


**Why should we attempt to reproduce this paper?** Complete data analysis is available in GitHub in Notebooks with command-line tools & R working together. In theory it's just downloading the repo with notebooks and run them on a server (or in Google Colab) that can process them. However, there are a lot of notebooks and structure is unclear. It might not be possible due to too big data files. 


**Paper URL:** https://www.biorxiv.org/content/10.1101/2020.07.06.188003v1.abstract  
**Data URL:** https://www.biorxiv.org/content/biorxiv/early/2020/07/06/2020.07.06.188003/DC1/embed/media-1.pdf?download=true   
**Code URL:** https://github.com/pachterlab/GRNP_2020  
 

**Tags:** `R`, `scRNA-seq`

### 5. Your paper?    
Nominate a paper by filling in [this link](https://forms.gle/VQCkWdifUhL6EWja8)  
