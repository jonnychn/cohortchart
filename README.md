**Cohort Analysis Table and Retention Chart Web App**

Build a web-based application for cohort analysis that provides a user-friendly interface for generating a cohort analysis table and retention curves using data from an Excel file. The app should meet the following requirements:

1.  **User-Friendly Design:**
    
    *   The UI should be modern and intuitive, following a style similar to Airbnb, with clean typography and spacing, soft rounded elements, and appropriate use of colors.
        
    *   Users should be able to upload a raw Excel data file to generate both a cohort table and a retention chart. Make sure the styling reflects a polished, visually appealing interface.
        
2.  **Upload and Visualization Capabilities:**
    
    *   Users upload an .xlsx file with raw cohort data. This file will contain columns for Cohort Month, New Users, and Retention by Week.
        
    *   When the file is uploaded, the data should be processed to generate the **Cohort Analysis Table**. Each row of the table represents a cohort, and columns represent retention rates at different time points (weeks).
        
    *   The cohort table should use **conditional formatting** for easy visualization:
        
        *   Green: High retention rate (e.g., ≥ 25%)
            
        *   Yellow: Moderate retention rate (e.g., ≥ 15%)
            
        *   Orange: Low retention rate (e.g., ≥ 5%)
            
        *   Red: Very low retention rate (e.g., < 5%)
            
3.  **Retention Curve Chart:**
    
    *   Below the cohort table, the **Retention Curve Chart** is displayed, which visualizes how the user retention rate changes over time.
        
    *   Each cohort has its retention rate represented as a line. Users should be able to observe trends easily. A smoother line curve is applied to improve visualization.
        
    *   Additionally, an "average retention curve" may be added to show an aggregated trend across all cohorts for better overall analysis.
        
4.  **Export Functionality:**
    
    *   Provide a button that enables users to **export the cohort table as a CSV** file. The button should have a label like "Download Cohort Table as CSV" for clarity.
        
    *   The CSV should contain all relevant data from the cohort table, maintaining proper formatting.
        
5.  **Details of Interpretation:**
    
    *   Add a **description box** to help users understand how to interpret the cohort table and the retention chart. Use simple, clear language, and include explanations about what each metric means (e.g., what a cohort is, how to understand the retention rate, and what the different colors represent).
        
6.  **Responsive Design:**
    
    *   Ensure the cohort table fits within the screen width to avoid horizontal scrolling. It should adjust based on the user's screen size while preserving the table's readability.
        
7.  **Interactive Elements:**
    
    *   When users hover over cells in the cohort table, show a tooltip indicating the **number of users remaining** from the initial cohort size.
        
8.  **HTML, CSS, and JavaScript Only:**
    
    *   The app should be developed using HTML, CSS, and JavaScript, avoiding any server-side dependencies.
        
    *   Chart.js and Sheet.js (XLSX) libraries are used to visualize data and read Excel files respectively.
