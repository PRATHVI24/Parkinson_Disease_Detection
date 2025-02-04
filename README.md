# Parkinson_Disease_Detection
This project implements a machine learning model to detect Parkinson's Disease using biomedical voice measurements. The goal is to classify individuals as healthy or having Parkinson's Disease based on specific vocal attributes.
The project performs the following tasks:

1️⃣ Data Collection
2️⃣ Data Preprocessing
3️⃣ Exploratory Data Analysis
4️⃣ Dataset Balancing & Scaling
5️⃣ Machine Learning Models Training & Evaluation

## Dataset

The dataset comprises biomedical voice measurements from 31 individuals, 23 with Parkinson's Disease and 8 healthy. Each entry includes various vocal features such as:

- **MDVP:Fo(Hz)**: Average vocal fundamental frequency
- **MDVP:Fhi(Hz)**: Maximum vocal fundamental frequency
- **MDVP:Flo(Hz)**: Minimum vocal fundamental frequency
- **MDVP:Jitter(%), MDVP:Jitter(Abs), RAP, PPQ, DDP**: Measures of variation in fundamental frequency
- **MDVP:Shimmer, MDVP:Shimmer(dB), APQ3, APQ5, APQ, DDA**: Measures of variation in amplitude
- **NHR, HNR**: Ratios of noise to tonal components in the voice
- **RPDE, D2**: Nonlinear dynamical complexity measures
- **DFA**: Signal fractal scaling exponent
- **spread1, spread2, PPE**: Nonlinear measures of fundamental frequency variation

The target variable is **status**, where 1 indicates Parkinson's Disease and 0 indicates healthy.

## Model

The project uses a machine learning model to classify individuals based on the provided features. The specific algorithm and performance metrics are detailed within the codebase.

## Requirements

To run the project, ensure you have the following Python packages installed:

- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib`
- `seaborn`

You can install the required packages using pip:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```
## Usage

### Clone the repository:

```bash
git clone https://github.com/PRATHVI24/Parkinson_Disease_Detection.git
cd Parkinson_Disease_Detection
```
## Run the Jupyter Notebook:
Open the Jupyter Notebook file in your preferred environment to explore the data analysis, model training, and evaluation steps.

## Acknowledgements
The dataset used in this project is sourced from the UCI Machine Learning Repository.

For more details, refer to the original dataset: UCI Machine Learning Repository: Parkinsons Data Set

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contributing
Contributions are welcome. Please fork the repository and submit a pull request for any enhancements or bug fixes.

## Contact
For any inquiries or issues, please open an issue in this repository.
