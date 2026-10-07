# Hi, I'm Luigi 👋

I'm a **Data Scientist and Data Engineer** with a background in Physics, working with large-scale data processing, distributed computing, Python-based data pipelines, and quantitative data analysis.

I currently work at [LIneA](https://github.com/linea-it), where I design and develop scalable workflows for complex scientific datasets. My work involves data ingestion, transformation, integration, validation, quality assurance, exploratory analysis, crossmatching, deduplication, and distributed execution across interactive Jupyter environments and multi-node HPC clusters.

I work primarily with **Python, SQL, Dask, Jupyter, SLURM, and HPC systems**, with a strong focus on scalability, performance, memory efficiency, data quality, reproducibility, testing, and maintainable software.

My current work is applied to large-scale astronomy, including projects connected to the Rubin Observatory / LSST ecosystem and international scientific collaborations, but the underlying challenges are broadly applicable to data science and data engineering.

## What I work on

- Designing scalable Python data pipelines
- Processing and analyzing datasets ranging from millions to hundreds of millions of records
- Performing exploratory and quantitative analysis using distributions, summary statistics, percentiles, and large-scale visualization
- Building distributed workflows with Dask and SLURM
- Integrating and standardizing heterogeneous data sources
- Developing data validation, quality assurance, profiling, and deduplication workflows
- Building Python packages, command-line tools, automated tests, and CI workflows
- Contributing to open-source scientific software

## Selected work

### [hipscatalog-gen](https://github.com/linea-it/hipscatalog_gen)

A distributed Python pipeline for generating large-scale HiPS catalogs using Dask, LSDB, and HPC infrastructure.

The project supports configurable selection strategies, YAML-based configuration, command-line execution, parallel processing, automated validation, and reproducible catalog generation. It is also published on [PyPI](https://pypi.org/project/hipscatalog-gen/).

---

### [Distributed Data Integration and Deduplication Pipeline](https://github.com/linea-it/pzserver_combine_redshift_dedup)

A distributed pipeline for integrating dozens of heterogeneous datasets into consolidated data products.

The workflow includes schema harmonization, quality metadata standardization, scalable spatial crossmatching, deterministic deduplication, validation, and memory-efficient distributed processing with Python, Dask, LSDB, HATS, and HPC infrastructure.

---

### [Interactive Analysis of 691 Million Records with Dask and HPC](https://github.com/linea-it/jupyterhub-tutorial/blob/main/minicurso/minicurso-HPC-2025/curso_hpc.ipynb)

A distributed workflow for interactive analysis and visualization of datasets containing up to **691 million records**.

<p align="center">
  <img
    src="assets/des-dr2-analysis.png"
    alt="Interactive analysis of 691 million records using Dask and HPC"
    width="900"
  >
</p>

The architecture integrates JupyterLab with a multi-node HPC cluster using Dask and SLURMCluster, combining distributed computation with HoloViews, Bokeh, and Datashader for responsive exploration of datasets that exceed single-machine memory.

I also taught a short course on this workflow and published the training materials openly.

---

### [Open-Source Contribution to LSDB: Distributed Catalog Concatenation](https://docs.lsdb.io/en/latest/reference/api/lsdb.catalog.Catalog.concat.html)

Designed and implemented the `.concat` API in the open-source [LSDB](https://github.com/astronomy-commons/lsdb) library, enabling concatenation of distributed catalogs stored in the HATS format.

<p align="center">
  <img
    src="assets/lsdb-concat-docs.png"
    alt="LSDB Catalog.concat API documentation"
    width="750"
  >
</p>

The contribution included feature design, implementation, integration with the existing catalog architecture, edge-case handling, and development of a comprehensive unit-test suite to validate correctness and reliability.

## Technologies

**Data Science & Analysis**  
Python · Pandas · Jupyter · Exploratory Data Analysis · Descriptive Statistics · Data Visualization

**Data Engineering**  
SQL · Parquet · Data Pipelines · Data Integration · Data Quality · Data Validation

**Distributed Computing & HPC**  
Dask · SLURM · Distributed Computing · Parallel Computing · HPC

**Scientific & Large-Scale Data**  
LSDB · HATS · HoloViews · Bokeh · Datashader

**Software Engineering**  
Git · GitHub · Testing · CI · CLI Development · Configuration-Driven Workflows

## Currently expanding my expertise

I'm currently expanding my data engineering background through formal studies in:

- Database systems and SQL
- Data modeling
- Data warehousing
- Cloud data engineering
- AWS

This complements my professional experience with large-scale and distributed data processing.

## Connect with me

- [LinkedIn](https://www.linkedin.com/in/luigi-lucas-d-a8b987156)
- [PyPI](https://pypi.org/user/luigilcsilva/)
