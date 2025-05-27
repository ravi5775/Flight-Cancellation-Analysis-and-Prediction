<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Flight Cancellation Analysis and Prediction</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      line-height: 1.6;
      margin: 0;
      padding: 30px;
      background-color: #f9f9f9;
      color: #333;
    }
    .container {
      max-width: 960px;
      margin: auto;
      background: #fff;
      padding: 40px;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    }
    h1, h2 {
      color: #2c3e50;
    }
    .logo img {
      height: 80px;
      display: block;
      margin: 0 auto 10px;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 20px;
    }
    th, td {
      border: 1px solid #ddd;
      padding: 10px;
      text-align: center;
    }
    th {
      background-color: #2c3e50;
      color: white;
    }
    a {
      color: #1a73e8;
      text-decoration: none;
    }
    code {
      background: #f4f4f4;
      padding: 2px 6px;
      border-radius: 4px;
    }
  </style>
</head>
<body>

<div class="container">
  <div class="logo">
    <img src="path_to_flyzy_logo" alt="Flyzy logo">
  </div>

  <h1>Flight Cancellation Analysis and Prediction</h1>
  <p><strong>Domain:</strong> IT and Services</p>
  <p><strong>Duration:</strong> 23 hours | <strong>Tasks:</strong> 4 | <strong>Skills:</strong> Python, EDA, ML & Algorithms</p>

  <hr>

  <h2>About Company</h2>
  <p>
    Flyzy is a one-of-a-kind travel-tech platform aiming to transform modern-day travel into a completely hassle-free experience. It connects retailers, service providers, and other stakeholders facilitating air, road, and train travel with passengers via its hi-tech AI-enabled platform.
  </p>
  <p>
    Flyzy ensures commercial benefits for stakeholders and will soon extend its services to rail and road travel, creating safer, simpler, and personalized passenger experiences.
  </p>

  <h2>Problem Statement</h2>
  <p>
    Flight cancellation disrupts travel and affects airline reputation and profitability. Predicting cancellations enables airlines to take proactive measures to reduce such disruptions.
  </p>

  <h2>Learning Objectives</h2>
  <ul>
    <li>Data cleaning and preparation techniques</li>
    <li>Performing exploratory data analysis (EDA)</li>
    <li>Implementing preprocessing for ML (encoding, scaling)</li>
    <li>Building and evaluating classification models</li>
    <li>Interpreting model performance metrics</li>
  </ul>

  <h2>Business Objectives</h2>
  <ul>
    <li>Predict cancellations to reduce impact and cost</li>
    <li>Improve operational planning and customer satisfaction</li>
    <li>Position Flyzy as a predictive, tech-enabled travel partner</li>
  </ul>

  <h2>Dataset Description</h2>
  <p>
    <a href="https://docs.google.com/spreadsheets/d/15eBYLoEDagmYb4Rh_pQRfk20VICkyf2Vin2ob-w2GeY/edit?gid=0" target="_blank">
      Download Dataset
    </a>
  </p>
  <ul>
    <li><code>Flight_ID</code>: Unique identifier (not used for modeling)</li>
    <li><code>Airline</code>: Operating airline (5 categories)</li>
    <li><code>Flight_Distance</code>: Distance in km (standardized)</li>
    <li><code>Origin_Airport</code> & <code>Destination_Airport</code>: Departure/arrival airports</li>
    <li><code>Scheduled_Departure_Time</code>: Minutes past midnight</li>
    <li><code>Day_of_Week</code>: 1 (Mon) to 7 (Sun)</li>
    <li><code>Month</code>: 1 (Jan) to 12 (Dec)</li>
    <li><code>Airplane_Type</code>: Aircraft model</li>
    <li><code>Weather_Score</code>: Severity of weather</li>
    <li><code>Previous_Flight_Delay_Minutes</code>: Delay in minutes</li>
    <li><code>Airline_Rating</code>: Airline quality score</li>
    <li><code>Passenger_Load</code>: Load percentage</li>
    <li><code>Flight_Cancelled</code>: Target variable (1 = cancelled)</li>
  </ul>

  <h2>Prerequisites</h2>
  <ul>
    <li>Basic Python knowledge</li>
    <li>Familiarity with Pandas, NumPy</li>
    <li>Understanding of EDA and data visualization</li>
    <li>Intro to classification ML models</li>
  </ul>

  <p><strong>Tools:</strong> Python, Jupyter/Colab, Pandas, Seaborn, Scikit-learn</p>

  <h2>Tasks</h2>
  <table>
    <thead>
      <tr>
        <th>Task Name</th>
        <th>Hours</th>
        <th>Skills</th>
        <th>Status</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Data Cleaning & Preprocessing Pipeline Development</td>
        <td>5</td>
        <td>Python</td>
        <td>Completed</td>
      </tr>
      <tr>
        <td>Exploratory Data Analysis & Insights Generation</td>
        <td>6</td>
        <td>EDA</td>
        <td>Completed</td>
      </tr>
      <tr>
        <td>Feature Engineering for Predictive Modeling</td>
        <td>6</td>
        <td>ML & Algorithms, Python</td>
        <td>Completed</td>
      </tr>
      <tr>
        <td>Classification Modeling, Evaluation & Result Interpretation</td>
        <td>6</td>
        <td>ML & Algorithms, Python</td>
        <td>Completed</td>
      </tr>
    </tbody>
  </table>

  <p style="text-align:center; margin-top: 30px;"><strong>Download Report Again</strong></p>

</div>

</body>
</html>
