# API-Risk-Assessment-Framework
This project quantifies the risk of the endpoint of each API based on security and data sovereignty markers. In this repository, we have included a well-annotated python script for (1) the data preprocessing and feature engineering, along with the (2) machine learning pipeline. These can be found in the `src` folder. 

This project is part of UBC MDS' capstone project where the contributors collaborated with TeejLab.

## Proposal

Our proposal can be found via [here](https://github.com/teejlab/API-Risk-Assessment-Framework/blob/main/docs/report_book/_build/pdf/book.pdf).

## Final Report
Our final report can be found [here](include link). 

## Usage
1. Clone the repo in your machine
2. Set up the environment using the instructions below.
3. The python scripts can be found in the `src` folder
4. The raw and processed data can be found in the `data` folder
5. To use the models directly, please refer to the `models` folder.

## Environment set up
You can install all the dependencies you need using conda:
```
# Create and activate the environment
conda env create -f env.yml
conda activate api-risk

# Install Presidio python package
pip install presidio_analyzer

# Presidio analyzer requires a spaCy language model
python -m spacy download en_core_web_lg
```
## Contributing

| Contributors         | Github                |
|----------------------|-----------------------|
| Anupriya Srivastava  | \@Anupriya-Sri        |
| Harry Chan           | \@harryyikhchan       |
| Jacqueline Chong     | \@Jacq4nn             |
| Son Chau             | \@SonQBChau           |

## License
(insert mit license sticker)