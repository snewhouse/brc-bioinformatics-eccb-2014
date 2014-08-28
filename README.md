brc-bioinformatics-eccb-2014
============================

Abstracts presented at ECCB 2014

# ECCB

[ECCB'14](http://www.eccb14.org/) is the key European computational biology event in 2014 gathering scientists working at the intersection of a broad range of disciplines including computer science, mathematics, biology, and medicine. New challenges are emerging today in these fields with the recent advances in low-cost ultra-fast sequencing, bio-imaging and big-data approaches. Databases and software are evolving especially rapidly. Nonetheless, new algorithms are still required to improve computing with massive biological or biomedical data. Indeed, multi-scale integrative analyses are struggling to deal with the enormous complexity of biological systems modeling and the "data deluge" that results from next-generation sequencing technologies.

Participation at ECCB'14 will be the prime opportunity to keep pace with cutting-edge research in such exciting topics, and to network with other members of our community.

****************

NIHR BRC-MH Bioinformatics Core: ECCB 2014
==============================================
## Abstracts

- [The Brain and Behaviour Genetic Resource Exchange – BB-GRE](https://github.com/snewhouse/brc-bioinformatics-eccb-2014/blob/master/README.md#the-brain-and-behaviour-genetic-resource-exchange--bb-gre)  
- [CohortExplorer](https://github.com/snewhouse/brc-bioinformatics-eccb-2014/blob/master/README.md#cohortexplorer-a-generic-application-programming-interface-api-for-entity-attribute-value-database-schemas)  
- [NGSeasy](https://github.com/snewhouse/brc-bioinformatics-eccb-2014/blob/master/README.md#ngseasy-easy-analysis-of-next-generation-sequencing-a-flexible-easy-to-use-automated-ngs-pipeline-for-research-and-clinical-laboratories)  
- [Exploiting the Quantified Self for clinical care](https://github.com/snewhouse/brc-bioinformatics-eccb-2014/blob/master/README.md#exploiting-the-quantified-self-for-clinical-care-a-framework-for-integrating-mobile-and-sensor-data-into-the-electronic-health-record)  
- [Cross-disorder assessment of a diagnostic Alzheimer’s disease gene expression signature](https://github.com/snewhouse/brc-bioinformatics-eccb-2014/blob/master/README.md#cross-disorder-assessment-of-a-diagnostic-alzheimers-disease-gene-expression-signature)  
- [Identification and Replication of Cis and Trans Effect Protein Quantitative Trait Loci in Ageing Adults](https://github.com/snewhouse/brc-bioinformatics-eccb-2014/blob/master/README.md#identification-and-replication-of-cis-and-trans-effect-protein-quantitative-trait-loci-in-ageing-adults)  
- [Circulating proteomic signatures of chronological age](https://github.com/snewhouse/brc-bioinformatics-eccb-2014/blob/master/README.md#circulating-proteomic-signatures-of-chronological-age)  
- [The use of Polygenic Risk Scores for predicting rate of cognitive decline in Alzheimer’s disease](https://github.com/snewhouse/brc-bioinformatics-eccb-2014/blob/master/README.md#the-use-of-polygenic-risk-scores-for-predicting-rate-of-cognitive-decline-in-alzheimers-disease)  
- [Predicting tumour grade across multiple adenocarcinomas using exome sequence data.](https://github.com/snewhouse/brc-bioinformatics-eccb-2014/blob/master/README.md#predicting-tumour-grade-across-multiple-adenocarcinomas-using-exome-sequence-data)  
- [Blood based gene expression markers of Alzheimer’s Disease diagnosis: a pathway based approach](https://github.com/snewhouse/brc-bioinformatics-eccb-2014/blob/master/README.md#blood-based-gene-expression-markers-of-alzheimers-disease-diagnosis-a-pathway-based-approach)   

****************

# The Brain and Behaviour Genetic Resource Exchange – BB-GRE
## Mr Abhishek Dixit

Studies of copy number variation (genomic imbalance) are providing insight into both complex and Mendelian genetic disorders. Array comparative genomic hybridization (array CGH), a tool for detecting copy number variants at a resolution previously unattainable in clinical diagnostics, is increasingly used as a first-line test at clinical genetics laboratories. Many copy number variants are of unknown significance; correlation and comparison with other patients will therefore be essential for interpretation. We present a resource for clinicians and researchers to identify specific copy number variants and associated phenotypes in patients from a single catchment area, tested using array CGH at the SE Thames Regional Genetics Centre, London. User-friendly searching is available, with links to external resources, providing a powerful tool for the elucidation of gene function. We hope to promote research by facilitating interactions between researchers and patients. The BBGRE (Brain and Body Genetic Resource Exchange) resource can be accessed at the following website: http://bbgre.org DATABASE URL: http://bbgre.org.  

****************
# CohortExplorer: A generic application programming interface (API) for entity attribute value database schemas
## Mr Abhishek Dixit
Most electronic data capture tools developed to collect and store clinical data from participants recruited into studies are based on generic Entity-Attribute-Value (EAV) database schemas which enable rapid and flexible deployment in a range of study designs. The drawback to such schemas is that they are cumbersome to query with structured query language (SQL). The problem increases when researchers involved in multiple studies use multiple electronic data capture tools each with variation on the EAV schema. We have developed a tool, CohortExplorer, which once configured for a EAV system will ‘plug-n-play’ with EAV schemas, enabling the easy construction of complex queries through an abstracted interface. To demonstrate the utility of the CohortExplorer system, we show how it can be used with the popular EAV based frameworks; Opal (OBiBa) and REDCap. The application is available under a GPL-3+ license at the following URL: https://www.metacpan.org/pod/CohortExplorer. The application source code is available on GitHub at the following URL: https://www.github.com/abhishekdxt/CohortExplorer and the users are encouraged to suggest new features and contribute to development of APIs for new EAV systems.  

****************
# NGSeasy (Easy Analysis of Next Generation Sequencing): a flexible, easy to use automated NGS pipeline for research and clinical laboratories.
## Dr Amos Folarin
We present NGSeasy (Easy Analysis of Next Generation Sequencing), a flexible and easy to use NGS pipeline for automated alignment, quality control, variant calling and annotation for research and clinical reporting.  

The software pipeline allows users with minimal computational/bioinformatic skills to be able set up and run a NGS pipeline on their own samples in less than an afternoon, as a virtual machine or container on any operating system (Windows, iOS, Linux). NGSeasy can be deployed on any medium to high-end workstation, high performance computer cluster and the cloud (public/private cloud computing) - enabling instant access without investment overheads for additional hardware and providing a solution for rapid and efficient deployment of NGS pipelines for clinical and research laboratories of all sizes.  

The pipeline is controlled from a single configuration file, produced in excel, that allows the user to upload sample/run related information and control multiple run parameters eg RAM, CPU usage, sample names, project names etc. eaNGS also provides flexibility to use multiple open-source aligners (stampy and bwa) and provide guidance for use with novoalign (commercial) .  

We have adapted the current best practices from the Genome Analysis Toolkit (GATK) for processing raw alignments in SAM/BAM format and variant calling. The current workflow, has been optimised for Illumina Platforms, but can easily be adapted for other  sequencing platforms, with minimal effort.  

We provide a modular workflow that runs from raw fastq file to final report and allow users to easily select from a range of modules: 1) Full Pipeline (fastq to full reports), 2) Alignment, 3) Indel Realignment and Base Recalibration, 4) SNP and small INDEL Variant Calling (single/multi sample), 5) Structural Variant Calling, 6) Alignment Quality Control Reports, 7)  Variant Annotation, 8) Variant Reports and 9) Custom Reports (HTML) . The pipeline can be used for population level, family based, single samples and cancer related studies.  

The NGSeasy pipeline will be made available as virtual machine, along with all scripts and detailed documentation for installation and configuration for alternative sequencing platforms and operating systems.  

****************
# Exploiting the Quantified Self for clinical care: a framework for integrating mobile and sensor data into the electronic health record
## Dr Cass Johnson
Rapid and continued advancement in 'omics technologies have provided us with a wealth of high resolution information on the inner workings of disease and genetic variability. A collateral rise in technological advances and widespread availability of mobile phones has at the same time been observed. These mobile technologies promise the potential of gaining equally fine grained information on patient behaviour and environment, especially when paired with additional small wearable probes that report specific information on the user. The ability to capture this data and report it back into the clinical record will be of immediate benefit, such as providing clinical trials with high resolution data for patient stratification, real-time response to treatment, and directly improve patient care and efficiency of intervention.  

SLaM employs an electronic health record (EHR): the Patient Journey System (PJS) and has implemented a de-identified derivative of this EHR for research use:  the Case Register Interactive Search (CRIS). Research projects can apply for access to CRIS data through a well-developed governance framework. To give patients a more interactive relationship with their clinical record, SLaM is using MyHealthLocker, a system built on top of Microsoft HealthVault. Clinicians can elect to share EHR data with their patients and patients can submit data to their own health record and elect to share parts of that record with their treatment team.  

The Purple Robot application, developed by the Centre for Behavioural Intervention Technology (CBITS) at Northwestern University, provides both an interface to the on-board mobile phone probes (e.g. gps, light, temperature) and also a framework for integrating other mobile-aware probes e.g. worn accelerometers, oxygen saturation, heart rate, blood pressure, blood glucose etc. Using this platform, we have built a framework to enable patient reported outcome (PROM) data from smartphone applications, smartphone sensors and other sensor devices to be collected and analysed. Pertinent summary data can then be exported into HealthVault and, through a MyHealthLocker widget, patients can access and visualise their data and choose to share that data with their care team or researchers.  

We have developed a proof-of-concept application which tracks sleep (quantity and quality) using mobile phone embedded sensors (GPS, light), a secondary wrist-worn accelerometer sensor (Fitbit) and  patient reported information provided through an Android application. Data are cached in HealthVault and patient and researcher/clinician views presented through MyHealthLocker.  

****************
# Cross-disorder assessment of a diagnostic Alzheimer’s disease gene expression signature
## Dr Martina Sattlecker
**Background:** In recent years several gene expression patterns have been identified for diagnosis of various disorders, for instance we identified a 48 gene signature in peripheral blood predicting Alzheimer’s disease (AD) with 75% accuracy. However, no attempt has been made to assess if diagnostic models are disease specific or weather they or share a common aetiology amongst disorders disorders.  We tested our Alzheimer’s disease gene expression patterns for disease specificity across neurological and age related disorders.  
**Material and methods:** We obtained 17 data sets, including neurological, autoimmune, diabetes and arterial related disorders from public depositories. Each dataset varied from one another by either microarray-platform used to generate the data (Illumina or Affymetrix), expression chip (2 different expression chips used for Illumina and 4 different expression chips used for Affymetrix), sample size (33 to 222) and sample type (blood or brain). For each dataset 1000 Random Forest classification models using the genes from the AD gene expression pattern were built by bootstrapping 75% of the smallest group from case/control, using equal bootstrapped complimentary case/control numbers and building a model with the probes to which the 48 genes mapped to.  
**Results:** The average accuracy, sensitivity and specificity over the 1000 models were calculated to demonstrate these 48 genes are not specific to AD and can be implemented as a diagnostic classifier in all 17 datasets to achieve an accuracy range of 89% (Rheumatoid arthritis) to  72% (Parkinson’s disease), sensitivity range from 92% (Rheumatoid arthritis) to 71% (Parkinson’s disease) and a specificity range of 74% (Parkinson’s disease) to 91% (Amyotrophic Lateral Sclerosis). We also compared the gene expression in blood to brain expression and an accuracy range of 73% (Major Depressive Disorder) to 82% (schizophrenia). Heat maps of the most influential genes in each classifier model across disorders indicated that no single gene was the driving force behind the classifiers and differential expression analysis suggests a different subset of genes in each disorder are most likely driving the classifier. Permutation tests verified the classifier is not influencing the results, and correlation tests showed no association with dataset sample size to results.  
**Conclusion:** Our results suggest that the AD gene expression signature might not be AD specific, rather an indication of ill health. Further investigations and comparisons of signatures for other disorders are required.  


****************

# Identification and Replication of Cis and Trans Effect Protein Quantitative Trait Loci in Ageing Adults
## Dr Jen Mollon
In this study we use an aptamer-based protein assay from SomaLogic and combine this with genotyped and imputed SNPs to identify protein quantitative trait loci (pQTLs). We map our hits to eQTLs in a subset of our samples as well as published eQTLS in other tissues.  

Samples from 106 individuals with Alzheimer's Diseases (AD), 90 with mild cognitive impairment (MCI) and 101 healthy elderly controls were selected from the AddNeuroMed (ANM) cohort.  Genotyping and imputation of these samples resulted in 6 345 198 SNPs from 297 individuals, and 1001 proteins targeted by 1016 SOMAmers were assayed in plasma from the same individuals.  We used regression to measure single-SNP effects, adjusting for age, gender, diseases status and 5 genetic principle component axes.  A strict Bonferroni threshold was used, allowing for multiple SNP signals as well as the 1016 protein phenotypes.  Replication was carried out in 102 unrelated individuals from the Healthy Aging in Twins Study (HATS).  

We identified 100 novel pQTLs in 88 different proteins, with 22 cis- (within 300kb of the protein-coding gene) and 78 trans-effects.  We found the pQTL SNPs to be highly enriched for hits in the NHGRI GWAS catalogue, and cis-hits were highly enriched for non-synonomous SNPs.  Eighty-six SNP/protein combinations were available in HATS, with 19 cis and 12 trans associations replicating at a nominal level of p<0.05.  Our top novel, replicated cis-hit was missense mutation rs3197999; the minor allele was associated with decreased levels of MST1 (p=3.83x10-74).  This SNP has been implicated in inflammatory bowel disease and primary sclerosing cholangitis. The top novel, replicated trans-hit was rs12614 (missense mutation in CFB), with the minor allele associated with increased levels of MMP8 (p=2.88x10-70).  We replicated 25/41 published pQTLs from other groups, and 85/94 from our previous pQTL.  Only 2 pQTLs mapped to eQTLs in plasma from the same individuals while 3 pQTLs are eQTLS in blood in gTEX, suggesting pQTL proteins are produced in other tissues.  Several our cis-pQTL SNPs are cis-eQTLS for other, nearby genes, for example rs62012908 and TPSAB1 (p=1.99x10-11).  In gTEX this SNP/gene combination is an eQTL in blood, and rs62012908 is also an eQTL for TPSD1 in six tissues, and for RP11 in four tissues.  

We have presented strong evidence of novel genetic control of protein expression. The study of such intermediary phenotypes may help unravel mechanisms through which genetic effects manifest in disease.  

****************

# Circulating proteomic signatures of chronological age
## Dr Steve Kiddle
**Objectives:** To elucidate the proteomic features of aging in plasma.  
**Methods:** The sub-proteome targeted by the SOMAscan assay was profiled in blood samples from 202 females from the TwinsUK (TUK) cohort and findings were replicated in 677 independent individuals from the AddNeuroMed, Alzheimer’s Research UK and Dementia Case Registry cohorts (collectively referred to as ANM+ARUK+DCR). Results were further validated using RNAseq data from whole blood in TwinsUK and the most significant proteins were tested for association with aging-related phenotypes after adjustment for age.  
**Results:** 11 proteins were associated with chronological age and were replicated at protein level in an independent population. These were further investigated at gene expression level in 384 females from the TwinsUK cohort. The two most strongly associated proteins were chordin-like protein 1 (CHRDL1, meta-analysis Beta(SE)=0.013(0.001), P= 3.66 x10-46)  and pleiotrophin (PTN) (0.012(0.005), P= 3.88x10-41). CHRDL1 was also significantly correlated with birthweight (0.06(0.02), P=0.005) and with the individual Framingham 10-years cardiovascular risk scores in TwinsUK (0.71(0.18), P= 9.9x10-5). PTN is a secreted growth factor with a plethora of functions in multiple tissues, and known to be a marker for cardiovascular risk and osteoporosis.  
**Conclusion:** Our study highlights the importance of proteomics to identify some molecular mechanisms involved in human health and aging.  


****************

# The use of Polygenic Risk Scores for predicting rate of cognitive decline in Alzheimer’s disease
## Miss Elizabeth Baker (PhD Student)
**Background:** There is huge variability in how patients with Alzheimer’ Disease (AD) progress in terms of their rate of cognitive decline.  It is reasonable to assume there is a genetic component to rate of progression, yet whilst there has been considerable progress in determining the genetic underpinnings of AD itself, with a recent study by Lambert el al identifying 11 new loci in the largest study to date, few studies have investigated the genetics of decline beyond the Apolipoprotein E gene. With rate of cognitive decline being a progressive phenotype with sigmoidal change over time, it may well be that multiple genes of low effect are acting together to infer susceptibility to AD progression. In this study we investigate the association between an AD polygenic risk score (PRS) and a patients rate of decline, to investigate whether patients having a high burden of risk alleles tend to be rapid decliners.  
**Method:** 874 subjects from the EU IMI AddNeuroMed (ANM) have been genotyped and imputed based on the 1000 Genomes datasets. Using SNPs from two large GWAS studies of AD diagnosis (Harold et al 2009 and Lambert et al 2013), a PRS has been calculated for each AD individual within ANM. Rate of cognitive decline estimates have also been generated for these subjects and as such the association with PRS will be investigated.  
**Results:** This study will quantify the association between the genetic risk burden harbored by a patient and their rate of cognitive decline in disease.  
**Discussion:** Our results will add to understanding of the genetic component of cognitive decline in AD subjects and improve our understanding of the contribution of genetic factors to the variability of AD progression. The polygenic risk profile may aid prediction of future cognitive decline in AD patients.  


****************

# Predicting tumour grade across multiple adenocarcinomas using exome sequence data.
## Mr Russel Sutherland (PhD Student) 
**Background:** There is a need for tumour grading tools that are applicable across multiple cancer types in order to make tumour grading a more objective process. Most tumour grading systems are only applicable to a single cancer type. The aim of this study was to develop a tumour grading prediction model using tumour/normal exome sequence data as a tumour grading decision support tool for Pathologists.  
**Methods:** We used exome sequence tumour/normal variant data and clinical data from the Pan Cancer Analysis from 970 patients with Kidney Renal Cell Carcinoma, Ovarian Carcinoma and Endometrial Carcinoma. We created a sample (S) by protein coding gene (P) “binary mutation matrix” that indicated the presence of any protein coding mutation for a sample (s) at a protein (p). Using the “binary mutation matrix” together with age, gender and cancer stage clinical variables we used multivariate logistic regression and Akaike Information Criterion (AIC) based backwards model selection to create classification models to predict the high grade or low grade status of tumours across cancer types and within cancer types. It was important to include the gender clinical variable to control for any gender bias introduced by the Endometrial and Ovarian Carcinomas. Classification accuracy, sensitivity and specificity were measured in an independent test set along with the area under the receiver operator characteristic (ROC) curves.  
**Results:** Across cancer types an AIC refined multivariate logistic regression model including 13 protein coding genes; TP53, MUC4, ANK2, CCDC171, CDH7, CTCF, CTNNB1, MYOF, NALCN, PARD3, PKD1L1, PTPRK and RAPGEF2 along with the cancer stage and age clinical variables was able to assign tumours to the correct grade status with an area under the curve (AUC) of 0.821. By comparison, the model using gender and cancer stage clinical variables refined from a model including clinical variables achieved an AUC of 0.756. The multivariate logistic regression model in Endometrial Carcinoma refined from protein coding genes and clinical variables age and stage included TP53, PTEN and cancer stage and performed with an AUC of 0.879 in comparison to a model including age and stage clinical variables that achieved an AUC of 0.753.  
**Conclusions:** There are protein coding genes across cancer types that are predictive of tumour grade when adjusting for cancer stage. The genes ANK2, CDH7, and CTNNB1 are involved in tumour and stromal cell interactions important in tumour progression. MUC4 is involved in glandular differentiation, important for adenocarcinomas. Mutations in TP53 can be indicative of aggressive tumour types. The 13 protein features capture predictive information in addition to that provided by age gender and cancer stage clinical variables.  

****************

# Blood based gene expression markers of Alzheimer’s Disease diagnosis: a pathway based approach
## Miss Nicola Voyle (PhD Student)
**Abstract:** Background: Methods of diagnosing Alzheimer’s Disease (AD) are invasive and expensive while treatments of AD only provide symptomatic relief. Discovery of a blood-based biomarker of disease would reduce the number of patients subject to such diagnostics and increase the likelihood of finding an effective treatment.  
Gene expression levels in blood are potential markers of AD [1]. However, limited findings are replicated in independent datasets, possibly due to differences in platforms, technologies and study design. We hypothesized that considering changes in gene expression at the pathway level may create a more robust model.  
**Materials and Methods:** 201 samples from the AddNeuroMed study were used to build and test a clinical diagnostic model, based on gene expression data, age, gender and ApoE4 genotype [2] . Genes were then grouped into pathways and scored using Gene Set Variation Analysis, to assign a pathway expression measure at the sample level [3]. The models were built in training data and tested on held out test data using Random Forests [4]. The model was compared with that built using age, gender and ApoE4 genotype alone. 
The diagnostic model was assessed for stability in an independent dataset of 173 samples.  
**Results:** In test data the model showed an accuracy of 0.60 using pathway predictors in comparison to 0.71 for gene level data. The model built using age, gender and ApoE4 genotype alone showed an accuracy of 0.49. Using a pathway approach enabled us to easily test the stability of the classifier in the independent dataset generated using a different version of the array.  
**Conclusions:** A pathway level analysis of gene expression enables application of predictive models across different datasets, produced using different platforms, with ease. It also reduces the dimensionality of these very large datasets. We think the use of a pathway based approach will enable the development of more robust predictive models of Alzheimer’s Disease diagnosis.  
