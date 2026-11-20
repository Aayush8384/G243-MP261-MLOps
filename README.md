\# G243-MP261 | Village Milk Collection Prediction



\### SCSE3040 – MLOps Mini Project



This repository contains an MLOps project developed to predict daily milk collection at village collection centres near Surat, Gujarat.



The project focuses on building a reproducible machine learning workflow, beginning with dataset versioning and data-quality investigation.



\## Project Information



| Field | Details |

|---|---|

| Institution | Bennett University |

| Course | SCSE3040 – MLOps |

| Group ID | G243 |

| Problem ID | MP261 |

| Batch | 54 |

| Faculty | Upasna Joshi |

| Project | Village Milk Collection (Surat) |



\## Team Members



| Name | Enrollment Number |

|---|---|

| Aayush Sharma | S24CSEU1198 |

| Anubhav Sharma | S24CSEU1201 |

| Rakshit Chugh | S24CSEU2485 |

| Khushhi Bakshi | S24CSEU1286 |



\## Problem Statement



The Surat District Dairy Cooperative needs a reliable way to estimate daily milk collection at village centres.



Accurate predictions can help improve transportation planning, optimize chilling-space allocation, reduce unnecessary operational costs, and minimize milk spoilage.



\*\*Machine Learning Task:\*\* Regression



\*\*Target Variable:\*\* `litres\_per\_day`



\*\*Evaluation Metric:\*\* Mean Absolute Error (MAE)



\## Dataset Overview



The project uses three datasets:



| Dataset | Purpose |

|---|---|

| `train.csv` | Historical training records from January to June 2026 |

| `later.csv` | July–August 2026 records for subsequent evaluation and monitoring |

| `holdout\_features.csv` | September 2026 records for final prediction |



The dataset includes information about cattle populations, fodder prices, temperature, veterinary visits, feed consumption, cattle breeds, and village clusters.



\## Stage 1 – Data Versioning and Quality Investigation



The first stage establishes the foundation for a reproducible MLOps workflow.



\### Objectives



1\. Set up a shared public GitHub repository for group collaboration.

2\. Configure Git and initialize DVC.

3\. Track the original training and later datasets using DVC.

4\. Examine the structure and characteristics of the training data.

5\. Investigate seven possible data-quality issues.

6\. Document verified findings in `reports/findings.yaml`.

7\. Commit and push the Stage 1 implementation.



\### Data Quality Checks



The following issues will be investigated:



| Issue | Description |

|---|---|

| Data Leakage | Features containing information unavailable at prediction time |

| Unit Mix-up | Measurements recorded in inconsistent units |

| Sentinel Values | Special numeric values used to represent missing data |

| Duplicate Rows | Repeated records in the dataset |

| Stuck Sensor | Sensor readings remaining constant over an abnormal period |

| Target Typos | Incorrect target values caused by an extra zero |

| Spelling Variants | Inconsistent representations of categorical values |



The results will be determined through Python-based analysis of the original training dataset.





\## Tools and Technologies



\- \*\*Python:\*\* Data exploration and analysis

\- \*\*Pandas:\*\* Data-quality investigation

\- \*\*Git:\*\* Source code version control

\- \*\*GitHub:\*\* Team collaboration and repository hosting

\- \*\*DVC:\*\* Dataset version management

\- \*\*YAML:\*\* Structured documentation of findings



\## Current Progress



\*\*Stage 1 – In Progress\*\*



The repository is being prepared for data versioning, quality investigation, and reproducible development.



\---



\*\*Bennett University | SCSE3040 – MLOps | Group G243 | Problem MP261\*\*



