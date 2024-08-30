# Fake News Detection

## Overview
This is a project that i have done during the holidays. This project implements a fake news detection model using a Naive Bayes classifier. The model is trained to classify news articles as either "Real" or "Fake" based on their content.

## Data
The dataset used for this project is sourced from [Kaggle](https://www.kaggle.com/datasets/bhavikjikadara/fake-news-detection). It includes two CSV files:
- One file contains real news articles.
- The other file contains fake news articles.

I combined these files a single dataset, where a new column was added to label the news articles: `1` for real news and `0` for fake news.


## Dataset Fields
- `title`: The title of the news article
- `text`: The main content of the news article
- `subject`: The category of the news article
- `date`: The date when the news article was published
- `is_true`: Label indicating if the news article is true (1) or fake (0)

 ## Model Performance
The model developed in this project achieves an average accuracy of 96%. This high level of accuracy indicates strong performance in distinguishing between real and fake news.
  
## Requirements
- Jupyter Notebook
- Python 3.x
- pandas
- scikit-learn
  
## Usage

To run this project, follow these steps:
To set up your environment and run this project, follow these steps:

1. **Install Python:**

   - **Download Python:**

     - Visit the [official Python website](https://www.python.org/downloads/).
     - Download the installer for your operating system (Windows, macOS, or Linux).

   - **Run the Installer:**
     - Execute the downloaded installer and follow the instructions.
     - On Windows, make sure to check the box that says "Add Python to PATH" during the installation process.

2. **Clone the repository:**
   ```
   git clone https://github.com/hendrikyong/fake-news-detection.git
   ```
3. **Navigate to project directory**
   ```
   cd fake-news-detection
   ```
4. Install Jupyter Notebook:
   ```
   pip install jupyter
   ```
5. Install the necessary dependencies:
   ```
   pip install pandas scikit-learn
   ```

