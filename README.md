# oSPARCHUB : An Extensible ETL Framework for Streamlining the SPARC Ecosystem
 ![image](https://github.com/user-attachments/assets/e2c126c1-2649-4f06-9cf6-2923b4dc9d0d)


# Introduction
The Sparc Database provides multiple datasets . mainly Anatomical models, Neural Connectivity data on the SCKAN database , Physiological and electrophysiological data, genomics data
And many other.
The Sparc datasets are divided across different websites, and the data usually requires a preprocessing step before visualization.
Additionally, many models are not directly usable but instead require a lot of preliminary work to be done by the end-user before any usable insight can be gained

oSPARC is a platform provided by SPARC, it provides Services , Code templated and modules to manage multiple SPARC datatypes 

However, not all data have specific data visualization tool on the oSPARC platform

| Data Type on SPARC                                | Dataset Count | Associated oSPARC Module/Service | Action Required             |
|---------------------------------------------------|---------------|----------------------------------|-----------------------------|
| SCKAN Database                                    | Various       | X                                | Created one                 |
| Anatomical Models                                 | 40            |  +  -                            | Created one                 |
| Navigate SPARC Portal Datasets                    |               | X                                | Created one                 |
| Datasets                                          |               |                                  |                             |
| - Microscopy                                      | 100           | V                                | Tutorial                    |
| - Anatomy                                         | 96            | V                                | Tutorial                    |
| - Physiology                                      | 96            |                                  | Tutorial                    |
| - Electrophysiology                               | 62            | V                                | Tutorial                    |
| - Connectivity                                    | 52            | V                                | Tutorial                    |
| - Histology                                       | 35            | -                                | -                           |
| - Spatial Transcriptomics                         | 22            | -                                | -                           |
| - Expression; Expression Characterization; Transcriptomics | 22  | +  -                             | Update + Add a UI           |
| - Other                                           | <20 each      | -                                | -                           |


## Introduction to oSPARC Hub

The oSPARC Hub framework is a collection of sparc pipelines, modules and Application  developed to fill the gaps in the oSPARC platform.
It integrates at first a pipeline to navigate the datasets available on the SPARC portal directly from the platform.
Depending on the target data type, 3 Application are available to access and use data on the SCKAN database; anatomical models on SPARC Portal, and Genomics datasets on the portal 
Additionally multiple modules were developed to process various data types

![image](https://github.com/user-attachments/assets/4c1fc6c6-ae96-40bd-b8ca-f77873d2ef1c)


