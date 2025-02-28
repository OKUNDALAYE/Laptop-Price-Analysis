# LAPTOP PRICE PREDICTION DATASET
## INTRODUCTION
###### This dataset contains 11,768 records of laptops with various hardware specifications and prices. It is designed for predictive modeling, price estimation, and exploratory data analysis. The dataset includes real-world values to reflect the factors that influence laptop prices.
## OBJECTIVE
###### The primary objective of this analysis is to analyze the factors that influence laptop prices and help users make informed purchasing decisions. It can also be used to identify trends in laptop features, performance metrics, and brand pricing strategies.
## Potential Questions to Explore:
### 1.	Price Analysis:
######o	What is the average price of laptops based on the brand?
###### o	How does the processor type affect the price?
###### o	Is there a significant correlation between RAM size and laptop price?
### 2.	Performance vs. Price:
###### o	Do laptops with higher GPU specifications have significantly higher prices?
###### o	How does battery life influence the price of a laptop?
### 3.	Brand Comparison:
###### o	Which brands tend to offer higher battery life?
### 4.	Feature Insights:
###### o	What is the most common screen size for laptops in this dataset?
###### o	How does storage capacity affect laptop pricing?
### 5.	Operating System Impact:
###### o	Are laptops with specific operating systems (Windows, Linux, FreeDOS) priced differently?
### 6.	Weight and Portability:
###### o	Is there a trade-off between weight and battery life in laptops
## Data Source
###### The data was downloaded from kaggle.com and loaded into Excel.
###### The contains 11 columns and 11769 rows.
### The following are information on the dataset used:
### Dataset Columns
###### 1.	Brand: The manufacturer of the laptop (e.g., Dell, HP, Apple, Asus, Lenovo).
###### 2.	Processor: The CPU model, including Intel (i3, i5, i7, i9) and AMD Ryzen (3, 5, 7, 9).
###### 3.	RAM (GB): The laptop's memory size (e.g., 4GB, 8GB, 16GB, 32GB, 64GB).
###### 4.	Storage: Type and size of storage (e.g., 256GB SSD, 512GB SSD, 1TB HDD).
###### 5.	GPU: The graphics processing unit, either integrated or dedicated (e.g., Nvidia GTX 1650, RTX 3060).
###### 6.	Screen Size (inch): The display size in inches (e.g., 13.3", 14", 15.6", 17.3").
###### 7.	Resolution: The screen resolution, such as 1366x768, 1920x1080, 2560x1440, or 3840x2160.
###### 8.	Battery Life (hours): Estimated battery life in hours, ranging from 4 to 12 hours.
###### 9.	Weight (kg): The weight of the laptop in kilograms, between 1.2kg and 3.5kg.
###### 10.	Operating System: The pre-installed OS, including Windows, macOS, Linux, and FreeDOS.
###### 11.	Price ($): The target variable, representing the laptop's price in US dollars.

## Data Cleaning 
###### 1.	The data did not contain duplicate values.
###### 2.	The data did not contain blank values.
## Analysis
###### Analysis was done using Pivot Tables


## INSIGHT
### Price Analysis
###### 1.	Apple laptops have the highest average price, likely due to premium build quality and brand value. Razer laptops are generally more expensive than MSI and Lenovo, possibly due to high-end specifications (e.g., larger storage, better GPUs). Acer offers the most budget-friendly options in this dataset

![image](https://github.com/OKUNDALAYE/Laptop-Price-Analysis/blob/main/assets/images/1.png)

###### 2.	Laptops with Intel i9 and AMD Ryzen 9 processors are the most expensive, likely due to their high performance for gaming, video editing, and professional workloads. Mid-range processors like Intel i5 and AMD Ryzen 5 offer a balance between performance and price while Budget-friendly laptops tend to use Intel i3 or AMD Ryzen 3 processors.
###### 3.	A correlation coefficient of 0.62 indicates a moderate positive correlation between RAM size and laptop price. As the RAM size increases, the laptop price tends to increase as well. A correlation of 0.62 suggests that RAM size explains some of the variability in laptop prices, but there are still other factors contributing to the price differences Laptops with higher RAM generally cost more because they offer better multitasking capabilities and performance.
### Performance vs. Price
###### 4.	Laptops equipped with dedicated GPUs (like the Nvidia RTX series or AMD Radeon) are generally more expensive due to their enhanced graphical performance, which is ideal for gaming, video editing, and 3D rendering. The Nvidia RTX 3060 has the highest average price, possibly due to its balance between performance and cost-efficiency. Laptops with Integrated GPUs are significantly cheaper, as they rely on shared system resources and are better suited for basic tasks like web browsing and document editing.
###### 5.	A correlation of 0.01 suggests a very weak positive correlation between battery life and laptop price. Laptops with longer battery life tend to be slightly more expensive, but battery life isn't a major factor influencing price. Factors like processor, GPU, RAM, and brand seem to have a much stronger influence on laptop prices.
### Brand Comparison:
###### 6. Apple, HP and Dell brand tend to offer higher battery life compare to Acer and Asus. Razer band has the least battery life (hour).
### Feature Insights:
###### 7.	The most common screen sizes are usually 14 inches or 13.3 inches in this dataset. Larger screens like 15.6, 16 and 17.3 inches are less common due to portability issues.
###### 8.	Higher storage capacity generally leads to a higher laptop price. SSDs (Solid State Drives) are faster, more reliable, and more expensive than HDDs (Hard Disk Drives). Laptops with larger SSDs (512GB, 1TB, or higher) are typically more expensive than those with similar capacities in HDDs.
Operating System Impact:
###### 9.	Operating systems do affect the price, mainly due to licensing costs and the target market (e.g., Windows for general users, Free DOS for developers or advanced users who install their own OS).
Weight and Portability:
###### 10.	The correlation between Weight and Battery Life is -0.0018 which indicate there is no clear relationship between Weight and battery life.
