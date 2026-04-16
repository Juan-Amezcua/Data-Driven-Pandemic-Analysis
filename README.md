# Data-Driven Pandemic Analysis with Power BI

## Project Description

This Big Data project focuses on analyzing information regarding COVID-19 cases, the disease that emerged in 2019 and triggered the global pandemic. The dataset includes details such as the number of infections, the specific countries where they occurred, and the corresponding dates. These data points are processed to present them in various interactive reports.

---

## Technologies Used

### Power BI
A Microsoft data analysis platform and service designed to provide interactive visualizations and business intelligence capabilities. Its accessible interface allows users to create reports and dashboards, transforming large datasets into easily understandable graphical formats.

### Microsoft Excel
Used as the foundational database for storing the initial raw data before establishing a connection with Power BI.

---

## Development Process & Visual Evidence

The following steps outline how the data was imported, transformed, and visualized:

1. **Importing Data**  
   First, we import data from Excel into Power BI. Starting a new project, we navigate to the **"Get Data"** section and select the Excel workbook option.
   
   <img width="492" height="548" alt="Imagen 1" src="https://github.com/user-attachments/assets/53ff2c67-40e4-4767-9999-2024c373bc0a" />

2. **Choosing the Data Tables**  
   A navigator window provides a preview of the file. We select the specific tables to import (in this case, the `BDCovi19` table).
   
   <img width="601" height="476" alt="Imagen 2" src="https://github.com/user-attachments/assets/86a7d544-0bbb-4100-8fb5-1a121e5a311a" />

3. **Data Transformation**  
   Before loading, we click on **"Transform Data"** to verify that data types align with analytical needs. After adjustments, we apply the changes.
   
   <img width="601" height="294" alt="Imagen 3" src="https://github.com/user-attachments/assets/a0468335-9168-4379-8602-d67768a2cc76" />

4. **Building Visualizations**  
   Using the panel on the right side of the screen, we insert various charts to display the data.
   
   <img width="270" height="579" alt="Imagen 4" src="https://github.com/user-attachments/assets/a44d1e88-1dcf-4126-8bc7-774f6f7edb14" />

5. **Final Dashboard**  
   The final dashboard includes:
   - Cases per month  
   - Total cases by country  
   - Map of affected countries  
   - Cases categorized by continent

  <img width="620" height="349" alt="Imagen 5" src="https://github.com/user-attachments/assets/442a49c9-6311-4576-8b92-3a8dbee02fac" />

---

## Potential Risks and Mitigation Strategies

### Data Quality
Big Data relies on massive volumes of information. If the data is inaccurate or incomplete, conclusions can be biased or incorrect.  

**Solution:**  
Implement data cleaning and validation techniques to ensure accuracy and completeness before analysis.

---

### Privacy and Security
Handling large amounts of personal data raises confidentiality concerns.  

**Solution:**  
Use encryption and robust security measures, ensuring compliance with applicable privacy laws and regulations.

---

### Data Interpretation
Automated systems may lead to misinterpretation and flawed decisions.  

**Solution:**  
Leverage advanced analytical tools and ensure human experts review results for proper context.

---

### Scalability
Processing large datasets in real-time requires specialized and often costly infrastructure.  

**Solution:**  
Adopt scalable storage and processing technologies such as cloud solutions or clustering.

---

### Lack of Skills
Effective Big Data management requires specialized expertise.  

**Solution:**  
Invest in training staff and hiring professionals with experience in Big Data implementation and administration.
