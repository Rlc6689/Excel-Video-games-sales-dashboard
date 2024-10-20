# Excel-Video-games-sales-dashboard
Video games sales dashboard, displaying graphs for top 5 sales for each region using pivot tables 

I downloaded a video game sales kaggle dataset to create a Excel dashboard. I created pivot tables to display the top 5 video game sales for 2 continents, 1 country, other sales and global sales from 1980-2020 and displayed the top selling video game and placed in a dashboard. 

To do this, I first selected all the data in excel, selected find & select, then go to special and selected blanks to see if there were any cells with no data entered. There were no blank cells. I then added filters to the data headings and found N/A for a few of the games in heading year and publisher. They were not included in the data for pivot tables to ensure cohesiveness. I then selected all the data exported from Kaggle, inserted a pivot table and placed the name of the video games, genre, publisher to the rows, year in the column and the sum of sales i.e North america in values. I then filtered the row labels to display the top 5 video games sold from 1980-2020 and inserted a column chart with data labels to show how many units were sold.  

I added a slicer in the dashboard from the pivot tables for the user to select specific dates that would display the top 5 sales in the year selected for the 2 continents, 1 country, other sales and global sales. The slicer is connected to a graph(Top 5 video game sales by year) in the dashboard which would allow the user to visually compare top 5 sales by year selected in the data for 2 continents, 1 country, other sales and global sales.    

I then created pivot tables to display the top 5 video game sales for every 10 years, but did not include in dashboard for the user to have as extra information.

For all the pivot tables I highlighted the top selling game within the top 5 using the top 10 conditional format. I made the rule to highlight the top selling game in red. 
