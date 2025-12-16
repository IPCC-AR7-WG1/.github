# IPCC Seventh Assessment Report - Working Group I

Welcome to the GitHub organization for the IPCC AR7 WGI 🗺️

This organisation provides a shared space to manage, develop, and archive code and figure-production workflows used in the assessment process. Its primary purpose is to support reproducibility, transparency, and long-term accessibility of the scientific outputs contributing to IPCC reports.

The repositories hosted here cover a wide range of activities, including data processing, analysis scripts, and figure generation. Authors are encouraged to use tools and workflows that best suit their scientific needs, while aligning with author guidance where required.


## Contents
- [Repository Organisation Guidelines](#repository-organisation-guidelines)
- [Name your repository](#name-your-repository)
- [Controlled vocabulary](#controlled-vocabulary)
- [Support](#support)


## Repository Organisation Guidelines

All repositories in this organization must follow the naming conventions in [Name your repository](#name-your-repository).

Please remember that when creating a repository, it must be kept **private**.

For **Zero Order Draft (ZOD) through Second Order Draft (SOD)**, authors and chapter teams have flexibility to organise their work as they see fit. This includes:

- Repository structure

- File organisation

- Choice of tools, languages, and workflows

This flexibility is intended to support diverse scientific approaches and evolving analyses during early draft stages.

For the **Final Government Draft (FGD)**, WGI applies more structured requirements to ensure consistency, traceability, and reproducibility:

- One repository per figure

- All repositories for final data and figures must be created from the official repository template at: <https://github.com/IPCC-AR7-WG1/ar7-wg1-fgd-ch99-fig_template>


## Name your repository

Please name your repository according to the following convention:  ``ar7-wg1-<draft>-<chapter>-<figure>``. All abbreviations must follow the definitions listed in [Controlled vocabulary](#controlled-vocabulary).

Note that we expect authors to create a new repo for each draft. This may feel like a bad practice for 
Git users, but keeping the same repository name across drafts would lead to name conflicts, because figure numbers 
change from one draft to the next.

**If you don't know yet the draft figure number, enter a descriptive name in the 
``figure`` field, e.g. ``cmip7_sea_ice_extent``, and change the repo name once you know your figure's number.**


## Controlled vocabulary

Whenever a template includes fields for `<report>, <draft>, <chapter>` or `<figure>`, please use abbreviations from the table below.

| Type        | Full name                                 | Abbreviation |
|-------------|-------------------------------------------|-------------|
| ``draft``   |                                           |             |
|             | Zero Order Draft                          | zod         | 
|             | First Order Draft                         | fod         |
|             | Second Order Draft                        | sod         |
|             | Final Government Draft                    | fgd         |
| ``chapter`` |                                           |             |
|             | Summary for Policymakers                  | spm         |
|             | Technical Summary                         | ts          |
|             | Chapter 1                                 | ch1         |
|             | Cross-Chapter Paper 1                     | ccp1        |
|             | Annex III                                 | ann3        |
|             | Atlas                                     | atlas       |
| ``figure``  |                                           |             |
|             | Figure 4.1                                | fig1        |
|             | Cross-Chapter Box 4.1, Figure 1           | ccb1fig1  |
|             | Cross-Section Box TS.1, Figure 1          | csb1fig1  |
|             | Box 4.1, Figure 1                         | box1fig1  |
|             | Frequently Asked Questions 4.1, Figure 1  | faq1fig1  |


## Support

If you encounter any technical issues or need assistance with code management, please feel free to contact the WGI TSU Data Team at <data.wg1-ar7-ipcc@universite-paris-saclay.fr>
