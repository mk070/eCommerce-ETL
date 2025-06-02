###  Gold layer 

1. customers Table - SCD Type 1
2. products  Table - SCD Type 2 (DLT)
3. orders  Table   - Fact table

**Summary of SCD Types**
| Type | Keeps Full History | Adds Rows | Adds Columns | Use Case                               |
| ---- | ------------------ | --------- | ------------ | -------------------------------------- |
| 1    | ❌                  | ❌         | ❌       | Overwrite data                         |
| 2    | ✅                  | ✅         | ❌            | Track full historical changes          |
| 3    | ❌ (limited)        | ❌         | ✅            | Track only recent changes (1–2 values) |


### DLT - Declarative ETL
