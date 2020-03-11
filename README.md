# automated-qsar-framework

<p align="center">
  <img align="middle" src="/docs/GA.png" width="400px" class="center">
 </p>
 
The increasing availability of extensive collections of chemical compounds associated with experimental data provides an opportunity to build predictive Quantitative Structure-Activity Relationship (QSAR) models using machine learning (ML) algorithms. These models can promote data-driven decisions and have the potential to speed up the drug discovery process and reduce their failure rates. However, many essential aspects of data preparation and modeling are not available in any standalone software. Here, we developed an automated framework for the curation of chemogenomics data and to develop QSAR models for virtual screening using the open-source KNIME software. The workflow includes four modules: (i) dataset preparation and curation; (ii) chemical space analysis and structure-activity relationships (SAR) rules; (iii) modeling; and (iv) virtual screening (VS). As case studies, applied these workflows to four datasets associated with different endpoints. The implemented protocol can efficiently curate chemical and biological data in public databases and generates robust QSAR models. We provide scientists a simple and guided cheminformatics workbench following the best practices widely accepted by the community, in which scientists can adapt to solve their research problems. The workflows are freely available for download at https://github.com/LabMolUFG/automated-qsar-framework. 

# Supported functionality
## Tasks:
* Data curation and preparation.
* SAR analysis.
* Automated model building and validation.
* Virtual screening.

## Data types
* SDF
* SMILES in .csv or .txt.

## Requirements
In order to get started you need:
* [KNIME 4.0.1](https://www.knime.com/)

# Acknowledgements

<p align="middle">
  <img src="./docs/UFG.png" alt="UFG" width="200">
  <img src="./docs/UNC.jpg" alt="UNC" width="400">
  <br>
</p>
