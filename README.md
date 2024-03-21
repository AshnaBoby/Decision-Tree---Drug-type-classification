# Decision-Tree---Drug-type-classification
This project uses a Decision Tree Classifier to predict drug types based on patient attributes. It preprocesses data, splits it into training and testing sets, fits the model, predicts outcomes, and evaluates accuracy via confusion matrix and heatmap visualization.
This project utilizes a Decision Tree classifier to classify drug types based on patient information such as sex, blood pressure (BP), and cholesterol level. After preprocessing the dataset using pandas and numpy libraries, including encoding categorical variables with LabelEncoder, the data is split into training and testing sets using train_test_split from sklearn. The DecisionTreeClassifier from sklearn.tree is then trained on the training data. Model evaluation is performed using accuracy_score and confusion_matrix metrics, with seaborn and matplotlib libraries used for visualization. The resulting heatmap of the confusion matrix provides insights into the classifier's performance across different drug types. Overall, while the Decision Tree model demonstrates a certain level of accuracy in drug type classification, further optimization and exploration of alternative algorithms may be warranted for improved performance.





