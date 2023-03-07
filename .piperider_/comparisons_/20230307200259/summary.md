<details>
<summary>Comparison Summary</summary>

Table | Rows | Columns 
--- | --- | ---
dim_zones | 265 (+0) | 4 (+0) 
fact_trips | 105219 (+0) | 27 (+0) 
dm_monthly_zone_statistics | 5599 (+0) | 15 (+0) 
dm_monthly_zone_revenue | 5599 (+0) | 12 (+0) 

Metric | Period | Base | Target | +/- 
--- | --- | :-: | :-: | :-: 
Average Distance (Monthly) | 2023-02-01 (Last month) | - | - | - 
 Average Distance (Quarterly) | 2022-10-01 (Last quarter) | 3.6001666666666665 | 2.061907284768212 | -1.5382593818984547 
 Average Distance (Yearly) | 2022-01-01 (Last year) | 4.840314503631226 | 3.764060654662098 | -1.0762538489691278 
 
</details>
<details>
<summary>Tables Summary</summary>
<blockquote>

<details>
<summary>dim_zones</summary>

Column | Type | Valid % | Distinct %
--- | --- | --- | ---
locationid | NUMERIC(18, 3) | 100.0% (+0.0%) | 100.0% (+0.0%) 
borough | VARCHAR | 100.0% (+0.0%) | 2.64% (+0.0%) 
zone | VARCHAR | 100.0% (+0.0%) | 98.87% (+0.0%) 
service_zone | VARCHAR | 100.0% (+0.0%) | 1.89% (+0.0%) 

</details>
<details>
<summary>fact_trips</summary>

Column | Type | Valid % | Distinct %
--- | --- | --- | ---
tripid | VARCHAR | 100.0% (+0.0%) | 99.99% (+0.0%) 
vendorid | INTEGER | 100.0% (+0.0%) | 0.0% (+0.0%) 
service_type | VARCHAR | 100.0% (+0.0%) | 0.0% (+0.0%) 
ratecodeid | INTEGER | 95.7% (+0.0%) | 0.01% (+0.0%) 
pickup_locationid | INTEGER | 100.0% (+0.0%) | 0.23% (+0.0%) 
pickup_borough | VARCHAR | 100.0% (+0.0%) | 0.01% (+0.0%) 
pickup_zone | VARCHAR | 100.0% (+0.0%) | 0.23% (+0.0%) 
dropoff_locationid | INTEGER | 100.0% (+0.0%) | 0.24% (+0.0%) 
dropoff_borough | VARCHAR | 100.0% (+0.0%) | 0.01% (+0.0%) 
dropoff_zone | VARCHAR | 100.0% (+0.0%) | 0.24% (+0.0%) 
pickup_datetime | TIMESTAMP | 100.0% (+0.0%) | 99.96% (+0.0%) 
dropoff_datetime | TIMESTAMP | 100.0% (+0.0%) | 99.88% (+0.0%) 
store_and_fwd_flag | VARCHAR | 95.7% (+0.0%) | 0.0% (+0.0%) 
passenger_count | INTEGER | 95.7% (+0.0%) | 0.01% (+0.0%) 
trip_distance | NUMERIC(18, 3) | 100.0% (+0.0%) | 2.32% (+0.0%) 
trip_type | INTEGER | 98.83% (+0.0%) | 0.0% (+0.0%) 
fare_amount | NUMERIC(18, 3) | 100.0% (+0.0%) | 2.3% (+0.0%) 
extra | NUMERIC(18, 3) | 100.0% (+0.0%) | 0.03% (+0.0%) 
mta_tax | NUMERIC(18, 3) | 100.0% (+0.0%) | 0.0% (+0.0%) 
tip_amount | NUMERIC(18, 3) | 100.0% (+0.0%) | 1.43% (+0.0%) 
tolls_amount | NUMERIC(18, 3) | 100.0% (+0.0%) | 0.11% (+0.0%) 
ehail_fee | NUMERIC(18, 3) | 95.68% (+0.0%) | 0.0% (+0.0%) 
improvement_surcharge | NUMERIC(18, 3) | 100.0% (+0.0%) | 0.0% (+0.0%) 
total_amount | NUMERIC(18, 3) | 100.0% (+0.0%) | 4.19% (+0.0%) 
payment_type | INTEGER | 98.83% (+0.0%) | 0.0% (+0.0%) 
payment_type_description | VARCHAR | 95.7% (+0.0%) | 0.0% (+0.0%) 
congestion_surcharge | NUMERIC(18, 3) | 95.7% (+0.0%) | 0.0% (+0.0%) 

