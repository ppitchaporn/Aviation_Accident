Mini Project: A 55-Year Overview of Aviation Accidents (1970-2025)  
[DADS5001: Data Analytics and Data Science Tools and Programming]
=======
## Introduction
Aviation has long been one of the most significant modes of transportation in modern society, offering speed, efficiency, and global connectivity. However, despite continuous advancements in technology and safety protocols, aviation accidents still occur. 

This study examines the trends and patterns of aviation accidents over the past 55 years, with a particular focus on the United States and a comparative analysis of commercial aviation accidents. The structure of the analysis is outlined as follows.

Part 1 – Overview of Global Aviation Accidents

Part 2 - U.S. Aviation Accident Insights

Part 3 - Comparative Study of Commercial Aviation Accident Trends

## Data Source
https://www.ntsb.gov/Pages/home.aspx Data for this analysis was obtained from the National Transportation Safety Board (NTSB), an independent U.S. government agency responsible for investigating civil transportation accidents.

## Research Questions
1. Is the frequency of aviation accidents increasing or decreasing over time?
2. Human error remains the leading cause of aviation accidents?
3. Has the safety of commercial air travel improved based on fatal accident rates over time?

## • Part 1 - Overview of Global Aviation Accidents in 1970-2025
A high-level view of accident trends and severity levels.

