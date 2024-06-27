
# RDBE: Reasoning Distillation-Based Evaluation Enhances Automatic Essay Scoring

## Abstract

This project introduces Reasoning Distillation-Based Evaluation (RDBE) which integrates interpretability to elucidate the rationale behind model scores while enhancing performance through initial reasoning. Our experimental results demonstrate the efficacy of RDBE across all scoring rubrics considered in the dataset.

## Features

- Provides interpretability in essay evaluation
- Enhances performance of small language models
- Adaptable for other long-form text evaluation tasks

## Installation and Setup

To set up the project, follow these steps:

```sh
# Clone the repository
git clone https://github.com/AliGhiasvand86/RDBE.git

# Navigate to the project directory
cd rdbe

# Install dependencies
pip install -r requirements.txt
Usage
Detailed instructions on how to use the project:

sh
Copy code
# Example command to run the model
python evaluate.py --input your_essay.txt
Methodology
Our method involves utilizing two main steps:

Synthetic Data Generation: Using the Llama3 70B model to generate scores and reasoning for each rubric.
Fine-Tuning Backbone Model: Training a smaller transformer model to generate reasoning and scores.
Experiments & Results
We used the DREsS dataset for training and testing. Our framework outperformed baseline models in all scoring rubrics.

Contributing
If you want to contribute to this project, please follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes.
Commit your changes (git commit -m 'Add new feature').
Push to the branch (git push origin feature-branch).
Open a Pull Request.
License
This project is licensed under the MIT License. See the LICENSE file for more details.

csharp
Copy code

You can now copy and paste this entire block into your README file on GitHub.