</details>
<details>
<summary>dm_monthly_zone_statistics</summary>

Column | Type | Valid % | Distinct %
--- | --- | --- | ---
revenue_zone | VARCHAR | 100.0% (+0.0%) | 4.3% (+0.0%) 
revenue_month | DATE | 100.0% (+0.0%) | 0.68% (+0.0%) 
service_type | VARCHAR | 100.0% (+0.0%) | 0.04% (+0.0%) 
revenue_monthly_fare | NUMERIC(38, 3) | 100.0% (+0.0%) | 60.15% (+0.0%) 
revenue_monthly_extra | NUMERIC(38, 3) | 100.0% (+0.0%) | 9.16% (+0.0%) 
revenue_monthly_mta_tax | NUMERIC(38, 3) | 100.0% (+0.0%) | 3.8% (+0.0%) 
revenue_monthly_tip_amount | NUMERIC(38, 3) | 100.0% (+0.0%) | 43.76% (+0.0%) 
revenue_monthly_tolls_amount | NUMERIC(38, 3) | 100.0% (+0.0%) | 4.48% (+0.0%) 
revenue_monthly_ehail_fee | NUMERIC(38, 3) | 68.41% (+0.0%) | 0.03% (+0.0%) 
revenue_monthly_improvement_surcharge | NUMERIC(38, 3) | 100.0% (+0.0%) | 3.79% (+0.0%) 
revenue_monthly_total_amount | NUMERIC(38, 3) | 100.0% (+0.0%) | 74.51% (+0.0%) 
revenue_monthly_congestion_surcharge | NUMERIC(38, 3) | 76.12% (+0.0%) | 5.02% (+0.0%) 
total_monthly_trips | BIGINT | 100.0% (+0.0%) | 3.68% (+0.0%) 
avg_montly_passenger_count | DOUBLE_PRECISION | 76.12% (+0.0%) | 19.76% (+0.0%) 
avg_montly_trip_distance | DOUBLE_PRECISION | 100.0% (+0.0%) | 68.16% (+0.0%) 

</details>
<details>
<summary>dm_monthly_zone_revenue</summary>

Column | Type | Valid % | Distinct %
--- | --- | --- | ---
revenue_zone | VARCHAR | 100.0% (+0.0%) | 4.3% (+0.0%) 
revenue_month | DATE | 100.0% (+0.0%) | 0.68% (+0.0%) 
service_type | VARCHAR | 100.0% (+0.0%) | 0.04% (+0.0%) 
revenue_monthly_fare | NUMERIC(38, 3) | 100.0% (+0.0%) | 60.15% (+0.0%) 
revenue_monthly_extra | NUMERIC(38, 3) | 100.0% (+0.0%) | 9.16% (+0.0%) 
revenue_monthly_mta_tax | NUMERIC(38, 3) | 100.0% (+0.0%) | 3.8% (+0.0%) 
revenue_monthly_tip_amount | NUMERIC(38, 3) | 100.0% (+0.0%) | 43.76% (+0.0%) 
revenue_monthly_tolls_amount | NUMERIC(38, 3) | 100.0% (+0.0%) | 4.48% (+0.0%) 
revenue_monthly_ehail_fee | NUMERIC(38, 3) | 68.41% (+0.0%) | 0.03% (+0.0%) 
revenue_monthly_improvement_surcharge | NUMERIC(38, 3) | 100.0% (+0.0%) | 3.79% (+0.0%) 
revenue_monthly_total_amount | NUMERIC(38, 3) | 100.0% (+0.0%) | 74.51% (+0.0%) 
revenue_monthly_congestion_surcharge | NUMERIC(38, 3) | 76.12% (+0.0%) | 5.02% (+0.0%) 

