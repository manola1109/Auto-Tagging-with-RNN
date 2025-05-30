# Auto-Tagging with RNN

## Business Problem
Untagged questions or questions with irrelevant tags lead to a large number of unanswered questions. The experts find it difficult to discover the right questions, and the users who post questions don't get timely responses. This situation leads to a drop in the level of user engagement on the platform.

## Project Overview
This project implements an automatic tagging system using Recurrent Neural Networks (RNN) to automatically suggest relevant tags for questions. The system analyzes the content of questions and predicts appropriate tags, helping to improve question discovery and expert engagement.

## Dataset
The project uses a dataset that includes:
- Question IDs
- Owner User IDs
- Creation Dates
- Scores
- Tags associated with questions

## Features
- Text preprocessing and tokenization
- RNN-based deep learning model for multi-label classification
- Support for multiple tags per question
- Vocabulary building and text vectorization
- Tag prediction capabilities

## Technical Stack
- Python
- Jupyter Notebook
- Deep Learning libraries
- Natural Language Processing (NLP) tools

## Model Components
The auto-tagging system includes:
1. Text preprocessing pipeline
2. Vocabulary generation
3. RNN model architecture
4. Multi-label classification layer
5. Tag prediction mechanism

## Key Features in the Dataset
The system processes various features including:
- Time-based features (CreationDate)
- User-based features (OwnerUserId)
- Content-based features (question text)
- Engagement metrics (Score)

## Installation and Usage
1. Clone the repository:
```bash
git clone https://github.com/manola1109/Auto-Tagging-with-RNN.git
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

3. Open and run the Jupyter notebook:
```bash
jupyter notebook Auto_Tagging_RNN.ipynb
```

## Project Structure
- `Auto_Tagging_RNN.ipynb`: Main Jupyter notebook containing the implementation
- Data processing and model training code
- Tag prediction and evaluation metrics

## Common Tags Found in Dataset
Based on the vocabulary analysis, some common tags include:
- regression
- classification
- machine-learning
- statistical-analysis
- python
- bayesian
- probability
- data-analysis

## Contributing
Feel free to contribute to this project by:
1. Forking the repository
2. Creating your feature branch
3. Committing your changes
4. Pushing to the branch
5. Creating a new Pull Request

## License
This project is available under the MIT License.

## Author
Created by @manola1109

## Acknowledgments
- Dataset used for training and evaluation
- Contributors and maintainers
- Open source community
