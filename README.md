In this PowerBi project we will look at the dataset Unicorns_in_india.csv, the dataset has been taken from kaggle.
Befor starting the project we will first analyse the dataset and see the informaion it offers.
The provided dataset has provides us with the information such as {company name, Sector, Entry valuation, Current valuation, Investors, Entry date, Current unicorn status and Location}.
The insights that could be useful and could be drawn outt from the provideed dataset are:

1. Number of Unicorns in each sector
2. How many unicorns are publicly listed
3. Avergae valuation of unicorns in India
4. How many unicorns have maintained there unicorn status
5. Investors that have produced the most number if unicorns

#Problem with the dataset
The data provided by Kaggle lacked the seperation of Investors in a company rather a single cell contained the group VC forms that have been an investor in the company, but this posed a problem in finding the company 
with the most number of unicorns, So the column was split into multple rows to with each cell in a row containig the name of a VC firm.
To counter the problem of duplicates rows with different VC firms, a new Total Measure was created to calculate total number of companies within a context.

Insights :
1. Most companies still maintain their unicorn status.
2. Average valuation of a company is 3.33 billion.
3. Only 7.27 % of companies are publicly listed.
4. Fintech > SAas > E-Commerce.
5. Accel > TigerGlobal > Sequio Capital.
6. Banglore > Mumbai > Gurgaon.

![Screenshot (149)](https://github.com/user-attachments/assets/c84a0e6c-7910-40ca-aeb0-838e119be7c8)
![Screenshot (150)](https://github.com/user-attachments/assets/40adad9e-4edc-4145-ae83-4e8cc1ce9955)
![Screenshot (151)](https://github.com/user-attachments/assets/a2576f30-14cd-44f4-8172-f0175ffa7a34)
