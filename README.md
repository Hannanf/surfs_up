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

![image](https://user-images.githubusercontent.com/103878061/197919517-2f8d969d-7b62-4e5a-ae1e-29fdcb0c7c9b.png)

Figure 1-- 10 sample datapoints of June temperature

![image](https://user-images.githubusercontent.com/103878061/197919616-4075ccc0-4893-47e2-bb86-9e57457dc5de.png)

Figure 2-- Statistical analysis performed on June temperatures using the .decribe() method

![image](https://user-images.githubusercontent.com/103878061/197919554-846a1c9a-a2be-480c-b199-072e48bc8237.png)

Figure 3-- 10 sample datapoints of December temperatures

![image](https://user-images.githubusercontent.com/103878061/197919643-487b4ef3-e0e6-495f-82d8-3a03a9beb55e.png)

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

![image](https://user-images.githubusercontent.com/103878061/197919696-7c191e53-ac0c-4fec-ab41-1c3e5218fac5.png)

Figure 5-- 10 sample datapoints of June precipitation

![image](https://user-images.githubusercontent.com/103878061/197919795-fc813b54-679c-46d8-b0db-9380ac901156.png)

Figure 6-- Statistical analysis performed on June precipitation using the .decribe() method

![image](https://user-images.githubusercontent.com/103878061/197919827-b4c8d3dc-705f-49c7-95bb-c04f4ca1925a.png)

Figure 7-- 10 sample datapoints of December precipitation

![image](https://user-images.githubusercontent.com/103878061/197919865-59f4ac34-9ab3-4b25-9d37-e8134f1ff997.png)

Figure 8-- Statistical analysis performed on December precipitation using the .decribe() method
______________________________________________________________________
