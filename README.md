# Baubap Hackathon 2

Model developed for the second Baubap Hackathon.

## Installation

- Python 3.10 was used for development.
- It is recommended to use the `requirements.txt` file to install the necessary libraries for the project.

## Usage

The project consists of 3 important Jupyter notebooks:

1. **EDA**: Exploration of the training data for the model. Used to choose the columns for the model.
2. **Stack**: Notebook where the ensemble model for the competition was developed.
3. **Test**: Notebook for obtaining data from each checkpoint and subsequently providing a list of predictions.

## Project Structure

The project structure is based on 4 folders: `data`, `models`, `notebooks`, and `results`.

- The `data` folder is used to store CSV and Parquet files.
- The `models` folder stores models in joblib format, along with a list of features for the model.
- The `notebooks` folder stores Jupyter notebooks used for model development.
- The `results` folder stores checkpoint results in Parquet format.

## Contribution

- ChatGPT was used to expedite development during the hackathon.
- Research was conducted on the creation of ensemble models, and the technique shown by YouTuber Data Professor was applied as demonstrated in this video: [Ensemble Learning with XGBoost](https://www.youtube.com/watch?v=0BGLfYY26zQ).

## License

MIT License

## Project Status

Stable

## Acknowledgments

Special thanks to the Baubap team for organizing and supporting the hackathon, along with workshops for modeling.

## Contact

For inquiries, please contact: casillas.arturo@proton.me
``
