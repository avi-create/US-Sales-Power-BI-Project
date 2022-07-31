# US-Sales-Power-BI-Project

Here with the data of US Regional Sales, we are predicting how much sales are done by particular team members of sales in the different regions.

Firstly clean the data in Power Query Editor. Here we can see there is an error in the Power Query Editor "OrderDate" Column of Sales Table. Right click on the column and click on replace errors option for replacing the error.

![orderdate](https://user-images.githubusercontent.com/79398731/182012957-38e6564b-3fe5-4a73-b031-cd4b9dc5764a.PNG)


Secondly there was a mistake in the "Sales Channel" Column because the words were not written properly like Online was written as On line, Wholesale as Whole# sale.

![replace](https://user-images.githubusercontent.com/79398731/182015749-b29340ff-c51d-435c-816c-72db24b2633b.PNG)


We have used DAX Query over here and calculated the sum of Total Unit and different year details which can later be used in the visualization.

![total unit](https://user-images.githubusercontent.com/79398731/182015671-9beaeaec-5ec8-43b7-9098-5406b152fd11.PNG)  ![year](https://user-images.githubusercontent.com/79398731/182015674-30fbc4c6-c545-4c24-865e-2f1360f1bcae.PNG)


Now we will be visualizing the data.

There are different SLICERS in the dashboard one is YEAR Slicer and other is REGION Slicer. These two slicers are arranged in HORIZONTAL Direction and can select alternate years and regions to know the sales in different regions.

![slicer](https://user-images.githubusercontent.com/79398731/182013760-c798f8f5-f3f6-44c8-9e08-d7167c10ddd4.PNG)

There is a visualization in the form of a Ribbon Chart of the Top 10 products by Unit Price. We have used advanced filter options to know the Top 10 Products in 2018 and Midwest Region. The yellow color is showing Unit Price and the orange color zone is dedicated to the Unit Cost of different products.

![ribbon](https://user-images.githubusercontent.com/79398731/182014292-2ede8b21-9d13-4593-be44-8d2bf9c5ffe5.PNG)   ![Advance Filter](https://user-images.githubusercontent.com/79398731/182014298-26621c46-e4ca-416d-b40c-12205d91b699.PNG)


Another visualization is done with the help of a bar chart showing Top 6 customers by Unit Price in 2018 and Midwest Region. Top 6 Customers by Unit Price are chosen with the help of Advanced filter Option.

![top 6 cus](https://user-images.githubusercontent.com/79398731/182014521-04167857-4576-49f1-9961-1f899069ef08.PNG)   ![filt](https://user-images.githubusercontent.com/79398731/182014528-c5df814a-e0da-44b9-a6ef-c1c1a43006df.PNG)

Same visualization is done with the help of a bar chart showing Bottom 6 customers by Unit Price in 2018 and Midwest Region. Bottom 6 Customers by Unit Price are chosen with the help of Advanced filter Option.

![Bottom 6](https://user-images.githubusercontent.com/79398731/182014687-c41f9095-9b73-4b53-874f-997eee41f99c.PNG)    ![Bottom fil](https://user-images.githubusercontent.com/79398731/182014694-11d5db3a-c745-44c7-a72d-50e9693e766e.PNG)

Here is a visualization in the form of a Map Chart showing data of different cities of the US as it US Regional Sales Data. It is showing cities of the Midwest and those cities in which products are sold out in 2018.

![map](https://user-images.githubusercontent.com/79398731/182015137-f06947b4-c9d7-4d43-ba77-f1ba2883d07d.PNG)

Other visualization is based on Pie Chart where it is showing the data of products in different city, township etc. The pink zone is showing data of City and blue zone is showing the data of Township.

![pie](https://user-images.githubusercontent.com/79398731/182015304-a8a9dd4a-c84c-4920-87e5-e48a6e6bfd8a.PNG)

The DASHBOARD is showing sales down by the members of the sales team in different regions and years. It is showing data of different products, Top 6 and Bottom 6 Customers, Top 10 Products by Unit Price, through Map also in different Regions and years.


![dashb](https://user-images.githubusercontent.com/79398731/182016015-d16ea853-e9dd-45df-900a-224cfec73933.PNG)

