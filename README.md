# oSPARC Hub : An Extensible ETL Framework for Streamlining the SPARC Ecosystem

![License Badge](https://img.shields.io/badge/license-MIT-blue.svg) ![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg) ![Version](https://img.shields.io/badge/version-0.1.0-blue) 

<br/>
<a href="https://github.com/SPARC-FAIR-Codeathon/2024-team-5">
<image src="https://github.com/appukuttan-shailesh/testData/blob/master/SPARC2024/oSPARCHub_logo.png?raw=true" height="200px" /></a>
<br/><br/>

## Video Overview

[![webinar_preview](https://github.com/appukuttan-shailesh/testData/blob/master/SPARC2024/Slide1.png?raw=true)](https://youtu.be/K5eAg9lYgkc)

## Table of Contents
- [Introduction](#introduction)
- [Presenting oSPARC Hub](#presenting-osparc-hub)
- [oSPARC Applications](#osparc-applications)
- [oSPARC Services](#osparc-services)
- [Deployment Status](#deployment-status)
- [License](#license)
- [Team Members](#team-members)


## Introduction
The SPARC Database offers a variety of datasets, including anatomical models, neural connectivity data available on the SCKAN database, physiological and electrophysiological data, genomics data, and more. These datasets are spread across different websites and typically require preprocessing before they can be visualized. Additionally, many models are not immediately usable and require significant preliminary work by the end-user to extract meaningful insights.

oSPARC is a platform provided by SPARC that offers services, code templates, and modules for managing various SPARC data types. However, not all datasets have dedicated visualization tools available on the oSPARC platform.

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


## Presenting oSPARC Hub

The oSPARC Hub framework is a comprehensive suite of SPARC pipelines, modules, and applications designed to enhance the capabilities of the oSPARC platform. It introduces an integrated pipeline that allows users to navigate datasets directly from the SPARC portal within the platform.

Depending on the data type, there are three specialized applications available: one for accessing and utilizing data on the SCKAN database, another for exploring anatomical models on the SPARC Portal, and a third for working with genomics datasets. In addition, several modules have been developed to efficiently process various data types, ensuring seamless integration and usability.

![image](https://github.com/user-attachments/assets/4c1fc6c6-ae96-40bd-b8ca-f77873d2ef1c)


In total, we have developed:
- 3 oSPARC Application,  and 
- 6 oSPARC Services 

that are accessible via the oSPARC platform. 


![image](https://github.com/user-attachments/assets/8402bf82-d38f-40e5-95e4-f3586637a615)

 
## oSPARC Applications

#### App 1: Visualize Anatomical Modules Demonstration

Tutorial : https://github.com/SPARC-FAIR-Codeathon/2024-team-5/blob/main/Apps/Tutorial%20for%20:Transcriptomics%20data%20visualization.md

Source code : [https://github.com/SPARC-FAIR-Codeathon/2024-team-5/tree/main/Apps/Transcriptomics%20data%20visualization](https://github.com/SPARC-FAIR-Codeathon/2024-team-5/blob/main/Apps/Tutorial%20for%20%3AVisualize%20Anatomical%20Modules.md)

#### App 2: Transcriptomics data visualization
This is an App for transcriptomics data analysis and visualization.

Tutorial : https://github.com/SPARC-FAIR-Codeathon/2024-team-5/blob/main/Apps/Tutorial%20for%20:Transcriptomics%20data%20visualization.md

Source code : https://github.com/SPARC-FAIR-Codeathon/2024-team-5/tree/main/Apps/Transcriptomics%20data%20visualization

#### App 3: Visualize SCKAN datadase data
Tutorial : https://github.com/SPARC-FAIR-Codeathon/2024-team-5/blob/main/Apps/Tutorial%20for%20%3A%20Visualize%20SCKAN%20datadase%20data.md

Source code : https://github.com/SPARC-FAIR-Codeathon/2024-team-5/tree/main/Apps/Visualize%20SCKAN%20datadase%20data
## oSPARC Services

### Service 1: File Format Converter
This module allows conversion of files between various formats such as CSV, JSON, YAML, XLS, XLSX, NWB (Neurodata Without Borders) and many others.
<br/><br/>
<b>Dedicated GitHub Repo:</b> https://github.com/SPARC-FAIR-Codeathon/2024-team-5-service-1
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.13308896.svg)](https://doi.org/10.5281/zenodo.13308896)

<b>Citation: </b> Appukuttan, S., Benaribi, H., & Rievers, F. (2024). oSPARC Service #1: File Format Converter. Zenodo. https://doi.org/10.5281/zenodo.13308896

### Service 2: VTK Converter
This module converts .vtk files to their .stl and .obj equivalents, which have wider support with visualization libraries.
<br/><br/>
<b>Dedicated GitHub Repo:</b> https://github.com/SPARC-FAIR-Codeathon/2024-team-5-service-2
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.13308927.svg)](https://doi.org/10.5281/zenodo.13308927)

<b>Citation: </b> Appukuttan, S., Benaribi, H., & Rievers, F. (2024). oSPARC Service #2: VTK Converter. Zenodo. https://doi.org/10.5281/zenodo.13308927

### Service 3: Visualize 3D Model
This module offers a quick and simple visualization of 3D scaffold models.
<br/><br/>
<b>Dedicated GitHub Repo:</b> https://github.com/SPARC-FAIR-Codeathon/2024-team-5-service-3
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.13308931.svg)](https://doi.org/10.5281/zenodo.13308931)

<b>Citation: </b> Appukuttan, S., Benaribi, H., & Rievers, F. (2024). oSPARC Service #3: Visualize 3D Model. Zenodo. https://doi.org/10.5281/zenodo.13308931

### Service 4: Fetch Scaffold From SPARC Portal
This module can fetch scaffold .vtk file from SPARC Portal for specified datasets.
<br/><br/>
<b>Dedicated GitHub Repo:</b> https://github.com/SPARC-FAIR-Codeathon/2024-team-5-service-4
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.13308937.svg)](https://doi.org/10.5281/zenodo.13308937)

<b>Citation: </b> Appukuttan, S., Benaribi, H., & Rievers, F. (2024). oSPARC Service #4: Fetch Scaffold From SPARC Portal. Zenodo. https://doi.org/10.5281/zenodo.13308937

### Service 5: Tabular Data Viewer
This module enables users to view tabular data fromw within study.
<br/><br/>
<b>Dedicated GitHub Repo:</b> https://github.com/SPARC-FAIR-Codeathon/2024-team-5-service-5
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.13308941.svg)](https://doi.org/10.5281/zenodo.13308941)

<b>Citation: </b> Appukuttan, S., Benaribi, H., & Rievers, F. (2024). oSPARC Service #5: Tabular Data Viewer. Zenodo. https://doi.org/10.5281/zenodo.13308941

### Service 6: Transcriptomics Data Explorer
This module allows users to explore and visualize transcriptomic data.
<br/><br/>
<b>Dedicated GitHub Repo:</b> https://github.com/SPARC-FAIR-Codeathon/2024-team-5-service-6
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.13308944.svg)](https://doi.org/10.5281/zenodo.13308944)

<b>Citation: </b> Appukuttan, S., Benaribi, H., & Rievers, F. (2024). oSPARC Service #6: Transcriptomics Data Explorer. Zenodo. https://doi.org/10.5281/zenodo.13308944


## Deployment Status

The services are awaiting deployment to oSPARC production. The GitHub actions fail, as we do not have the required permissions for the `build` stage:

> /home/scu/.venv/bin/python3: can't open file '/home/scu/.venv/bin/ooil': [Errno 13] Permission denied

Service has been deployed and tested locally via:
```
make publish-local
```

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Team Members
- **Shailesh Appukuttan** - Aix-Marseille Université, CNRS, INT, Marseille, France - [@appukuttan-shailesh](https://github.com/appukuttan-shailesh)
- **Hiba Ben Aribi** - University of Tunis El Manar, Tunis, Tunisia
 - [@HibaBenAribi](https://github.com/HibaBenAribi)
- **Fynn Rievers** - Tilburg University, Tilburg, The Netherlands - [@schrievicode](https://github.com/schrievicode)


## Have an issue or question?
Please open an issue [here](https://github.com/SPARC-FAIR-Codeathon/2024-team-5/issues).
