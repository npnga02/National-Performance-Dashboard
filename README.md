# AIESEC in Vietnam | National Performance Dashboard
## **📖Project Overview**

### **Objective**

The performance dashboard provides real-time monitoring of operational KPIs at functional and national levels. It enables data-driven decision-making, proactive management of performance issues, and continuous improvement. By transforming complex data into actionable insights, this tool supports operational efficiency and strategic alignment

### Role

As the Data Manager, I was responsible for data collecting, data cleaning, performing calculations, visualization and building an interactive system readily available for decision-making.

## **💡Data processing**

**Data Collection & Processing**

The data is imported from the OD Database to the Looker Studio Database sheet using the importrange combined with address functions.

```
=IMPORTRANGE('importrange purpose'!$B$2,
ADDRESS('importrange purpose'!$C$4,COLUMN($CV$1),,,"Database") &":"& ADDRESS('importrange purpose'!$C$5,COLUMN($CU$1),,,))
```

![Screenshot 2025-03-11 102042](https://github.com/user-attachments/assets/923073c9-3c7e-43c7-b03c-abb2aa0780b2)

The database then imported to Looker Studio.

Blends are created to perform funnel of exchange functions and financial ratios.

## **🔮Dashboard Sections**

The National Performance Dashboard is a comprehensive tool designed with Looker Studio to provide actionable insights into functional operations. It features 12 interactive pages, including Overall  Performance and Functional Performances.

### **Overall Performance**

The Overall Performance page provides a comprehensive summary of the rankings of 9 branches, compiled from 5 key bottom lines: #YE, #APD, #RE, #Revenue, and #Profit.
![AIESEC_in_Vietnam___National_Performance_Dashboard_24 25_(bit ly_AiV-performance-dashboard)-01](https://github.com/user-attachments/assets/978e9c75-160f-40eb-9b35-d1b1f675d466)


### Functional Performance

The 11 Functional Performance pages provide an overall picture of each function with various metrics. These metrics are presented in different ways to be visually intuitive for viewers, including scorecards, combined columns & lines, funnels, stacked bars, gauges, and pie charts.
![Untitled presentation-1 (1) (1)](https://github.com/user-attachments/assets/4dae467d-6805-4164-9657-cb29d105c5b3)
