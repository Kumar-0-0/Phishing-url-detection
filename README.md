# Phishing URL Detection

This project aims to detect phishing URLs using machine learning techniques. Phishing URLs are malicious web pages that try to trick users into revealing their personal or financial information, such as passwords, credit card numbers, or bank accounts. Phishing URLs can pose a serious threat to online security and privacy.

## Files

The project consists of the following files:

- `GUI.py`: A graphical user interface that allows users to enter a URL and check if it is phishing or not.
- `Phishing Website Detection.ipynb`: A Jupyter notebook that contains the data analysis and model building process.
- `dataset2.csv` and `dataset3.csv`: Two datasets that contain features and labels of phishing and legitimate URLs.
- `feature_extractor.py`: A Python script that extracts various features from a given URL, such as domain length, presence of IP address, presence of HTTPS, etc.
- `rf_model.py`: A Python script that trains and saves a random forest classifier using the extracted features.

## Dependencies

To run the project, you need to install the following dependencies:

- pandas
- numpy
- sklearn
- tkinter
- urllib

You can install them using pip or conda.

## Usage

To use the GUI, run the following command:

`bash
python GUI.py`

To use the Jupyter notebook, open it in your preferred IDE or browser.

To use the feature extractor or the random forest model, import them in your Python code as follows:

from feature_extractor import extract_features
from rf_model import predict
## Disclaimer
The project is still in progress and may contain bugs or errors. Feel free to report any issues or suggestions on GitHub.
