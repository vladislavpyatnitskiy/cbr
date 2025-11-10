# Data Retrieval for Central Bank of Russia's Data

Welcome to the repository! Here you find a collection of scripts that enable to retrieve data from Central Bank of Russia's Website.

## Interest Rate Data
```
head(cbr_interest_rate("18.11.2024", "28.10.2025"), 5)
```

```
GMT
           Interest Rate
2024-11-18            21
2024-11-19            21
2024-11-20            21
2024-11-21            21
2024-11-22            21
```

## Bond Zero Coupon Yield Curve Data

```
head(cbr_yields("25.09.2024", "25.09.2025"), 5)
```

```
GMT
              3M    6M    9M    1Y    2Y    3Y    5Y    7Y   10Y   15Y   20Y   30Y
2024-09-25 18.63 18.71 18.75 18.76 18.55 18.13 17.21 16.45 15.68 14.95 14.56 14.15
2024-09-26 18.88 18.94 18.97 18.96 18.68 18.21 17.24 16.48 15.73 15.03 14.66 14.28
2024-09-27 19.03 19.08 19.09 19.07 18.79 18.34 17.37 16.58 15.78 15.04 14.64 14.23
2024-09-30 19.49 19.50 19.48 19.43 19.05 18.52 17.47 16.65 15.85 15.10 14.68 14.24
2024-10-01 19.64 19.66 19.63 19.58 19.14 18.57 17.49 16.67 15.87 15.18 14.83 14.48
```
