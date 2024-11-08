# Bank Marketing Data

## Overview 
The Bank Marketing dataset, sourced from a Portuguese bank, contains information on a direct marketing campaign that aimed to convince clients to subscribe to a term deposit. It includes data on client demographics (e.g., age, job, marital status), details of the campaign (e.g., contact frequency, last contact day), and economic context (e.g., employment variation rate, consumer price index). The target variable indicates whether a client subscribed to the term deposit. This dataset, with around 45,000 entries, poses challenges due to its imbalanced nature, as most clients did not subscribe, making it useful for classification models that handle imbalanced data.

### Features 

1. **age**: Age of the client (numeric).
2. **job**: Type of job (categorical, e.g., "admin", "technician", "entrepreneur").
3. **marital**: Marital status (categorical, e.g., "married", "single", "divorced").
4. **education**: Education level (categorical, e.g., "primary", "secondary", "tertiary", "unknown").
5. **default**: Has credit in default? (categorical, "yes" or "no").
6. **balance**: Average yearly balance, in euros (numeric).
7. **housing**: Has housing loan? (categorical, "yes" or "no").
8. **loan**: Has personal loan? (categorical, "yes" or "no").

### Related to the Last Contact of the Current Campaign

9. **contact**: Contact communication type (categorical, e.g., "cellular", "telephone").
10. **day**: Last contact day of the month (numeric, 1–31).
11. **month**: Last contact month of year (categorical, e.g., "jan", "feb", "mar").

### Campaign-related Information

12. **duration**: Last contact duration, in seconds (numeric). *Note*: Can be predictive if the duration is zero.
13. **campaign**: Number of contacts performed during this campaign for this client (numeric).
14. **pdays**: Days since the client was last contacted (numeric; -1 means client was not previously contacted).
15. **previous**: Number of contacts before this campaign (numeric).
16. **poutcome**: Outcome of the previous marketing campaign (categorical, e.g., "success", "failure", "unknown").

### Economic Indicators

17. **emp.var.rate**: Employment variation rate — quarterly indicator (numeric).
18. **cons.price.idx**: Consumer price index — monthly indicator (numeric).
19. **cons.conf.idx**: Consumer confidence index — monthly indicator (numeric).
20. **euribor3m**: Euribor 3 month rate — daily indicator (numeric).
21. **nr.employed**: Number of employees — quarterly indicator (numeric).

### Target Variable

22. **y**: Has the client subscribed to a term deposit? (binary: "yes" or "no").
