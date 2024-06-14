
# Workshop: Spatial multi-omics data analysis with Giotto Suite

## August 5-7, 2024

## Book

Find the book at: https://drieslab.github.io/giotto_workshop_2024/

## Instructors

- [Ruben Dries](https://www.drieslab.com/): Assistant Professor of Medicine at Boston University

- [Joselyn Cristina Chávez Fuentes](https://comunidadbioinfo.github.io/es/authors/josschavezf/): Postdoctoral fellow at Icahn School of Medicine at Mount Sinai

- [Jiaji George Chen](https://x/jiaji_g_chen): Ph.D. Student at Boston University

- [Junxiang Xu]()

- [Edward C. Ruiz](https://x.com/ed2uiz): Ph.D. Student at Boston University  

- [Jeff Sheridan]()

- [Wen Wang]()


## Topics and Schedule:


- Day 1: Introduction
    - Spatial omics technologies
        - Spatial sequencing
        - Spatial in situ 
        - Spatial proteomics
        - spatial other: ATAC-seq, lipidomics, etc
    - Introduction to the Giotto package
        - Ecosystem
        - Installation + python environment
        - Giotto instructions
    - Data formatting and Pre-processing
    - Creating a Giotto object
        - From matrix + locations
        - From subcellular raw data (transcripts or images) + polygons
        - Using convenience functions for popular technologies (Vizgen, Xenium, CosMx, …)
    - Spatial plots
    - Subsetting:
        - Based on IDs
        - Based on locations
        - Visualizations
    - Introduction to spatial multi-modal dataset (10X Genomics breast cancer) and goal for the next days
    - Quality control
        - Statistics
    - Normalization
    - Feature selection:
        - Highly Variable Features:
            - loess regression
            - binned
            - pearson residuals
        - Spatial variable genes
    - Dimension Reduction
        - PCA
        - UMAP/t-SNE
        - Visualizations
    - Clustering
        - Non-spatial
            - k-means
            - Hierarchical clustering
            - Leiden/Louvain
        - Spatial
            - Spatial variable genes
            - Spatial co-expression modules

    
- Day 2: Spatial Data Analysis
    - Spatial sequencing based technology: Visium
        - Differential expression
        - Enrichment & Deconvolution
            - PAGE/Rank
            - SpatialDWLS
            - Visualizations
        - Interactive tools
        - Spatial expression patterns
            - Spatial variable genes
            - Spatial co-expression modules
            - Spatial HMRF
    - Spatial sequencing based technology: Visium HD
        - Tiling and aggregation
        - Scalability (duckdb) and projection functions
        - Spatial expression patterns
            - Spatial co-expression module
    - Spatial in situ technology: Xenium
        - Read in raw data
            - Transcript coordinates
            - Polygon coordinates
            - Visualizations
        - Overlap txs & polygons
            - Typical aggregated workflow
            - Feature/molecule specific analysis
            - Visualizations
        - Transcript enrichment GSEA
        - Spatial location analysis
            - Spatial cell type co-localization analysis
            - Spatial niche analysis
            - Spatial niche trajectory analysis
            - Visualizations
    - Spatial proteomics: multiplex IF
        - Read in raw data
            - Intensity data (IF or any other image)
            - Polygon coordinates
            - Visualizations
        - Overlap intensity & workflows
            - Typical aggregated workflow
            - Visualizations


- Day 3:  Advanced Tutorials
    - Multiple samples 
        - Create individual giotto objects
        - Join Giotto Objects
        - Perform Harmony and default workflows
        - Visualizations
    - Spatial multi-modal
        - Co-registration of datasets
        - Examples in giotto suite manuscript
    - Multi-omics integration
        - Example in giotto suite manuscript
    - Interoperability w/ other frameworks
        - AnnData/SpatialData
        - SpatialExperiment
        - Seurat
    - Interoperability w/ isolated tools
        - Spatial niche trajectory analysis
    - Interactivity with the R/Spatial ecosystem 
        - Kriging
    - Contributing to Giotto
