#Inspiration: 

The inspiration behind creating a predictive model for hotel booking cancellations was to help hotel managers better plan their resources and staffing. By predicting which bookings are likely to be cancelled, hotel managers can optimize their resources and offer incentives to guests who are likely to cancel in order to retain their business.

**What it does:** The predictive model uses machine learning algorithms to predict the likelihood of a booking being cancelled based on various features such as lead time, arrival date, and the number of adults/children. The model outputs a probability score which can be used by hotel managers to make informed decisions about resource allocation.

**How we built it:** We built the predictive model using Python and the scikit-learn machine learning library. We started by cleaning and pre-processing the dataset, which involved handling missing values and encoding categorical features. We then split the dataset into training and testing sets and trained several machine learning models on the training data. We evaluated the performance of each model using metrics such as accuracy, precision, and recall, and selected the best-performing model to make predictions on the test data.

**Challenges we ran into:** One main challenge was dealing with a class imbalance in the dataset. The majority of bookings in the dataset were not cancelled, which made it difficult for the machine learning models to accurately predict the minority class (i.e. cancelled bookings). To address this, we used techniques such as undersampling and adjusting the classification threshold to improve the performance of the models.

**Accomplishments that we're proud of:** We are proud of the high accuracy and recall achieved by the predictive model, which indicates that it is able to identify a large proportion of cancelled bookings accurately. We are also proud of the clean and well-structured codebase we created, which makes it easy for others to understand and build upon our work.

**What we learned:** Through building this predictive model, we learned about the importance of data preprocessing and feature selection in machine learning, as well as techniques for dealing with a class imbalance in the data. We also gained a better understanding of how to evaluate the performance of machine learning models and select the best one for a given task.

**What's next for the Predictive Model for Booking Cancellations:** In the future, we plan to explore the use of more advanced machine learning techniques such as ensemble methods and deep learning to further improve the performance of the predictive model. We also plan to incorporate additional features such as weather data and local events to make the model even more accurate and useful for hotel managers.

**Project Submission Link:** https://devpost.com/software/predictive-model-for-booking-cancellations
