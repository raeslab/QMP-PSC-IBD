# QMP in PSC and IBD – companion website and supplementary data

Companion website and supplementary data for:

> Vieira-Silva S, Sabino J, Valles-Colomer M, Falony G, Kathagen G, Caenepeel C, Cleynen I, van der Merwe S, Vermeire S, Raes J. **Quantitative microbiome profiling disentangles inflammation- and bile duct obstruction-associated microbiota alterations across PSC/IBD diagnoses**. *Nature Microbiology* 4(11):1826–1831 (2019). [doi:10.1038/s41564-019-0483-9](https://doi.org/10.1038/s41564-019-0483-9)

It contains the quantitative microbiome profiling (QMP) matrix of the study dataset and a short animation shown on the original page.

**Website:** https://raeslab.github.io/QMP-PSC-IBD/ (GitHub Pages, served from `docs/` on the `main` branch)

This material was previously hosted on the Raes Lab website at `raeslab.org/software/QMP2/` and has been migrated to this repository.

## Contents

| Path | Size | Description |
|------|------|-------------|
| `supplementary/QMP.matrix.tsv` | 246 KB | Quantitative microbiome profiling (QMP) matrix: genus-level abundances per sample (tab-separated). |

Total supplementary data: 246 KB.

## Repository layout

```
docs/                 Static, self-contained website (GitHub Pages source; no external CSS/JS/fonts)
  index.html
  assets/             Stylesheet, script, logo, figure previews
supplementary/        Downloadable data files (Git LFS)
.gitattributes        Git LFS tracking rules
```

### Git LFS

All files in `supplementary/` are tracked with [Git LFS](https://git-lfs.com). Install it before cloning
(`git lfs install`), or download individual files from the website. Because GitHub Pages does not serve LFS
objects, the website's download buttons point to `https://github.com/raeslab/QMP-PSC-IBD/raw/main/supplementary/...`;
when `docs/index.html` is opened from a local checkout the links switch to the relative `../supplementary/` paths.

### Publishing

In the repository settings, enable GitHub Pages with source *Deploy from a branch* → `main` / `/docs`.

## How to cite

If you use these data, please cite:

> Vieira-Silva S, Sabino J, Valles-Colomer M, Falony G, Kathagen G, Caenepeel C, Cleynen I, van der Merwe S, Vermeire S, Raes J. **Quantitative microbiome profiling disentangles inflammation- and bile duct obstruction-associated microbiota alterations across PSC/IBD diagnoses**. *Nature Microbiology* 4(11):1826–1831 (2019). [doi:10.1038/s41564-019-0483-9](https://doi.org/10.1038/s41564-019-0483-9)

```bibtex
@article{vieirasilva2019quantitative,
  title   = {{Quantitative microbiome profiling disentangles inflammation- and bile duct obstruction-associated microbiota alterations across PSC/IBD diagnoses}},
  author  = {Vieira-Silva, S. and Sabino, J. and Valles-Colomer, M. and Falony, G. and Kathagen, G. and Caenepeel, C. and Cleynen, I. and van der Merwe, S. and Vermeire, S. and Raes, J.},
  journal = {Nature Microbiology},
  year    = {2019},
  volume  = {4},
  number  = {11},
  pages   = {1826--1831},
  doi     = {10.1038/s41564-019-0483-9}
}
```

## Contact

Raes Lab, VIB–KU Leuven Center for Microbiology – Prof. Jeroen Raes (jeroen.raes@kuleuven.be).
