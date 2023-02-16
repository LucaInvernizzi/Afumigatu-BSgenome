# Aspergillus-fumigatus-BSgenome
Tarball ready to install for the BSgenome package of Aspergillus fumigatus Af293

## Installation
Save the tarball into a folder named "BS_genome_fumigatus" in the working directory. Copy and launch this from the console:

```
install.packages("BS_genome_fumigatus/BSgenome.Afumigatus.fungiDB.Af293_1.0.0.tar.gz", repos = NULL, type="source")
```

## Load the genome
```
library(BSgenome.Afumigatus.fungiDB.Af293)
```
The genome is available as:
```
Afumigatus
```
