# 📌 Project: Loan Default Prediction using Artificial Neural Network (ANN)

## 📂 Dataset
The dataset used in this project is available on Kaggle:  
👉 [Lending Club Loan Dataset](https://www.kaggle.com/datasets/musabhawai/lending-club-loan-dataset?select=lending_club_loan_two.csv)


## 📖 Description

Developed a deep learning model to predict loan default (charged-off vs
fully-paid) using *LendingClub dataset* containing **396,030 records
and 27 features**. The project aimed to assist financial institutions in
assessing borrower risk, thereby improving loan approval accuracy and
reducing default rates.

------------------------------------------------------------------------

## 🛠️ Key Responsibilities & Steps

-   Conducted *Exploratory Data Analysis (EDA)* using Pandas, NumPy,
    Matplotlib, Seaborn to identify important features, handle
    duplicate/missing values, and analyze class distribution.\
-   Performed *data preprocessing*: removed redundant features,
    converted categorical variables to dummy variables, normalized
    numerical data, and encoded target labels (*1 = Fully Paid, 0 =
    Charged Off*).\
-   Built an *Artificial Neural Network (ANN)* using TensorFlow &
    Keras Sequential API with multiple Dense layers, ReLU activation,
    Dropout regularization, and a Sigmoid output layer for binary
    classification.\
-   Compiled model with *Adam optimizer* and **Binary Crossentropy
    loss**, trained with large batch size and multiple epochs using
    validation data to prevent overfitting.\
-   Implemented *model evaluation* using classification report,
    confusion matrix, accuracy score, and performance visualization
    (training vs validation loss).\
-   Deployed *prediction pipeline* for unseen loan applications and
    saved model for future use.

------------------------------------------------------------------------

## ⚙️ Technologies Used

-   *Languages/Libraries*: Python, Pandas, NumPy, Matplotlib, Seaborn,
    Scikit-learn, TensorFlow, Keras\
-   *Techniques*: Data Preprocessing, Feature Engineering, Dummy
    Encoding, Normalization, ANN, Dropout, Model Evaluation\
-   *Tools*: Jupyter Notebook

------------------------------------------------------------------------

## ✅ Impact

-   Automated the *loan risk assessment process*, enabling faster and
    more consistent borrower evaluation.\
-   Enhanced the ability of financial institutions to **identify
    high-risk loan applicants** before approval.\
-   Improved *decision-making efficiency* by replacing manual credit
    risk checks with a scalable AI-driven solution.\
-   Built a *reusable prediction pipeline* that can be integrated into
    real-world lending platforms for operational use.
