#Training#
Title proposal: 
# How to use single-cell RNA-seq to advance your study: workflow and considerations. 

# Self-introduction: previous projects on single cell RNAseq
>>Wetlab background in stem cell biology and neurodegeneration.
Current function: 
### Promote/support scRNA seq 
### Service scope: Consultation/bioinformatic analysis

# Major modules: 
## Biological question--stay focused on your question. 
#### Well-known advantages
>> -> Heterogeneity
>> -> Transitions 
>> -> Rare cell popolations
>> -> High resolution
#### Be-aware of known challenges
>> -> Transcriptional regulation
>> -> High dropout rates
>> -> Platform setup money/time consuming
>> -> Accessible to professionals and instruments
>> #### Computationally intensive
## Experimental setup, 
-> 10x Genomics / dropseq
-> SmartII pipeline
-> Nextseq 500/Novaseq /Hiseq
-> Other considerations —scATAC, scCite-seq.
## Bioinformatic analysis, 
> ### Languages : shell script/linux + HPC, R, Python
>> -> Shell script
>> -> R/Rstudio/Rmarkdown
>> -> Python/Jupyter lab/ Notebook
>> ### Organization
>>> ####  -> Scripts: Version control git/github
>>> #### -> Folder organization: cookiecutter
>>> #### -> Automation: Snakemake
>>> #### -> Reproduciability: Singularity/ Docker.
> ### Approaches
>> #### Pipelines
-> Pipelines are available, Seurat, you just need to figure out input/output
-> Troubleshooting, you need to know R/Shell, R S4 class and methods.
> ### Consisiderations 
>>> #### Alignment
>>> -> Cellranger
>>> -> Cite-seq-count
>>> #### Routine analysis (Seurat)
>>>> -> Clustering
>>>> -> Temporal/spatial progression
>>>> -> Differential expression —> pathway/GO analysis. (Deseq2, IPA, David, GSEA)
>> #### Selecting candidate for validations
>>> -> Regulatory analysis (iRegulon, Scenic, IPA) 
>>> -> Overlap with existing data/cross validation with other conditions. (Geo datasets, SRA etc)
>>> #### Literature search
## Downstream validations
> ### Expresssional : FISH/IHC
>> -> FISH are timeconsuming 
>>> -> IHC need good antibodies <--analysis need to know what kind of molecules to find for validation.
> ### Functional validation: Virus, Drugs
>> -> Selection of candidates has to be informed by the domain knowledge and must involve intensive discussions. 



