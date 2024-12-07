[readme.docx](https://github.com/user-attachments/files/18047750/readme.docx)
Music Streaming Data Analysis Project
________________________________________
Project Title


Exploring Music Streaming Habits and User Preferences
________________________________________
Group Members

•	KRISHNA THAKER:         [KU2407U418]

•	KHUSHAL MATHUR:      [KU2407U414]

•	JAIWARDHAN SINGH:   [KU2407U407]

•	OMI RATHOD:                 [KU2407U429]

________________________________________
Objective of the Project


The primary objective of this project is to analyze the music streaming habits of users based on a dataset of 10 records. It aims to uncover trends, such as popular genres, device usage, and listening patterns, and to identify factors influencing user behavior like replay and skip rates.

________________________________________

Tools and Libraries Used

•	Programming Language: Python

•	Libraries:


o	pandas: Data preprocessing and manipulation.

o	numpy: Numerical computations.

o	matplotlib: Basic visualization and plotting.

o	seaborn: Enhanced data visualization with statistical insights.


________________________________________

Data Source(s)

•	Dataset Name: Music_Streaming_Data_India_2023_Expanded.csv

•	Size: 10 records

•	Fields: User_ID, Age_Group, Device_Usage, Preferred_Genres, Artist_Name, Listening_Time_Pattern, Skip_Rate, Replay_Rate, Total_Streams, Subscription_Type, Location.

(The dataset was gathered by Khushal Mathur for this project.)

________________________________________

Execution Steps

1.	Clone the Repository:

               git clone       https://github.com/justkrishnaaa/SYNTH_INTELLIGENCE_MUSIC_STREAMING_ANALYSIS

2.	Navigate to the Project Directory:

              cd music-streaming-analysis

3.	Install Required Libraries:

               pip install -r requirements.txt(pandas , numpy ,matplotlib,seaborn)

4.	Run the Analysis Script: Execute the script to generate visualizations and reports:
 
              python src/analysis.py

5.	Access Output:

o	Visualizations: Saved in the visuals/ folder.

o	Reports: Available in the data/ folder as a report document.

________________________________________

Summary of Results

•	Popular Genres: Age groups significantly influence genre preferences, with younger users favoring genres like Pop and EDM.

•	Device Usage: Mobile devices dominate music streaming trends, with desktop usage trailing significantly.

•	Listening Patterns: Peak listening hours occur in the evening, aligning with user downtime.

•	Subscription Insights: Premium users tend to have higher total streams, suggesting higher engagement levels.

•	Correlation Analysis: Replay rates positively correlate with skip rates, indicating user experimentation with new tracks.

________________________________________


Challenges Faced

1.	Data Cleaning:

o	Managing inconsistent and missing data in fields like Skip_Rate and Replay_Rate.

o	Splitting and exploding multi-value fields (e.g., Preferred_Genres).

2.	Visualization Aesthetics:

o	Ensuring plots were both informative and visually appealing.

o	Choosing appropriate color palettes for diverse graphs.

3.	Own Dataset:

o	Made a new dataset from scratch of a few people from the persons around.

4.	Feature Engineering:

o	Extracting meaningful insights from fields like Location and Listening_Time_Pattern.



CREDITS:

o	Khushal Mathur for making the dataset of few random people from our circle.

o	Jaiwardhan singh and Omi rathod for working on the code giving such exceptional python program putting efforts for a great output.

o	Krishna thaker for handling the documents and making a fine overall organization, aesthetics, and professionalism of the repository consisting of  Data , Visuals , Assets  and Output report.







