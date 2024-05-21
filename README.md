# Data for Days <a href="https://github.com/JonWayland/data-for-days"><img src="images/logo.png" align="right" height="140" /></a>

**You won't find this data anywhere else!**

This repo is dedicated to bringing tabular structure to otherwise unstructured information. It aims to provide the data science community with diverse datasets curated from a wide variety of domains and topics. All data created and subsequently shared in this repository has been programmatically scraped from the web and therefor may be imperfect. In other words, additional data cleansing may be required for your desired analysis and/or model.

## Project Overview

Unstructured data represents the vast majority of data available in the digital world, yet harnessing it meaningfully remains a challenge. This repository addresses this gap by providing carefully curated datasets that are (mostly) ready for analysis, machine learning models, and educational purposes. I highly encourage others to contribute to **Data for Days**.

## The Data

Each dataset in this repository was programmatically scraped from the internet. For each set of data, the following files are provided:

- **Dataset:** The data is provided in a `.csv` file in the format of 1 row per observation.
- **Metadata:** Metadata providing additional context about the data collection such as the source and date it was scraped is shared as a `.txt` file.

### Available Datasets

The following datasets are currently available for download:
- **[American Desserts](https://github.com/JonWayland/data-for-days/blob/main/data/american_desserts_20240323.csv)**  [[...*Metadata*]](https://github.com/JonWayland/data-for-days/blob/main/data/american_desserts_20240323.txt)
  - **Description:** List of American Desserts and their respective ingredients in a comma-separated string
- **[Country Music Hall of Fame](https://github.com/JonWayland/data-for-days/blob/main/data/country_hof_20240521.csv)**  [[...*Metadata*]](https://github.com/JonWayland/data-for-days/blob/main/data/country_hof_20240521.txt)
  - **Description:** List of Country Music Hall of Fame Inductees (1 row per individual), the year they were inducted, their birth date, their date of death if applicable, current age or age at death, and living status.
- **[Harry Potter](https://github.com/JonWayland/data-for-days/blob/main/data/harry_potter_20240521.csv)**  [[...*Metadata*]](https://github.com/JonWayland/data-for-days/blob/main/data/harry_potter_20240521.txt)
  - **Description:** List of all Harry Potter characters with a known surname, a description of the character, and any additional notes.
- **[Hurricanes](https://github.com/JonWayland/data-for-days/blob/main/data/hurricanes_20240507.csv)**  [[...*Metadata*]](https://github.com/JonWayland/data-for-days/blob/main/data/hurricanes_20240507.txt)
  - **Description:** List of all US Hurricanes, their Saffir Simpson Category, the state they impacted, the date they formed, the date they became extra tropical, the date they dissipated, the number of estimated fatalities, and the estimated damage in USD

### How to Use Data for Days

1. **Download Data:**
  - Each dataset is available for download as a .csv file.
  - Analyze it, build dashboards, create web apps, develop machine learning models, have fun with it!

2. **Contribute Data:**
   I welcome contributions to our dataset repository! Please follow these steps to submit your data:

   ### Step 1: Fork the Repository

   1. Go to https://github.com/JonWayland/data-for-days
   2. Click on the "Fork" button at the top right of the page. This will create a copy of the repository under your GitHub account.
  
   ### Step 2: Clone Your Fork
  
   1. Clone the forked repository to your local machine using the following command:
      ```bash
      git clone https://github.com/your-username/data-for-days.git

   2. Navigate into the cloned directory:
      ```bash
      cd data-for-days

   ### Step 3: Create a New Branch

   1. Create a new branch for your data contribution:
      git checkout -b add-your-data

   ### Step 4: Add Your Data

   1. Add your data files to the appropriate directory in the repository.
   2. If necessary, update any relevant documentation or metadata files.
  
   ### Step 5: Commit Your Changes

   1. Stage your changes:
      ```bash
      git add .
   2. Commit your changes with a descriptive message:
      ```bash
      git commit -m "Add new dataset: [describe your dataset briefly]"

   ### Step 6: Push to Your Fork

   1. Push your changes to your forked repository:
      ```bash
      git push origin add-your-data

   ### Step 7: Open a Pull Request
   
   1. Go to your forked repository on GitHub.
   2. Click on the "Compare & pull request" button.
   3. Provide a clear description of your data contribution and any relevant information.
   4. Submit the pull request.
   
