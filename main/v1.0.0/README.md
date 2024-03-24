
# Flagship Dataset of Type 2 Diabetes from the AI-READI Project

## Version number
1.0

## Publication date
2024-04-01

!comment: update date when available

## Identifier
https://doi.org/10.5281/fairhub.7641684

!comment: update DOI when available

## Overview of the study
The Artificial Intelligence Ready and Equitable Atlas for Diabetes Insights (AI-READI) project seeks to create a flagship ethically-sourced dataset to enable future generations of artificial intelligence/machine learning (AI/ML) research to provide critical insights into type 2 diabetes mellitus (T2DM), including salutogenic pathways to return to health. The ability to understand and affect the course of complex, multi-organ diseases such as T2DM has been limited by a lack of well-designed, high quality, large, and inclusive multimodal datasets. The AI-READI team of investigators will aim to collect a cross-sectional dataset of 4,000 people and longitudinal data from 10% of the study cohort across the US. The study cohort will be balanced for self-reported race/ethnicity, gender, and diabetes disease stage. Data collection will be specifically designed to permit downstream pseudo-time manifold analysis, an approach used to predict disease trajectories by collecting and learning from complex, multimodal data from participants with differing disease severity (normal to insulin-dependent T2DM). The long-term objective for this project is to develop a foundational dataset in T2DM, agnostic to existing classification criteria or biases, which can be used to reconstruct a temporal atlas of T2DM development and reversal towards health (i.e., salutogenesis). Six cross-disciplinary project modules involving teams located across eight institutions will work together to develop this flagship dataset. Data will be optimized for downstream AI/ML research and made publicly available. This project will also create a roadmap for ethical and equitable research that focuses on the diversity of the research participants and the workforce involved at all stages of the research process (study design and data collection, curation, analysis, and sharing and collaboration).

## Description of the dataset
This dataset contain data from 204 participants from the pilot period of the project (July 19, 2023 to November 30, 2023). Data from multiple modalities are included. A full list is provided in the "Data Standards" section below. The data in this dataset contain no personel health information (PHI). Information related to the sex and race/ethnicity of the participants has also been removed.

The dataset contains a total of 1,265 files (including data and metadata files) and is 250 GB in size.

!comment: Update final file count and dataset size.

A detailed description of the dataset is available at [docs.aireadi.org](https://docs.aireadi.org/).

## Protocol
The protocol followed for collecting the data can be found at [docs.aireadi.org](https://docs.aireadi.org/).

## Dataset access/restrictions
Accessing the dataset requires several steps, including:
1. Login in through a verified ID system (such as Microsoft Entra Verified ID or Login.gov)
2. Agreeing to use the data only for type 2 diabetes related research.
3. Agreeing to the license terms which set certain restrictions and obligations for data usage (see "License" section below). 

## Data standards followed
This dataset is organized following the [Clinical Dataset Structure (CDS) v0.1.0](https://github.com/AI-READI/high-level-dataset-structure). We refer to the CDS documentation for more details. Briefly, data is organized at the root level into one folder per datatype (c.f. Table below). Within each datatype folder, there is one folder per modality. Within each modality folder, there is one folder per device used to collect that modality. Within each device folder, there is one folder per participant. Each datype, modality, and device folder is named using a code name that best defines it while keeping it short. Each participant folder is named after the participant's ID number used in the study. For each datatype, the data files follow the standards listed in the Table below. More details are available in the dataset_structure_description.json metadata file included in this dataset. An example of the dataset structure is available [here](https://github.com/AI-READI/ai-readi-dataset-mock-up).

| Datatype      | Code name | Description | File format standard followed |
| ----------- | ----------- | ----------- | ----------- 
| Activity Monitoring      | activity_monitoring  | description | [Open mHealth](https://www.openmhealth.org/documentation/#/schema-docs/schema-library)
| Contiuous Glucose Monitoring   | cgm      | description | [Open mHealth](https://www.openmhealth.org/documentation/#/schema-docs/schema-library)
| Clinical data     | clinical_data  | description | [Observational Medical Outcomes Partnership (OMOP) Common Data Model (CDM)](https://ohdsi.github.io/TheBookOfOhdsi)
| Electrocardiogram    | ekg  | description | [WaveForm DataBase (WFDB)](https://wfdb.readthedocs.io/en/latest/wfdb.html)
| Environmental sensor data    | environmental_sensor  | description | [Earth Science Data Systems (ESDS) format](https://www.earthdata.nasa.gov/esdis/esco/standards-and-practices/ascii-file-format-guidelines-for-earth-science-data)
| Fluorescence Lifetime Imaging Ophthalmoscopy (FLIO) image   | flio | description | [Digital Imaging and Communications in Medicine (DICOM)](http://medical.nema.org/)
| Optical Coherence Tomography (OCT) image  | oct  | description | [Digital Imaging and Communications in Medicine (DICOM)](http://medical.nema.org/)
| Optical Coherence Tomography Angiography (OCTA) image  | octa  | description | [Digital Imaging and Communications in Medicine (DICOM)](http://medical.nema.org/)
| Retinal photography image    | retinal_photography  | description | [Digital Imaging and Communications in Medicine (DICOM)](http://medical.nema.org/)


!comment: add CDS link + description in table

## Resources
All of our data files are in formats that are accessible with free software commonly used for such data types so no specific software is required. Some useful resources related to this dataset are listed below:
- Documentation of the dataset: [docs.aireadi.org](https://docs.aireadi.org/)
- Dataset mock-up: [GitHub template](https://github.com/AI-READI/ai-readi-dataset-mock-up)
- AI-READI project website: [aireadi.org](https://aireadi.org/)
- Zenodo community of the AI-READI project: [zenodo.org/communities/aireadi](https://zenodo.org/communities/aireadi)
- GitHub organization of the AI-READI project: [github.com/AI-READI](https://github.com/AI-READI)

## License
This work is licensed under a custom license specifically tailored to enable reuse of the AI-READI dataset (and other clinical datasets) for commercial or research purpose while putting strong requirements around data usage, security, and secondary sharing to protect study participants, especially when data is reused for artificial intelligence (AI) and machine learning (ML) related applications. More details are available in the License file included in the dataset and also available at https://doi.org/10.5281/zenodo.10642459. 

## How to cite
 If you use this dataset for any purpose, please cite the dataset the resources specified in the [AI-READI documentation](https://docs.aireadi.org/docs/1/citation).

## Contact
For any questions, suggestions, or feedback related to this dataset, please email contact@aireadi.org. We refer to the study_description.json and dataset_description.json metadata files included in this dataset for additional information about contact person/entity, authors, and contributors of the dataset.

## Acknowledgement
The AI-READI project is supported by NIH grant [1OT2OD032644](https://reporter.nih.gov/search/1ADgncihCk6fdMRJdCnBjg/project-details/10471118) through the NIH Bridge2AI Common Fund program.
