# Dataset
Four pairs of Real Datasets (processed) and the downsampled datasets mentioned in the manuscript are available through: https://drive.google.com/drive/folders/1famn_tRVT_Es0GgFng508QggXcqETPCJ?usp=sharing
# Simulation Datasets
Please find the corresponding Rscripts for simulation data.
# Run the Rscripts with Docker
Pull the software versions used in the manuscript from the Docker file (Here illustrate the use with Singularity).
## usage in R session
```bash
SINGULARITY_DOCKER_USERNAME=dockerusername SINGULARITY_DOCKER_PASSWORD=dockerpassword singularity pull docker://qhhuang/benchmark_celltype_r_packages:versioncontrol
singularity exec -B /path/to/your/working/directory /path/to/docker/img/benchmark_celltype_r_packages-versioncontrol.simg R
```
Then, proceeds your analysis as usual.

## execute Rscript directly
```bash
singularity exec -B /path/to/your/working/directory /path/to/docker/img/benchmark_celltype_r_packages-versioncontrol.simg Rscript /path/to/your/Rscript/sample.R
```

# Link to Softwares
For the information of software updates, please go to their corresponding pages.\
[Seurat](https://satijalab.org/seurat/) \
[SingleR](https://github.com/dviraran/SingleR) [Recently Add Rejection Option]\
[scmap](https://bioconductor.org/packages/release/bioc/html/scmap.html) \
[Garnett](https://cole-trapnell-lab.github.io/garnett/docs/) [Recently Add Automatic Marker Detection]\
[CHETAH](https://github.com/jdekanter/CHETAH) \
[SCINA](https://github.com/jcao89757/SCINA) \
[singleCellNet](https://github.com/pcahan1/singleCellNet) \
[scID](https://github.com/BatadaLab/scID)
