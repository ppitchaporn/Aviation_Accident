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
This section provides an overall view of aviation accidents over the past five decades.

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
This section explores where, when, and how aviation accidents happen in the United States, with a focus on factors like geography, weather, flight phase, and aircraft type.

**Where in the U.S. do aviation accidents occur most often?**

![Figure6](https://github.com/user-attachments/assets/5066809d-4351-4802-aeea-691151b1d4d9)
***Figure 6: Geographic Distribution of Aviation Accidents in U.S. States***  
This map provides a snapshot of aviation accident patterns between 1970 and 2025, helping us explore where accidents are most common.
- States like California, Texas, Florida, and Alaska report the highest number of accidents.
- Central and northeastern states tend to show much lower counts.

These high numbers may reflect more flight activity and larger general aviation fleets in populous or tourism-heavy states like California and Florida.

**What patterns stand out?**

![Figure7-1](https://github.com/user-attachments/assets/73206a8a-f0d5-4bbe-a3f0-8baa2e652019)
***Figure 7-1: Top 10 U.S. States by Aircraft Damage***  
This bar chart highlights the states with the most aircraft damage incidents.
- Most of these incidents involve non-commercial flights, with Alaska showing a relatively higher count for commercial ones.


**What kind of damage is most common?**

![Figure7-2](https://github.com/user-attachments/assets/53732c4a-d6c3-4999-82c3-90d5a6d15a84)
***Figure 7-2: Aircraft Damage Types and Injury Severity Levels in U.S. Flights*** 
This dual chart explores both damage categories and injury severity.
- Substantial and destroyed damage types dominate.
- Again, non-commercial flights lead significantly in both categories.

**How severe are these accidents?**
- Fatal injuries are the most reported, especially in non-commercial operations.
- Commercial flights show far fewer incidents in every category.


**What kind of weather are most accidents happening in?**

![Figure8](https://github.com/user-attachments/assets/5c969774-5b38-4c69-a231-e861c0a74997)
***Figure 8: U.S. Aviation Accidents by Weather Condition***  
This chart shows how accidents break down by weather and flight condition.

**Abbreviations Explained**

| Abbreviation | Meaning                        | Description                                                                 |
|--------------|--------------------------------|-----------------------------------------------------------------------------|
| **VMC**      | Visual Meteorological Conditions | Clear skies and good visibility; pilots fly by sight.                        |
| **VFR**      | Visual Flight Rules             | Flying by visual reference, typically in good weather, without ATC guidance. |
| **IMC**      | Instrument Meteorological Conditions | Low visibility; pilots must navigate using flight instruments.              |
| **IFR**      | Instrument Flight Rules         | Flying under instrument navigation, usually in poor weather or low visibility. |

- Surprisingly, most accidents occur under VMC (Visual Meteorological Conditions) — clear skies and good visibility.
  
**Why it matters:**
Accidents happening in good weather suggest that visibility isn’t the main factor — rather, it may be pilot error, mechanical failure, or operational misjudgment during routine conditions.

**Which aircraft manufacturers appear most in pilot-related accidents?**

![Figure9](https://github.com/user-attachments/assets/ac98d630-fe14-4e9f-9b6e-ba80ae27bd88)
***Figure 9: Top 5 Aircraft Manufacturers in Pilot-Related Accidents (U.S. Commercial Flights)***  
This chart ranks manufacturers by their involvement in pilot-related commercial accidents.
- Cessna stands out with the highest number of pilot-related accidents in U.S. commercial flights.
- Piper and Beech follow at a distance, with Boeing and De Havilland also making the list.

**Why Cessna?**
Cessna aircraft are widely used in training, private flying, and smaller commercial ops — so their high count likely reflects exposure more than a design flaw.

**Do different airport face different risks?**

![Figure10-1](https://github.com/user-attachments/assets/1521bdaa-79a6-4340-b569-fa4b8439c266)
***Figure 10-1: Top 5 Airports with Most Takeoff and Landing Accidents (Commercial Flights)***  
This chart visualizes accident counts at key airports during takeoff and landing phases in commercial aviation.

![Figure10-2](https://github.com/user-attachments/assets/53054067-1118-4f40-8bff-43c1bbd25c0e)
***Figure 10-2: Top 5 Airports with Most Takeoff and Landing Accidents (์Non-Commercial Flights)***  
This plot focuses on non-commercial aviation activity and related accidents at smaller airports.
- Commercial flights show accidents clustered in regional hubs like Bethel (Alaska) and LaGuardia (New York)—often with fairly balanced counts between takeoff and landing.
- Non-commercial flights, however, concentrate around smaller general aviation airports like Big Bear City, Camarillo, and Catalina (California), with landing accidents more frequent than takeoff.

**Insight:** Non-commercial airports have significantly more landing accidents, possibly due to less advanced runway infrastructure, pilot training levels, or traffic control limitations.
**Contrast:** Commercial airports show fewer incidents, likely due to stricter procedures, better maintenance, and professional pilots.

## • Part 3 - Comparative Study of Commercial Aviation Accident Trends
A comparison of accident frequency relative to the number of commercial flights per year to assess risk per flight activity.

![image](https://github.com/suparerkjk/Commercial-Accident/blob/main/flight_trends.png?raw=true)  
***Figure 11: US Commercial Flight Trends***  
- Before 2020: Relatively stable with a gradual decline; peaked at approximately 11.3M and leveled off around 10M flights annually.
- 2020: Significant decrease to 5.8M flights, due to the COVID-19 pandemic.
- After 2020: Consistent recovery observed, with flight numbers rising to 9.7M by 2024.

![image](https://github.com/suparerkjk/Commercial-Accident/blob/main/passengers_trends.png?raw=true)
***Figure 12: US Passengers Trends***
- Before 2020: Steady growth from 701M in 2003 to 1053M in 2019, with minor fluctuations.
- 2020: Sharp drop to 401M passengers due to the COVID-19 pandemic.
- After 2020: Strong rebound, reaching 1106M passengers by 2024, surpassing pre-pandemic levels.

  Although flight volume hasn’t fully returned to pre-pandemic levels, passenger numbers have exceeded them. This suggests higher passenger load per flight, indicating better airline efficiency or a shift toward fuller, larger aircraft post-COVID.
  
![image](https://github.com/suparerkjk/Commercial-Accident/blob/main/fatal_accident_MA.png?raw=true)
***Figure 13: Fatal Accidents in Commercial and Non-Commercial Aviation (Moving Average)***  
- The safety gap between commercial and non-commercial flights has widened significantly over the past few decades.
- Non-commercial aviation, while improving, still poses greater safety risks and accounts for most fatalities.
- Commercial aviation is now extremely safe, with fatal accidents becoming increasingly rare.
- Improvements in technology, regulations, and pilot training likely played major roles in reducing both trends, but have had a more dramatic effect in commercial aviation.

![image](https://github.com/suparerkjk/Commercial-Accident/blob/main/fatal_rate_MA.png?raw=true)
***Figure 14: Fatal injury rate for commercial flights in the US***  

***Figure 15: Root Cause Analysis of Commercial Aviation Accidents***   

## • Summary of Findings
1. Is the frequency of aviation accidents increasing or decreasing over time?
Ans:

2. Human error remains the leading cause of aviation accidents?
Ans:

3. Has the safety of commercial air travel improved based on fatal accident rates over time?
Ans:

>>>>>>> master
