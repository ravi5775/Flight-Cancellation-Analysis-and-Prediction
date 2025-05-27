# Flight-Cancellation-Analysis-and-Prediction

Flyzy logo
IT and Services

Flight Cancellation Analysis and Prediction
23 hours
4 tasks
Python, EDA, ML & Algorithms3 skills

About Company
Flyzy is one-of-a-kind travel-tech platform that aims to transform modern-day travel into a completely hassle-free experience by bringing innovation and power of technology right to your fingertips, quite literally! It connects retailers, service providers, and other stakeholders facilitating air, road, and train travel with the passengers via its unique hi-tech AI-enabled platform.
Apart from creating safer, simpler, and more personalised experiences for the passengers, Flyzy also ensures commercial benefits for the service providers and stakeholders involved. Flyzy's services will soon be made available for other popular modes of travel like rail and road.

#Problem statement
Flyzy is a company focused on providing a smooth and hassle-free air travel experience. They offer personalized in-flight and airport recommendations, and they also provide real-time flight tracking, mobile check-in, and more. Flyzy aims to redefine the future of air travel with a more personalized and connected experience from the beginning of the trip to the end. 

Flight cancellation is a significant issue in the aviation industry. It not only disrupts the customers' plans but also impacts the airlines' reputation and profitability. Therefore, predicting flight cancellations can help airlines take preventive measures and minimize disruptions.

#Learning Objectives

Understand and apply data cleaning techniques to prepare raw datasets for analysis.
Perform exploratory data analysis (EDA) to uncover patterns, trends, and relationships within the data.
Implement preprocessing steps such as encoding and feature scaling to prepare data for machine learning models.
Build, evaluate, and compare classification models to predict binary outcomes effectively.
Interpret model performance metrics to select the most suitable algorithm for the given business problem.

#Business Objectives
Reduce the impact of flight cancellations by predicting them in advance.
Improve Flyzy’s operational planning and customer satisfaction.
Strengthen Flyzy’s positioning as a predictive, tech-enabled travel partner.

#Dataset Description
Download: https://docs.google.com/spreadsheets/d/15eBYLoEDagmYb4Rh_pQRfk20VICkyf2Vin2ob-w2GeY/edit?gid=0#gid=0
The dataset you will be using is a dataset of flight cancellations. It contains the following columns:

Flight_ID (Numeric): This is a unique identifier for each flight. The values are randomly generated and have no particular meaning. This column will not be used in the analysis and modeling, as it does not contain any useful information.
Airline (Categorical): This column represents the airline that operates the flight. It is a categorical variable with five different airlines. Each airline has a different reputation and operational efficiency, which might affect the likelihood of flight cancellations.
Flight_Distance (Numeric): This column represents the distance of the flight in kilometers. The values have been scaled to have a mean of 0 and a standard deviation of 1. Longer flights might have a higher chance of cancellation due to more complex logistics and higher chances of encountering issues.
Origin_Airport and Destination_Airport (Categorical): These columns represent the airport from where the flight departs and the airport to which the flight arrives, respectively. They are categorical variables with five different airports each. Some airports might have a higher chance of flight cancellations due to factors like weather conditions, operational efficiency, and local regulations.
Scheduled_Departure_Time (Numeric): This column represents the time when the flight is scheduled to depart. The time is represented as the number of minutes past midnight. The departure time might affect the likelihood of flight cancellations. For example, flights scheduled to depart late at night might have a higher chance of cancellation due to less operational staff or unfavorable weather conditions.
Day_of_Week (Numeric): This column represents the day of the week when the flight is scheduled. The days are represented as numbers from 1 (Monday) to 7 (Sunday). The day of the week might affect the likelihood of flight cancellations. For example, flights scheduled on weekends might have a higher chance of cancellation due to higher passenger load.
Month (Numeric): This column represents the month when the flight is scheduled. The months are represented as numbers from 1 (January) to 12 (December). The month might affect the likelihood of flight cancellations. For example, flights scheduled in winter months might have a higher chance of cancellation due to bad weather conditions.
Airplane_Type (Categorical): This column represents the model or type of the airplane. It is a categorical variable with five different airplane types. Some airplane types might have a higher chance of flight cancellations due to factors like age, maintenance issues, and fuel efficiency.
Weather_Score (Numeric): This column represents a score of the severity of the weather conditions, with higher scores indicating worse weather. Bad weather is one of the most common reasons for flight cancellations.
Previous_Flight_Delay_Minutes (Numeric): This column represents the delay of the previous flight by the same airplane in minutes. If the previous flight was delayed, it might affect the current flight's schedule and lead to its cancellation.
Airline_Rating (Numeric): This column represents a score of the quality or reputation of the airline, with higher scores indicating better airlines.Better-rated airlines might have lower chances of flight cancellations due to higher operational efficiency and customer service.
Passenger_Load (Numeric): This column represents the load or capacity utilization of the flight, represented as a percentage. Flights with a higher passenger load might have a lower chance of cancellation, as airlines want to avoid inconveniencing a large number of passengers.
Flight_Cancelled (Binary): This is the target variable, represented as a binary variable where '1' means the flight was canceled and '0' means it was not canceled. The flight cancellations are based on various factors and some randomness.


#Prerequisites

Understanding of Python basics
Familiarity with Pandas and NumPy
Basic knowledge of statistics and data visualization
Introductory machine learning concepts (classification models)
Platform/Tools

Python (Jupyter Notebook or Google Colab) Pandas, NumPy Matplotlib, Seaborn (for visualization) Scikit-learn (for ML models) GitHub or Google Drive (for submission)

# Tasks



<h1>Tasks</h1>

<table>
  <thead>
    <tr>
      <th colspan="4" style="text-align:center;">Tasks</th>
    </tr>
    <tr>
      <th style="text-align:center;">Task Name</th>
      <th style="text-align:center;">Hours</th>
      <th style="text-align:center;">Skills</th>
      <th style="text-align:center;">Status</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:center;">Data Cleaning & Preprocessing Pipeline Development</td>
      <td style="text-align:center;">5</td>
      <td style="text-align:center;">Python</td>
      <td style="text-align:center;">Completed</td>
    </tr>
    <tr>
      <td style="text-align:center;">Exploratory Data Analysis & Insights Generation</td>
      <td style="text-align:center;">6</td>
      <td style="text-align:center;">EDA</td>
      <td style="text-align:center;">Completed</td>
    </tr>
    <tr>
      <td style="text-align:center;">Feature Engineering for Predictive Modeling</td>
      <td style="text-align:center;">6</td>
      <td style="text-align:center;">ML & Algorithms, Python</td>
      <td style="text-align:center;">Completed</td>
    </tr>
    <tr>
      <td style="text-align:center;">Classification Modeling, Evaluation & Result Interpretation</td>
      <td style="text-align:center;">6</td>
      <td style="text-align:center;">ML & Algorithms, Python</td>
      <td style="text-align:center;">Completed</td>
    </tr>
    <tr>
      <td colspan="3" style="text-align:center;"></td>
      <td style="text-align:center;">Download Again</td>
    </tr>
  </tbody>
</table>
