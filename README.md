# parkinsons-analysis

The purpose of this analysis project is to reveal and analyze patterns between Parkinson's diagnosis and patient demographic, lifestyle factors, medical history, clinical measurements, cognitive and functional assessments, and symptoms. Each section aims to characterize diagnosis dependencies and relationships and depict them intuitively, providing a thorough breakdown of the physiological and diagnostic phenomena associated with Parkinson's against diagnoses.

## Motivation

Parkinson's is a common neurodegeneative disorder, becoming more prevalent due to aging populations worldwide. Early diagnosis and treatment are crucial in preserving the comfort, functionality, and quality of life of those afflicted by Parkinson's, yet remains a challenge despite advancements in diagnostic techniques. Thus, a comprehensive understanding of the conditions and symptoms with which Parkinson's appears is critical in providing accurate and timely treatment. 

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/your-repo.git
   cd your-repo

2. Create Virtual Environment (Optional but Recommended)
    python -m venv env
    source env/bin/activate # mac OS/Linux
    env/Scripts/activate # windows

3. Install Required Dependencies:
    To run this project, you need to install the required Python libraries. You can do this using `pip` (Python's package manager).
    Run the following command to install all dependencies:
    pip install pandas numpy matplotlib seaborn scipy scikit-learn

4. Verify Installation:
    Check if everything is installed correctly by running:
    python -c "import pandas, numpy, matplotlib.pyplot, seaborn, scipy.stats, sklearn.linear_model; print('All libraries installed successfully!')"

## Usage:

    To run the analysis, follow these steps:

    1. Launch Jupyter Notebook
    jupyter notebook
    This will open a web interface where you can navigate to the parkinsonsDiseaseDatasetAnalysis.ipynb file

    2. Open and run the notebook:
    Open the notebook in Jupyter interface and execute the cells to run the analysis

    You can also convert the notebook into a script:
    jupyter nbconvert --to python parkinsonsDiseaseDatasetAnalysis.ipynb
    Then, run it as a standard Python script:
    python parkinsonsDiseaseDatasetAnalysis.py

## License:

    This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

    The dataset used in this analysis is from [Parkinson’s Disease Dataset Analysis](https://www.kaggle.com/datasets/rabieelkharoua/parkinsons-disease-dataset-analysis) by Rabie El Kharoua, available on Kaggle. Many thanks to the author for making this dataset available for analysis.

## Contact

    Questions and feedback are greatly appreciated; feel free to create an issue in this repository.
