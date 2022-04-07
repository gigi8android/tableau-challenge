# United State - New Jersey Citi-Bike

A study of New Jersey Citi-Bike for year 2020 on geographical location, popularity, gender and other metrics.

## Overview

The premise of this homework was to analyse and visualise data which showed the New Jersey share bikes network based on their geographical location and monthly performance. Further metrics included user type (subcription and non-subscription), gender, and age. 

The datasets used for this project included:
* Data files obtained from the public https://ride.citibikenyc.com/system-data webpage.
* 12 monthly files for year 2020

Tableau online workbook: https://prod-apsoutheast-a.online.tableau.com/#/site/gigi8android/views/NewJerseyCiti-Bike2020/Citi-BikeShortStory?:iid=3

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
* Citi-Bike subscribers/members mostly used bikes at the stations along 6th such as Brunswick & 6th (87%), Monmouth & 6th (87%) and Jersey & 6th (84%). Non-subscriber/ casual users mostly hired bikes nead the Point Of Interests such as Liberty Rail (57%), Communipaw & Berry Lane (50%) and Jackson Square & Loncoln Park (47%).
* Business at Liberty Light Rail and Newport Pkwy were improving significantly during Spring and Summer months

![image](https://user-images.githubusercontent.com/92906443/162130235-82dfa481-37e1-4b7a-bbb8-e1d4e9594e30.png)

* The top performing business was at station Grove St PATH due to many events were organised from May to September, i.e. after the lift of covid-19 pandemic restriction in New Jersey, to boost up local businesses. The popular events were New Hope Block Party, Groove on Grove, Artist & Makers Market and 90's Themed Midnight Market and many more re-opennings of the recurring events.

![image](https://user-images.githubusercontent.com/92906443/162130297-f0ee5b9c-5202-4a58-aef2-375c1b640641.png)

* Citi-Bike riders age were ranging from 18 to 93 with the peak at age 53. The main contribution to this peak age group was the non-scribers/casual users (total of 98,800 hired bikes) and most of them were withheld their personal details when were asking about their genders.

![image](https://user-images.githubusercontent.com/92906443/162130323-32a0d6db-0ea5-4127-9916-afb0e378db00.png)

* On a weekday, the busiest period was in the morning from 7am to 9am and in the everning from 5 to 7pm. It appeared that most people were riding bike to/from work. On a week-end, the pattern was very different, the peak period was from 12 to 7pm which could mean most people just using bike to ride around for their leisures.

![image](https://user-images.githubusercontent.com/92906443/162130368-2a20f46e-a75f-4086-a2df-af360b21585b.png)

* There was a big drop in business in April due to covid-19 pandemic and restrictions with the number of deaths in Jersey City reached to 7,228 deaths. However, the bike riders were booming from May onward (i.e. after the restriction) as people started to switch their commuting methods. With the merge of Lyft share rides and expansion of more stations in Hoboken neighbour that announnced in August, the number of bikes that hired by subscribers/members was slowing down in the Jersey City's stations while the number of non-scribers were increased significantly in October.

![image](https://user-images.githubusercontent.com/92906443/162130405-bb13fec8-93f9-44f0-a20d-eeed889a14d2.png)

