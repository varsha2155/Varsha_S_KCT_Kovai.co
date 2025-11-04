*Forecasting with SARIMAX*
Dataset Desription: Dataset is basically having data on different service based passenger journey in daily public transport

Attributes- 7 (Date, Local ROute, Light Rail, Peak Service,Rapid Route, School,Other)
Records- 1919 

OUTPUT- 7 DAY FORECASTING
7-Day Forecast Summary (Values within 95% Confidence Range)

         Service       Date  forecast  lower_bound  upper_bound
0    Local Route 2024-08-31   6146.21      1337.51     10954.92
1    Local Route 2024-09-01   4599.60         0.00      9800.78
2    Local Route 2024-09-02  15382.21     10045.87     20718.54
3    Local Route 2024-09-03  16896.83     11472.44     22321.21
4    Local Route 2024-09-04  16841.00     11340.48     22341.52
5    Local Route 2024-09-05  16834.70     11261.86     22407.54
6    Local Route 2024-09-06  16175.24     10531.76     21818.73
7     Light Rail 2024-08-31   6446.52      4036.15      8856.90
8     Light Rail 2024-09-01   4856.51      2231.87      7481.15
9     Light Rail 2024-09-02  10085.75      7353.61     12817.89
10    Light Rail 2024-09-03  11312.27      8491.44     14133.09
11    Light Rail 2024-09-04  11453.42      8549.41     14357.43
12    Light Rail 2024-09-05  11095.84      8111.51     14080.18
13    Light Rail 2024-09-06  10758.58      7696.13     13821.02
14  Peak Service 2024-08-31    -12.38         0.00       105.65
15  Peak Service 2024-09-01     -7.18         0.00       120.37
16  Peak Service 2024-09-02    305.43       174.96       435.91
17  Peak Service 2024-09-03    349.78       217.60       481.96
18  Peak Service 2024-09-04    344.04       210.46       477.62
19  Peak Service 2024-09-05    307.12       172.24       442.01
20  Peak Service 2024-09-06    238.93       102.78       375.08
21   Rapid Route 2024-08-31   9223.09      4393.20     14052.98
22   Rapid Route 2024-09-01   7393.33      2128.75     12657.91
23   Rapid Route 2024-09-02  18786.65     13333.22     24240.09
24   Rapid Route 2024-09-03  21027.24     15430.68     26623.80
25   Rapid Route 2024-09-04  21005.66     15278.30     26733.01
26   Rapid Route 2024-09-05  20638.61     14785.44     26491.78
27   Rapid Route 2024-09-06  19230.20     13254.36     25206.04
28        School 2024-08-31     90.99         0.00      2500.94
29        School 2024-09-01     72.67         0.00      2947.61
30        School 2024-09-02   3939.25       888.38      6990.13
31        School 2024-09-03   4204.47      1081.68      7327.27
32        School 2024-09-04   4063.26       910.16      7216.37
33        School 2024-09-05   4045.54       879.42      7211.66
34        School 2024-09-06   3530.68       358.88      6702.49


KEY INSIGHTS:
1. Passenger service is high midweek at weekdays, stating more passengers take public transports at weekdays and there is a noticable drop at weekends due to absence of work hours and school hours
2. Rapid route count is high indicating high demand areas and School and Peak services have less count and have sudden peaks indicationg school or officehours at weekdays 
3. Peak service have one outlier - sudden festival or event peak due to unpredictable sudden events
4. We could use weekends for vehicle management and inspections