![image](https://github.com/PTUNTUK/Aviation_Accident_Graphs/blob/main/figure_1_accidents_trend.png) 
***Figure 1: Trends in Aviation Accidents (1970-2025)***  
The figure shows a steady downward trend in aviation accidents over time, with the red horizontal line (≈952) highlighting the average number of accidents per year.
-  	1970s–1980s: High accident rates, often above 1,500/year. This may reflects rapid aviation growth during that era, alongside less advanced safety regulations and technology.
-  	1985s onward: Gradual decrease due to improvements in aircraft design, maintenance procedures, and the implementation of stricter safety protocols.
-  	2001: A decline follows the 9/11 attacks, prompting stricter aviation security and regulations.
-  	2020: Sharp drop during COVID-19 due to fewer flights.


![image](https://github.com/PTUNTUK/Aviation_Accident_Graphs/blob/main/figure_2_injury_severity.png)
***Figure 2: Injury Severity in Aviation Accidents by Year***  
The figure presents yearly aviation injury counts, divided by severity—fatal, serious, and minor. It highlights a consistent decrease in injuries, especially after the late 1970s. Fatal injuries consistently represent the largest share but show substantial declines alongside other categories, reflecting advancements in aviation safety, technology, and emergency responses.

**1977-1979**  
-  Tenerife Airport Disaster (1977): Two Boeing 747s collided on the runway in heavy fog, killing 583 people.
-  Malaysian Airline System Flight 653 (1977): A hijacked Boeing 737 crashed, resulting in 100 fatalities.
-  American Airlines Flight 191 (1979): A DC-10 crashed shortly after takeoff in Chicago, killing all 273 onboard.

**1996**  
-  Mid-Air Collision Over India : A Saudi Arabian Airlines Boeing 747 collided with a Kazakhstan Airlines Ilyushin Il-76, leading to 349 deaths.
-  TWA Flight 800: A Boeing 747-100 exploded mid-air due to a fuel tank explosion, killing all 230 onboard.
-   harkhi Dadri Mid-Air Collision: A Saudi Arabian Airlines Boeing 747 collided with a Kazakhstan Airlines Ilyushin Il-76, causing 349 deaths.


![image](https://github.com/PTUNTUK/Aviation_Accident_Graphs/blob/main/figure_3_accidents_continent.png)
***Figure 3: Global Distribution of Aviation Accidents by Continent***  
This figure shows the geographic distribution of aviation accidents across continents.  **North America and Europe** appear to have the highest concentration of accidents, especially in the United States and Western Europe.  **Africa and South America** also show significant incident clusters. **Asia and Oceania** show widespread but relatively less dense occurrences. Some points remain unclassified due to missing or ambiguous location data.


![image](https://github.com/PTUNTUK/Aviation_Accident_Graphs/blob/main/figure_4_probable_causes.png)
***Figure 4: Probable Causes of Aviation Accidents***  
This figure presents a textual analysis of the probable causes of aviation accidents using two visualizations:  

**-  Word Cloud**: The word cloud highlights the most common terms found in accident reports' "Probable Cause" sections. The size of each word reflects how often it appears—larger words like pilot, failure, engine, maintain, and loss indicate they are mentioned frequently across reports.  
**-  Bar Chart**: Shows the frequency of selected keywords, revealing that "pilot" is the most common cause-related term, followed by "engine", "control", "fuel", and "weather". These keywords represent critical areas contributing to aviation accidents, suggesting that human factors, mechanical issues, and environmental conditions are leading contributors.  

Overall, this figure emphasizes the importance of pilot performance, equipment maintenance, and operational environment in aviation safety.


![image](https://github.com/PTUNTUK/Aviation_Accident_Graphs/blob/main/figure_5_top5_countries.png)
***Figure 5: Top 5 Countries by Injury Level***  
This figure shows the top five countries with the most aviation accidents by injury severity (fatal, serious, and minor). The U.S. leads with over 50,000 incidents, while Brazil, Mexico, Canada, and the Bahamas each report under 300. The logarithmic scale helps enable better comparison by compressing the wide range of values, making it easier to observe the injury level distribution across all five countries.


## • Part 2 - U.S. Aviation Accident Insights
A focused analysis on aviation accidents occurring in the United States, including geographic distribution, injury severity and types of aircraft involved.

***Part 2: U.S. Aviation Accident Insights***  

  This section explores where and how aviation accidents occur across the United States.
Some states, like California, Texas, Alaska, and Florida, report significantly more incidents. 
This may reflect their large size, busy skies, or unique flying conditions—especially in places like Alaska, where air travel is often essential.

  Non-commercial flights account for the majority of aircraft damage, especially in substantial and destroyed categories. 
In contrast, commercial flights show far fewer incidents, but still deserve close attention.

  Interestingly, most accidents happen in good weather, under clear skies and visual flight rules. 
This suggests that visibility alone doesn’t guarantee safety.

  State-level comparisons show different mixes of commercial and non-commercial incidents, 
while certain aircraft manufacturers—such as Cessna and Piper—appear more often in pilot-related accidents.

  Finally, takeoff and landing remain risky phases of flight. A handful of airports, including BETHEL and LAGUARDIA, show higher accident counts during these moments.
Together, these patterns offer valuable insight into the factors shaping aviation safety in the U.S.—inviting further exploration, not conclusions.

![Geographic Distribution of Aviation Accidents in the US (1970–2025)](https://github.com/user-attachments/assets/0e88572d-e482-4261-acbb-7ba90b3df88d)
***Figure 6: Geographic Distribution of Aviation Accidents in U.S. States***  

  Between 1970 and 2025, California, Texas, Alaska, and Florida reported the highest number of aviation accidents.
These states have large land areas, busy air traffic, and major population hubs.

![Aircraft Damage Types by Flight Type (US 1970–2025)](https://github.com/user-attachments/assets/c1e6ec86-2406-452f-babc-f7ba8d914bb7)

![Aircraft Damage (Top 10 US States by Flight Type](https://github.com/user-attachments/assets/eee94b4a-a1dc-4964-b197-b9fc0916d916)
***Figure 7: Top 5 U.S. States by Damage Types***  

  Most aircraft damage incidents in the U.S. involve non-commercial flights, especially under “Substantial” and “Destroyed” categories.
States like California, Alaska, and Texas report the highest numbers, likely due to their high general aviation activity.
  In contrast, commercial flights show significantly fewer damage cases across all states.

![Weather Conditions in US Aviation Accidents](https://github.com/user-attachments/assets/dcc4be7b-6ef8-414a-b794-0d1a44da6443)
***Figure 8: U.S. Aviation Accidents by Weather Condition***  

  The majority of aviation accidents in the U.S. occurred under VMC (Visual Meteorological Conditions) and 
VFR (Visual Flight Rules)—conditions generally considered safe with clear skies and good visibility.

  This suggests that even in favorable weather, human error or other operational issues can still lead to accidents.
  In contrast, accidents under IMC (Instrument Meteorological Conditions) and IFR (Instrument Flight Rules)—which involve reduced visibility and reliance on instruments—were less frequent, though these situations demand higher pilot skill and precision.

Abbreviations shown in the chart:
• VMC – Visual Meteorological Conditions
    Visibility and clouds are clear, allowing flight by visual reference.

• VFR – Visual Flight Rules
    Flight without assistance from ATC, typically in good weather, though with stricter visual requirements.

• IMC – Instrument Meteorological Conditions
    Visibility is restricted, requiring pilots to fly using instruments for safety.

• IFR – Instrument Flight Rules
    Flight planned and conducted in controlled airspace using instruments, with strict separation and weather minimums.

![Top 5 Aircraft Manufacturers in Pilot-Related Accidents (US Commercial Flights)](https://github.com/user-attachments/assets/a9882d4f-68c6-4ff5-8ef7-3b7b2fb1328b)
***Figure 9: Top 5 Aircraft Manufacturers in Pilot-Related Accidents (US Commercial Flights)***  

  Cessna leads in pilot-related accidents, followed by Piper and Beech. 
These manufacturers are commonly used for smaller commercial operations and pilot training. 
  In contrast, larger manufacturers like Boeing appear less often, likely reflecting differences in aircraft size and usage.


![Top 5 US Airports with Most Takeoff and Landing Accidents (Commercial Flights)](https://github.com/user-attachments/assets/66aa55d9-f150-4a4d-878f-6d0bf1b9c598)
***Figure 10: Top 5 Airports with Most Takeoff and Landing Accidents (Commercial Flights)***  

  Bethel (Alaska) reports the highest number of takeoff and landing accidents, followed by airports like LaGuardia and Nashville International.
These incidents highlight where flight operations during takeoff and landing may involve greater risk.




## • Part 3 - Comparative Study of Commercial Aviation Accident Trends
A comparison of accident frequency relative to the number of commercial flights per year to assess risk per flight activity.

***Figure 10: Commercial Flight Trends***  
xxxx  

***Figure 11: Figure 9: Accident Rate (5 Year moving average)***  
xxxx  

***Figure 12: Total passenger***  
xxxx  

***Figure 13: Fatal Rate***  
xxxx  

***Figure 14: Root Cause Analysis of Commercial Aviation Accidents***  
xxxx  

## • Summary of Findings
1. Is the frequency of aviation accidents increasing or decreasing over time?
Ans:

2. Human error remains the leading cause of aviation accidents?
Ans:

3. Has the safety of commercial air travel improved based on fatal accident rates over time?
Ans:

>>>>>>> master
