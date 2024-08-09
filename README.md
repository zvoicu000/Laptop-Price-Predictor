# Laptop Price Predictor

A machine learning project that predicts laptop prices based on various features such as specifications, brand, and other relevant factors. This project aims to help users estimate the cost of a laptop based on its attributes.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Model](#model)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview

This project uses machine learning algorithms to predict the price of laptops. The model is trained on a dataset containing various features of laptops, including but not limited to, processor type, RAM, storage, screen size, and brand. 

## Features

- Predicts laptop prices based on input features
- Provides visualizations of feature importance and model performance
- Allows users to input their own laptop specifications to estimate the price

## Installation

To set up this project locally, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/Laptop-Price-Predictor.git
    ```

2. Navigate to the project directory:

    ```bash
    cd Laptop-Price-Predictor
    ```

3. Install the required dependencies. It’s recommended to use a virtual environment:

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    pip install -r requirements.txt
    ```
4. Run the app:
   ```streamlit run app.py```
## Data

The dataset used for training the model can be found in the `data` directory. The dataset includes features such as:

- Brand
- Processor
- RAM
- Storage
- Screen Size
- GPU

Ensure that you preprocess the data as specified in `data_preprocessing.py`.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements, bug fixes, or additional features.

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Create a new Pull Request


Feel free to reach out if you have any questions or need further assistance!
