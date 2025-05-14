Medical Insurance Cost Estimation


Check out the live website [link](https://ribhu01.github.io/Medical_expense_predictor/)


📋 Project Overview

This project aims to predict medical insurance charges based on various features like age, sex, BMI, number of children, smoking habits, and region. It utilizes a machine learning model trained on the Medical_insurance.csv dataset to estimate the insurance costs, providing users with a quick and accurate way to understand potential charges.

🎯 Key Features

Predicts medical insurance charges based on user input.

Interactive frontend built with HTML and Tailwind CSS.

Backend API using FastAPI for seamless integration.

Trained machine learning model using linear regression.

Deployed as a web application for real-time predictions.

🗂️ Project Structure

Medical-Insurance-Cost-Estimator/
│
├── app.py               # Backend API using FastAPI
├── index.html           # Frontend interface
├── model.ipynb          # Model training notebook
├── model.pkl            # Trained machine learning model
├── Medical_insurance.csv # Dataset for training the model
└── README.md            # Project documentation
🚀 Setup and Installation

To run this project locally, follow these steps:

Clone the Repository:

git clone <repository_url>
cd Medical-Insurance-Cost-Estimator

Install Required Packages:

pip install -r requirements.txt

Run the Backend API:

python app.py

Open the Frontend:
Open index.html in your browser to access the prediction interface.

📝 Usage

Enter the required details like age, sex, BMI, number of children, smoker status, and region.

Click the Predict button to get the estimated insurance charges.

📊 Model Training

The machine learning model was trained using a linear regression approach. It considers multiple features such as:

Age (18-100)

Sex (Male/Female)

BMI (10-50)

Children (0-10)

Smoker (Yes/No)

Region (Northwest, Northeast, Southeast, Southwest)

🛠️ API Endpoints

POST /predict - Takes the input parameters and returns the predicted insurance charges.

💻 Technologies Used

Python (FastAPI, Pandas, Scikit-learn)

HTML, Tailwind CSS (Frontend)

JavaScript (Frontend Logic)

🤝 Contribution

Feel free to fork this repository and contribute by submitting pull requests. Suggestions are welcome!

📄 License

This project is licensed under the MIT License.

🙏 Acknowledgments

Special thanks to the contributors and the data science community for their continuous support and guidance.
