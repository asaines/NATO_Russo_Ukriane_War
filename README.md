# NATO-Russo-Ukraine War Analysis

This repository contains a detailed analysis of the NATO-Russo-Ukraine conflict, focusing on key events, military actions, and geopolitical implications. The analysis was performed using R and is presented as a markdown file, providing an alternative to traditional Jupyter notebooks.

## Project Overview

The project aims to explore the dynamics of the conflict through data-driven insights. It includes comprehensive visualizations, trend analyses, and discussions on the implications of the ongoing war.

## Structure

- **Analysis**: The core analysis is presented in markdown format [here](https://asaines.github.io/NATO_Russo_Ukriane_War/), generated using R. The analysis includes:
  - Key events timeline
  - Military actions and outcomes
  - Geopolitical and economic impacts
- **Data**: Raw and processed data used for the analysis is available in the `data` folder.
- **Scripts**: R scripts for data processing and visualization are located in the `scripts` folder.

## Usage

To replicate the analysis, follow these steps:

1. **Clone the Repository**: Clone this repository to your local machine.
   
   ```bash
   git clone https://github.com/asaines/NATO_Russo_Ukriane_War.git

2. **Install Required R Packages**: Install the necessary R packages. You can do this by opening R and running:

    ```bash
    install.packages(c("quanteda", "quanteda.textplots", "cowplot", "vader", "readxl", "tidyverse", "REdaS"))


Alternatively, if a DESCRIPTION or renv.lock file is provided, use it to install the exact package versions used.

3. **Render the R Markdown File**: Open the NATO_Russo_Ukriane_War.Rmd file in RStudio or another R environment and render it to produce the analysis.

    ```bash
    rmarkdown::render("NATO_Russo_Ukriane_War.Rmd")

4. **View the Analysis**: Once rendered, open the generated HTML file in a web browser to view the analysis.


## Results
The analysis confirmed a significant finding: there is a negative relationship between the distance from Russia and the proportion of positive tweets about NATO. Specifically, the closer a European country is to Russia, the more positively it tweets about NATO. This conclusion was supported by the scatter plot, correlation matrix, and Europe heat map, validating the hypothesis that proximity to Russia influences public sentiment toward NATO.

### Word Cloud

<div align="center">
    <img src="https://github.com/user-attachments/assets/9c56b6b3-4c87-4d08-bc0e-d668957860b3" alt="Word Cloud">
</div>

The word cloud shows the most frequently mentioned terms in tweets related to the Russo-Ukrainian war and NATO, highlighting key topics of discussion.

### Geographical Sentiment Map

<div align="center">
    <img src="https://github.com/user-attachments/assets/37cbffbc-2d71-4cb6-9d3a-6e8222ed35c1" alt="Geographical Sentiment Map">
</div>

This map illustrates the percentage of positive words about NATO in tweets across different European countries. The results indicate that countries closer to Russia have a higher rate of positive sentiment towards NATO.

### Positive Score vs. Distance

<div align="center">
    <img src="https://github.com/user-attachments/assets/d2d5898d-9d76-4b9f-b93a-0b12538a2181" alt="Positive Score vs. Distance">
</div>

The scatter plot displays the relationship between the distance from Russia and the positive sentiment score. It suggests that proximity to Russia may positively influence NATO's perception.


The analysis confirmed a significant finding: there is a negative relationship between the distance from Russia and the proportion of positive tweets about NATO. Specifically, the closer a European country is to Russia, the more positively it tweets about NATO. This conclusion was supported by the scatter plot, correlation matrix, and Europe heat map, validating the hypothesis that proximity to Russia influences public sentiment toward NATO.

## License

This project is licensed under the MIT License.


## Contact

For questions or further information, feel free to reach out via [Linkedin](https://www.linkedin.com/in/asaines/)
