# nhc_errors
Analysis of NHC forecast errors

# nhc_advisories
Downloads and parses latest NHC advisory texts
Uses percentiles calculated from nhc_errors (table1.csv to table2.csv) to compute storm intensity category probabilities for each forecast hour
Computes probabilities (only AL and EP basins) using table5.csv and table10.csv, and also computes a second set conditionalizing on whether RI is forecast for certain TAU
