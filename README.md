    <h1>Logistic Regression for Titanic Dataset</h1>

    <h2>Overview</h2>
    <p>This repository contains a project that applies logistic regression to the Titanic dataset to predict survival. The project involves data analysis, visualization, model training, and evaluation. The goal is to build a logistic regression model to classify passengers' survival based on various features.</p>

    <h1>Project Structure</h1>
    <ul>
        <li><strong>data/:</strong> Contains the Titanic dataset file.</li>
        <li><strong>notebooks/:</strong> Jupyter notebooks with data analysis, visualization, and model training.</li>
        <li><strong>scripts/:</strong> Python scripts for data preprocessing, model training, and evaluation.</li>
        <li><strong>results/:</strong> Generated plots and model evaluation metrics.</li>
    </ul>

    <h1>Data Analysis</h1>
    <p>The Titanic dataset is analyzed to understand the distribution of missing values and to visualize the data. Key steps include:</p>
    <ul>
        <li><strong>Loading and Cleaning Data:</strong> Handling missing values and converting categorical variables.</li>
        <li><strong>Visualization:</strong> Creating plots to understand data distributions and relationships.</li>
    </ul>

    <h3>Example Visualization</h3>
    <p>A heatmap was created to visualize missing values in the dataset:</p>
    <img src="results/missing_values_heatmap.png" alt="Missing Values Heatmap" style="max-width:100%; height:auto;">
    
    <p>A histogram plot was created to show age distribution.</p>
    <p>A count plot was created to count the number of male and female survivors and non-survivors.</p>
    <p>A bar plot was created to show the survival rate based on passenger class.</p>

    <h1>Model Training</h1>
    <p>A logistic regression model is trained using the cleaned and preprocessed data. Key steps include:</p>
    <ul>
        <li><strong>Splitting Data:</strong> Dividing the dataset into training and test sets.</li>
        <li><strong>Training the Model:</strong> Fitting the logistic regression model to the training data.</li>
        <li><strong>Making Predictions:</strong> Predicting survival on the test set.</li>
    </ul>