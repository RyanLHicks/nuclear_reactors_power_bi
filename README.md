# Nuclear Reactor Analysis - Power BI
[Power BI link](https://app.powerbi.com/links/dbK-xRd6Et?ctid=34b14805-261a-4b4f-996f-842e8a731db2&pbi_source=linkShare&bookmarkGuid=d3e605d1-68af-47d8-8df5-ab91d22f3c0c)
## Introduction
![PBIDesktop_TJFIM2LRtC](https://github.com/user-attachments/assets/dc7ae728-fd4d-4cda-b9e2-51520d31dc0e)

### Background
- This nuclear reactor analysis is part of a 4 part learning journey so I can effictively learn top programs used by data analysts. This section mainly focuses on visualization and presentation of data through graphs and statistics. I pinpoint certain metrics to get a good picture of the nuclear reactor landscape by using Power BI as a tool for storytelling and insights. I chose nuclear power as a subject because it's extremly intriguing and I believe that it's the future of energy that most countries will adopt. I will show key metrics through recent years to back up my claim.  
### Goals
1. Understand the nuclear reactor types and occurance
2. Uncover common reactor models
3. Find out where this reactors are located
4. Understand the past nuclear energy to look forward to the future. 
### Plan
- I will import all the data from the IAEA from my postgreSQL server database.
- Use various visualizations from Power BI to see the data.
- Interpret the data based on the tools used in Power BI and draw conclusions.

## Procedure

### Introduction Page

  <img width="1285" height="729" alt="image" src="https://github.com/user-attachments/assets/36845fd7-f062-42bd-bee3-ab2bd51d3856" />

#### Graphs and Data

- Slicers that allow multiple variables to be manipulated giving options such as 'all', 'operational', and 'shutdown' reactors; desired year(s) or country(s)

  <img width="845" height="114" alt="image" src="https://github.com/user-attachments/assets/9a8d93d1-01a6-4774-97e8-fb37a8c8df61" />

- Quick facts about the whole nuclear reactor landscape or desired changes as listed in the slicers above. Shows how many total reactors, the count of unique reactor types, net and median energy output in Mega Watts Electrical (MWE).

  <img width="1289" height="130" alt="image" src="https://github.com/user-attachments/assets/6a00a084-22df-4b80-b029-df6f0bce6b1c" />

- More general facts about where the majority of nuclear reactors are distributed by country,  the count by each reactor type, how much energy each country outputs currently, and how much energy each reactor type outputs on average.

  <img width="1282" height="261" alt="image" src="https://github.com/user-attachments/assets/e224229c-0cdb-41c3-b085-d84de1b4856b" />

- Two line graphs to visualize the energy added each year and the reactor types added each year since 1954 for all reactors or 1969 for current operational reactors.

  <img width="1301" height="221" alt="image" src="https://github.com/user-attachments/assets/6dd9eec4-b377-4182-8926-7cf64253dd4a" />

#### Intrepretation
- There are 412 active nuclear reactors and 209 deactivated reactors.
- Currently 7 unique operational reactor types and 11 accounting for the shutdown reactors.
- 370K MWE of energy output and 105k MWE equivalent energy shutdown.
- Median energy output for all operational reactors is 950MWE per reactor.
- The USA, France and China have the most current nuclear reactors and total energy output.
- Though Pressurized Water Reactors (PWRs) are the most common type, boiling Water Reactors seem to be the most effiecent type of reactor.
- In 1985, we saw the most energy added in nuclear energy along with PWR addition.

### Nuclear Reactor Types

<img width="1282" height="727" alt="image" src="https://github.com/user-attachments/assets/d1d74313-5f5d-46bb-8bc8-77a0431a35c6" />

#### Graphs and Data

- Slicers that give options for operational, shutdown, or all reactors. Tile section also allows the user to breakdown each reactor type and see multiple or individual statistics.

<img width="838" height="245" alt="image" src="https://github.com/user-attachments/assets/bd2d1d62-d926-434d-813d-8e775050c312" />

- This section breaks down the selected reactor type into countries involved, total reactors, total and median output for selected reactor types.

<img width="1297" height="264" alt="image" src="https://github.com/user-attachments/assets/89dc5a48-f45c-4c3c-9a74-78b2b1ecf222" />

- The final section breaks down the distribution for reactor types into a bar and pie chart.

<img width="1298" height="224" alt="image" src="https://github.com/user-attachments/assets/df7b043e-3674-46e7-96ec-56cf1b0b1da5" />

#### Intrepretation

If we use operational PWRs as an example, we can see that:
- 28 countries are involved
- 303 are currently operational
- They produce 290K MWE and on average produce 986 MWE per reactor

### Nuclear Reactor Models

<img width="1286" height="727" alt="image" src="https://github.com/user-attachments/assets/22f8f9f1-e1b0-4992-baa4-d7b929431d7b" />

#### Graphs and Data

- This section follows similar slicers from the previous section but the only difference is the model type for selectiability.

#### Intrepretation

If the VVER V-320 is selected, we can see that:
- 4 Countries use this model
- There are 25 total reactors
- It produces 24k MWE and averages about 950 MWE per reactor

### Nuclear Energy Countries

<img width="1307" height="729" alt="image" src="https://github.com/user-attachments/assets/b7a85670-d3d5-469e-9b1e-956355e08ecc" />

#### Graphs and Data

- This section follows similar slicers from the previous section but the only difference is the countries are now selectable.
  
#### Intrepretation

If operational USA reactors is selected, we can see that: 
- They have 92 total nuclear reactors, leading all the countries.
- Output 95k MWE and average 1125 MWE per reactor.


### Nuclear Reactor History

<img width="1302" height="728" alt="image" src="https://github.com/user-attachments/assets/faedf83a-cf81-480a-a212-30ca310c31f7" />

#### Graphs and Data

- This section follows similar slicers from the previous section but the only difference is the years are now selectable.
  
#### Intrepretation

If 1985 is selected without changing the status, we see that:
- 18 countries were involved.
- There was 40 total reactors built, which was the highest history has seen. If we switch over to operational we can see that 6 were taken offline when they were built in 1985.
- An output of 40K MWE and 981 MWE per reactor.

## Conclusion

### Skills Learned
- Power BI
- DAX
- Power Query
- Data control and insertion
- Git
- Github

### Reflection

### Sources


