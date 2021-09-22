Question/need:
•	What is the framing question of your analysis, or the purpose of the model/system you plan to build?
o	Purpose of this project is to find the best determinants of a successful movie (in terms of Lifetime box office gross) when considering movie lifetime rank, MPAA, run time, genre, budget, ect.
•	Who benefits from exploring this question or building this model/system?
o	Movie producers and those who invest in movie production companies will benefit from this analysis. 
Data Description:
•	What dataset(s) do you plan to use, and how will you obtain the data?
o	I will use title summary data for movies from Box Office Mojo. 
•	What is an individual sample/unit of analysis in this project? What characteristics/features do you expect to work with?
o	Units of analysis include run time, MPPA, lifetime gross, genre, budget, ect. I expect to work closely with lifetime gross, budget, and run time. 
•	If modeling, what will you predict as your target?
o	I will use the features mentions to predict lifetime gross
Tools:
•	How do you intend to meet the tools requirement of the project?
o	I plan to use Beautiful Soup to parse the HTML of the Box Office Mojo website, and potentially Selenium to navigate the site.
MVP Goal:
•	What would a minimum viable product (MVP) look like for this project?
o	An MVP would include a linear regression model with 3 or 4 parameters that I have found produce the lowest error and explain the most variance in the target variable 
![image](https://user-images.githubusercontent.com/86431477/134420021-3081669a-e446-4eaf-8ead-c5496a8a82be.png)
