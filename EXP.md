## EXPERIENCE

---
#### Microbiome Data Scientist | Microbiome Insights Inc | Vancouver, BC, Canada |Feb 2020 - present

Analysed microbiome data obtained from **fecal, skin, oral, saliva, insect & soil** samples from more than **100 projects** 
#### Selected projects:
1. Study the effect of **Ivermectin on gut microbiota** using animal model - **_Peggy L Kandell, MD_, Washington University in St Louis.**
   -  Leaded and performed microbiome data (16Sv4) analysis (community examination in [3D plot](http://www.sthda.com/english/wiki/impressive-package-for-3d-and-4d-graph-r-software-and-data-visualization), identifying differential abundant taxa)
   -  Applied unsupervised clustering technique to distinguish main traits by microbiome features
   -  Identified co-abundance group (CAG: [method](https://link.springer.com/article/10.1186/s40168-020-00887-w;)) of bacteria and assessed their inter and intra [association network](https://cytoscape.org/) to evaluate the impact of Ivermectin on bacterial ecology

2. Comparing **biofilms**, which were obtained from **dental plaque**, grown on different materials - **_Thomas M. Johnson DMD, MS, COL, DC_, USARMY DENCOM ATLANTIC (USA) & _Joseph Retrum, DMD, MAJ, DC_, US Army Advanced Education in Periodontics, Tingay Dental Clinic**
   - Processed raw amplicon sequencing data (16Sv3v4) to generate amplicon sequencing variant (ASV) table 
   - Performed [Linear mixed model](https://cran.r-project.org/web/packages/lme4/vignettes/lmer.pdf) to evaluate richness and evenness of longitudinal data
   - Performed Adonis test and pairwise comparisons to assess beta-diversity of bacterial communities
   - Identified abundant taxa which are significantly different to test hypotheses using [DEseq2](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-014-0550-8) method 
 3. Identifying possible **pathogenic** bacteria inside Asian long horned **ticks** - **_LTC Sillas Davidson,Msc, PhD_, United State Military Academy WEST POINT**
      - Executed automate pipeline to visualise proportion of different types of bacteria in each sample at different taxonomic levels (Phylum - genus) in a [stacked bar plot](https://www.r-graph-gallery.com/stacked-barplot.html) using [Phyloseq](https://joey711.github.io/phyloseq/) package in R. 
      - Computed different diversity indices to compare microbiome across groups by ANOVA
      - Performed literature search to avoid false positive results
      - Interpreted the results and explained the analysis and discussed the future direction with the client
4. Study the effect of wearing a **N95 mask** on **skin microbiome** - **_Grey Hillerband, PhD_, Ammway**
   - Processed raw amplicon sequencing data (16Sv1v3) to generate OTU table 
   - Examined longitudinal data of skin microbiome and performed univariate & multivariate analysis
   - Visualised and interpret the results
5. Study the effect of aggregate mining disturbance on **soil microbiome** - **_Akshit Puri, PhD_, University College Dublin**
   - Processed raw amplicon sequencing data (16Sv4 & ITS2)
   - Illustrated microbiome and mycobiom communities using [Krona chart](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-12-385)
   - Converting microbiome data using [Phylogenetic Isometric Log-Ratio Transform (Philr)](https://bioconductor.org/packages/release/bioc/html/philr.html) before applying [environmental fitting vector](https://www.rdocumentation.org/packages/vegan/versions/2.4-2/topics/envfit) to determine the association between microorganism and soil parameters on [principal component analysis](https://www.nature.com/articles/nmeth.4346)


#### Voluntary Project 

+ [Efficacy of Lifestyle Intervention in BRCA1/2 Mutation Carriers (LIBRE-2)](https://clinicaltrials.gov/ct2/show/NCT02516540) - _**Prof. Stephan C Bischoff, MD**_, **University of Hohenheim** 
    - Leaded the data analysis part to study the impact of Mediterranean diet on gut barrier function of women with high risk of breast cancer
    - Performed [Mediation analysis](https://cran.r-project.org/web/packages/mediation/vignettes/mediation.pdf) to identify the possible mechanisms between Diet, SCFA and gut barrier function
    - Identified different patterns of the response within the same treatment to raise the question regarding individualised responses by [clustering subjects](https://www.rdocumentation.org/packages/factoextra/versions/1.0.7/topics/fviz_dend) on [circle heatmap](https://jokergoo.github.io/circlize_book/book/circos-heatmap.html)
    - Visualised multi-dimensional data in [complex heatmap](https://jokergoo.github.io/ComplexHeatmap-reference/book/) 
    - Performed Machine learning (Random Forest Classification - [Caret package](https://cran.r-project.org/web/packages/caret/vignettes/caret.html); [ROC curve](https://cran.r-project.org/web/packages/ROSE/ROSE.pdf) ) to test if baseline characteristics can determine the individual response to Mediterranean diet
    - Introduced the study, design, method and results by generating infographic figure
    - Generated the [discussion figure](https://biorender.com/) which highlights the implication of machine learning in predicting the response and raised the questions on the possible underline mechanisms of how diet can impact the gut integrity. 
    - Participated in writing the manuscript

     
### Research Assistant | Li Ka Shing Center for Health Research Innovation| University of Alberta | Edmonton, AB, Canada | May 2016 - Jan 2020

#### Main Projects
 
- Participated in  [FYBER project](https://clinicaltrials.gov/ct2/show/NCT02322112) & [RESISTANT STARCH TYPE-4 project](https://clinicaltrials.gov/ct2/show/NCT03255603)
   - Processed, extracted and quantified bacterial DNA from fecal samples

   - Processed raw 16S rRNA (v5v6) sequencing data by ([QIIME](http://qiime.org/), [USEARCH](https://www.drive5.com/usearch/), [FASTX-Toolkit](http://hannonlab.cshl.edu/fastx_toolkit/))
   - Applied [Centered-log-ratio](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5695134/) to transform microbiome data to control for compositionality 
  
   - Assessed bacterial community by a wide range of Alpha diversity indices (**Shannon, Simpson, Observed species, Unifrac**), Beta diversity distances (**Bray-curtis, Euclidean - with transformed data**) visualised in PCoA or [NMDS](https://mb3is.megx.net/gustame/dissimilarity-based-methods/nmds))
   
   - Performed univariate and multivariate analyses for dietary, microbiome, SCFA data in controlling for small sample size and longitudinal design ([GEE model](https://www.jstatsoft.org/article/view/v015i02); Mann-whitney, Wilcoxon sign ranked test, Friedman test, [Multiple linear regression](https://www.investopedia.com/terms/m/mlr.asp), [AICc](https://www.rdocumentation.org/packages/AICcmodavg/versions/2.3-1/topics/AICc) for model selection)

   - Supported the multidisciplinary team in data analysis and bioinformatic by consulting, developing statistical analysis plans, performing advanced analyses, visualizing data, writing code for particular statistical tasks, gathering and depositing genomic data, identifying taxonomy and gene functions.
   
   - Contributed to grant application by preparing SOP, manuals of gut microbiome analysis from human sample collection to data analysis.
 
   - Assisted the PI by explaining the statistical approaches, providing slides for conference and meeting with companies, conducting literature review and training a visiting scholar in a collaborative project.
      

### Research Assistant | International University - VNU - HCM| HoChiMinh city | Vietnam | July 2012-Oct 2015

-  Kombucha project
   -  Leaded the Kombucha project to study microbial symbiosis and producing glucuronic acid – a detoxifying reagent
   -  Conceived the idea and designed the experiment, collected & analysed data, wrote 3 papers and earned both first and corresponding author.
   -  Expanded and built network to seek for help/support to solve difficulties. 


---
## SERVICES
---
- Peer Review ([Publon](https://publons.com/researcher/862046/khoi-nguyen-nguyen/)):
-     **Clinical and Translational Medicine (IF 11.4) 
-     **Food science and technology international (IF 2)**
-     **International journal of food science & technology (IF 3.7)**

- Tax preparer: **Canada Revenue Agency** (Community volunteer income tax program-Vancouver) 2021

- Choreography: trained students to perform **Ballroom dancing** for an Anniversary event in School of Biotechnology, International University – Vietnam

- American society for nutrition: membership

- American society for Microbiology: membership



## [BACK](https://biokhoi.github.io/)
