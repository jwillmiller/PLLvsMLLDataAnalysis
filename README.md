# PLLvsMLLDataAnalysis
Web scraping and visualizing data comparing the new professional lacrosse league, the PLL, with the existing league, the MLL.

## Intro
In 2018, Paul Rabil, arguably the best lacrosse player in the world, announced that he was branching away from Major League Lacrosse (the MLL),
and starting a new professional field lacrosse league called the Premier Lacrosse League (the PLL). Many of the most notable players in the game
immediately committed to playing in the PLL over their current professional MLL contracts. The goal of this project was to determine if the PLL
did in fact take the best players from Major League Lacrosse.

## Process
I used 'Requests' and 'BeautifulSoup' to scrape data from the [MLL website](http://mll.stats.pointstreak.com/scoreboard.html), as well as from a 
[webpage](https://www.insidelacrosse.com/article/premier-lacrosse-league-announces-140-plus-player-list/53201) that listed the 140 players in the PLL 
(the PLL website's JS rendering made it difficult to scrape). Then I used the 'Pandas' toolkit to clean and format the data, and finally the 'Seaborn'
toolkit for the visualizations. For each position, I selected two variables that I determined to be a good indication of overall ability: goals and
assists for offensive players, ground balls and caused turnovers for defensive players, games played and save percentage for goalies, and games played
and face off percentage for FoGos.

## Results
The final data visualizations did not show the complete dominance of the PLL over the MLL that has been portrayed on social media and in lacrosse circles.
The trendline for the offensive players did show better average goals and assists for players going to the PLL next year, but for the other three
plots the trendlines were largely unhelpful. This was also due partially to a lack of data and the way in which data was organized. Given the lack
of rigorous statistical analysis on this data, I would encourage viewers to inspect the plots and draw their own conclusions about which professional
lacrosse league contains more talent.

# Libraries used
- [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
- [Pandas](https://pandas.pydata.org/)
- [Seaborn](https://seaborn.pydata.org/)
