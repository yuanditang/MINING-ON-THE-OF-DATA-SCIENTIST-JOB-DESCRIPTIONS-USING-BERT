# Mining Data Scientist Job Descriptions Using BERT

This repository contains a project that leverages BERT (Bidirectional Encoder Representations from Transformers) to analyze and mine data scientist job descriptions in the United States. The goal is to extract insights regarding the required skills, qualifications, and trends in the data science job market.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Analysis Techniques](#analysis-techniques)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

With the increasing demand for data scientists, understanding the skills and qualifications sought by employers is crucial for aspiring professionals. This project utilizes BERT for natural language processing tasks to analyze job descriptions and extract key features and trends that define the data scientist role.

## Dataset

The dataset includes job descriptions collected from various job boards and company websites. Key features of the dataset include:

- **Job Title:** Title of the job position (e.g., Data Scientist, Junior Data Analyst).
- **Company Name:** Name of the hiring company.
- **Location:** Geographical location of the job.
- **Job Description:** Full text of the job description, outlining responsibilities and requirements.
- **Skills Required:** List of skills mentioned in the job description.
- **Posted Date:** Date when the job was posted.

### Source

[Dataset Link](#) (provide a link if applicable)

## Technologies Used

- Python
- BERT
- Pandas
- NumPy
- Transformers
- Scikit-learn
- Jupyter Notebook

## Analysis Techniques

The analysis performed in this project includes:

- **Text Preprocessing:** Cleaning and preparing job descriptions for analysis.
- **Feature Extraction:** Using BERT to extract embeddings and important features from job descriptions.
- **Clustering and Visualization:** Grouping similar job descriptions and visualizing trends in the data.
- **Trend Analysis:** Identifying skills in demand and evolving job requirements in the data science field.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yuanditang/MINING-ON-THE-OF-DATA-SCIENTIST-JOB-DESCRIPTIONS-USING-BERT.git
   ```

2. Navigate to the project directory:
   ```bash
   cd MINING-ON-THE-OF-DATA-SCIENTIST-JOB-DESCRIPTIONS-USING-BERT
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Open the Jupyter Notebook file (`job_description_analysis.ipynb`).
2. Run the cells to execute the analysis and view the results.
3. Modify the code as needed to explore different aspects of the job descriptions.

## Contributing

Contributions are welcome! If you have suggestions or improvements, please open an issue or submit a pull request.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
