# Amazon-Spending-Analysis
**RAW DATA FILE IS NOT SHARED FOR PRIVACY PURPOSES**
🌟 PERSONAL DATA PROJECT 🌟
- AMAZON SPENDING ANALYSIS

Hello #dataenthusiast today I feel very excited to present a #DataAnalysisproject on my data from lifetime spending made on Amazon.in
It was a fantastic experience to see the insights of each and every order I placed on Amazon at a single glance, Let me walk you through some key points and metrics of the project

novyPro link: https://lnkd.in/gji-4fev
(𝘔𝘢𝘬𝘦 𝘴𝘶𝘳𝘦 𝘵𝘰 𝘶𝘴𝘦 "𝘍𝘪𝘵 𝘵𝘰 𝘱𝘢𝘨𝘦" 𝘰𝘳 59% 𝘪𝘯 𝘵𝘩𝘦 𝘻𝘰𝘰𝘮 𝘴𝘭𝘪𝘥𝘦𝘳 𝘣𝘦𝘧𝘰𝘳𝘦 𝘪𝘯𝘵𝘦𝘳𝘢𝘤𝘵𝘪𝘯𝘨 𝘸𝘪𝘵𝘩 𝘵𝘩𝘦 𝘥𝘢𝘴𝘩𝘣𝘰𝘢𝘳𝘥)

🌟 Steps Involved:
• #DataExtraction
• #DataCleaning
• #DataModelling
• #DataVisualisation

→ Data Extraction: Amazon allows you to request your account information, you do not need any extraction script or tool to extract data, just visit your profile and under Data and Privacy you will find the "Request Your Information" link and proceed further (If confused checkout youtube tutorials)

→ Data Cleaning: Understanding your Data is very important since Amazon has been evolving every year new payment methods new subscription method keep getting added which can be the reason for a lot of missing values in your data, assuming since this is your personal data you may know easily how to handle those values by replacing or deleting it.

→ Data Modeling: I have worked with 2 Tables OrderHistory and ReturnHistory, both table does not have any relation with each other to avoid Many to Many Cardinaltiy

→ Data Visualization: This report is inspired by following the design tutorial of datatraining.io from Youtube. Must checkout their youtube channel for amazing dashboarding tips and tricks

🌟 KEY POINTS TO REMEMBER :
» Data is from January 2016 - June 2023
» Total Return is always constant as there is no relation between Orders & Return Tabel to avoid Many to Many Cardinality
» No Orders were Placed in the year 2020 that's why not included in Year Slicer.
» 4 Buttons (Y - Yearly / Q - Quarterly / M - Monthly / D - Daily) were added with Yearly Slicer making the drilling inside the line chart a lot easier.
» In the "Most Expensive Product Ordered" Tab Utility Bills payments like Credit card bills, Electricity bills, etc have been excluded to show only the Product name.

🌟 KEY INSIGHTS:
※ Total of 207 Orders were made between January 2016- June 2023
※ ₹1,00,724 is the maximum amount spent on Amazon in the year 2022 and ₹723 is the lowest amount spent on Amazon in the year 2016
※ Maximum Utility Bill Payments are made on Credit Card Bills
※ Most of the Orders were made between Morning(38%) & Afternoon(38%)
※ Shipping Charges were reduced to ₹0 in the year 2022-23 due to Amazon Prime Subscription
※ Most of the Orders were made by Recipients Sumir Kr. Mandal
※ The most expensive product ordered is LG Single Door Refrigerator
(Ps: Utility payments are excluded from products)
※ Most of the Orders were made by Recipient Sumir Kr. Mandal