</details>
</blockquote></details><details>
<summary>Metrics Summary (metric changed=3)</summary>
<blockquote>

<details>
<summary>Average Distance (Monthly) (!)</summary>

Date_month | Base | Target | -/+ 
:-: | :-: | :-: | :-: 
2023-03-01 | - | - | 
2023-02-01 | - | - | -
2023-01-01 | - | - | -
2022-12-01 | - | - | -
2022-11-01 | - | - | -
2022-10-01 | 3.6001666666666665 | 2.061907284768212 | -1.5382593818984547
2022-09-01 | 3.519299442033478 | 2.0306399700598803 | -1.4886594719735977
2022-08-01 | 3.5632715447154473 | 2.0617773359840954 | -1.5014942087313519
2022-07-01 | 3.5327770780856422 | 2.0961170212765956 | -1.4366600568090466
2022-06-01 | 3.44476821192053 | 2.075323859881031 | -1.369444352039499
2022-05-01 | 3.464009394860459 | 2.0755563047875927 | -1.3884530900728662
2022-04-01 | 3.3701899441340784 | 2.0986181575433913 | -1.271571786590687
2022-03-01 | 3.314434311769735 | 2.0260393353679214 | -1.2883949764018134
</details>
<details>
<summary>Average Distance (Quarterly) (!)</summary>

Date_quarter | Base | Target | -/+ 
:-: | :-: | :-: | :-: 
2023-01-01 | - | - | 
2022-10-01 | 3.6001666666666665 | 2.061907284768212 | -1.5382593818984547
2022-07-01 | 3.5380837817874853 | 2.062695996930554 | -1.4753877848569315
2022-04-01 | 3.426533308694447 | 2.083165331553182 | -1.343367977141265
2022-01-01 | 8.436418594256342 | 8.174650979361115 | -0.26176761489522704
2021-10-01 | 6.2662874771040205 | 2.0382949308755762 | -4.227992546228444
2021-07-01 | 4.3557348314606745 | 2.107191328934967 | -2.2485435025257074
2021-04-01 | 14.733777777777778 | 2.0432425321157717 | -12.690535245662007
2021-01-01 | 2.882855313700384 | 1.9180055541529917 | -0.9648497595473924
2020-10-01 | 2.8030404984423676 | 1.8671488521352753 | -0.9358916463070923
2020-07-01 | 3.1629169193450575 | 1.9882053231939163 | -1.1747115961511412
2020-04-01 | 3.589078850405306 | 2.1134919028340082 | -1.4755869475712977
2020-01-01 | 2.868499880753637 | 1.8649236285406956 | -1.0035762522129414
</details>
<details>
<summary>Average Distance (Yearly) (!)</summary>

Date_year | Base | Target | -/+ 
:-: | :-: | :-: | :-: 
2023-01-01 | - | - | 
2022-01-01 | 4.840314503631226 | 3.764060654662098 | -1.0762538489691278
2021-01-01 | 7.2654188315802815 | 2.040827773380075 | -5.224591058200207
2020-01-01 | 2.9307522292508192 | 1.8917039881558249 | -1.0390482410949944
2019-01-01 | 2.9279728332069226 | 1.8291329625884731 | -1.0988398706184495
2018-01-01 | - | - | -
2017-01-01 | - | - | -
2016-01-01 | - | - | -
2015-01-01 | - | - | -
2014-01-01 | - | - | -
2013-01-01 | - | - | -
</details>
</blockquote></details>