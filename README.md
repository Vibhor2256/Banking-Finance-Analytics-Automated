# Banking-Finance-Analytics-Automated-Portfolio

## [Banking-Finance-Analytics-Automated-Repository](https://github.com/Vibhor2256/Banking-Finance-Analytics-Automated)

This portfolio showcases an interactive report made for a bank which shared its details for past 5 years. The report showcases various usefull insights and <b>key performance indicator (KPIs)</b> using the provided dataset. The visualization is shown in one <b>Power BI report</b> and the way this report works is that it updates itself automatically, every time the client/stakeholder adds new dataset or information into one of the dimensional table on his cloud platform. This way as per client/stakeholder behaviour, everytime they upload new transaction details dataset, the <b>report fetches the data automatically</b> and refreshes itself in <b>every 24 hours</b> giving you the updated KPIs.

<br>
In this project, I successfully implemented a comprehensive data analytics solution for the banking finance industry. The project involved leveraging <b>Power BI, Stored procedures & Task in SQL, and Snowflake storage integration with AWS S3</b> to deliver advanced analytics capabilities and automate critical tasks.
<br><br>
Below are the <b>overview</b> pointers about the project:-<br>


1. Provided dataset has total 8 tables, out of which 7 were dimensional tables (account, card, client, disp, district, loan, order) and 1 fact table (transactions).

2. Data cleaning and Data manipulation was performed on the dataset using Excel and SQL script and finally reports were drawn as per different key performance indicators.
 
3. Snowflake storage integration with AWS S3 bucket by creating policy and role for it using Identity and Access Management (IAM) functionality of AWS was performed.

4. Once AWS S3 bucket is integrated with snowflake, concepts of staging and snowpipe were utilised.

5. Finally using task functionality of stored procedure the process was automated with proper schedule time given to the tasks created.

6. The created report table was then fed into PowerBI(desktop) and scheduled refresh functionality of PBI was used to refresh the PBI report as per the client/stakeholder need.
<br><br>

Workflow works like this-> <br>When task is resumed, it'll call the stored procedure which will execute SQL scripts involving transactions table in snowflake which is being triggered and taking data from AWS S3 bucket every time client/stakeholder is uploading new dataset and give the resultant report tables which further is connected with Power BI and finally at the scheduled refresh time, PowerBI's interactive report will get updated which in our case is 24 hours every day.
This reduced the manual effort and automated this business critical task so well.
<br><br>
### Process Flow shown below:-
![Process Workflow](https://github.com/Vibhor2256/Banking-Finance-Analytics-Automated/assets/61342727/9804feeb-1fff-41d9-a5eb-3b405d38ab18)

### Snowflake storage integration with AWS S3:-
![snowflake storage integration with S3](https://github.com/Vibhor2256/Banking-Finance-Analytics-Automated/assets/61342727/a124e30c-c3c1-4918-a1bc-580018cc5cf5)

### Snowflake storage integration with AWS S3 using IAM functionality:-
![storage-integration-s3_IAM](https://github.com/Vibhor2256/Banking-Finance-Analytics-Automated/assets/61342727/2f1f702f-c78b-4f19-b6b6-cdb482975cf1)



Below is the Power Bi report:-
<iframe title="Czech Bank Dashboard" width="1140" height="541.25" src="https://app.powerbi.com/reportEmbed?reportId=b6394f91-ba31-4ba0-8693-c78184981d4c&autoAuth=true&ctid=8c4a594c-3c88-495b-ad83-7ca54bf53753" frameborder="0" allowFullScreen="true"></iframe>
<br>
Here is PowerBI report link:-
[Click here](https://www.novypro.com/project/banking-finance-analytics)

### Key Achievements:

1. Task Automation: By utilizing task and stored procedures, I developed an efficient task automation framework within the banking finance environment. This allowed for streamlined processes and reduced manual effort, resulting in increased productivity and accuracy.

2. Scheduled Refresh in Power BI: I implemented scheduled data refresh functionality in Power BI, ensuring that the reports and dashboards are always up-to-date with the latest information. This feature enabled real-time monitoring of financial data and improved decision-making for stakeholders.

3. Snowflake Storage Integration: As part of the project, I seamlessly integrated Snowflake, a cloud-based data warehousing platform, with AWS S3 storage. This integration provided scalable and secure storage capabilities for the banking finance data, enabling efficient data management and analysis.

4. Enhanced Data Analytics: By leveraging the power of Power BI, I designed visually appealing and interactive reports and dashboards that provided deep insights into financial trends, risk analysis, and performance metrics. These analytics capabilities empowered stakeholders to make informed decisions and drive business growth.
