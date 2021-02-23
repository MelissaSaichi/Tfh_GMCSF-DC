# GM-CSF-activated human dendritic cells promote Tfh1 polarization in a CD40- dependent manner

Using single-cell RNA sequencing  (10X technology) on CD4+T cells, we report that GM-CSF-activated human blood CD1c+ dendritic cells (DC) (cDC2) drive the differentiation of naïve CD4+ T cells into Tfh1. These Tfh1 cells displayed typical Tfh molecular features, including high levels of PD-1, CXCR5, and ICOS. They co-expressed Bcl6 and T-bet, and secreted large amounts of IL-21 and IFN-γ. 

## Computational objectives

1- Analyze scRNAseq of CD4 T cells activated with different DC set-ups.

2- Validate the correlation between DC-ICOSLlow & TFH1 cells in Tuberculosis microarray data ( Berry London dataset) & in COVID-19 PBMC scRNAseq data 

## Folder components
- ### GEO_Submission_scRNAseq_polarized_CD4Tcells: Comprises 
  - **the RAW files** : .fastq files from CellRanger
  - **PROCESSED files** : both the **Raw count matrices** from cell ranger and the **FINAL SEURAT Objects** 
  - **METADATA** which describes all the samples and files
  
- ### Analysis folder:
has .png figures generated during the analysis
- ### Script: has the .Rmd Scripts
- ### COVID19_Tfh: Analysis performed on the PBMC COVID19 scRNAseq public dataset
-### TB_Tfh: Analysis performed on the Tuberculosis Microarray Berry London dataset
- ### Manuscript: Cell reports output file 

 Folder architecture
 
 

├── GEO_Submission_scRNAseq_polarized_CD4Tcells
│   ├── Metadata
│   ├── Processed_Data
│   │   ├── Raw_Matrices
│   │   └── Seurat_Objects
│   └── Raw_Data
├── Manuscript
│   ├── Figures_Paper
│   └── Paper\ Korniotis\ et\ al.\ Tfh1\ -\ Submission\ next\ Tuesday
├── PublicDatasets_Analysis
│   ├── PBMC_COVID19_scRNAseq
│   │   ├── Analysis_Files
│   │   ├── Figures
│   │   ├── Script
│   │   └── Seurat_Rds
│   └── Tuberculosis_BerryLondon_Dataset
│       ├── Articles
│       ├── Figures_Analysis
│       └── Script
└── scRNAseq_CD4Tcells_activated
    ├── Analysis_GMCSF
    │   ├── Figures
    │   └── Seurat_Rds
    ├── Analysis_LPS
    │   ├── Figures
    │   └── Seurat_Rds
    ├── Analysis_MEDIUM
    │   ├── Figures
    │   └── Seurat
    └── Global_Scripts

