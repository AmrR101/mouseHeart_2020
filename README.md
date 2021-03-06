### Single-cell RNA-seq atlas of the earliest stages of mouse heart development

Code used to analyse the single-cell RNA-seq data from Tyser et al., 2020.

The repository contains:

- `scripts`: contains all `R markdown` scripts used to analyse the data and produce figures. Output in `md` and `html` is provided to explore the results.

- `data`:  contains a file with gene annotation for the mouse reference genome, based on Ensembl version 87. To run the scripts, it is necessary to download and add to this folder the count matrix and metadata. Both are provided as supplementary information with the paper.
    + `SupplementaryTable1.tab`: contains the metadata for all samples. Download from [here](add link).
    + `SupplementaryData1.tab`: contains the raw counts for all samples. Download from [here](add link). Read this file into R and save as an `Rds` file, named `heartData_unbiased.RAW.Rds`.

- `shinyApp`: scripts used for the [shiny app](https://marionilab.cruk.cam.ac.uk/heartAtlas/).
