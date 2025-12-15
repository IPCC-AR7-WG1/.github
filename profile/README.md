# IPCC Seventh Assessment Report - Working Group I

Welcome to the GitHub organization for the IPCC AR7 WGI 🗺️

This organisation provides a shared space to manage, develop, and archive code and figure-production workflows used in the assessment process. Its primary purpose is to support reproducibility, transparency, and long-term accessibility of the scientific outputs contributing to IPCC reports.

The repositories hosted here cover a wide range of activities, including data processing, analysis scripts, and figure generation. Authors are encouraged to use tools and workflows that best suit their scientific needs, while aligning with author guidance where required.


## Contents
- [Repository Structure and Workflow](repository-structure-and-workflow)
- [Name your repository](#name-your-repository)
- [Controlled vocabulary](#controlled-vocabulary)
- ...


## Repository Structure and Workflow

For **Zero Order Draft (ZOD) through Second Order Draft (SOD)**, authors and chapter teams have flexibility to organise their work as they see fit. This includes:

- Repository structure

- File organisation

- Choice of tools, languages, and workflows

This flexibility is intended to support diverse scientific approaches and evolving analyses during early draft stages.

For the **Final Government Draft (FGD)**, WGI applies more structured requirements to ensure consistency, traceability, and reproducibility:

- One repository per figure

- Each repository must follow the standardized structure provided in the repository template for final data and figures. <https://github.com/IPCC-AR7-WG1/ar7-wg1-fgd-ch99-fig_template>

All Repositories names in this organisation must follow the naming conventions defined in [Name your repository](#name-your-repository).

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

Note that with every pull request into the `main` branch, actions are run to check the conformity of the repo's structure and content. 
