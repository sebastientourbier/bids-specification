# Contributing to and extending the BIDS specification

This page lists some ways that you can get involved with the BIDS community.

## Contributing to BIDS

There are many ways to get involved with the BIDS community!

### The BIDS Starter Kit

If you're new to the BIDS community and you'd like to learn a bit more, we
recommend checking out the [BIDS Starter Kit](https://github.com/bids-standard/bids-starter-kit/blob/master/README.md).
This has introductory information about the BIDS specification, tools in the
BIDS ecosystem, and how you can get involved.

### The BIDS Contributor guide

If you'd like to get involved more heavily in helping extend the BIDS
specification or develop tools for it, see the [BIDS Contributor Guide](https://docs.google.com/document/d/1pWmEEY-1-WuwBPNy5tDAxVJYQ9Een4hZJM06tQZg8X4).
It contains more in-depth information for getting involved with the BIDS
community.

## BIDS Extension Proposals

The BIDS specification can be extended in a backwards compatible way and will
evolve over time. These are accomplished with BIDS Extension Proposals (BEPs),
which are community-driven processes.

Below is a table of currently-active BEPs. The "Extension label" column
provides a direct link to the documentation.

| Extension label                                                                           | Title                                                                                                      | Moderators/ leads                                                          | Summary                                                                                                                                                                                                                                   | Blocking point(s)                                                                      |
| :---------------------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| [BEP001](https://github.com/bids-standard/bep001)                                         | Structural acquisitions that include multiple contrasts (multi echo, flip angle, inversion time) sequences | Gilles de Hollander and Kirstie Whitaker                                   | The draft BEP is nearly ready to be submitted as a PR.                                                                                                                                                                                    | A few items need to be revised and a final decision made.                              |
| [BEP002](https://docs.google.com/document/d/1bq5eNDHTb6Nkx3WUiOBgKvLNnaa5OMcGtD0AZ9yms2M) | The BIDS Models Specification                                                                              | Tal Yarkoni                                                                | Working with the computational models group for consistency. Starting with fMRI then extend to other modalities.                                                                                                                          | An item that is blocking progress is transformed data.                                 |
| [BEP004](https://docs.google.com/document/d/1kyw9mGgacNqeMbp4xZet3RnDhcMmf4_BmRgKaOkO2Sc) | Susceptibility Weighted Imaging (SWI)                                                                      | Available                                                                  | Looking for a new leader.                                                                                                                                                                                                                 | Searching for a new leader.                                                            |
| [BEP005](https://docs.google.com/document/d/15tnn5F10KpgHypaQJNNGiNKsni9035GtDqJzWqkkP6c) | Arterial Spin Labeling (ASL)                                                                               | Henk-Jan Mutsaerts and Michael Chappell                                    | Very close to completion. This includes finalizing the implementation in the validator and drafting the manuscript.                                                                                                                       | None.                                                                                  |
| [BEP009](https://docs.google.com/document/d/1mqMLnxVdLwZjDd4ZiWFqjEAmOmfcModA_R535v3eQs0) | Positron Emission Tomography (PET)                                                                         | Melanie Ganz                                                               | Very close to completion. This includes finalizing the standard and writing the paper.                                                                                                                                                    | None.                                                                                  |
| [BEP011](https://docs.google.com/document/d/1YG2g4UkEio4t_STIBOqYOwneLEs1emHIXbGKynx7V0Y) | The structural preprocessing derivatives                                                                   | Andrew Hoopes                                                              | Have finalized the surface-based and volumetric overlays (and stats), differentiate between discrete and probabilistic segmentation. The next step for this BEP is standardizing the universal look-up table and characterizing surfaces. | None.                                                                                  |
| [BEP012](https://docs.google.com/document/d/16CvBwVMAs0IMhdoKmlmcm3W8254dQmNARo-7HhE-lJU) | The functional preprocessing derivatives                                                                   | Camille Maumet and Chris Markiewicz                                        |                                                                                                                                                                                                                                           | None.                                                                                  |
| [BEP014](https://docs.google.com/document/d/11gCzXOPUbYyuQx8fErtMO9tnOKC3kTWiL9axWkkILNE) | The affine transformations and nonlinear field warps                                                       | Oscar Esteban                                                              | A new file format (X5) to store spatial transforms is being created, and a draft proposal has been discussed under the scope of this BEP. A software prototype demonstrating X5 is currently under development.                           | In progress.                                                                           |
| [BEP015](https://docs.google.com/document/d/1WYOTXDB7GzlHoWqLjd45I3uGBgPxXddST-NTqBnroJE) | Mapping file                                                                                               | Eric Earl, Camille Maumet, and Vasudev Raguram                             | Comments in BEP suggest this could be a tool rather than a BEP. This BEP is looking for thoughts and contributions.                                                                                                                       | Thoughts and contributions.                                                            |
| [BEP016](https://docs.google.com/document/d/1cQYBvToU7tUEtWMLMwXUCB_T8gebCotE1OczUpMYW60) | The diffusion weighted imaging derivatives                                                                 | Franco Pestilli and Oscar Esteban                                          | Being discussed in a [GitHub repository](https://github.com/bids-standard/bids-bep016)                                                                                                                                                    |                                                                                        |
| [BEP017](https://docs.google.com/document/d/1ugBdUF6dhElXdj3u9vw0iWjE6f_Bibsro3ah7sRV0GA) | Generic BIDS connectivity data schema                                                                      | Eugene Duff and Paul McCarthy                                              | This BEP is searching for a reviewer with fresh eyes that understands the scope of this BEP.                                                                                                                                              | None.                                                                                  |
| [BEP018](https://docs.google.com/document/d/1uRkgyzESLKuGjXi98Z97Wh6vt-iLN5nOAb9TG16CjUs) | Genetic information                                                                                        | Cyril R Pernet, Clara Moreau, and Thomas Nichols                           | Submitted a [pull request](https://github.com/bids-standard/bids-specification/pull/287) for review                                                                                                                                       | None.                                                                                  |
| [BEP019](https://docs.google.com/document/d/1FqJI791ycXr0bfRg2qyLqAf0RpVttJ2cInOgMWrKsNU) | DICOM Metadata                                                                                             | Satrajit Ghosh                                                             | Not active - perhaps this is in the 20% of use cases. Could be a NIDM extension rather than in BIDS.                                                                                                                                      | None.                                                                                  |
| [BEP020](https://docs.google.com/document/d/1eggzTCzSHG3AEKhtnEDbcdk-2avXN6I94X8aUPEBVsw) | Eye Tracking including Gaze Position and Pupil Size(ET)                                                    | Benjamin Gagl and Dejan Draschkow                                          | BEP is progressing and reaching consensus on items.                                                                                                                                                                                       | Small issues are blocking completion.                                                  |
| [BEP021](https://docs.google.com/document/d/1PmcVs7vg7Th-cGC-UrX8rAhKUHIzOI-uIOh69_mvdlw) | Common Electrophysiological Derivatives                                                                    | Mainak Jas, Stefan Appelhoff, Cyril Pernet, Robert Oostenveld, Teon Brooks | Work has resumed since merging in EEG and iEEG. Next steps are to distribute a survey to gather what derivatives researchers care about, create example datasets to understand practical issues, and updates to the validator.            | A few blocking items is what file format may be best suited and annotations.           |
| [BEP022](https://docs.google.com/document/d/1pWCb02YNv5W-UZZja24fZrdXLm4X7knXMiZI7E2z7mY) | Magnetic Resonance Spectroscopy (MRS)                                                                      | Dickson Wong                                                               | This is stalled effort, but trying to restart.                                                                                                                                                                                            | Restarting the effort.                                                                 |
| [BEP023](https://docs.google.com/document/d/1yzsd1J9GT-aA0DWhdlgNr5LCu6_gvbjLyfvYq2FuxlY) | PET Preprocessing derivatives                                                                              | Martin Noergaard, Graham Searle, Melanie Ganz                              | Work is paused until BEP009 manuscript has been submitted/accepted.                                                                                                                                                                       | A blocking item is the need for more contributors, especially from senior PET experts. |
| [BEP024](https://docs.google.com/document/d/1fqnJZ18x5LJC8jiJ8yvPHUGFzNBZ6gW2kywYrUKWtuo) | Computed Tomography scan (CT)                                                                              | Hugo Boniface                                                              | This effort has stalled and looking for more contributors and experts.                                                                                                                                                                    | None.                                                                                  |
| [BEP025](https://docs.google.com/document/d/1chZv7vAPE-ebPDxMktfI9i1OkLNR2FELIfpVYsaZPr4) | Medical Population Imaging Data structure (MIDS)                                                           | Jose Manuel Saborit Torres, Maria de la Iglesia Vayá                       | This BEP is working on the automated recognition of the DICOM sequence and writing the manuscript.                                                                                                                                        | None.                                                                                  |
| [BEP026](https://docs.google.com/document/d/14KC1d5-Lx-7ZSMtwS7pVAAvz-2WR_uoo5FvsNirzqJw) | Microelectrode Recordings (MER)                                                                            | Greydon Gilmore                                                            | Active effort. Looking for thoughts and contributions                                                                                                                                                                                     | None.                                                                                  |
| [BEP027](https://docs.google.com/document/d/104HLZedFtx0TaXEUwd7eyWvJUlc0CcSUtCzwjNgmGxE) | BIDS Execution                                                                                             | Chris Markiewicz and Greg Kiar                                             | Partial draft seeking community input and fleshing out of some details. Examples and tooling should be available prior to release to demonstrate viability.                                                                               | None.                                                                                  |

When an extension reaches maturity it is merged into the main body of the
specification. Below is a table of BEPs that have been merged in the main body
of the specification.

| Extension label                                                                           | Title                                      | Moderators/leads                                  |
| :---------------------------------------------------------------------------------------- | :----------------------------------------- | :------------------------------------------------ |
| [BEP006](https://docs.google.com/document/d/1ArMZ9Y_quTKXC-jNXZksnedK2VHHoKP3HCeO5HPcgLE) | Electroencephalograpgy (EEG)               | Cyril Pernet, Stefan Appelhoff, Robert Oostenveld |
| [BEP007](https://docs.google.com/document/d/1gs7USIVO1OApZs3IVo6TeXw9_tfzxhjM2-m--ex4g6o) | Hierarchical Event Descriptor (HED) Tags   | Chris Gorgolewski                                 |
| [BEP008](https://docs.google.com/document/d/1FWex_kSPWVh_f4rKgd5rxJmxlboAPtQlmBc1gyZlRZM) | Magnetoencephalography (MEG)               | Guiomar Niso                                      |
| [BEP010](https://docs.google.com/document/d/1qMUkoaXzRMlJuOcfTYNr3fTsrl4SewWjffjMD5Ew6GY) | intracranial Electroencephalograpgy (iEEG) | Chris Holdgraf, Dora Hermes                       |
| [BEP003](https://docs.google.com/document/d/1Wwc4A6Mow4ZPPszDIWfCUCRNstn7d_zzaWPcfcHmgI4) | Common Derivatives                         | Chris Gorgolewski                                 |

BEPs that have been closed down or merged into other BEPs:

| Extension label                                                                           | Title                                                                                                      | What happened?                                                             |
| :---------------------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------- |
| [BEP013](https://docs.google.com/document/d/1qBNQimDx6CuvHjbDvuFyBIrf2WRFUOJ-u50canWjjaw) | The resting state fMRI derivatives                                                                         | merged into BEP012                                                         |

All of the extension ideas that are not backwards compatible and thus
will have to wait for BIDS 2.0 are listed
[here](https://docs.google.com/document/d/1LEgsMiisGDe1Gv-hBp1EcLmoz7AlKj6VYULUgDD3Zdw).