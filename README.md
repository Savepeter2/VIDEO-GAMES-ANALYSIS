# VIDEO GAMES ANALYSIS


PROJECT DESCRIPTION

The video game sales dataset contains a list of video games with sales greater than 100,000 copies along with various additional details such as the ranking of overall sales, genre of the games, publisher of the games, Platform of the games released, and sales of the games in North America (in millions), Sales in Europe, Sales in Japan and sales in the rest of the world. All sales of the video games were in millions. The problem statement is to understand the sales of the video games either by the game name, platform, genre, to find out games with high sales in the various regions specified In the data, which could give business owners insights about the game detail they could invest in with the sole aim of yielding more revenue for them. 

![Annotation 2022-03-03 162227](https://user-images.githubusercontent.com/68739792/156603528-573d6845-9ec8-44e1-b676-d9fceb7da006.jpg)

![Annotation 2022-03-03 162547](https://user-images.githubusercontent.com/68739792/156603558-86ec920e-a09c-41bd-b535-58ff8f25f548.jpg)

THE PROBLEM

The business problem is to increase the revenue of businessmen by investing in-game details; Publisher, Genre e.t.c, with high sales at various regions for them to yield more revenue. The data required for the problem are the Video Games Sales and its details. The data can be presented in pictorial representation that is comprehensible.

DESIGN 

The dataset of the video games sales contains a list of video games and their associated details of about 16,598 records. As the first and an important aspect of data preparation, data cleaning needs to be done. Data cleaning refers to removing redundant and missing data. Data cleaning is required to ensure an accurate analysis of data to yield accurate insights. The first step is to handle missing data, Missing data could be handled in multiple ways – deletion or imputation. In the deletion method, all rows containing a column with null values are removed. In the imputation method, the missing values can be replaced by either the mean, median, or mode of the column depending on the dataset. In this case, the missing data rows were removed, The duplicate rows were also eliminated to ensure unique records. 
Google spreadsheets and Tableau have been used for data preparation and data visualization respectively. Google spreadsheets was used to edit, explore and visualize data. Pivot tables were made from the data and some visualizations through the pivot tables. There are a wide variety of visualizations e.g Pie-chart, bar charts, Line-graph, Histograms e.t.c. Along with spreadsheets, Tableau was also used to create interactive dashboards, It has the advantage of handling large amounts of data.

FINDINGS

1.	The Viz 1 below shows the total sales of video games for each year, and it could be seen that the highest sales of video games were made in the year 2008, A column chart was used in the visualization.
2.	Table 2 and Viz 2 below shows the total sales of games from all regions in the data; North America(NA), Europe(EU), Japan(Jp), Other parts of the world. We could deduce from the visualization that the particular genre: (Action) had the highest sales in Europe, North America, and Other parts of the world, then the Role-Playing genre has the highest sales in Japan. Other deductions can also be made from the pivot table and the visualization.
3.	Table 3 and Viz 3 below show the total worldwide sales by the game's genre, and the (Action) genre emerged to have the highest total sales and the strategy genre emerged to have the lowest total worldwide sales.
4.	The Viz 4 shows the chart of the total sales of games by region, and we could deduce that sales from North America have the highest total sales of about a 4.4billion dollars while the sales of games from other countries have the lowest total sales estimated to be about 800 million dollars. 

![total sales for each year](https://user-images.githubusercontent.com/68739792/156604886-7713dab1-08b8-440c-8f70-59cff5dd4b99.jpg)

Viz 1

![Annotation 2022-02-21 145215](https://user-images.githubusercontent.com/68739792/156605060-b1dd48a9-ce23-4275-82da-5731243c18ed.jpg)
Table 2
 
![Annotation 2022-02-21 145235](https://user-images.githubusercontent.com/68739792/156605392-b4905c7f-ce4f-4612-97bf-4793734e763a.jpg)
Viz 2

![Annotation 2022-02-21 151258](https://user-images.githubusercontent.com/68739792/156605548-a51e711e-5efc-4887-b23f-9ff18cf79185.jpg)


![Annotation 2022-02-21 151323](https://user-images.githubusercontent.com/68739792/156606180-5a4920d5-0282-4755-87a8-6fb9d6eb663e.jpg)
Viz 3

![Annotation 2022-02-25 073531](https://user-images.githubusercontent.com/68739792/156606306-e21e6276-8798-4761-bc8a-842cc5a656bf.jpg)
Viz 4

ANALYSIS

The visualizations below show the two dashboards created by tableau which enables us to have multiple visualizations from tableau sheets curated together as one. It gives an interactive visualization and can handle a large amount of data. The dashboard shows the overview and detailed analysis of the video game sales. From the dashboards, we got the following findings:

1.	Wii sports emerged to be the best-selling game with a total sale of about 82 million dollars followed by Grand Theft Auto V with total sales of about 56 million dollars, the chart shows the descending order in total sales of each of the games. 

2.	The Genre: Action emerged to be the most ranked genre followed by with Strategy being the least ranked.

3.	As the genre: Action has the highest rank, It also turned out to generate the highest revenue by having the highest total sales, and the Strategy genre has the least total sales. Does this mean Ranking and Sales are correlated in some way? It doesn’t appear to be true for all genres though. 

4.	It is also seen that the highest sale of games was made in the year 2008 and having the lowest sales of games from 2016 to 2020. Thus, the chart Video Games Released By Genre Yearly appears to have a similar trend with the Sales Of Games Yearly.

5.	The Video Games Released By Genre Chart shows that the genre: Action has the highest number of games released, Could this influence the effect of Action having the highest number of sales due to the high number of games released under the genre: Action, Same applies to the genre: Sports.
6.	It is also seen that highest total sales were made in North America followed by Europe then Japan and then the least, sales in other countries. 


 ![Dashboard 1 (6)](https://user-images.githubusercontent.com/68739792/156606789-1f9a8e4d-be6b-4e5a-af1b-576df9cdf15a.png)
 
 
 ![Dashboard 2](https://user-images.githubusercontent.com/68739792/156607047-2379c056-aac9-4b6c-8c5b-be5e71de4195.png)
 
 RECOMMENDATIONS IN SOLVING THE PROBLEM STATEMENT
 
As we’ve been able to make various possible visualizations and insights from the data given, the main aim is to solve the problem statement by providing recommendations from insights drawn. How would you increase the revenue of the business by investing in-game details? We know that from the data given, the columns revolved around sales from genre, publishers in various regions e.t.c, Thus, insights that are drawn will also revolve around the data as information can’t be drawn outside the data. 


1.	The genre: Action being the most ranked genre, the revenue of the business can be increased by investing more in games under the genre: Action. 

2.	Regions where the games were sold can also influence the revenue of the business. From the Sales By Region chart, North America had the highest total sales of games, probably because there are more people who video games in this region, Thus investing more in video games in this particular region could yield more revenue for game-owners. For instance, the genre: Action having a high rank, selling of games under this Action genre in this particular region; North America could yield more revenue for game-owners.

3.	WII-Sports emerged to be the best-selling video game, Thus, we can conclude it is the most loved game or popular game, Releasing different versions of this particular video game for individuals to purchase could generate more revenue for game-owners.  


CONCLUSION

The problem statement was to give game owners insights on how more revenues could be generated based on insights and data-driven decisions from the analysis of this project. Data visualization tools such as Spreadsheets and Tableau were leveraged for this purpose. The charts and graphs have made the task more comprehensible. The best-selling game has been identified as Wii-Sports and the most ranked and highest-selling genre had also been identified as Action. An increase in the cost of games under the genre: Action could bring an increase in revenue for game owners necessary findings and analysis were also made for the goal of this project








