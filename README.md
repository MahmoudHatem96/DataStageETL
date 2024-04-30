# **Retail Data Mart ETL Usiing IBM DataStage**
## **Introduction**

This document outlines the ETL (Extract, Transform, Load) solution implemented using IBM DataStage to fulfill the business requirements specified in the project.

## **Business Requirements**

The business requirements entail creating a data mart to display each transaction for each customer, categorized into "citizen" or "foreign" types. Additionally, insights into transaction counts for each customer at each store and determining the maximum profit made by each customer type are needed. Furthermore, a bonus calculation based on profitability is required.

## **Solution Overview**

The ETL solution is designed to efficiently extract data from the source, transform it according to the specified business rules, and load it into the target data mart.

1. **Extract**: Data is extracted from the source system, including transactional data, customer information, product details, and stock information.
2. **Transform**: Transformation involves several steps:
    - Categorizing customers into "citizen" or "foreign" types based on predefined criteria.
    - Converting customer names to uppercase to maintain consistency.
    - Directly representing date information in the display columns instead of using a date dimension table.
    - Aggregating data to display each transaction for each customer, including product and stock information.
    - Analyzing transaction counts for each customer at each store.
    - Determining the maximum profit made by each customer type.
    - Calculating bonuses for customers based on profitability.
3. **Load**: Transformed data is loaded into the target data mart, integrating both retail and activation sales data.

## **Insights and Process Key Values**

During the implementation process, several insights and key values were obtained:

1. **Efficiency**: Utilizing IBM DataStage facilitated efficient ETL processes, ensuring timely extraction, transformation, and loading of large volumes of data.
2. **Scalability**: The solution is designed to handle scalable data processing requirements, accommodating future growth in data volume and complexity.
3. **Accuracy**: By implementing predefined business rules and transformations, data accuracy is maintained throughout the ETL pipeline.
4. **Flexibility**: The solution offers flexibility in adapting to evolving business needs and changing data structures.
5. **Performance Optimization**: Performance tuning techniques were applied to optimize ETL processes, enhancing overall system performance and responsiveness.
6. **Data Integrity**: Data integrity measures were implemented to ensure the consistency and reliability of the transformed data stored in the data mart.

## **Conclusion**

The ETL solution implemented using IBM DataStage successfully fulfills the business requirements outlined in the project. The data mart provides comprehensive insights into customer transactions, product purchases, stock information, transaction counts, maximum profits by customer type, and bonus calculations based on profitability.
