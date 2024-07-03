# Tennis Shot Classification

## Description
This project focuses on the classification of lawn tennis shots using machine learning techniques. We employ a hybrid model combining Long Short-Term Memory (LSTM) and Convolutional Neural Networks (CNN) to achieve accurate shot classification. The model is trained on a dataset of tennis videos and is capable of distinguishing between different types of shots.

## Table of Contents

- Description
- Installation
- Usage
- Project Structure
- Models and Techniques
- Results
- Contributing
- Acknowledgments

## Installation

To get started with this project, follow these steps:
1. **Clone the Repository:**
   ```
   git clone https://github.com/celestialberry/Tennis-Shot-Classification.git
   
   cd tennis-shot-classification
   ```
2. **Create a virtual environment and activate it:**
   ```
   pip install virtalenvpython -m venv venv
   
   source venv\Scripts\activate  # On MacOS, use `venv/bin/activate`
   ```
3. **Install the required packages:**
   ```
   pip install -r requirements.txt
   ```
   
## Usage
To train the model, run the following command:
```
python train.py --data_dir path_to_data --output_dir path_to_save_model
```

To evaluate the model, run:
```
python evaluate.py --model_dir path_to_model --data_dir path_to_data
```

For detailed usage instructions, refer to the usage guide.

## Project Structure
`data/` - Directory containing the dataset. <br>
`notebooks/` - Jupyter notebooks for exploratory data analysis and model experimentation. <br>
`src/` - Source code for the project. <br>
`models/` - Directory for storing trained models. <br>
`docs/` - Documentation and guides. <br>
`train.py` - Script to train the model. <br>
`evaluate.py` - Script to evaluate the model. <br>

## Models and Techniques
This project uses a hybrid model combining LSTM and CNN. The LSTM network captures the temporal dependencies in the shot sequences, while the CNN extracts spatial features from the video frames. This combination leverages the strengths of both models to improve classification accuracy.

## Results
The model achieves a high accuracy in classifying different types of lawn tennis shots. Below is a summary of the results:

| __Metric__ | __Values__ | 
|------------|------------|
| Accuracy   | 95.4% |
| Precision  | 94.7% |
| Recall	   | 95.1% |
| F1 Score	 | 94.9% |

For more detailed results and analysis, refer to the results report.

## Contributing
We welcome contributions to improve the project. To contribute, follow these steps:

1. Fork the repository. <br>
2. Create a new branch: `git checkout -b feature-branch`. <br>
3. Make your changes and commit them: `git commit -m 'Add new feature'`. <br>
4. Push to the branch: `git push origin feature-branch`. <br>
5. Open a pull request.

## Acknowledgments
We would like to thank all the contributors and the community for their valuable inputs and support.

