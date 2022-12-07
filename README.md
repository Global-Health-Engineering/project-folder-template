
# README

## Overview

This is a template directory for projects at the Global Health
Engineering research group at ETH Zurich. It can be used for BSc and MSc
projects, but also for scientific publications or other research
products. The folder contains a structure for generated data with
guidance on how to store raw and derived data. Templates are provided
for metadata and documentation.

<!--# A style guide provides an outline and general guidance on report writing. The guide is provided as a MS Word .docx file, but can also be edited with Google Docs, as Google Drive is used for file management. The outline of the style guide is also provided as a Quarto file (.qmd), which can be used for report writing. Depending on the set of tools for data analysis and report writing, some files are only relevant in specific cases. -->

## Version control

This folder is under version control using the git version control
system. Students that do not work with git version control also do not
need to start, but it allows those that can to do it. Despite the folder
being stored within a Google Workspace, it contains an RStudio project
file (.Rproj) which can be used to open the folder (project) with the
RStudio IDE, which can used for authoring and to interact with git for
those that are not familiar using the terminal.

## Computational Competencies

Within the GHE group, we have competent practitioners in using STATA and
R. Students are free to use any other programming language for data
analysis (Python, SQL, Julia, etc.), but no support can be provided for
code review. Students using R for their data analysis are free to use .R
scripts or literate programming tools, such as R Markdown or Quarto.

# Directories & Files

The repository has the following directory tree.

    .
    ├── CITATION.cff
    ├── CONDUCT.md
    ├── LICENSE.md
    ├── README.md
    ├── README.qmd
    ├── README.rmarkdown
    ├── data
    │   ├── README.md
    │   ├── derived_data
    │   │   └── README.md
    │   ├── metadata
    │   │   ├── README.md
    │   │   └── codebook.csv
    │   └── raw_data
    │       └── README.md
    ├── docs
    │   ├── report
    │   │   ├── README.md
    │   │   ├── ghe-style-guide.docx
    │   │   └── report-outline.qmd
    │   └── slides
    │       └── README.md
    ├── project-folder-template.Rproj
    └── src
        └── README.md

| name         | description                                                                                                                                                                                                                                                                            |
|--------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| CITATION.cff | A citation file in the citation file format (.cff). Names of contributors and their ORCID iD are added to this file.                                                                                                                                                                   |
| CONDUCT.md   | A code of conduct for this project.                                                                                                                                                                                                                                                    |
| LICENSE.md   | A license for this project. The CC-BY 4.0 license is chosen as the default. Reasons for using a different license may apply in which case the license can be adapted in coordination with the supervisor.                                                                              |
| CITATION.cff | A citation file in the citation file format (.cff). Names of contributors and their ORCID iD are added to this file.                                                                                                                                                                   |
| README.md    | A README.md file compiled from README.qmd with format gfm (GitHub Flavoured Markdown)                                                                                                                                                                                                  |
| README.qmd   | A README.qmd file to write up general information about this project.                                                                                                                                                                                                                  |
| data         | A data directory with sub-directories (raw_data, derived_data). The data directory contains a [README.md](https://github.com/Global-Health-Engineering/msc-thesis-template/tree/main/data "README file in data folder") with instructions and information about its content.           |
| docs         | A directory for documents that are generated as part of the project. Two sub-folders provide structure for a report and slides.                                                                                                                                                        |
| grading      | This folder contains a template for grading of the project. Supervisors need to ensure that students are aware of this grading rubric prior to starting their work with the GHE group. This folder is not on GitHub as it is not tracked under version control, but available locally. |
| src          | An optional folder for scripts that provide machine-readable instructions for data processing (e.g. R scripts).                                                                                                                                                                        |
