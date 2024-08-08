# MusicGenrePrediction

This project develops a machine learning model to classify music tracks into various genres based on their audio features. The model uses a dataset with different audio features and applies classification algorithms to identify the genre of a given music track.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Music genre classification is a fundamental task in music information retrieval and has applications in recommendation systems, music streaming platforms, and music categorization. This project aims to build a model that can accurately classify music tracks into genres based on their audio features.

## Features

- **Data Preprocessing:** Cleans and prepares the dataset, handling missing values and normalizing audio features.
- **Model Training:** Implements various classification models, such as K-Nearest Neighbors, Support Vector Machine (SVM), and Neural Networks.
- **Model Evaluation:** Uses cross-validation and metrics such as accuracy, precision, recall, and F1-score to evaluate the performance of different models.
- **Visualization:** Provides visualizations to compare model performance and analyze feature importance.

## Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- TensorFlow/Keras (if Neural Networks are used)
- Matplotlib
- Seaborn

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/kabirkohli123/music-genre-classification.git
   cd music-genre-classification
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the Jupyter notebook to execute the model training and evaluation:
   ```bash
   jupyter notebook MusicGenreClassification.ipynb
   ```

2. Follow the steps in the notebook to preprocess data, train models, and evaluate performance.

## Project Structure

```
music-genre-classification/
├── MusicGenreClassification.ipynb
├── README.md
├── requirements.txt
├── data/
│   └── music_data.csv
```

- **MusicGenreClassification.ipynb:** Jupyter notebook with the full implementation of the project.
- **README.md:** Project documentation.
- **requirements.txt:** List of dependencies.
- **data/music_data.csv:** Dataset containing audio features for music genre classification.

## Contributing

Contributions are welcome! If you have any suggestions, improvements, or bug fixes, please open an issue or create a pull request. Follow the contribution guidelines in `CONTRIBUTING.md`.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

Thank you for using the Music Genre Classification project! If you have any questions or need further assistance, please feel free to contact us.

Happy coding!
