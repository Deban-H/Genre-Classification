# Movie Genre Classifier (Java)

A **machine learning** project that predicts the genre of a movie based on its description and features. This project is built in **Java**, designed to take training and test data, and classify movies into genres with a simple, intuitive approach.

---

## Project Overview

This **Movie Genre Classifier** utilizes a basic machine learning model written in **Java**. It processes datasets containing movie information and predicts the most suitable genre. The program reads movie data from provided text files and outputs predictions for test data.

The project demonstrates the implementation of machine learning concepts such as **data preprocessing**, **feature extraction**, and **classification** using custom logic—without external libraries.

---

## Dataset

The project uses three data files:

- `train_data.txt` - Contains movie details along with their genres (used for training).
- `test_data.txt` - Contains new movie details for which the genre needs to be predicted.
- `test_data_solution.txt` - Contains the correct genres for test data (for evaluation).

Each file follows a structured format, making it easy to parse and process.

---

## ⚙️ How It Works

1. **Training Phase**  
   Reads and analyzes the `train_data.txt` file to learn the patterns in descriptions related to genres.

2. **Prediction Phase**  
   Processes `test_data.txt` and predicts genres for each movie based on the training data.

3. **Evaluation Phase**  
   Compares predicted genres with the actual genres in `test_data_solution.txt` to measure accuracy.

---

##  Technologies Used

- **Java** (Core)
- Basic **file handling**, **data structures**, and **algorithms**
- No external machine learning libraries—fully custom logic!

---

## Features

- Simple machine learning algorithm
- File-based input/output for flexibility
- Easy to read and modify for further development
- Evaluates accuracy by comparing predictions with the actual genres

---

## Future Enhancements (Blueprint)

- Implement advanced machine learning algorithms (Naive Bayes, Decision Trees)
- Add support for multiple genres per movie
- Integrate with external datasets (IMDB, TMDB API)
- Build a graphical interface to visualize predictions
- Improve accuracy with NLP techniques

---

## Working Principle

1. Clone the repository  
   `git clone https://github.com/yourusername/movie-genre-classifier.git`

2. Compile the Java program  
   `javac MovieGenreClassifier.java`

3. Run the program  
   `java MovieGenreClassifier`

4. Ensure dataset files (`train_data.txt`, `test_data.txt`, `test_data_solution.txt`) are in the project directory.

---

## 📝 License

This project is licensed under the [MIT License](LICENSE).

---

## Author

Created by **Debanjana Barua**

---

