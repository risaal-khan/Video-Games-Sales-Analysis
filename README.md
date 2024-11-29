# Video Games Sales Analysis 🎮🕹️

## About 🛈
* Video game sales from North America, Japan, the EU, Africa, and the rest of the world for 64,016 titles released from 1971-2024, including information like critic's score, genre, console, and more.

## Objective 🎯
*  Which titles sold the most worldwide?
* Which year had the highest sales? Has the industry grown over time?
* Do any consoles seem to specialize in a particular genre?
* What titles are popular in one region but flop in another?

## Dataset Description 📝

| Column Name       | Description                                                                                     |  
|--------------------|-------------------------------------------------------------------------------------------------|  
| `img`             | URL slug for the box art at [vgchartz.com](https://www.vgchartz.com).                            |  
| `title`           | Title of the video game.                                                                        |  
| `console`         | Console the game was released for (e.g., PlayStation, Xbox, Nintendo, etc.).                    |  
| `genre`           | Genre of the game (e.g., Action, RPG, Sports).                                                  |  
| `publisher`       | Publisher of the game.                                                                          |  
| `developer`       | Developer of the game.                                                                          |  
| `critic_score`    | Metacritic score (out of 10).                                                                   |  
| `total_sales`     | Global sales of the game in millions of copies.                          


## Insights 💡🧐🤔

1. #### Sales by Region
* North America: Dominates with 17.22K sales.
* Europe & Africa: Strong presence with 9.60K sales.
* Japan: Significant market with 6.42K sales.
* Rest of World: Smaller segment with 2.61K sales.
* Total Sales: 35.86K overall, showcasing a substantial global market.

![image](https://github.com/user-attachments/assets/52591ebc-2114-4015-abe2-076f0354b252)

2. #### Critic Scores
* Average Critic Score: 7.22, indicating generally favorable reviews.
* Correlation with Sales: Low correlation (0.17) between critic scores and sales, suggesting sales aren't strongly influenced by critic reviews.
* Distribution: Critic scores range widely, most games cluster around mid to high scores.

![image](https://github.com/user-attachments/assets/68ae89bb-e522-4bf7-9a2f-b073522ca408)

3. #### Top Selling Games
* Grand Theft Auto V, multiple entries of Call of Duty, and Minecraft are the top-performing titles, highlighting their widespread popularity and market impact.

4. #### Console Sales
* Leading Consoles: PC, PS2, and PS4 have the highest sales, showing their long-lasting popularity.
* Other Notables: DS, PS, PS3, X360, and newer consoles like NS (Nintendo Switch) also perform well.

![image](https://github.com/user-attachments/assets/fb844887-77dd-472f-9e5f-37b408ff4362)

5. #### Genre Sales
* Top Genres: Miscellaneous, Action, and Shooter genres lead in sales.
* Consistent Performers: Sports, Adventure, and Role-Playing games also show strong sales, indicating diverse gaming preferences.

![image](https://github.com/user-attachments/assets/ed369f9b-9d85-48c7-bedc-66ad9b61ccc9)

6. #### Average Sales
* 0.56K per game, providing a benchmark for sales expectations across titles.

![image](https://github.com/user-attachments/assets/59de7255-3f7f-4214-b169-cabe30b94dad)

7. #### Top Selling Publisher
* The bar chart shows the top-selling publishers with "Unknown" leading, followed by Sega, Electronic Arts, Activision, Ubisoft, Sony Computer Entertainment, Nintendo, Konami, Microsoft, and EA Sports. 
* "Unknown" has the highest sales, close to 5K.

![image](https://github.com/user-attachments/assets/cf6987b9-7dbd-44ce-9558-fed92efee394)

8. #### Sales by Critic Score Category
* This bar chart categorizes sales by critic scores (High, Low, Medium) for various games. "Grand Theft Auto V" has the highest sales with a high critic score. Several "Call of Duty" titles and "Minecraft" are also listed, with varying sales and critic scores.

![image](https://github.com/user-attachments/assets/2ddcc08b-ece3-4eb0-b798-d6d3de3e9932)

9. #### Regional Sales by Genre
* This stacked bar chart shows regional sales (NA, Other, PAL, JP) by genre. "Misc" has the highest sales, followed by "Action," "Shooter," "Adventure," "Sports," and other genres.
* NA sales are dominant in most genres.

![image](https://github.com/user-attachments/assets/c594543d-5237-4940-870f-f4601a0c1d51)

10. #### Average Critic Score by Publisher
* This line chart shows the average critic score for various publishers. "Bimboosoft" has the highest average critic score, followed by "2D Boy," "Psyonix," "Number None," and others. 
* The scores generally decrease from left to right.

![image](https://github.com/user-attachments/assets/6e1e1252-6b4f-41d6-953f-388b44409feb)

11. #### Total Sales and Average of Critic Score by Year
* This combined line and bar chart shows total sales and the average critic score by year from 1960 to 2040. 
* Sales peaked around 2010-2020, while the average critic score has remained relatively stable around 7.20 to 7.25.

![image](https://github.com/user-attachments/assets/9f08f304-7b9e-4092-a2a7-9c34c65487cb)

## Key Findings 🔎

1. #### Top Selling Titles
* Grand Theft Auto V: Consistently the highest-selling title across multiple regions.
* Call of Duty Series: Multiple entries in this series feature prominently in the top sellers list.
* Minecraft: Another top performer, showcasing widespread appeal and high sales.

2. #### Highest Sales Year
* The industry peaked in sales around 2010-2020. Sales were especially high during this period, indicating a golden era for video game sales.
* 2013 stands out as a particularly strong year, with several high-profile releases and robust sales figures.

3. #### Consoles and Genre Specialization
* PC: Excels in a variety of genres but particularly strong in Strategy and Role-Playing Games (RPGs).
* PlayStation (PS2, PS3, PS4): Known for a wide range of genres, with a notable strength in Action and Adventure games.
* Xbox (X360): Shows strong performance in Shooter and Sports genres, catering to fans of high-intensity and competitive gaming.
* Nintendo Consoles (DS, Switch): Excel in Miscellaneous and Adventure genres, appealing to a broad audience with family-friendly and innovative titles.

4. #### Regional Popularity
* Japan: Games like Pokemon and certain JRPGs are extremely popular in Japan but may not perform as well in North America and Europe.
* North America: Titles like Madden NFL and NCAA Football are big hits in North America but have limited appeal in Japan and other regions.
* Europe: Certain simulation games and soccer-related titles, such as FIFA, perform exceptionally well in Europe but may have lower sales in Japan and North America.
* The Critic Scores and regional sales data show that cultural preferences and gaming habits significantly influence the popularity of titles across different regions.
