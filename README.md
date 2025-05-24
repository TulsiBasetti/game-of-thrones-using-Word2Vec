# Game of Thrones Word2Vec Exploration

This project utilizes Word2Vec to analyze and visualize semantic relationships between characters and terms in the "Game of Thrones" series. By training a Word2Vec model on the text data from the books, we can uncover intriguing associations and patterns within the narrative.

## 📚 Project Overview

- **Objective**: Explore semantic similarities in "Game of Thrones" using Word2Vec.
- **Dataset**: Text data from the "Game of Thrones" book series.
- **Techniques**:
  - Data Preprocessing: Tokenization, stopword removal.
  - Model Training: Word2Vec with Gensim.
  - Visualization: t-SNE plots to visualize word embeddings.

## 🗂️ Repository Structure

- `data/`: Contains the text data used for training.
- `game-of-throne.ipynb`: Jupyter notebook implementing the Word2Vec model and visualizations.

## 🚀 How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/TulsiBasetti/game-of-thrones-using-Word2Vec.git
2. Navigate to the project directory:

   ```bash
   cd game-of-thrones-using-Word2Vec

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt

4. Launch the Jupyter notebook:

   ```bash
   jupyter notebook game-of-throne.ipynb

## 🧰 Requirements

Install the necessary Python libraries using:

```bash
pip install -r requirements.txt

## 📊 Results

The trained Word2Vec model reveals interesting relationships, such as:

- Similar characters clustering together.
- Associations between locations and the characters linked to them.
- Semantic analogies, e.g., `"King" is to "Queen" as "Man" is to "Woman"`.

## 📌 Notes

- Ensure that the `data/` directory contains the necessary text files before training the model.
- Adjust hyperparameters like vector size, window size, and minimum word count in the notebook to experiment with different model configurations.



