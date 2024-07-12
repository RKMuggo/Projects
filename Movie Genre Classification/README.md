# Movie Classification Project

## Project Overview
In this project, I built a k-nearest neighbors (k-NN) classifier to predict whether a movie is a comedy or a thriller based on the frequency of certain words in its screenplay. The main steps of the project included selecting features, defining the classifier, and evaluating its performance on a test set.

## Objectives
By the end of this project, I had learned to:
1. Build a k-nearest neighbors classifier.
2. Test a classifier on data.
3. Select and engineer features for classification.
4. Evaluate the performance of a classifier.

## Data Sources
The dataset I used in this project contained word frequencies from movie screenplays, along with the genres of the movies (comedy or thriller). The data was preprocessed to include only the words that appeared in the screenplays and their respective frequencies.

## Project Structure
The project was divided into several key parts:

### Part 1: The Dataset
- **Objective:** Explore the dataset and understand its structure.
- **Steps:** I loaded the dataset, investigated word frequencies, and performed exploratory data analysis.

### Part 2: K-Nearest Neighbors - A Guided Example
- **Objective:** Build an understanding of the k-NN algorithm through visualization and example.
- **Steps:** I calculated Euclidean distances, found nearest neighbors, and classified a movie based on its nearest neighbors.

### Part 3: Feature Selection and Classification
- **Objective:** Select discriminative features to improve classification accuracy.
- **Steps:** I analyzed word frequencies, selected features, classified movies using selected features, and evaluated the classifier's performance.

## Conclusion
### Summary
At this point, I had gone through one cycle of classifier design. Let's summarize the steps:

1. From available data, I selected test and training sets.
2. I chose the k-nearest neighbors (k-NN) algorithm for classification.
3. I identified some features that I believed would help distinguish between comedy and thriller movies.
4. I defined a classifier function using my features and the training set.
5. I evaluated its performance (the proportion of correct classifications) on the test set.

### Key Findings
- **Feature Selection:** The choice of features played a crucial role in the performance of the classifier. Words that were chosen for their discriminative power significantly impacted the accuracy of the predictions.
- **Misclassifications:** Many of the misclassified movies had ambiguous genre listings or contained elements of multiple genres. This highlighted the challenge of classifying movies with mixed or unclear genre characteristics.
- **Classifier Performance:** The overall performance of the classifier was evaluated by the proportion of correct classifications. While the classifier performed well on clear-cut cases, it struggled with movies that blended genres or had less distinctive word usage patterns.

### Next Steps
To further improve the classifier, I could:
- **Refine Feature Selection:** Experiment with different sets of features or increase the number of features to capture more nuanced differences between genres.
- **Advanced Algorithms:** Explore more advanced classification algorithms that might handle mixed-genre movies better.
- **Additional Data:** Incorporate more data or metadata (such as movie summaries or reviews) to provide additional context for classification.

Overall, this project provided valuable insights into the process of designing and evaluating a classifier. By understanding the strengths and limitations of the k-NN algorithm and the importance of feature selection, I am better equipped to tackle similar classification tasks in the future.

## My Experience
Working on this project allowed me to deepen my understanding of machine learning and natural language processing (NLP). I gained practical experience in:
- **Data Analysis and Preprocessing:** Handling and analyzing large datasets, including word frequency analysis and feature engineering.
- **Machine Learning Algorithms:** Implementing and understanding the k-nearest neighbors algorithm for classification tasks.
- **Evaluation Techniques:** Evaluating the performance of a classifier and understanding the importance of test and training splits.
- **Python Programming:** Utilizing libraries such as `datascience`, `numpy`, and `matplotlib` to manipulate data and create visualizations.

I found that feature selection is a critical step in building effective classifiers. The project also highlighted the challenges of working with ambiguous and mixed-genre data, which is common in real-world applications. This experience has equipped me with the skills to approach complex classification problems and the confidence to explore more advanced machine learning techniques in the future.