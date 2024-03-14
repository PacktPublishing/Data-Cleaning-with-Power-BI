# Data-Cleaning-with-Power-BI
Data Cleaning with Power BI, published by Packt

<a href="https://www.packtpub.com/product/data-cleaning-with-power-bi/9781805126409?utm_source=github&utm_medium=repository&utm_campaign=9781805126409"><img src="https://content.packt.com/B21105/cover_image_small.jpg" alt="Data Cleaning with Power BI" height="256px" align="right"></a>

This is the code repository for [Data Cleaning with Power BI](https://www.packtpub.com/product/data-cleaning-with-power-bi/9781805126409?utm_source=github&utm_medium=repository&utm_campaign=9781805126409), published by Packt.

**The definitive guide to transforming dirty data into actionable insights**

## What is this book about?
Unlock the benefits of Power BI’s data cleaning capabilities to simplify the process of preparing data for analysis with this guide to transforming your data using tools like DAX, PowerQuery, and M language to build compelling visualizations.

This book covers the following exciting features:
* Connect to data sources using both import and DirectQuery options
* Use the Query Editor to apply data transformations
* Transform your data using the M query language
* Design clean and optimized data models by creating relationships and DAX calculations
* Perform exploratory data analysis using Power BI
* Address the most common data challenges with best practices
* Explore the benefits of using OpenAI, ChatGPT, and Microsoft Copilot for simplifying data cleaning

If you feel this book is for you, get your [copy](https://www.amazon.com/dp/1805126407) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" 
alt="https://www.packtpub.com/" border="5" /></a>

## Instructions and Navigations
All of the code is organized into folders. For example, Chapter02.

The code will look like the following:
```
Total Sales by Category =
CALCULATE(
SUM('Sales'[Sales Amount]),
ALLEXCEPT('Sales', 'Sales'[Product Category])
)
```

**Following is what you need for this book:**
If you’re a data analyst, business intelligence professional, business analyst, data scientist, or anyone who works with data on a regular basis, this book is for you. It’s a useful resource for anyone who wants to gain a deeper understanding of data quality issues and best practices for data cleaning in Power BI. If you have a basic knowledge of BI tools and concepts, this book will help you advance your skills in Power BI.

With the following software and hardware list you can run all code files present in the book (Chapter 1-15).
### Software and Hardware List
| Chapter | Software required | OS required |
| -------- | ------------------------------------ | ----------------------------------- |
| 1-15 | Power BI Desktop | Windows, Mac OS X, and Linux (Any) |
| 1-15 | Power BI Report Builder | Windows, Mac OS X, and Linux (Any) |
| 1-15 | Power BI Service | Windows, Mac OS X, and Linux (Any) |
| 1-15 | Power Automate | Windows, Mac OS X, and Linux (Any) |
| 1-15 | R | Windows, Mac OS X, and Linux (Any) |
| 1-15 | Python | Windows, Mac OS X, and Linux (Any) |


### Related products
* Microsoft Power BI Performance Best Practices [[Packt]](https://www.packtpub.com/product/microsoft-power-bi-performance-best-practices/9781801076449?utm_source=github&utm_medium=repository&utm_campaign=9781801076449) [[Amazon]](https://www.amazon.com/dp/1801076448)

* Microsoft Power BI Data Analyst Certification Guide [[Packt]](https://www.packtpub.com/product/microsoft-power-bi-data-analyst-certification-guide/9781803238562?utm_source=github&utm_medium=repository&utm_campaign=9781803238562) [[Amazon]](https://www.amazon.com/dp/1803238569)

## Get to Know the Author
**Gus Frazer**
 is a seasoned analytics consultant who focuses on business intelligence solutions. With over eight years of experience working for the two market-leading platforms, Power BI (Microsoft) and Tableau, he has amassed a wealth of knowledge and expertise.
He also has experience in helping hundreds of customers to drive their digital and data transformations, scope data requirements, drive actionable insights, and most important of all, clean data ready for analysis.
