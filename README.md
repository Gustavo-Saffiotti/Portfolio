<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Projects by Gustavo Maldonado Saffiotti</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
        }
        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
        }
        main {
            padding: 20px;
        }
        h1, h2 {
            color: #333;
        }
        a {
            color: #007bff;
            text-decoration: none;
        }
        .project {
            background-color: #fff;
            margin: 10px 0;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .project img {
            max-width: 100%;
            height: auto;
        }
        .cta-button {
            display: inline-block;
            padding: 10px 20px;
            background-color: #007bff;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 10px;
        }
        .cta-button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>

<header>
    <h1>Gustavo Maldonado Saffiotti - Data Science & Machine Learning Projects</h1>
</header>

<main>

    <section class="project">
        <h2>Project 1: Higher Education in Brazil in 2020</h2>
        <p>This project, developed as part of the Data Analytics course, analyzes the landscape of public higher education in Brazil in 2020, utilizing data from the National Institute of Educational Studies and Research Anísio Teixeira (Inep). Key components of the project include data preparation, analysis, and interactive visualizations using Power BI.</p>
        
        <h3>Dashboard Overview</h3>
        <p>Explore the interactive Power BI dashboard for insights into public higher education in Brazil:</p>
        <a href="https://app.powerbi.com/view?r=eyJrIjoiOTcxMjBmN2YtZWFhNS00YzA4LWE2NzEtNzRmZGQ3OWY5ZmE5IiwidCI6IjJkM2IxMDY0LTc1MDEtNDQ0NC04MzRlLTI2YmI2NjNkMzhmZSJ9&pageName=ReportSectione93835085c205b6e0c94" class="cta-button">View the Dashboard</a>
        
        <h3>Visualizations</h3>
        <ul>
            <li><strong>Menu:</strong> Intuitive navigation to access the main areas of focus: Region, Higher Education Institutions (IES), or Freshmen.</li>
            <li><strong>Region:</strong> Freshmen distribution by region, state, and municipality.</li>
            <li><strong>IES (Higher Education Institutions):</strong> Map and charts of institutions and courses.</li>
            <li><strong>Freshmen:</strong> Insights into entrants, including gender, course type, and age group.</li>
        </ul>

        <h3>Tools Used</h3>
        <ul>
            <li><strong>Microsoft Excel</strong> - Data cleaning and preparation</li>
            <li><strong>Power BI</strong> - Interactive visualizations</li>
            <li><strong>DAX (Data Analysis Expressions)</strong> - Used for dynamic calculations and measures in Power BI</li>
        </ul>

        <h3>Project Documentation</h3>
        <p>For a detailed view of all project stages, including data collection, preparation, modeling, and visualization, see the full project report here:</p>
        <a href="Data_Analytics_Higher_Education_Data_2020___English.pdf" class="cta-button">Higher Education in Brazil - Project Documentation (PDF)</a>
        
        <h3>References</h3>
        <ul>
            <li><a href="https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/microdados/censo-da-educacao-superior">Data Source: Inep</a></li>
            <li><a href="https://github.com/Gustavo-Saffiotti/Data_Analytics/tree/main/Dataset_Education">Prepared Data Files (GitHub)</a></li>
        </ul>
    </section>

    <section class="project">
        <h2>Project 2: Vehicle Price Prediction using Machine Learning</h2>
        <img src="Images/Machine_Learning_Image.jfif" alt="Machine Learning" />
        <p>This project uses machine learning to predict the average price of vehicles based on features like engine size, fuel type, and brand. The model was built using the Random Forest Regressor and optimized with RandomizedSearchCV.</p>
        
        <h3>Project Notebook</h3>
        <p>For a detailed walkthrough of the project, including data preprocessing, model training, and evaluation, please refer to the full Jupyter Notebook:</p>
        <a href="Vehicle_price_prediction.ipynb" class="cta-button">View Project Notebook</a>
        
        <h3>Evaluation Metrics</h3>
        <ul>
            <li><strong>MAE</strong> (Mean Absolute Error): 4659.15</li>
            <li><strong>MSE</strong> (Mean Squared Error): 151821780.30</li>
            <li><strong>RMSE</strong> (Root Mean Squared Error): 12321.60</li>
            <li><strong>R²</strong> (Coefficient of Determination): 1.00</li>
        </ul>

        <h3>Future Improvements</h3>
        <ul>
            <li>Enhancing the model with additional features such as mileage and vehicle condition.</li>
            <li>Experimenting with other algorithms like Gradient Boosting, XGBoost, or neural networks.</li>
            <li>Further hyperparameter tuning for optimization.</li>
        </ul>

        <h3>Author</h3>
        <ul>
            <li><a href="https://www.linkedin.com/in/gustavo-maldonado-saffiotti">LinkedIn</a></li>
            <li><a href="https://github.com/Gustavo-Saffiotti">GitHub Profile</a></li>
        </ul>
    </section>

</main>

</body>
</html>
