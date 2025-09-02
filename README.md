# Data Analytics Module 1 - Fundamentals
Access the Rossmann and Walmart datasets here:

## Rossmann Store Sales Dataset
You’ll work with a curated version of Rossmann’s dataset throughout the guided lessons of Module 1. This dataset is based on a public Kaggle competition, but we’ve prepared everything you need so you can focus on analysis without distractions.
<br><br>Download [Rossmann Store Sales](rossmann-store-sales.zip) dataset here. 
<br><br>
### Data
The dataset is available in two files: 
- `rossmann-sales.xlsx` has sales data for selected 100 stores for 3 years
- `rossmann-store.xlsx` has store information of 1115 stores.
<br><br>

The following are descriptions for the fields:

- **Id** - an Id that represents a (Store, Date) duple within the test set
- **Store** - a unique Id for each store
- **Sales** - the turnover for any given day 
- **Customers** - the number of customers on a given day
- **Open** - an indicator for whether the store was open: 0 = closed, 1 = open
- **StateHoliday** - indicates a state holiday. Normally all stores, with few exceptions, are closed on state holidays. Note that all schools are closed on public holidays and weekends. a = public holiday, b = Easter holiday, c = Christmas, 0 = None
- **SchoolHoliday** - indicates if the (Store, Date) was affected by the closure of public schools
- **StoreType** - differentiates between 4 different store models: a, b, c, d
- **Assortment** - describes an assortment level: a = basic, b = extra, c = extended
- **CompetitionDistance** - distance in meters to the nearest competitor store
- **CompetitionOpenSince[Month/Year]** - gives the approximate year and month of the time the nearest competitor was opened
- **Promo** - indicates whether a store is running a promo on that day
- **Promo2** - Promo2 is a continuing and consecutive promotion for some stores: 0 = store is not participating, 1 = store is participating
- **Promo2Since[Year/Week]** - describes the year and calendar week when the store started participating in Promo2
- **PromoInterval** - describes the consecutive intervals Promo2 is started, naming the months the promotion is started anew. E.g. "Feb,May,Aug,Nov" means each round starts in February, May, August, November of any given year for that store

<br><br>

## Walmart Recruiting - Store Sales Forecasting Dataset
In the exercises and independent project of Module 1, you’ll apply your skills to a curated Walmart dataset. 
<br><br>Download [Walmart Recruiting - Store Sales Forecasting](walmart-store-sales.zip) dataset here. 
<br><br>
### Data
The dataset is available in three files. Here are the field descriptions for each of the files:

#### 
- `rossmann-sales.xlsx` has sales data for selected 100 stores for 3 years
- `rossmann-store.xlsx` has store information of 1115 stores.
<br><br>

The following are descriptions for the fields:
You are provided with historical sales data for 45 Walmart stores located in different regions. Each store contains a number of departments, and you are tasked with predicting the department-wide sales for each store.

In addition, Walmart runs several promotional markdown events throughout the year. These markdowns precede prominent holidays, the four largest of which are the Super Bowl, Labor Day, Thanksgiving, and Christmas. The weeks including these holidays are weighted five times higher in the evaluation than non-holiday weeks. Part of the challenge presented by this competition is modeling the effects of markdowns on these holiday weeks in the absence of complete/ideal historical data.

stores.csv

This file contains anonymized information about the 45 stores, indicating the type and size of store.

train.csv

This is the historical training data, which covers to 2010-02-05 to 2012-11-01. Within this file you will find the following fields:

Store - the store number
Dept - the department number
Date - the week
Weekly_Sales -  sales for the given department in the given store
IsHoliday - whether the week is a special holiday week
test.csv

This file is identical to train.csv, except we have withheld the weekly sales. You must predict the sales for each triplet of store, department, and date in this file.

features.csv

This file contains additional data related to the store, department, and regional activity for the given dates. It contains the following fields:

Store - the store number
Date - the week
Temperature - average temperature in the region
Fuel_Price - cost of fuel in the region
MarkDown1-5 - anonymized data related to promotional markdowns that Walmart is running. MarkDown data is only available after Nov 2011, and is not available for all stores all the time. Any missing value is marked with an NA.
CPI - the consumer price index
Unemployment - the unemployment rate
IsHoliday - whether the week is a special holiday week
For convenience, the four holidays fall within the following weeks in the dataset (not all holidays are in the data):

Super Bowl: 12-Feb-10, 11-Feb-11, 10-Feb-12, 8-Feb-13
Labor Day: 10-Sep-10, 9-Sep-11, 7-Sep-12, 6-Sep-13
Thanksgiving: 26-Nov-10, 25-Nov-11, 23-Nov-12, 29-Nov-13
Christmas: 31-Dec-10, 30-Dec-11, 28-Dec-12, 27-Dec-13

<br><br>
## Explore the Full Program
The video tutorials for Module 1 are available on YouTube as part of the Fundamentals of Data Analytics series.  
You’ll build core Excel and analytics skills using real-world datasets and structured guidance.

**Watch the playlist**: [Fundamentals of Data Analytics | Essential Excel Skills for Data Analytics](https://youtube.com/playlist?list=PL8NWlkzz4LQgjzKjOslLSwBOG5FzzmCX2&si=D5AAtZT0PAqYRtgK)

## 
These datasets and guided lessons are part of [Lumen's Data Analytics Program](https://digitalmunich.com/lumen/data-analytics/), where we empower you to **Future-Proof Your Tech Career** and **Master in-demand data and AI skills and launch your dream career in just 5 weeks**.

