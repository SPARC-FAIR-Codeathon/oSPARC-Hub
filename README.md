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


In total We devloped 3 oSPARC Application and 6 Modules that are availabel on the oSPARC platform 


![image](https://github.com/user-attachments/assets/8402bf82-d38f-40e5-95e4-f3586637a615)

 
## Documentations

1. App : Visualize Anatomical Modules Demonstration
This app visualize Anatomical Scafford 3D models. 
Source Code : [Apps/Visualize Anatomical Modules](https://github.com/SPARC-FAIR-Codeathon/2024-team-5/tree/main/Apps/Visualize%20Anatomical%20Modules)

3. App : Transcriptomics data visualization
This app analyse and visualize transcriptomics data.
Source Code : [Apps/Transcriptomics data visualization](https://github.com/SPARC-FAIR-Codeathon/2024-team-5/tree/main/Apps/Transcriptomics%20data%20visualization)

5. App: Visualize SCKAN datadase data
This app allow access and data manipulation from the SCKAN database
Source Code : [Apps/Visualize SCKAN datadase data](https://github.com/SPARC-FAIR-Codeathon/2024-team-5/tree/main/Apps/Visualize%20SCKAN%20datadase%20data)

 
7. Module : File Format Converter
This module allows conversion of files between various formats such as CSV, JSON, YAML, XLS, XLSX, NWB (Neurodata Without Borders) and many others.
Source Code : https://github.com/SPARC-FAIR-Codeathon/2024-team-5-service-1

8. Module : VTK Converter
This module converts .vtk files to their .stl and .obj equivalents, which have wider support with visualization libraries.
Source Code :https://github.com/SPARC-FAIR-Codeathon/2024-team-5-service-2

9. Module : Visualize 3D Model
This module offers a quick and simple visualization of 3D scaffold models.
Source Code : https://github.com/SPARC-FAIR-Codeathon/2024-team-5-service-3

10. Module : Fetch Scaffold From SPARC Portal
This module can fetch scaffold .vtk file from SPARC Portal for specified datasets.
Source Code :https://github.com/SPARC-FAIR-Codeathon/2024-team-5-service-4

11. Module :Tabular Data Viewer
This module enables users to view tabular data fromw within study.
Source Code : https://github.com/SPARC-FAIR-Codeathon/2024-team-5-service-5

12. Module : Transcriptomics Data Explorer
This module allows users to explore and visualize transcriptomic data.
Source Code : https://github.com/SPARC-FAIR-Codeathon/2024-team-5-service-6



## Team Members
Shailesh Appukuttan; Indian Institute of Technology Bombay, Mumbai, India
Hiba Ben Aribi;  University of Tunis El Manar, Tunis, Tunisia

Fynn Rievers; Tilburg University, Tilburg, The Netherlands





