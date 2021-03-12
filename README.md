# insurance-activity-mkd


Here we include the data used in the paper "The short-run impact of COVID-19 on the activity in the insurance industry in the Republic of North Macedonia". 
The paper is available at https://arxiv.org/pdf/2011.10826.pdf

The Seasonal ARIMA models can be estimated using MATLAB.

An alternative: Python-based environment SARIMA models estimation package: https://www.statsmodels.org/dev/generated/statsmodels.tsa.statespace.sarimax.SARIMAX.html 

The replication data is consisted of:

*** insurance_activity_mkd.xlsx -- a file which contains quarterly time-series data for the insurance classes divided in two sheets, GWP and GCP, for premiums and claims, respectively.  The data in this file is in 000 MKD. 61.5 MKD = 1 EUR. The time variable spans the period from 2Q 2012 to 2Q 2020.

The variables, by insurance class, are:

* Accident;
* Health;
* Motor vehicles (casco);
* Cargo; 
* Property fire and nat.forces;
* Property, other;
* Motor Third Party Liability insurance (MTPL, total);
* General liability;
* Financial losses;
* Tourists assistance;
* Life assurance.
