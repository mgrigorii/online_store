# online_store
Data analysis pipe-line, with docker, python and tableau


## Challenge

The challenge involves examining the purchase intent of online shoppers on an e-commerce website. In order to facilitate this examination, the stakeholders have provided a dataset encompassing details about the behavior of these shoppers, encompassing diverse factors that may impact their purchasing choices. Your objective is to delve into the dataset, conduct pertinent analysis, and deliver actionable insights to aid the stakeholders in enhancing their website and elevating the overall shopping experience.

### Additional Information:

The dataset consists of feature vectors belonging to 12,330 sessions. Also, it was formed so that each session would belong to a different user in a 1-year period to avoid any tendency to a specific campaign, special day, user profile, or period.

## Data

The dataset provided contains the following features:

- Administrative: Number of pages visited in the administrative section of the website.
- Administrative_Duration: Total time spent on the administrative section of the website.
- Informational: Number of pages visited in the informational section of the website.
- Informational_Duration: Total time spent on the informational section of the website.
- ProductRelated: Number of pages visited in the product-related section of the website.
- ProductRelated_Duration: Total time spent on the product-related section of the website.
- BounceRates: Percentage of visitors who enter the website and leave without any further interaction.
- ExitRates: Percentage of visitors who leave the website from a specific page.
- PageValues: Average value of the pages visited by the visitor.
- SpecialDay: Closeness of the visit to a special day (e.g., Mother's Day, Valentine's Day).
- Month: Month of the year when the visit occurred.
- OperatingSystems: The operating system used by the visitor.
- Browser: Browser used by the visitor.
- Region: Geographic region of the visitor.
- TrafficType: Type of traffic source (e.g., search engines, direct traffic).
- VisitorType: Type of visitor (new visitor, returning visitor, other).
- Weekend: Indicator of whether the visit occurred on the weekend or not.
- Revenue: Indicator of whether the visitor made a purchase (1) or not (0).

<aside>
<img src="https://s3-us-west-2.amazonaws.com/secure.notion-static.com/6c7b58b1-0498-4a6f-82fc-b4daa384967b/db.png" alt="https://s3-us-west-2.amazonaws.com/secure.notion-static.com/6c7b58b1-0498-4a6f-82fc-b4daa384967b/db.png" width="40px" /> You can get the backup of the database below.

[OnlineShoopersIntentionDatabase.zip](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/3e843e9e-6751-4d4e-83f5-43ae2d041734/OnlineShoopersIntentionDatabase.zip)

</aside>

## Technologies

We expect you to use in this challenge:

- [PostgreSQL](https://www.postgresql.org/download/)
- [pgAdmin](https://www.pgadmin.org/download/)
- Visualization tool (you choose)

## Instructions

To successfully tackle this challenge, please follow these steps:

1. Create a database using pgAdmin. Then, restore the previously downloaded backup 
2. Drill down into the data set and perform relevant analysis.
3. Create adequate data visualizations using appropriate SQL queries or export the data to a visualization tool (e.g., Excel, Tableau, Looker).
4. Consolidate your findings and observations into a comprehensive report, encompassing both visual representations and the outputs of SQL queries.

### Instructions for restoring the DB

1. Decompile the previously downloaded zip file. 
2. Launch pgAdmin and connect to your PostgreSQL server.
3. In the left-hand panel, expand the server group and select the target database where you want to restore the backup.
4. Right-click on the database and choose "Restore..." from the context menu. Alternatively, you can select the "Restore" option from the "Tools" menu at the top.
5. In the "Filename" section, click on the "..." button next to the "Filename" field to browse and select the backup file you want to restore.
6. Click the "Restore" button to initiate the restoration process.
7. Wait for the restore operation to complete. You will see the progress in the "Messages" tab of the restore dialog.

## Evaluation Criteria

Your performance in addressing this challenge will be evaluated based on the following criteria:

- Accuracy and relevance of the SQL queries and analysis conducted.
- Effectiveness and clarity of data visualizations used to communicate insights.
- Overall structure and clarity of the report generated.
- Presentation and communication of the findings and actionable recommendations provided should contribute to optimizing the website and improving the overall shopping experience.
