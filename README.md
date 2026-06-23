Phishing Website Detection Using Machine Learning

Overview

Phishing attacks are one of the most common cybersecurity threats, where attackers create fake websites to steal sensitive user information such as usernames, passwords, and banking details. This project presents a machine learning-based system for detecting phishing websites and classifying them as either **Phishing** or **Legitimate**.

The system analyzes website URL features and applies machine learning algorithms to identify malicious websites with high accuracy.


Features

* Detection of phishing and legitimate websites
* URL feature extraction and preprocessing
* Machine Learning-based classification
* Django web application interface
* Performance comparison of multiple algorithms
* Real-time website prediction
* graph of phishing and legitimate websites 


## Technologies Used

* Python
* Django
* Scikit-Learn
* Pandas
* NumPy
* HTML
* CSS
* SQLite



## Machine Learning Algorithms

The following algorithms were implemented and evaluated:

1. Decision Tree Classifier
2. Random Forest Classifier
3. Support Vector Machine (SVM)
4. SGD Classifier

The best-performing model was selected based on accuracy and evaluation metrics.



## Dataset

The project uses a dataset containing phishing and legitimate website URLs.

Files:

* Website_urls.csv
* labeled_data.csv

Dataset preprocessing includes:

* Data cleaning
* Feature extraction
* Feature selection
* Label encoding



## System Architecture

User Input URL
↓
Feature Extraction
↓
Machine Learning Model
↓
Classification
↓
Phishing / Legitimate Result



## Performance

| Algorithm      | Accuracy |
| -------------- | -------- |
| Decision Tree  | ~94%     |
| Random Forest  | ~95%     |
| SGD Classifier | ~96%     |
| SVM            | ~94%     |

The SGD Classifier achieved the highest accuracy during experimentation.



## Installation

Clone the repository:

```bash
git clone https://github.com/SunnY2513/Phishing-Website-Detection-ML.git
```

Navigate to the project folder:

```bash
cd detection_of_phishing_websites
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the Django server:

```bash
python manage.py runserver
```

Open:

```text
http://127.0.0.1:8000/
```



## Contributors

* A. Bhanu Prakash
* U. Venkata Swamy
* S. Pardhu Pranay



## Future Enhancements

* Deep Learning-based phishing detection
* Real-time browser extension
* Cloud deployment
* Improved feature engineering
* Real-time threat intelligence integration


SCREEN SHOTS

1.1.Home Page

<img width="700" height="400" alt="image" src="https://github.com/user-attachments/assets/e4cb182f-6b56-43fa-8369-2d666d370b56" />

1.2.Registration Page

<img width="700" height="400" alt="image" src="https://github.com/user-attachments/assets/2c080db1-4ea6-4710-bdcc-a670f917968b" />

1.3 Login Page

<img width="700" height="400" alt="image" src="https://github.com/user-attachments/assets/49ba8e89-e1a9-4fd3-b168-ca6c9fba299d" />

1.4.Graph

<img width="700" height="400" alt="image" src="https://github.com/user-attachments/assets/b3189af0-7afa-4546-8897-6d50a28f80e8" />







## License

This project was developed for academic and educational purposes.
