
# [Joshua_Profile](https://github.com/mukorodgreat/joshprofile)
<!-- Floating Go to Top Button -->
<div style="position: fixed; bottom: 10px; right: 10px; background-color: #f1f1f1; border-radius: 5px; padding: 10px;">
  <a href="#top" style="text-decoration: none;">Go to Top</a>
</div>

## Menu

[About Me](#about-me) | [Data Analysis](#data-analysis) | [Application Development](#application-development) | [Data Engineering](#data-engineering)

---

## About Me

![Josh 2](https://github.com/user-attachments/assets/3d88aa16-c3ff-422f-b90e-027eef94a38d)

I am a Data Analyst, An Accountant and Application Developer. I have trained over 15,000 persons across Nigeria in various ICT field. I am Data Analyst with very good knowledge of Python, R, Power BI , Tableau, SQL and  Advance Excel.     Project Management Professional (PM) with good knowledge of Microsoft Project .     Database Administrator with very good knowledge of Database Management System (Oracle 11g). FileMaker Database Application Developer and database integration expert. Customized software developer for small and medium scale businesses aimed at problem solving.    Accountant with very good knowledge of accounting packages like Sage 50 (Peachtree), Tally ERP and QuickBooks.

### PROFESSIONAL EXPERIENCE

- 2021 – Date: Senior Accountant, Rocad Construction Company
- 2010 – 2021: Data Analyst/Kano Centre Manager, HiiT Training Institute
- 2006 – 2007: Youth Service, ADESEMI NIG LTD (ISP) ABA, ABIA STATE
- 2003 – 2006: Computer Instructor, REHOBOTH COMPUTERS ABRAKA DELTA STATE
- 1999 – 2003: Accountant, DUMJOS CHEMIST NIG LTD. JOS
- 1996 – 1999: Auditor, MICHEAL NWOKE & SONS (CHARTERED ACCOUNTANT) JOS



---

### SKILLS
- Excellent knowledge of Oracle 11g database
- Excellent knowledge of Python for data analysis
- Excellent knowledge of software development (Filemaker development)
- Excellent knowledge of MS Power BI (Business Intelligence)
- Excellent knowledge of Excel for Data Analysis and Visualization
- Knowledge of Tableau for Data Analysis and Visualization
- Data analysis with R (In view)
- Excellent knowledge of Accounting Packages Like QuickBooks, Sage 50, and Tally ERP
- Excellent knowledge of MS Excel, MS Word, MS Corel Draw, MS PowerPoint
- Ability to not only align but integrate a wide range of technical and management principles

---

### SOFTWARE DEVELOPED
- Automated Hotel Management Application
- Automated Hospital Management System
- Customized Security Outfit Management Application
- Automated School Management Application
- Automated RetailPro Application

---

### OTHER CERTIFICATES OBTAINED
- Data Analyst (Scenario Academy)
- Machine Learning (Scenario Academy)
- CBT Software Solution Developer (HiiT Institute)
- Project Management Professional (HiiT Institute)
- Proficiency Certificate in Management (Nigeria Institue of Management MIN)



Connect with me on [LinkedIn](https://www.linkedin.com/in/joshua-umukoro-amnim-1aa25b3b/).





# Data Analysis
## Superstore Sales Analysis
I will be carrying out Exploratory Data Analysis of a notable dataset, the Superstore Dataset from Kaggle.com

## Superstore Sales Analysis
This is an exploratory data analysis I performed on the Superstore Sales Data available on Kaggle website [Link]. 
The purpose of this project is to get insights into the Superstore sales data to uncover trends in sales patterns, profit and Customers demography. 
This project is going to be in 5 Phases  
1.	Superstore Sale Data Analysis using Excel
2.	Superstore Sale Data Analysis using SQL
3.	Superstore Sale Data Analysis Python
4.	Superstore Sale Data Analysis using Power BI
5.	Superstore Sale Data Analysis using Tableau

# 1.	Superstore Sale Data Analysis using Excel
![Dashboard](https://github.com/user-attachments/assets/9ba1b4f3-ff8d-4a65-b88f-ffeb1dcee09c)
*Superstore Dashboard with Excel*

In this phase I will be carry out an exploratory data analysis on the Superstore Sales Dataset using the traditional 
Ms. Excel tools and the Ms. Excel Power Query Tools in which produce the above Dashboard  
- A.	Data cleaning and preprocessing
  1. Load the Dataset to Excel:
  2. Inspect and Understand the Data:
  3. Handle Missing Values (If any):
  4. Calculate Summary Statistics:
  5. Data Modelling/Normalization: 
- B.	Data Visualization:
- C.	Hypothesis Testing/ Statistical analysis:
- D.	Documentation:

## A.	Data cleaning and preprocessing
   ### i.	Load the Dataset to Excel:
The downloaded dataset came in csv. (Comma Separated Values) format and I will be using 
**Data Tab > Get External Data > From Text** to load the data to excel worksheet or

![Import1](https://github.com/user-attachments/assets/0f31429f-406f-406d-ba1f-c54c1940363b)

Load and Transform the Data using Power Query Editor

![import3](https://github.com/user-attachments/assets/56a2758a-6d9e-4c1e-8a53-d1bd10c2a106)
**Data Tab > Get and Transform > New Query**

The data will be loaded into the Power Query Editor where we will easily cleanup the data, create new tables among others 
to completely transform the data and Load the transform data into Excel Data Model Environment as shown below.   
![Import4](https://github.com/user-attachments/assets/cba6bbc0-f753-4abc-8138-85777ea24f3f)

   ###  ii.	Inspect and Understand the Data:
        After loading the data, I used Data Tab > Filter to review the dataset to understand its structure, contents and 
        check the column headers and data types to ensure they are correctly interpreted by Excel. The dataset has the following headers/Columns

- Row ID => which contain Unique ID for each row (Each Product in the Order).
- Order ID => Order ID for each Customer Order 
- Order Date => Order Date of the product.
- Ship Date => Shipping Date of the Product.
- Ship Mode=> Shipping Mode specified by the Customer.
- Customer ID => Customer ID of the Customer that Placed the Order.
- Customer Name => Name of the Customer.
- Segment => The segment where the Customer belongs.
- Country => Customer Country of residence.
- City => Customer City of residence.
- State => Customer State of residence.
- Postal Code => Postal Code of every Customer.
- Region => Region where the Customer belong.
- Product ID => Unique ID of the Product.
- Category => Category of the product ordered.
- Sub-Category => Sub-Category of the product ordered.
- Product Name => Name of the Product
- Sales => Sales of the Product.
- Quantity => Quantity of the Product.
- Discount => Discount Allowed.
- Profit => Profit/Loss from the Product.

Note: The data is clean but for the purpose of Feature Engineering and performance, there will be need for Normalization of the 
Dataset because it contains a lot of redundant data which I did using both the traditional Excel tools and the Excel Power Query Tools as shown above.

**Order ID** 
        : A total of 9,994 Products were sold in 5,009 Unique Orders (The Order ID is not Unique in this Column) Multiple Products in each Unique 
        Order ID as shown in the figure below. 
        
![Orderid](https://github.com/user-attachments/assets/2e72b2c1-6b7e-4898-9316-cd1225733fc3)

### iii.	Identifying Unique Values / Handling duplication Values in Excel
In this section I will be fletching unique values that we will need to population the tables we will be creating for this project using 
the “Remove Duplication Function” in Ms. Excel which include 
- Customers
- Products 
- Location 
- Orders
- Sales Table

![Remove Duplicate](https://github.com/user-attachments/assets/db800d51-c4c5-4261-b902-31aeaf6d8e24)

### iv.	Handle Missing Values (If any):
The data in this dataset are clean and did not contain any missing values. However, it is important to note that Ms. Excel can handle missing values (If any) 


### v.	Calculate Summary Statistics:
I will use Descriptive statistics in Microsoft Excel which provide a summary of the main features of Quantity of product Ordered in the Superstory dataset, offering insights into the product order through measures of central tendency, dispersion, and distribution shape. Common descriptive statistics include mean, median, mode, standard deviation, variance, range, minimum, maximum, and more. Below is the result from Ms. Excel which shows the calculations and interpretation these statistics using Excel.
![Statistic Summary](https://github.com/user-attachments/assets/5385eb38-4f8e-42ca-8159-e8919b959b5f)

- Mean: The average quantity every Customer ordered 3.79.
- Standard Error: How much the average order would vary if you picked different groups of orders from the Sales table 0.02.
- Median: The quantity ordered right in the middle when all the ordered quantities are lined up 3.
- Mode: The quantity that the most customers ordered 3.
- Standard Deviation: How much Customers' order vary from the average order 2.23.
- Sample Variance: Another way to show how much Customers' orders vary 4.95.
- Kurtosis: Shows if there were many Customers with very high or very low quantity orders 1.99.
- Skewness: Indicates if more Customers placed lower quantity orders and a few placed really high orders, or vice versa 1.28.
- Range: The gap between the highest and lowest quantity ordered 13.
- Minimum: The lowest quantity ordered in the dataset 1.
- Maximum: The highest quantity ordered in the dataset 14.
- Sum: The total of all the Customers' quantity ordered added together 37873.
- Count: The number of transaction that took place in the dataset 9994.


### vi.	Data Modelling/Normalization 
In this section I will be organizing the data in a database efficiently, which involves creating tables and establishing relationships between these tables based on rules designed to protect the data and make the database more flexible by eliminating redundancy and inconsistent dependency.

The Superstore data can be analysis as it is now, but for the purpose of improve performance in Ms. Excel you can use the **Traditional Excel Tool** or the **Excel Power Query Engine** to create the following tables from this dataset.

1.	**Order Table** (Order ID, Customer ID, Location ID, Order Date, Shipping Date, Segment)
2.	**Product Table** (Product ID, Product Name, Category ID)
3.	**Category Table** (Category ID, Cat Name)
4.	**Subcategory Table** (SubCat ID, SubCat Name)
5.	**Customers Table** (Customer ID, Customer Name, Segment)
6.	**Location Table** (Location ID, City, State, Region, County)
7.	**Fact Sales Table** (Row ID, Order ID, Customer ID, Location ID, Product ID, Sales, Quantity, Discount, Profit) as shown below.

![Org Table](https://github.com/user-attachments/assets/012681bf-fe3a-4fa9-8e7c-43c70e92d93b)


### a.	Creating Table Relationship in Excel.
![Relationship in Excel](https://github.com/user-attachments/assets/208196b4-b445-4de3-b654-7aa99c2fa433)

After creating all the above mentioned tables, I created Relationships to relate all the tables in the Data Model using the Relationship button in Excel **Data Tab** which can also be done by using Click and drag in **Diagram View** of the **Manage Data Model** Window as shown above. And below is the **Diagram View** of the Data Model in the **Manage Data Model** Window of Excel.

![Data Model](https://github.com/user-attachments/assets/e039bc93-6e12-48b8-938a-640e3c70af13)

#### i.	Outcome of Data Modelling/Normalization 
After carrying out this step, each of the tables was well organized by pulling all the related columns into their individual tables as shown above.
After creating the tables and fletching the Unique data into the individual tables, the data shows that 
1.	Orders: There are 5,009 Unique Orders (Multiple items in an order)
2.	Customers: There are 793 Unique Customers
3.	Products: There are 1,862 Unique Products
4.	Location: There are 531 Unique Locations

#### ii. Calendar Table
In addition to the above created tables, I created a Calendar table which is simply a table of all the consecutive dates between the selected start and end date. Each row contains one date and is thus unique. Beside the date the table usually contains attributes like year, quarter, month, day, day of week, week of year etc.  which is an essential part of every data modelling and analysis. One of its major advantage is that as the data grows, the Calendar table is automatically update.



## B.	Data Visualization:
Here we will use various visualization techniques, such as histograms, scatter plots, box plots, and heat-maps to visually explore the data and identify patterns or trends that may not be immediately apparent from the summary statistics alone. 

In this section I took advertage of the **Ms Excel Power Pivot** to create carry out my analysis before creating the Dashboard as show below

![Dashboard](https://github.com/user-attachments/assets/cb979e7a-3674-47a0-a7e6-14bd5d0b9f6a)

## C.	Hypothesis Testing/ Statistical Analysis:
Hypothesis Testing: 
Here we will test hypotheses or assumptions about the data. This may involve comparing different groups or categories within the data to see if there are significant differences or correlations.

Below are some of the analysis done us Power Pivot
### 1. Profitability 

#### A. Profit By Region	
![image](https://github.com/user-attachments/assets/2db65d4f-b43a-4fd3-b818-0afd1dd79877)

#### B. Profit By Sub-Category		
![image](https://github.com/user-attachments/assets/34462649-a688-4f91-87d7-9ba047253360)

#### C. Profitable Months	
![image](https://github.com/user-attachments/assets/2ad69c69-250f-49d4-b857-5fd90f15e210)

#### D. Top 5 Profitable States	
![image](https://github.com/user-attachments/assets/bcbde224-3929-4327-8761-013524d2beee)

#### E. Least 3 Profitable Products	
![image](https://github.com/user-attachments/assets/4cfea6d6-dd3c-467a-a888-42d543de72a5)


### 2. Customers Distribution/Demography

#### F. Least 5 States with the Lowest Number of Customers and Sales		
![image](https://github.com/user-attachments/assets/a0df5cfc-4186-482c-b301-b3bbe49679af)






---

# Application Development

## MY SOFTWARE APPLICATION DEVELOPMENT PROJECTS
## [PROJECT 1 : School Management System](#school-management-system)
## PROJECT 2
## PROJECT 3

## School Management System

 ![Main Page](https://github.com/mukorodgreat/School-Management-ERP/assets/67916594/e9a22a54-005c-41e5-91a1-c4717f4c0fbe)
## Tailored Solutions for Educational Institutions

---

## Overview
- **Purpose**: Our Customizable School Management System offers a flexible and adaptable solution to meet the unique needs of educational institutions of all sizes.
- **Target Audience**: Schools, colleges, and educational institutions seeking a customizable management system.
- **Key Features**: Student enrollment, ID card processing, fee management, result processing, stock item management, supplier management, and staff management.

---

## Application Overview
- **Description**: Our Customizable School Management System is designed to empower educational institutions with the tools they need to efficiently manage their administrative tasks. With customizable features and modules, schools can tailor the system to suit their specific requirements.


## Key Features
1. **Student Enrollment System**:
   - Customizable enrollment forms and fields to capture relevant student information.
   - Flexible workflow options to accommodate various enrollment processes.
   - Included here is the ACCOUNT TAB where you can view details of the Student Bills and Payment.
   - Also included is the INVENTORY TAB where you can view all the inventories that have been given to the Student.
   - The PARENT/COLLECTORS TAB display information about the Student Parent and persons who will be picking up the Student.
![Student Page](https://github.com/mukorodgreat/School-Management-ERP/assets/67916594/ef0b775d-0c51-4efa-bb07-61a557d2da22)
---
2. **Student ID Card Processing**:
   - Customizable ID card templates with options for school logos, colors, and layout.
   - Integration with enrollment system for seamless ID card generation.
![Student ID Card](https://github.com/mukorodgreat/School-Management-ERP/assets/67916594/db83b029-3c95-4b51-a112-100da17a7873)
---   
3. **School Fee Management System**:
   - Flexible fee structure setup with customizable fee categories and payment plans.
   - Dynamic fee calculation based on student enrollment status and other factors.
![Payment 1](https://github.com/mukorodgreat/School-Management-ERP/assets/67916594/74a0231e-b911-4dcc-be13-e99e4013cc6c)
---
4. **Student Result Processing System**:
   - Customizable result entry forms to accommodate different grading systems and assessment methods.
   - With ability to import/export students scores to and from Ms. Excel. 
   - Advanced result analysis tools for generating custom reports and analytics.
![Result Processing1](https://github.com/mukorodgreat/School-Management-ERP/assets/67916594/61bf5a8c-e00d-4247-a792-1c6136185ab9)
---
5. **Student Result Printing**:
   - Customizable result templates with options for formatting, branding, and language.
   - Batch printing capabilities for efficiently processing large volumes of result sheets.
   - Student results can be exported in PDF and other format.
   
6. **School Stock Item Management System**:
   - Customizable inventory categories and attributes to track various types of stock items.
   - User-defined stock item codes, descriptions, and units of measurement.
   
7. **Suppliers Management System**:
   - Customizable supplier profiles with fields for contact information, pricing agreements, and delivery terms.
   - Supplier rating and evaluation features for assessing performance and reliability.
![Suppliers](https://github.com/mukorodgreat/School-Management-ERP/assets/67916594/6e2b37d5-e739-4028-8654-b95e3dea1f77)
---   
8. **Staff Management System**:
   - Customizable staff profiles with options for recording qualifications, certifications, and training records.
   - Role-based access controls and permissions for managing staff access to system features.

---
## Technical Details
- **Technology Stack**: Developed using FileMaker Pro (As a Product of Apple company, Claris FileMaker adopts rigorous security standards including holding SOC 2® Type 2 and ISO compliance accreditations.) It also run 
    effectively on Windows Platform..
- **Architecture**: Scalable architecture with modular design for easy customization and expansion.
- **Data Modelling**: Integrated database system designed with room for future expansion.
![Data Modelling](https://github.com/mukorodgreat/SIRJOSH-APPLICATION-DEVELOPMENT-PROJECTS/assets/67916594/ac004018-4489-4c37-bb2b-74ed49c66d2c)
---
## Conclusion
- **Summary**: Our Customizable School Management System offers educational institutions the flexibility and adaptability they need to tailor their administrative processes to suit their unique requirements.
- **Call to Action**: Interested in learning more about how our Customizable School Management System can benefit your institution? Contact us for a personalized demonstration or consultation.

---

## Contact Information
- **Email**: [mukorodgreat@gmail.com]
- **Website**: [(https://www.linkedin.com/in/joshua-umukoro-amnim-1aa25b3b/)]
- **Phone**: +234 8053078449

<!-- Repeat Go to Top Link as needed -->

## Data Engineering
[Details about your Data Engineering, tools, or methodologies.]


[Go to Top](#menu)
