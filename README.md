# United States - New Jersey ![image](https://user-images.githubusercontent.com/92906443/162133533-b5bd9207-4f9d-4592-9530-29baa950368c.png)


A study of New Jersey Citi-Bike for year 2020 on geographical location, popularity, gender and other metrics.

## Overview

The premise of this homework was to analyse and visualise data which showed the New Jersey share bikes network based on their geographical location and monthly performance. Further metrics included user type (subcription and non-subscription), gender, and age. 

The datasets used for this project included:
* Data files obtained from the public https://ride.citibikenyc.com/system-data webpage.
* 12 monthly csv files for year 2020

Tableau online published workbook: https://prod-apsoutheast-a.online.tableau.com/#/site/gigi8android/views/NewJerseyCiti-Bike2020/Citi-BikeShortStory?:iid=3

## Method

### Python

Jupyter notebook and pandas were used to cleanse the data and merge all csv data files together into one large combined file called "JC-2020-data.csv". Due to the limitation of github, these data files were not uploaded to github but they were embedded in the Tableau workbook.

### Tableau

Tableau was used to visualised the data, hosted the visualisation stories and dashboards via Tableau Online cloud server. The workbook structure is as followed:
1- New Jersey Citi-Bike Short Story: a short version of Citi-Bike story with the summary of all chapters
2- The main story are broken into 2 sub-stories/chapters:
  * Chapter A - JC Stations: all information about JC stations and bikes with their geographical location and performance
  * Chapter B - JC Riders: all information about JC customers with US seasonal, monthly, daily, and hourly riding trends

## Summary & Observations

Data analytics were performed and embedded in the Tableau workbook's stories.

In summary, it is observed that:
* Citi-Bike subscribers/members mostly used bikes at the stations along 6th street such as Brunswick & 6th (87%), Monmouth & 6th (87%) and Jersey & 6th (84%). Non-subscriber/ casual users mostly hired bikes nead the Point Of Interests such as Liberty Rail (57%), Communipaw & Berry Lane (50%) and Jackson Square & Loncoln Park (47%).
* Business at Liberty Light Rail and Newport Pkwy were improving significantly during Spring and Summer months

![image](https://user-images.githubusercontent.com/92906443/162130235-82dfa481-37e1-4b7a-bbb8-e1d4e9594e30.png)
![image](https://user-images.githubusercontent.com/92906443/162134194-1b46ab97-133e-47a5-92dd-d11cfad5cab0.png)

* The top performing business was at station Grove St PATH due to many events were organised from May to September, i.e. after the lift of covid-19 pandemic restriction in New Jersey, to boost up local businesses. The popular events were New Hope Block Party, Groove on Grove, Artist & Makers Market and 90's Themed Midnight Market and many more re-opennings of the recurring events.

<img width="954" alt="image" src="https://user-images.githubusercontent.com/92906443/162132019-15f7b795-a104-413f-b722-687c15d509ae.png">
<img width="954" alt="image" src="https://user-images.githubusercontent.com/92906443/162131839-7a4e612b-9a7e-4615-9611-b6750b72a2c8.png">

* Citi-Bike riders age were ranging from 18 to 93 with the peak at age 53. The main contribution to this peak age group was the non-scribers/casual users (total of 98,800 hired bikes) and most of them were withheld their personal details when were asking about their genders.

![image](https://user-images.githubusercontent.com/92906443/162130323-32a0d6db-0ea5-4127-9916-afb0e378db00.png)
![image](https://user-images.githubusercontent.com/92906443/162130559-07ddb731-d8b5-460c-bb0c-ec2a42fed960.png)


* On a weekday, the busiest period was in the morning from 7am to 9am and in the everning from 5 to 7pm. It appeared that most people were riding bike to/from work. On a week-end, the pattern was very different, the peak period was from 12 to 7pm which could mean most people just using bike to ride around for their leisures.

![image](https://user-images.githubusercontent.com/92906443/162134595-c40bbcae-5961-4cf9-8974-0de126e53a2d.png)

* There was a big drop in business in April due to covid-19 pandemic and restrictions with the number of deaths in Jersey City reached to 7,228 deaths. However, the bike riders were booming from May onward (i.e. after the restriction) as people started to switch their commuting methods. With the merge of Lyft share rides and expansion of more stations in Hoboken neighbour that announnced in August, the number of bikes that hired by subscribers/members was slowing down in the Jersey City's stations while the number of non-scribers were increased significantly in October.

![image](https://user-images.githubusercontent.com/92906443/162130405-bb13fec8-93f9-44f0-a20d-eeed889a14d2.png)

* A personalised dashboard had been created, where user could select a range of dates/ months to view a station performance during that period with Citi-Bike user metrics. A summary of information will be revealed in the little square in the table by clicking on it.

<img width="954" alt="image" src="https://user-images.githubusercontent.com/92906443/162132591-4058b2e3-e0ab-4a7a-8c95-0559ac59c320.png">
