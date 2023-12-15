What is difference between Pandas Dataframe and Spark Dataframe?
1. Scalability:
   Pandas are designed to work with smaller datasets which fits in single machine's memory.
   Spark Dataframes are designed to handel large scale distributed data processing.
2. Performance:
   Pands work fast with smaller datasets.
   Spark is optimised for large datsets.
3. Other than above, Pandas dataframe are mutable, but Spark dataframes are immutable.

    | Pandas Dataframe     | Spark Dataframe|
    | -------------        | -------------  |
    | Mutable              | Immutable|
    | Eager Evaluation     | Lazy Evaluation|
    | Not Fault Tolerant   | Fault Tolerant |
    | Doesn't support paralellization   | Support paralellization |

    
