# `coronaanalysis`
The first case of the 2019–20 coronavirus pandemic in India was reported on 30 January 2020, originating from China.
The country reported its first three cases in Kerala, all of whom were students who had returned from Wuhan, China.
The transmission escalated in the month of March, after several cases were reported all over the country, most of which were linked to people with a travel history to affected countries.

On 10 March, the total cases reached 50.
On 12 March, a 76-year-old man who had returned from Saudi Arabia became the first victim of the virus in the country. 
The total cases reached 100 on 15 March, 250 on 20 March and 500 on 24 March.The death toll reached 10 on 24 March.
The infection rate of COVID-19 in India is reported to be 1.7, which is remarkably lower than in the worst affected countries.
This disease does not have any medicine to cure,maintaing social distance is the only solution left.
Government of India announce lockdown in all the states from 25,march 2020 for 21 days.For more information [see here](https://en.wikipedia.org/wiki/2020_coronavirus_pandemic_in_India).

From available data,we can visualize how the virus infected population increase in last 55 days.
This analysis help us to **compare the count with respect to time and place**.This analytics help in visualizing **current situation** on map which help in **tracking corona cases all over India in real time.**
The data used in the analysis starts from first confirmed case record date i.e.,*30,jan 2020 to 23,march 2020*.More data can be added into it to keep it updated.The data used is available in csv format and also you can refer [link1](https://www.kaggle.com/sudalairajkumar/covid19-in-india), [link2](https://www.kaggle.com/imdevskp/covid19-corona-virus-india-dataset) and [link3](https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset).

Let us get into analytics to get more insights from the available data.
## `Data Description`
The data used for analysis has 9 columns:
* Sno--The serial number of record.                   
* Date--Date of record.                       
* State/UnionTerritory--State of record.        
* ConfirmedIndianNational--People count infected from virus and belongs to indian national.    
* ConfirmedForeignNational--People count infected from virus and belongs to foreign national.
* Cured--People count cured from virus.                       
* Deaths--People count died due to corona virus.                      
* Latitude--Latitude of state.                     
* Longitude--Longitude of state.    

#### `Note`:
The data used here is upto 23,march 2020 futher analysis performed on it.More data can be easily added to keep it update.***last date in analysis refer last record in data that is 23,march 2020 however the record change in future.***

## `Analysis`
- **Total confirmed case in india of indian national till last date?**
    - 451
- **Total confirmed case in india of foreign national till last date?**
    - 41
- **Total confirmed cases in india till last date?**
    - 492
- **Number of States infected due to corona virus?**
    - 23
- **Total Confirmed case in India on map to visualize state wise?**
    - <a href="https://ibb.co/s9Km13P"><img width='350' height='300' src="https://i.ibb.co/d4PWpKc/confirmmap.png" alt="confirmmap" border="0"></a>
    - pop up shows the state name and total confirmed cases count
- **Total Cured case in India on map to visualize state wise?**
    - <a href="https://ibb.co/YTBwCxL"><img width='350' height='300' src="https://i.ibb.co/93HSD7r/cured-map.png" alt="cured-map" border="0"></a>
    - pop up will display the total state wise count 
- **Total Death case in India on map to visualize state wise?**
    - <a href="https://imgbb.com/"><img width='350' height='300' src="https://i.ibb.co/X7gFY9D/deathmap.png" alt="deathmap" border="0"></a>
    - pop up will display the total state wise count
- **Which state has maximum active confirmed case till last date?**
    - Kerala
- **Number of confirmed case in highly infected state?**
    - 94
- **Which state has minimum infected case till last date?**
    - Chhattisgarh
- **Number of confirmed case in least infected state?**
    - 1
- **State wise confirmed case comparison to visualize all the states of India?**
    - <a href="https://ibb.co/QNsS57B"><img width='350' height='300' src="https://i.ibb.co/DC3cqPX/statewiseconfirmcasehist.png" alt="statewiseconfirmcasehist" border="0"></a>
    - X-axis refer to states in incresing order
    - Y-axis refer to confirmed case count.
- **State wise cured case comparison to visualize all the states of India?**
    - <a href="https://ibb.co/M8gDGMr"><img width='350' height='300' src="https://i.ibb.co/CJw5Mhg/statewisedeathcasehist.png" alt="statewisedeathcasehist" border="0"></a>
    - X-axis refer to states in incresing order
    - Y-axis refer to cured case count.
- **State wise death case comparison to visualize all the states of India?**
    - <a href="https://ibb.co/3kVqw7J"><img width='350' height='300' src="https://i.ibb.co/yVK1DX3/statewisecuredhist.png" alt="statewisecuredhist" border="0"></a>
    - X-axis refer to states in incresing order.
    - Y-axis refer to cured case count.
 - **Growth of confirmed case in India with time?**
     - <a href="https://ibb.co/HNsGkNV"><img width='350' height='300' src="https://i.ibb.co/B4xTS4t/confirmline.png" alt="confirmline" border="0"></a>
     - X-axis show the date from first case date.
     - Y-axis refer to count of confirm case.
 - **Cured case in India with time?**
     - <a href="https://ibb.co/MNYx2Dc"><img width='350' height='300' src="https://i.ibb.co/j4cP6vy/curedline.png" alt="curedline" border="0"></a>
     - X-axis show the date from first case date.
     - Y-axis refer to count of cured case.
 - **Death case in India with time?**
     - <a href="https://ibb.co/ZYxqgTM"><img width='350' height='300' src="https://i.ibb.co/txDV2CJ/deathline.png" alt="deathline" border="0"></a>
     - X-axis show the date from first case date.
     - Y-axis refer to count of death case.
 - **Growth of infected case in one state with respect to time such that the journey of corona virus in Maharashtra?**    
     - <a href="https://ibb.co/dkY7LYN"><img width='350' height='300' src="https://i.ibb.co/j3XHWXC/stateconfirmline.png" alt="stateconfirmline" border="0"></a>
 - **Compare the growth of infected case in all the states of India with respect to time?**
     - <a href="https://ibb.co/P6FwBYq"><img width='450' height='400' src="https://i.ibb.co/sVbyLP8/allhist.png" alt="allhist" border="0"></a>
 ## `Conclusion`
This is all analysis which can be performed on the available data.<br/>
 The above analysis is not just the few graphs it gives the complete information of count with respect to states.<br/>
 The severity in state can be found with respect to other states.<br/>
 State dealing the best by having maximum cured cases.<br/>
 State suffering the most by having the highest death case count.<br/>
 Confirmed cases vs date help to analyse how it is spreading in India.<br/>
 Cured case vs date help to know the cured time required.<br/>
 India confirmed case of all states vs date gives us the insights of its growth with time.<br/>
 **Hence,the above analysis can be maintain in real time by updating data to get the more insights.**
  
