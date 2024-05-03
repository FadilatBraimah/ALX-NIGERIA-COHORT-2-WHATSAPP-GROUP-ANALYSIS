# ALX NIGERIA COHORT 2 WHATSAPP GROUP ANALYSIS
![](https://github.com/FadilatBraimah/ALX-NIGERIA-COHORT-2-WHATSAPP-GROUP-ANALYSIS/blob/df1efb441dff67b83ff91e95711a71bfbe9d4e3f/Alxlogo1.png)

ALX, A Sand Company whose mission is to address the global shortage of tech talent and ALX Africa takes centre stage. It serves as the technology training apparatus that provides the techno-fluent leaders of tomorrow with access to the skills and tools needed to succeed in today’s digital world.
During Foundations, you will learn professional skills that will help you succeed in your ALX specialization and that can carry you throughout your career. The skills you learn are future-proof and able to adapt to whatever changes might happen as tech evolves.

## Introduction
Upon completing the ALX Foundation program, I embarked on a journey to analyze our interactions within the Nigerian Cohort 2 group chat. This analysis aims to uncover insights, patterns, and trends within our communication channel throughout the program.
In this documentation, you will find a detailed project overview, including the objectives, methodology, data analysis techniques employed, and key findings. Also, I will provide some insights into the tools and technologies used, along with the challenges encountered throughout the analysis process.

## Problem Statement
The ALX Nigeria Cohort 2 Group Chat serves as a central hub for communication and collaboration among participants of the ALX Foundation program. With participants from different backgrounds and experiences coming together to learn, grow, and support one another, the group chat represents a rich data source that can offer valuable insights into this project. The objective of this project is to conduct a comprehensive analysis of the ALX Nigeria Cohort 2 Group Chat to:
- Gain insights into the patterns and trends of communication among participants.
- Identify key topics and words that dominate discussions within the group.
- Determine peak chatting times and assess overall engagement levels.


## Methodology 

### Data Collection
The data for this analysis was extracted from the ALX Nigeria Cohort 2 Group, which served as the primary source of communication among participants during the ALX Foundation program. The chat data was exported from the WhatsApp group as a text document for further analysis. see here for dataset 
![](https://github.com/FadilatBraimah/ALX-NIGERIA-COHORT-2-WHATSAPP-GROUP-ANALYSIS/blob/45f4eb6e942758ba4cdd79bd19f3f5a0eaab8e82/DirtyData.jpeg)

### Data Cleaning and Transformation
Before analysis, the raw chat data was thoroughly cleaned and transformed using Power BI Power Query Editor. This involved removing duplicates, handling missing values, replacing values, removing unwanted columns, removing null values, and standardizing the format of the data to ensure consistency and accuracy.
See here for cleaned data [](https://github.com/FadilatBraimah/ALX-NIGERIA-COHORT-2-WHATSAPP-GROUP-ANALYSIS/blob/d7a697da3949f973e21aebe41f66f9a41121970d/Cleaneddata.jpeg)

### Data Analysis Techniques
The Microsoft Power BI was used to extract insights from the cleaned dataset. Basic and advanced formulas were written in DAX (Data Analysis Expressions) to calculate metrics such as total chats, peak chatting times, and user activity levels. I created a table to act as a reference table, providing a list of dates inside within the conversation period. This table allows for smooth data connection and time-based data analysis. 
See data modeling here 
![](https://github.com/FadilatBraimah/ALX-NIGERIA-COHORT-2-WHATSAPP-GROUP-ANALYSIS/blob/1cf8d1943914fdd68b1e9d8980ce778f09a44836/Datamodelling.jpeg)

### Definition of terms
- *Date:* This is a standard timetable that contains a list of dates within the duration of the chat.
- *Time:* The timetable to facilitate analysis across time, hour, and day
- *Person:* The assigned name of group participants
- *Active Users:* Users that have dropped a message within the stated duration of this project

## Visualization
- *Peak Chatting Time and Most Active Month*: The analysis revealed that the overall peak chatting time occurred at 8:44 PM, indicating a heightened level of activity during this period. January emerged as the month with the highest conversation volume, suggesting increased engagement among participants during this timeframe.

- *User Engagement*: Person 16 and Person 20 were identified as the most engaged participants in the group chat, contributing 682 and 680 comments respectively. This indicates a significant level of interaction and participation from these individuals within the ALX Nigeria Cohort 2 community.

![](https://github.com/FadilatBraimah/ALX-NIGERIA-COHORT-2-WHATSAPP-GROUP-ANALYSIS/blob/main/ALXDashboard.jpeg)

## Data and Report Limitations
- From the data extracted, there is no way to identify who a particular message was sent to or tagged.
- Parts of the messages might be omitted due to some data-cleaning processes in the power query editor.
- The report does not include all the messages in the chats, it only contained messages from the day I joined the group.
- The report does not cover a thematic analysis of the chats.


## Conclusion
I had fun carrying out this project. The Pbix file containing the user's ID was only shared with the group based on a general request to check on their activity in the group for privacy. In the future, there might be a possible improvement in the report.

_**Disclaimer**:_ If your information is revealed during the process of this analysis, it was not intentional. This report is published with the approval of my team mate. 


*Here is a link to the interactive* [Dashobard](https://app.powerbi.com/view?r=eyJrIjoiMjAwOWI4ZDItNTJmZS00ZmFmLTg5ODQtODFjZDExZjFkMTEyIiwidCI6IjgyMTFmMzM1LWI0YWUtNGQ3NS04ODdkLTdkZGM4ZTJlZDRhYiJ9)



_*Thank you for reading*_ 😄

