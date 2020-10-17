
**Objective**: This task is intended to test
1. Thinking through the problem
2. Code quality
3. Code Performance

**Problem Statement**: larisights is a data visualization platform. The heart of data visualization tool is tables. 
We intend our tables to be top notch and smooth while loading 1000s of rows. We would like you to build a table which
can handle up to 1000 rows without hiccups. The table is expected to have the following:

1. Data should match the given API response.
2. Trends chart as to how the data modifies over time.
3. Total sum of all metrics in the column name.

![](https://i.imgur.com/VrXM3fU.png)

The given API response contains 4 metrics for 1000 campaigns. 
`aj_coh_0w_ios_real_acquisition`, `aj_app_and_installs`, `aj_app_ios_installs` and `aj_coh_0w_and_real_acquisition`. 
You are expected to display only 2 metrics `aj_app_and_installs`, `aj_coh_0w_and_real_acquisition` in your table.

API Response: https://clarisights-users.s3.eu-central-1.amazonaws.com/frontend- assignment/1000+items+table+response.json