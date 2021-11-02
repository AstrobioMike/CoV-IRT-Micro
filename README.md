# CoVIRT-Micro tools

These are a collection of scripts utilized by the [CoV-IRT](https://www.cov-irt.org/) Microbial subgroup in our "Analysis of Bronchoalveolar Lavage Fluid Metatranscriptomes Among Patients with COVID-19 Disease" manuscript. Our OSF site for this project can be found [here](https://osf.io/7nrd3/).

## Conda install

```bash
conda create -y -n covirt-micro -c conda-forge -c bioconda -c defaults -c astrobiomike covirt-micro
conda activate covirt-micro
```

All programs are prefixed with `cov-`. Version info can be accessed with `cov-version`.
