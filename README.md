# zindi-african-credit-score
African Credit Scoring Challenge

You will work with loan and customer data from Kenya (train and test set) and Ghana (test set). This split emphasises the need for models that generalise well, i.e. perform well across different countries and financial contexts.

You will notice that a customer ID can appear in multiple rows of the dataset, and for a given customer, a loan ID can also appear with different lender IDs. For example, we can have the same customer ID on three rows with the same loan ID on each but a different lender ID. This observation means that the loan is funded by three separate lenders.

Additional data pulled from the Federal Reserve Economic Data (FRED) portal are provided to enrich model performance and offer insights into features that impact on credit scoring.

The economic indicators are:

FP.CPI.TOTL.ZG: Inflation, consumer prices (annual %)
PA.NUS.FCRF: Official exchange rate (LCU per US$, period average)
FR.INR.RINR: Real interest rate (%)
AG.LND.PRCP.MM: Average precipitation in depth (mm per year)
FR.INR.DPST: Deposit interest rate (%)
FP.INR.LEND: Lending interest rate (%)
FR.INR.LNDP: Interest rate spread (lending rate minus deposit rate, %)
EG.USE.COMM.FO.ZS: Fossil fuel energy consumption (% of total)
SL.UEM.TOTL.ZS: Unemployment rate
The data downloaded from FRED is saved in a separate CSV in the data section.



ID_269404226088267278, ID_247613296713267278, ID_271847294122267278, ID_308399367770267278, and ID_253278278418267278