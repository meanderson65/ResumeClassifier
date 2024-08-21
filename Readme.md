# Resume Categorization

This project focuses on developing a machine learning model to automatically categorize resumes into predefined job-related categories, such as Data Science, Software Development & QA, Sales & Marketing, based on the textual content within each resume. The primary objective is to streamline the recruitment process by automating resume screening, thereby reducing the time and effort required for initial candidate evaluation.

## Overview

The model analyzes text data, including job descriptions, skills, education, and experience, to assign each resume to the most relevant category. The process involves several steps, including data wrangling, text preprocessing, vectorization, dimensionality reduction, and classification. The final model aims to be robust and accurate, making it a valuable tool for recruiters and HR professionals.

## <b>Author:</b>  
<b>Team</b> Intro to Machine Learning Team 
<b>Date:</b> 21 Aug 2024  
<b>Location:</b> UCSC Extention   
<b>Program:</b> Artificial Intelligence Application Development  
<b>Course:</b> Intro to Machine Learning  
<b>Assignment:</b> Class Project

## Techniques Used

### Dimensionality Reduction
- **LSA (TruncatedSVD)**: Reduces the dimensionality of text data while capturing the underlying semantic structure.
- **CNN (Convolutional Neural Networks)**: A deep learning approach that directly learns features from text data.
- **PCA (Principal Component Analysis)**: Transforms features into principal components to reduce dimensionality.

### Classification
- **Logistic Regression**: Used for binary and multi-class classification to estimate the probability of a class based on feature inputs.
- **Naive Bayes**: A probabilistic classifier based on Bayes' theorem, which assumes independence between features.

## Project Workflow

The project is organized into the following steps:

0. **Data Wrangling**: Handling 363 resumes and placing their data into a `.csv` file.
1. **Import Libraries**: Includes libraries for shallow learning (scikit-learn) and deep learning (TensorFlow).
2. **Load Data**: Loading the `.csv` file into the project.
3. **Exploratory Data Analysis (EDA)**: Understanding the distribution and structure of the data.
4. **Test and Train Split**: Dividing the dataset into training and testing sets.
5. **Pre-Processing**: Cleaning and preparing the data for modeling.
6. **Vectorization**: Converting text data into numerical format using `TfidfVectorizer`.
7. **Dimensionality Reduction**:
   - **LSA (TruncatedSVD)**
   - **CNN**
   - **PCA**
8. **Classification**:
   - **CNN (Logistic Regression)**
   - **PCA (Naive Bayes)**
9. **Model Optimization**: Fine-tuning model hyperparameters for better performance.
10. **Model Evaluation**: Assessing the performance of different models.
11. **Model Deployment**: Preparing the final model for use in real-world applications.

## Results

The results include a comparison of the performance of various models and techniques used in this project. The best-performing model is selected based on accuracy and other evaluation metrics.

## Conclusion

This project demonstrates the effectiveness of combining text preprocessing, vectorization, dimensionality reduction, and classification techniques to build an accurate and efficient resume categorization model. The final model can significantly aid in automating the resume screening process, making recruitment faster and more efficient.

---

## Usage
To use the code for a specific assignment, go to the corresponding directory in the repository and follow the instructions in the assignment's README file or code comments.

## Contributing
Contributions to this project are welcome. If you would like to contribute, please fork the repository, make changes in a separate branch, and submit a pull request detailing your changes.

## License
This project is copyrighted by the authors and cannot be used without the authors' prior permission.

## Contact
For further information, questions, or comments about this repository, please contact:

xxxxx GitHub: https://github.com/xxxxx

Feel free to reach out with any questions or contributions you might want to make to the project.

Happy learning and best of luck with your assignments!

