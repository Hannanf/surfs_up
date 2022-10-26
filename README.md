<h2>Module 9 Challenge — Extracting Temperature Data for Specifiic Months using an .SQLITE File 
  </h2>
______________________________________________________________________
<h4>OVERVIEW OF MODULE 
</h4>
______________________________________________________________________
The main purpose of this module was to extract data from a .sqlite file. We created an engine to create a path to our database then used the session.query method to query our database and extract information without alterating the actual database. We extracted all of the temperatures from the months of June and December and created a DataFrame as seen in Figure 1 and 2. We then used the .decribe() method to run statistical anaysis of the temperture data as seen in Figure 3 and 4

______________________________________________________________________
<h4>RESULTS 
</h4>
______________________________________________________________________
Three key differences in weather between June and December:
<br>
<br>1) As seen in Figure 1 and 3. The avergae temperature in December is 71F and the avergae temperature in June is about 75F</br>
<br>2) As seen in Figure 1 and 3. The min temperature in December is 56F and the min temperature in June is about 64F. The max temperature in December is 83F and the max temperature in June is about 85F </br>
<br>3) As seen Figure 1 and 3 and supported by 2) the STD in december temperature is higher (3.74) than the STD in June temperature (3.26)

https://github.com/Hannanf/surfs_up/blob/main/Resources/sample_temp_june.png?raw=true
Figure 1-- 10 sample datapoints of June temperature

https://github.com/Hannanf/surfs_up/blob/main/Resources/sample_temp_dec.png?raw=true
Figure 2-- Statistical analysis performed on June temperatures using the .decribe() method

https://github.com/Hannanf/surfs_up/blob/main/Resources/analysis_temp_june.png?raw=true
Figure 3-- 10 sample datapoints of December temperatures

https://github.com/Hannanf/surfs_up/blob/main/Resources/analysis_temp_dec.png?raw=true
Figure 2-- Statistical analysis performed on December temperatures using the .decribe() method
______________________________________________________________________
<h4>SUMMARY
</h4>
______________________________________________________________________
MAIN SUMMARY:

Quering our database and performing statistical anysis of our data. We can determine that the average temperature in June is higher than in Decemeber. We also determined there is a greater variance in temperature in December than in June as seen by the difference in the STD 

2 ADDITIONAL QUERIES PERFORMED:
<br>1) As seen in figures 5 and 6 and in my code, I queried the database to determine the precipitation in June and Decemeber  </br>
<br>2) As seen in figures 7 and 8 and in my code, I used the .decribe() method to conduct simple statistical anysis of the precipitation in June and December  </br>

https://github.com/Hannanf/surfs_up/blob/main/Resources/prcp_june.png?raw=true
Figure 5-- 10 sample datapoints of June precipitation

https://github.com/Hannanf/surfs_up/blob/main/Resources/prcp_june_analysis.png?raw=true
Figure 6-- Statistical analysis performed on June precipitation using the .decribe() method

https://github.com/Hannanf/surfs_up/blob/main/Resources/prcp_dec.png?raw=true
Figure 7-- 10 sample datapoints of December precipitation

https://github.com/Hannanf/surfs_up/blob/main/Resources/prcp_june_analysis.png?raw=true
Figure 8-- Statistical analysis performed on December precipitation using the .decribe() method
______________________________________________________________________
