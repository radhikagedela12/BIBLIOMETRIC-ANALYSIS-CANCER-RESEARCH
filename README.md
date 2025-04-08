# BIBLIOMETRIC-ANALYSIS-CANCER-RESEARCH
This repository contains the bibliometric analysis of cancer research, using Bibliometrix to explore trends, key themes, author collaborations, citation patterns, and more. The analysis focuses on scientific literature in cancer research, providing insights into emerging topics and influential publications.



# Bibliometric Analysis of Cancer Research

## Overview
This repository presents the results of a bibliometric analysis of cancer research literature. The analysis was conducted using the **Bibliometrix** R package, which was used to evaluate publication patterns, citation relationships, research trends, and collaborations in the field of cancer research. The dataset used includes publications related to cancer research over the last 5 years, with a focus on bone, muscle, and metabolism studies.

## Key Features
- **Citation Analysis:** Examines the influence of publications based on citation counts.
- **Co-authorship Analysis:** Identifies collaboration patterns among researchers and institutions.
- **Keyword Analysis:** Highlights core research topics and emerging areas of interest.
- **Network Mapping:** Visualizes relationships between authors, institutions, and keywords.
- **Trend Identification:** Detects emerging research topics and evaluates the impact of research over time.

## Tools Used
- **Bibliometrix** (R Package): A comprehensive tool for bibliometric research.
- **VOSviewer**: Used for network visualizations like co-authorship and citation mapping.
- **CiteSpace**: Used for trend analysis and cluster detection in scientific literature.

## Data Source
- **Web of Science**: The dataset was obtained from Web of Science using the keywords *bone AND muscle AND metabolism*. The analysis was performed on publications from the last 5 years, excluding review articles.

## Installation Instructions
To run the analysis locally, you will need to have **R** and **RStudio** installed, along with the **Bibliometrix** package.

1. **Install R and RStudio**: [Download here](https://posit.co/download)
2. **Install Bibliometrix**:
   ```R
   install.packages("bibliometrix")
   library(bibliometrix)


## Running the Analysis:
Import the data downloaded from Web of Science into the Bibliometrix interface.
Use biblioshiny() to launch the interactive analysis app in your browser.

## How to Contribute

Feel free to fork this repository and submit pull requests for improvements or additional analysis. Contributions are always welcome!

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.

## Acknowledgements

RStudio for the development environment.
Bibliometrix package developers for their work in making bibliometric analysis accessible.
Web of Science for providing the dataset.
