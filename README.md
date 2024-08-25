# oSPARC Hub : An Extensible ETL Framework for Streamlining the SPARC Ecosystem

![License Badge](https://img.shields.io/badge/license-MIT-blue.svg) ![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg) ![Version](https://img.shields.io/badge/version-0.1.0-blue) 

<br/>
<p align="center">
  <img src="https://github.com/appukuttan-shailesh/testData/blob/master/SPARC2024/oSPARCHub_logo.png?raw=true" width="300"  />
</p>
<br/><br/>

## Table of Contents
- [Video Overview](#Video_Overview)
- [Introduction](#introduction)
- [Presenting oSPARC Hub](#presenting-osparc-hub)
- [oSPARC Applications](#osparc-applications)
- [oSPARC Services](#osparc-services)
- [License](#license)
- [Team Members](#team-members)
  
## Video Overview

[![webinar_preview](https://github.com/appukuttan-shailesh/testData/blob/master/SPARC2024/Slide1.png?raw=true)](https://youtu.be/K5eAg9lYgkc)
<br/><br/>

## Introduction
The SPARC Database offers a variety of datasets, including anatomical models, neural connectivity data available on the SCKAN database, physiological and electrophysiological data, genomics data, and more. These datasets are spread across different websites and typically require preprocessing before they can be visualized. Additionally, many models are not immediately usable and require significant preliminary work by the end-user to extract meaningful insights.

oSPARC is a platform provided by SPARC that offers services, code templates, and modules for managing various SPARC data types. However, not all datasets have dedicated visualization tools available on the oSPARC platform.
<br/><br/>
## Presenting oSPARC Hub

The oSPARC Hub framework is a comprehensive suite of SPARC pipelines, modules, and applications designed to enhance the capabilities of the oSPARC platform. It introduces an integrated pipeline that allows users to navigate datasets directly from the SPARC portal within the platform.

![image](https://github.com/user-attachments/assets/4c1fc6c6-ae96-40bd-b8ca-f77873d2ef1c)

Depending on the data type, there are three specialized applications available: one for accessing and utilizing data on the SCKAN database, another for exploring anatomical models on the SPARC Portal, and a third for working with genomics datasets. In addition, several modules have been developed to efficiently process various data types, ensuring seamless integration and usability.
<br/><br/>
In total, we have developed: 

-3 oSPARC Application available on the oSPARC platform. 

<p align="center">
  <img src="https://github.com/user-attachments/assets/37dd82d6-00c2-4cc2-ba56-300698aafabf" width="700"  />
</p>

-And  6 oSPARC Services, that are accessible via the oSPARC platform. 

<p align="center">
  <img src="https://github.com/SPARC-FAIR-Codeathon/oSPARC-Hub/blob/main/assets/screenshots/ListServices.png" width="700"  />
</p>
<br/><br/>

## oSPARC-Hub Applications

| Name                                 | Utility                                                           | Tutorial                                                                                           | Source Code                                                                                                              | Zenodo                                                                                                    |
|--------------------------------------|-------------------------------------------------------------------|----------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------|
| Visualize Anatomical Modules Demonstration | Visualizes Anatomical 3D Scaffold                                      | [Tutorial](https://github.com/SPARC-FAIR-Codeathon/oSPARC-Hub/blob/main/Apps/Tutorial%20for%20%3AVisualize%20Anatomical%20Modules.md) | [Source Code](https://github.com/SPARC-FAIR-Codeathon/oSPARC-Hub/tree/main/Apps/Visualize%20Anatomical%20Modules)        |                                                                                                           |
| Transcriptomics data visualization   | Analyzes and visualizes transcriptomics data                        | [Tutorial](https://github.com/SPARC-FAIR-Codeathon/2024-team-5/blob/main/Apps/Tutorial%20for%20:Transcriptomics%20data%20visualization.md) | [Source Code](https://github.com/SPARC-FAIR-Codeathon/2024-team-5/tree/main/Apps/Transcriptomics%20data%20visualization) |                                                                                                           |
| Visualize SCKAN database data        | Accesses and visualizes SCKAN database data                         | [Tutorial](https://github.com/SPARC-FAIR-Codeathon/2024-team-5/blob/main/Apps/Tutorial%20for%20%3A%20Visualize%20SCKAN%20datadase%20data.md) | [Source Code](https://github.com/SPARC-FAIR-Codeathon/2024-team-5/tree/main/Apps/Visualize%20SCKAN%20datadase%20data)    |                                         <br/><br/>                                                                  |                                                                  |
## oSPARC Services

| Name                                 | Utility                                                           | Tutorial                                                                                           | Source Code                                                                                                              | Zenodo                                                                                                    |
|--------------------------------------|-------------------------------------------------------------------|----------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------|
| File Format Converter                | Converts files between various formats                             |                                                                                                    | [Dedicated GitHub Repo](https://github.com/SPARC-FAIR-Codeathon/2024-team-5-service-1)                                  | [Zenodo](https://doi.org/10.5281/zenodo.13308896)                                                         |
| VTK Converter                        | Converts .vtk files to .stl and .obj formats                       |                                                                                                    | [Dedicated GitHub Repo](https://github.com/SPARC-FAIR-Codeathon/2024-team-5-service-2)                                  | [Zenodo](https://doi.org/10.5281/zenodo.13308927)                                                         |
| Visualize 3D Model                   | Visualizes 3D scaffold models                                      |                                                                                                    | [Dedicated GitHub Repo](https://github.com/SPARC-FAIR-Codeathon/2024-team-5-service-3)                                  | [Zenodo](https://doi.org/10.5281/zenodo.13308931)                                                         |
| Fetch Scaffold From SPARC Portal     | Fetches scaffold .vtk files from SPARC Portal                      |                                                                                                    | [Dedicated GitHub Repo](https://github.com/SPARC-FAIR-Codeathon/2024-team-5-service-4)                                  | [Zenodo](https://doi.org/10.5281/zenodo.13308937)                                                         |
| Tabular Data Viewer                  | Views tabular data within studies                                  |                                                                                                    | [Dedicated GitHub Repo](https://github.com/SPARC-FAIR-Codeathon/2024-team-5-service-5)                                  | [Zenodo](https://doi.org/10.5281/zenodo.13308941)                                                         |
| Transcriptomics Data Explorer        | Explores and visualizes transcriptomic data                        |                                                                                                    | [Dedicated GitHub Repo](https://github.com/SPARC-FAIR-Codeathon/2024-team-5-service-6)                                  | [Zenodo](https://doi.org/10.5281/zenodo.13308944)                                                         |

####  Models Deployment Status

The services are awaiting deployment to oSPARC production. The GitHub actions fail, as we do not have the required permissions for the `build` stage:

> /home/scu/.venv/bin/python3: can't open file '/home/scu/.venv/bin/ooil': [Errno 13] Permission denied

Service has been deployed and tested locally via:
```
make publish-local
```
<br/><br/>
## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Team Members
- **Shailesh Appukuttan** - Aix-Marseille Université, CNRS, INT, Marseille, France - [@appukuttan-shailesh](https://github.com/appukuttan-shailesh)
- **Hiba Ben Aribi** - University of Tunis El Manar, Tunis, Tunisia - [@HibaBenAribi](https://github.com/HibaBenAribi)
- **Fynn Rievers** - Tilburg University, Tilburg, The Netherlands - [@schrievicode](https://github.com/schrievicode)


## Have an issue or question?
Please open an issue [here](https://github.com/SPARC-FAIR-Codeathon/2024-team-5/issues).
