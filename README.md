# INU-2021-PROGRAMMING-PROJECT

Final Project Information
“Analysis of South Korean Pollution Data”
One of the main goals of “Programming Languages” class is to prepare you to apply easy data analysis to realworld tasks, or to leave you well-qualified to start a previous prerequisite for future courses of machine learning
or AI research. The final project is intended to be a class project, specifically to use python.
Think that a big company hired your team to carry out a study on the increase in pollution in South Korea. It is
not necessary to have knowledge about how pollution affects people. The company only seeks to analyze the
different levels of pollution (and visualize) what happened during year 2020. They basically provide the data for
you to analyze, and you are free to add more data (enrich it) if necessary.
Each team will consist of 6 people. Additionally, each team must elect a representative (team leader). The team
leader will be in charge of coordinating the meeting days and the work of each member. It is important that you
meet via Zoom, Skype, etc., and work in GitHub.
You can download the pollution data of year 2020 from:
https://www.airkorea.or.kr/web/last_amb_hour_data?pMENU_NO=123
After you send me the list of members, I will designate which area you will analyze from the following list:
- Incheon
- Busan
- Gwangju
- Daegu
- Daejeon
Due date of the Project: December 14, 2021, 11:00 pm
Project Parts: Develop Project and Final Report
Submission: We’ll be using GitHub for submission of all parts of the final project. I will open a link in GitHub
for our class so you can work as a team. The use of Github will be qualified within each of the sections.
- First, send me an email with the members of each team. Include what day you are taking the
course.
o Names, student id, github id of each one and specify the name of the team leader.
Develop Project << Jupyter Notebook (95 pts)
The use of Github will be rated, it is important that you use everything you learned
previously.
1. Prepare the problem (2.5 pts)
The first step not just in Data Science, but in any project, is to simply define the problem at hand. You
must first understand the situation and the problem to be solved. And then devise how to get meaningful
information that would solve that problem efficiently. Once you know the problem well, you then head
on to solve it.
You need to answer the following questions:
• How many meteorological stations are in your area of study?
• How many empty/null values do you have in your data?
• How many pollutants are recorded and what are their levels of quality? 6 pollutants (SO2, NO2, CO, O3,
PM10, PM2.5)
o You need to search the levels of quality for each pollutant and integrate these colors in your data
visualizations.
▪ Good – Blue color
▪ Normal – Green color
▪ Bad – Yellow color
▪ Very bad – Red color
• Total data size (rows and columns)
2. Data Handling/Cleaning (2.5 pts)
• Load Libraries
• Load Datasets
• Data Cleaning (NumPy and Pandas)
o Total data contains all the information from all South Korea.
o Here you need to select and merge different files. In total there are 12 files for each month.
o Sometimes you do not have any measure. (How will you treat this empty data?)
3. Summarize Data (90 pts)
• Descriptive statistics
• Data visualizations
What you must have to find in the dataset for your region of study:
Graphical Visualization (Matplotlib, Seaborn, etc.) (70pts)
- Levels of pollution throughout the 2020 period for each pollutant (20 pts)
o Levels of pollution for all year
o Comparison between months (January … December)
o Levels along seasons (Spring, Summer, Autumn, Winter)
- Do pollutants have correlation? (10 pts)
- How pollutant concentrations vary between locations of each station? (20 pts)
- What are the most and least polluted regions in your region (Incheon, Daejeon, etc) (10 pts)
o Calculate the mean concentration of each pollutant per each district in your area.
- What happened on December 25th in your district? (10 pts)
 Maps (20 pts) (For this section you must search for the tools that are necessary for the implementation.)
- Where are stations located? (10 pts)
o Here, with the address of each station, you need to find the latitude and longitude of each station
o Basically, you need to show a map of Korea where it is located each station
o You can use any library to create a map. If you do not know anyone, I recommend you search
about “folium” library.
▪ https://towardsdatascience.com/creating-a-simple-map-with-folium-and-python4c083abfff94
- What are the most and least polluted districts in your region (10 pts)
o Calculate the mean concentration of each pollutant per each district in your area.
o I recommend that you show a map with different districts of your designated area in South Korea.
o You can obtain the Korean district maps from
▪ https://github.com/southkorea/southkorea-maps
▪ https://github.com/southkorea/southkorea-maps/tree/master/kostat/2018/json
Final Report << Word document (5 pts)
1. Team members
2. Prepare the problem
3. Governmental district “Visualizations”
4. Contributions
• This section should describe what each team member worked on and contributed to the project.
5. References/Bibliography 
