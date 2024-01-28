# Diamond Price Prediction

Welcome to the Diamond Price Prediction project! This repository focuses on predicting diamond prices using machine learning models. The project is equipped with an end-to-end deployment setup, allowing users to access predictions through a Flask web application.


## Project Components

- **artifacts**: Contains serialized data and model files.
- **logs**: Stores log files for training and application activities.
- **notebooks**: Jupyter notebooks for exploratory data analysis (EDA), model training, and dataset exploration.
- **src**: Source code for the project.
  - **components**: Modules for data ingestion, preprocessing, and model definition.
  - **pipelines**: Pipelines for training and making predictions.
  - **utils.py**: Utility functions.
  - **logger.py**: Logging configuration.
  - **exception.py**: Custom exception handling.
- **templates**: HTML templates for the web application.
- **application.py**: Flask application for serving the web pages.
- **requirements.txt**: Dependencies needed for the project.
- **setup.py**: Setup file to install project dependencies.

## Usage

1. Run the setup file to install all dependencies.
   ```bash
   python setup.py install
   ```

2. Run the training pipeline to train the model.

    ```bash
    python src/pipelines/training_pipeline.py
    ```

3. Start the Flask application.

    ```bash
    python application.py
    ```

4. Visit `http://localhost:5000/` in your browser to access the Diamond Price Prediction web application.

## Contributors

- GreatClasher

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code. If you make significant improvements, consider contributing back to the project.

Happy predicting! 🚀


