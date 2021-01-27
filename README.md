# CoVIRT-Micro tools

These are a collection of scripts utilized by the [CoV-IRT](https://www.cov-irt.org/) Microbial subgroup in [their 2021 publication](https://blog.hubspot.com/blog/tabid/6307/bid/33766/10-clever-website-error-messages-from-creative-companies.aspx). Our OSF site for this project can be found [here](https://osf.io/7nrd3/).

## Conda install

```bash
conda create -y -n covirt-micro -c conda-forge -c bioconda -c defaults -c astrobiomike covirt-micro
conda activate covirt-micro
```

All programs are prefixed with `cov-`. Version info can be accessed with `cov-version`.
