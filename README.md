

## Contents
- ...
- [Name your repository](#name-your-repository)
- [Controlled vocabulary](#controlled-vocabulary)
- ...
  
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
