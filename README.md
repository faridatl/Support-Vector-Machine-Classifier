## Support Vector Machine (SVM):

The Glass Dataset from the UCI Machine Learning Repository was motivated by criminological investigation. Glass found at the scene of a crime can serve as evidence if correctly identified. This study focuses on the classification of seven types of glass. The dataset comprises 10 features/attributes used to determine the glass class. Glass classes are described as follows: Building Windows Float Processed (Class 1), Building Windows Non-Float Processed (Class 2), Vehicle Windows Float Processed (Class 3), Vehicle Windows Non-Float Processed (none in this database), Containers (Class 5), Tableware (Class 6), and Headlamps (Class 7). A 5-Fold cross-validation is employed to evaluate the classification performance of an SVM classifier. Metrics such as the confusion matrix, sensitivity, specificity, overall model accuracy, F1-score, and ROC & AUC curve are calculated to determine how well the model performed.

**Important Note:** There is no Class 4 since 'Vehicle Windows Non-Float Processed' has no instances in this dataset. 

## 🛠️ Technologies Used:

Python: Leveraging the power of Pandas, NumPy, and Scikit-Learn.

Jupyter Notebooks: Transparent and interactive documentation of the entire workflow.

## 📈 Results:

* The SVM classifier applied to the UCI glass dataset demonstrated impressive sensitivity, achieving 100% for class 1, 94% for class 2, 50% for class 3, 100% for class 5, 100% for class 6, and 80% for class 7, while exhibiting high specificity, with scores ranging from 94.8% to 100% across various classes. The 5-fold cross-validation demonstrated consistent model performance across folds, with accuracy scores ranging from 83.7% to 93%. Notably, the SVM classifier exhibited strong predictive ability, achieving high F1 scores for several classes, impeccable precision for certain classes, and an overall commendable accuracy of 93% on the glass dataset.

* High sensitivity values, such as those observed for Classes 1, 2, 5, 6, and 7 (ranging from 94% to 100%), indicate that the SVM classifier excels in correctly identifying positive instances for these classes.

* The specificity scores, mostly exceeding 90% and reaching 100% for several classes, highlight the SVM classifier's proficiency in accurately identifying negative instances. This indicates a low rate of false positives, emphasizing the model's ability to correctly classify instances that do not belong to a specific class.

* The lower precision for Class 5 (60%) implies a relatively higher rate of false positives for this class. The high precision scores observed for the remaining classes indicate that when the model predicts a positive class, it is highly likely to be correct.

* The ROC and AUC analysis for the SVM classifier revealed compelling insights into its discriminatory power across different classes. Class 1 exhibited a perfect AUC of 1.0, signifying flawless performance in distinguishing positive instances from negative ones. Class 2 demonstrated a strong AUC of 0.93, indicating a high degree of accuracy in its predictive ability. Class 3 displayed an impressive AUC of 0.99, showcasing near-perfect discriminatory capabilities. Similarly, both Class 6 and Class 7 achieved a perfect AUC of 1.0, emphasizing their exceptional performance in classification. Class 5 yielded a notable AUC of 0.93, suggesting a robust ability to discriminate between its positive and negative instances. These AUC values collectively underscore the SVM classifier's effectiveness in producing accurate and reliable predictions for various classes within the glass dataset.

* The SVM classifier displayed excellent overall performance on the UCI machine learning glass dataset, achieving a commendable accuracy of 93%. These results indicate the classifier's effectiveness in accurately classifying glass types, suggesting its reliability for classification tasks.

## 🔗 How to Use:

Each project/code along with their dataset has been uploaded for your review or observation. Please feel free to reach out if you have questions, suggestions, or if you're interested in collaboration!

## 🌐 Connect with Me:

LinkedIn: (https://www.linkedin.com/in/faridatlawal/)

##### I'm continuously learning and expanding my skill set. Join me on this exciting journey through the world of machine learning! 🤖✨
