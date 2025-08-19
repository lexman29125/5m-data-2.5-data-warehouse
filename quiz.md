# Quiz

### Q1: Which of the following is NOT a characteristic of a data warehouse?

- A. Domain-driven
- B. Integrated
- C. Real-time data updates (ANS)
- D. Time-variant

### Q2: In the ETL process, what does the "T" stand for?

- A. Transfer
- B. Transform (ANS)
- C. Transpose
- D. Transmit

### Q3: What is the main difference between the ETL and ELT approaches?

- A. In ETL, data is transformed before loading, while in ELT, data is transformed after loading (ANS)
- B. ETL is used for batch processing, while ELT is used for real-time processing
- C. ETL is used for on-premises data warehouses, while ELT is used for cloud data warehouses
- D. There is no difference between ETL and ELT

### Q4: What is a data mart?

- A. A subset of a data warehouse focused on a specific business area or department (ANS)
- B. A type of database used for transactional processing
- C. A tool for extracting data from source systems
- D. A data modeling technique used in data warehousing

### Q5: What is the main advantage of a snowflake schema over a star schema?

- A. Improved query performance
- B. Reduced data redundancy and improved data integrity (ANS)
- C. Simpler schema structure
- D. Better support for slowly changing dimensions

### Q6: What is the purpose of slowly changing dimensions (SCDs)?

- A. To manage changes to dimension data over time (ANS)
- B. To optimize query performance
- C. To normalize data in a data warehouse
- D. To integrate data from multiple sources

### Q7: Which type of SCD simply overwrites the old value with the new value when a change occurs?

- A. Type 1 SCD (ANS)
- B. Type 2 SCD
- C. Type 3 SCD
- D. Type 4 SCD

### Q8: In a Type 2 SCD, what happens when a change occurs in a dimension attribute?

- A. The old value is overwritten with the new one
- B. A new row is added to the dimension table to represent the new value (ANS)
- C. Both the old and new values are stored in the same row
- D. A separate mini-dimension table is created to store historical changes

### Q9: Which type of SCD keeps both the old and new values in the same row, with an additional column to store the previous value?

- A. Type 1 SCD
- B. Type 2 SCD
- C. Type 3 SCD (ANS)
- D. Type 4 SCD

### Q10: What is the main benefit of using a Type 4 SCD?

- A. It reduces the size of the main dimension table and improves performance (ANS)
- B. It allows for tracking multiple changes to dimension attributes
- C. It provides a historical record of changes without creating new rows
- D. It simplifies the schema structure by avoiding additional columns
