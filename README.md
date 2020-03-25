# `coronaanalysis`
The first case of the 2019–20 coronavirus pandemic in India was reported on January 30,2020, originating from China.
The country reported its first three cases in Kerala, all of whom were students who had returned from Wuhan, China.
The transmission escalated in the month of March, after several cases were reported all over the country, most of which were linked to people with a travel history to affected countries.

On 10th March, the total cases reached 50.
On 12th March, a 76-year-old man who had returned from Saudi Arabia became the first victim of the virus in the country. 
The total cases reached 100 on 15th March, 250 on 20th March and 500 on 24th March.The death toll reached 10 on 24th March.
The infection rate of COVID-19 in India is reported to be 1.7, which is remarkably lower than in the worst affected countries.
Currently,there is no vaccination or medicine available for this disease so maintaing social distance is the only solution left.
To limit the spread of virus government of India announced lockdown in all states and union territories from 25th march 2020 for 21 days.For more information [see here](https://en.wikipedia.org/wiki/2020_coronavirus_pandemic_in_India).

From available data,we can visualize how the virus infected population increased in last 55 days.
This analysis will help us to **compare the count with respect to time and place**.This analysis helps us in visualizing **current situation** on map which will help in **tracking corona virus affected cases all over India in real time.**
The data used in the analysis starts from first confirmed case record date i.e.,*30 Jan 2020 to 23 March 2020*.To keep analysis up to date and accurate more data can be added into it.The data used in repo is represented in csv format(you can also refer [link1](https://www.kaggle.com/sudalairajkumar/covid19-in-india), [link2](https://www.kaggle.com/imdevskp/covid19-corona-virus-india-dataset) and [link3](https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset)).

Let us get into analysis to get more insights from available data.
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
The data used here is upto 23rd march 2020 futher analysis performed on this data.More data can be easily added to keep it up to date.***last date in analysis refer last record in data that is 23rd march 2020, however the record will change in future.***

## `Analysis`
- **Total confirmed cases in india of indian national till last date?**
    - 451
- **Total confirmed cases in india of foreign national till last date?**
    - 41
- **Total confirmed cases in india till last date?**
    - 492
- **Number of States infected due to corona virus?**
    - 23
- **State wise representation of total confirmed cases in India on map:**
    - <a href="https://ibb.co/s9Km13P"><img width='350' height='300' src="https://i.ibb.co/d4PWpKc/confirmmap.png" alt="confirmmap" border="0"></a>
    - pop up shows the state name and count of total confirmed cases.
- **State wise representation of total cured cases in India on map:**
    - <a href="https://ibb.co/YTBwCxL"><img width='350' height='300' src="https://i.ibb.co/93HSD7r/cured-map.png" alt="cured-map" border="0"></a>
    - pop up will display the total state wise count. 
- **State wise representation of total death cases in India on map:**
    - <a href="https://imgbb.com/"><img width='350' height='300' src="https://i.ibb.co/X7gFY9D/deathmap.png" alt="deathmap" border="0"></a>
    - pop up will display the total state wise count.
- **Which state has maximum active confirmed cases till last date?**
    - Kerala
- **Number of confirmed cases in highly infected state?**
    - 94
- **Which state has minimum active confirmed cases till last date?**
    - Chhattisgarh
- **Number of confirmed cases in least infected state?**
    - 1
- **State wise comparison of total confirmed cases all over India**
    - <a href="https://ibb.co/QNsS57B"><img width='350' height='300' src="https://i.ibb.co/DC3cqPX/statewiseconfirmcasehist.png" alt="statewiseconfirmcasehist" border="0"></a>
    - X-axis refer to states in increasing order
    - Y-axis refer to count of confirmed cases.
- **State wise comparison of total cured cases all over India**
    - <a href="https://ibb.co/M8gDGMr"><img width='350' height='300' src="https://i.ibb.co/CJw5Mhg/statewisedeathcasehist.png" alt="statewisedeathcasehist" border="0"></a>
    - X-axis refer to states in increasing order
    - Y-axis refer to count cured cases.
- **State wise comparison of total death cases all over India**
    - <a href="https://ibb.co/3kVqw7J"><img width='350' height='300' src="https://i.ibb.co/yVK1DX3/statewisecuredhist.png" alt="statewisecuredhist" border="0"></a>
    - X-axis refer to states in increasing order.
    - Y-axis refer to count cured cases.
 - **Growth of number of confirmed cases in India with respect to time**
     - <a href="https://ibb.co/HNsGkNV"><img width='350' height='300' src="https://i.ibb.co/B4xTS4t/confirmline.png" alt="confirmline" border="0"></a>
     
 - **Cured cases in India with respect to time**
     - <a href="https://ibb.co/MNYx2Dc"><img width='350' height='300' src="https://i.ibb.co/j4cP6vy/curedline.png" alt="curedline" border="0"></a>

 - **Death cases in India with respect to time?**
     - <a href="https://ibb.co/ZYxqgTM"><img width='350' height='300' src="https://i.ibb.co/txDV2CJ/deathline.png" alt="deathline" border="0"></a>

 - **Growth of confirmed cases in one state with respect to time(e.g Maharashtra)**    
     - <a href="https://ibb.co/dkY7LYN"><img width='350' height='300' src="https://i.ibb.co/j3XHWXC/stateconfirmline.png" alt="stateconfirmline" border="0"></a>
     
 - **Comparison of growth of confirmed cases in all the states of India with respect to time**
     - <a href="https://ibb.co/P6FwBYq"><img width='450' height='400' src="https://i.ibb.co/sVbyLP8/allhist.png" alt="allhist" border="0"></a>
 ## `Conclusion`
 All these analysis can be performed on available data.<br/>
 The above analysis is not just the few graphs it gives the complete information of count with respect to states.<br/>
 The severity in the state can be found with respect to other states.<br/>
 The state having maximum cured cases refer as best dealing state from corona virus<br/>
 State suffering the most by having the highest death case count.<br/>
 Confirmed cases vs date help to analyse how it is spreading in India.<br/>
 Cured case vs date help to know the cured time required.<br/>
 India confirmed case of all states vs date gives us the insights of its growth with time.<br/>
 **Hence,the above analysis can be maintain in real time by updating data to get the more insights.**
  
