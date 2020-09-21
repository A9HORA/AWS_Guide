# This is about comparing two different AWS services `Athena` and `Macie`, which will help you to choose the best one as per your need.
## Athena
  * An interactive **query service** enables you to **anaylse and query data located in S3** using standard SQL.
  * Characteristics
    1.  Serverless (Pay per query/ per scanned TB)
    2.  No need to set up complex ETL processes **(Extract/Transform/Load)**
    3.  **Works directly with the data** stored in S3
  * General use cases
    1.  Query any kind of log file you have in S3.
    2.  Generate business reports of data stored in S3.
    3.  Analyse AWS cost & usage report.
    4.  Run queries on click-stream data.
  
  ## Macie
  * A security service powered with **ML(Machine Learning) & NLP(Natural Language Processing)** to discover, classify & protect senstitve data stored in S3.
  * Uses AI to recognise if you S3 object contains senstitve data i.e. PII.
  * Provides dashboard, reporting & alerts.
  * Works directly with the data stored in S3.
  * **Capable to analyze cloudtrail logs.**
  * **Great for preventing identity-theft & PCI-DSS.**
