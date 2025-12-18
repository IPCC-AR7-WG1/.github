# IPCC Seventh Assessment Report - Working Group I

Welcome to the GitHub organization for the IPCC AR7 WGI 🗺️

This organisation provides a shared space to manage, develop, and archive code and figure-production workflows used in the assessment process. Its primary purpose is to support reproducibility, transparency, and long-term accessibility of the scientific outputs contributing to IPCC reports.

The repositories hosted here cover a wide range of activities, including data processing, analysis scripts, and figure generation. Authors are encouraged to use tools and workflows that best suit their scientific needs, while aligning with author guidance where required.


## Contents
- [Contents](#contents)
- [Repository Organisation Guidelines](#repository-organisation-guidelines)
  - [Standard Figure Folder Structure](#standard-figure-folder-structure)
  - [General Rules](#general-rules)
- [Folder Naming Conventions](#folder-naming-conventions)
  - [Figure Folder Names](#figure-folder-names)
  - [Naming Rules](#naming-rules)
- [Support](#support)


## Repository Organisation Guidelines

This repository is organized by figure, with one top-level folder per figure.

Each figure folder is fully self-contained and includes the code, metadata, outputs, and citation information needed to reproduce that figure.

### Standard Figure Folder Structure

Each figure directory must follow this structure:

```
fig_xx/
├── code/ # Scripts or notebooks used to generate the figure
├── data/ # Metadata for input datasets (original data files excluded)
├── figure/ # Generated figure(s)
├── CITATION.cff # Citation information for this figure
└── README.md # Figure description, usage, and citation instructions
```

### General Rules

- **One figure per folder**  
  Do not combine multiple figures in a single directory.

- **Do NOT store large data files**  
  The `data/` folder must contain **metadata only** (e.g. `.yml`, schema files, small samples).  
  Large datasets must be stored in external long-term storage and referenced via links.

- **Reproducibility first**  
  All scripts or notebooks required to generate the figure must be placed in `code/`.

- **Clear attribution**  
  Every figure folder must include a `CITATION.cff` file to ensure proper authorship and citation tracking.


## Folder Naming Conventions

### Figure Folder Names

- Use the format: `fig_XX`

where `XX` is a **two-digit figure number** (e.g. `fig_01`, `fig_02`).

- If the final figure number is not yet known, use a **descriptive temporary name**: fig_<short_descriptive_name> 

Please rename the folder to the final `fig_XX` format once the figure number is confirmed.

### Naming Rules

- Use lowercase letters
- Use underscores (`_`) instead of spaces or hyphens
- Keep names short, clear, and descriptive


## Support

If you encounter any technical issues or need assistance with code management, please feel free to contact the WGI TSU Data Team at <data.wg1-ar7-ipcc@universite-paris-saclay.fr>
