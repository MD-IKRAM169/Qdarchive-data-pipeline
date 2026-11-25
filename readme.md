
<h1 align="center">QDArchive Data Pipeline</h1>

<p align="center">
  <strong>Automated Research Data Acquisition, Classification & Analytics</strong>
</p>

<p align="center">
  Academic Project · Friedrich-Alexander-Universität Erlangen-Nürnberg (FAU)
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-306998?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/SQL-35647F?style=for-the-badge" alt="SQL">
  <img src="https://img.shields.io/badge/SQLite-176D91?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite">
  <img src="https://img.shields.io/badge/ETL-176B65?style=for-the-badge" alt="ETL">
  <img src="https://img.shields.io/badge/scikit--learn-B96718?style=for-the-badge" alt="scikit-learn">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Projects-62-315C81?style=for-the-badge" alt="62 projects">
  <img src="https://img.shields.io/badge/File_Records-4%2C087-176B65?style=for-the-badge" alt="4087 file records">
  <img src="https://img.shields.io/badge/Acquisition_Validation-10_Checks_Passed-237A57?style=for-the-badge" alt="10 validation checks passed">
</p>

---

## Project Overview

An end-to-end Python and SQLite data engineering pipeline developed as part of the Seeding QDArchive academic project at FAU Erlangen-Nürnberg.

The system collects, organizes and classifies qualitative research metadata from the Qualitative Data Repository (QDR) and the CESSDA Data Catalogue.

The workflow combines API-based data acquisition, ETL processing, relational database management, text classification, data validation and automated reporting.

## Key Results

| Metric | Documented Result |
|---|---:|
| Research projects processed | 62 |
| File records collected | 4,087 |
| Keywords extracted | 352 |
| Relevant projects classified using ISIC Rev. 5 | 32 |
| Primary file records processed for classification | 3,724 |
| Independent content classifications | 87 |
| Project-class fallback classifications | 3,637 |
| ISIC Rev. 5 divisions imported | 87 |
| SQ26 acquisition database validation | 10 checks passed |
| Acquisition validation warnings and errors | 0 |

Results refer to the documented academic submission snapshot.
File records do not represent successful downloads.
Classification confidence is not equivalent to measured accuracy.

## Core Technical Contributions

- Automated data acquisition from QDR and CESSDA.
- Metadata extraction and relational SQLite database design.
- Dataset deduplication and download outcome tracking.
- Rule-based project-type classification.
- Weighted word-level and character-level TF-IDF classification.
- ISIC Rev. 5 project and primary-file categorization.
- Transparent handling of unavailable file content.
- Database validation, Excel exports and PDF reporting.

## Author

**Md Ikram Tareq**

M.Sc. Data Science — FAU Erlangen-Nürnberg, Germany

[LinkedIn](https://www.linkedin.com/in/md-ikram-tareq/) · [Portfolio](https://md-ikram169.github.io/) · [GitHub](https://github.com/MD-IKRAM169)

---
