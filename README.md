#Exploratory Data Analysis

Long story short: 
Exploratory analysis is an underrated process that allows us to gain some critical knowledge about the data to discover trends and outliers. You need to explore your data before you try and predict your data 

Intro: (What is this article and what will you show me?)
For quite some time I’ve been meaning to jump into the realm of sports analytics but there were way too many things to take into account and five-thirty-eight is killing’ the game so why even bother? Because it’s real out here and I still have questions that are not answered, and I aint going to Sway for the answers. So who better than myself. My plan is to provide analytics for teams that interest me. There’s no point in choosing my LeBron-less Cavs since we all know what fate lies ahead for them but as Joel Embiid said we’re still the defending eastern conference champs! No instead I chose two teams that aren’t favorites to win the finals but provide enough interest to study their playing style. Those teams are the Milwaukee Bucks and the Sacramento Kings….”Imma let you finish David, you had me with the Bucks but the Kings my dude….really?” - Yes really. There’s really no need to explain the Bucks as they have the Greek Freak, Giannis Antetokounmpo. This kid, yes I said kid (he was born in 1994!) is 6’11 and 245 lbs (sweet Jesus this kid is a freak). His time with he Bucks was eventually going to come and with LeBum leaving that time might be now. The Milwaukee Bucks (MIL) and Sacramento Kings (SAC) were initially selected from my knowledge of watching basketball over the years with no analytic knowledge to backup my initial selections. In an effort to support these claims, let’s do some exploratory analysis to backup my initial selections

###In this article I will show:
* Why my selections for SAC and MIL are valid numerically
* Two exploratory analysis plots, why and when to use them 
* The conducive information that can be analyzed from exploratory data 
The box plot:
* What’s the jist?
* Observing the overall percentage distribution of the dataset will give useful insight of where the subject of interest lies especially when there is a benchmark 

Some people think you need have have your programming skills at a Bruce Lee level to do analytics or machine learning, I believe a primary skill needed is an imagination and ability to ask the right questions .  Why is that? - I’ll write a 2-piece on this later but how else do you know what you’re going to code analytically if you don’t know what information you want? Just follow along for a sec and you’ll see where I’m getting at. Before I get into analyzing MIL or SAC I need to know where they sit in the league. This article will just observe the general stats (assists, turnovers, field goal percentage, etc) before getting into the weeds with the advanced analytics that are becoming standard in the league. To start off let's do a little underhand pitch on this:

<b>How well did MIL and SAC average amongst the entire league last year?<b>
Before we start getting jiggy with it, what are some things we already know about what happened last year (2017-2018)? GSW shot the lights out! This KD added team terrorized the entire NBA and made a snooze fest out of the regular and post season, even J.R. Smith went to sleep during the finals 

![](https://gph.is/2so7x0v)

So to answer this question we need the right type of plot to give us a quick glance of the entire NBA league over the season. This calls for a box plot summary of the stats we wish to view. A quick summary for those who dosed off during stats about box plots and when they’re useful. A box plot provides a graphical percentage summary of the distribution of the data. With this information in mind, I’m gonna guess GSW are at the top of a shooting percentage (FG and/or 3P). Knowing where the 2-time NBA champs sat gives us a benchmark to compare how SAC and MIL are with those same stats. 

![](nba_plots/2017-2018%20NBA%20Szn.png)

What is the take away from observing the 2017-2018 season overall?
* Though 40% does not initially sound great, having ~35-37% 3P% shooting is great for a team and SAC was pretty efficient from the 3 point line last year
* Teams usually average between 40 - 50 rebounds for a game with most of them being defensive rebounds 
* There is a wide range for the FT% but teams still averaged more than 70% for the season 
* MIL had the lowest total rebounds in the league
* SAC was surprisingly efficient from the 3 point line
Now that we got a glance at last season, let's see how SAC and MIL are doing this current NBA season. 

![](nba_plots/2018-2019%20NBA%20Szn.png)

What is the current 2018-2019 season takeaway?
* SAC is still efficient from the 3 point line and increased their field goal percentage from the court
* MIL went from the worst total rebounding team to the league’s best for the season
* MIL and SAC are moving the ball more efficiently with significant increases in AST
The box plot is great as a quick glance to see the trends within the data but there’s another plot that will slice the data into an even finer exploration for analysis 
[Milly Rock]
A histogram will show how frequently a specific stat occured, and with a little extra sauce we can split that data to view home and away wins and losses. 
The Histogram 
* What’s the jist?
* Using a histogram with a little bit of sauce, we'll be able to see how well a team performed home vs away and if they more frequently win or lost those games
How well did MIL and SAC play during home and away games?
Of the 32 games the Milwaukee Bucks have managed 42 or more total rebounds they’ve won 75% of those games or 26 games to be exact. The league’s average for team’s total rebounds is 43! This means it is more than probable for this team to increase their team rebounding
Note the league FGA, FG and Milwaukee’s FGA, FG (MIL shoots 3 shots less than the league FGA but maintains to be within the league mean of FG with 39)

![](nba_plots/2017-2018%20MIL%20TRB.png)

Of the 47 times the Sacramento Kings have been able to produce 23 or more assists they’ve won 74% of those game (35 games to be exact)
Though assists may not seem imperative to a team’s production, the defending champions Golden State Warriors led the league in assists with 29.3 which were one of the three outliers from the box plot. The other two outliers were the New Orleans Pelicans and the Philadelphia 76ers (both 2017-2018 playoff teams)

![](nba_plots/2017-2018%20SAC%20AST.png)

When observing MIL assists, they only have a 60% increase in wins when producing over 22 assists (28 wins out of 46 games)
Last season SAC won 74% of their games (24/34) when they had 23 or more assists (which was their mean assists last year). This year through 55 games that mean has increased to 25 assists over the current season. Of the 34 games SAC has been able to produce 25 or more assists, they’ve won 20 of those games or 58%. The assist increase is directly correlated to their FG% increase from 45 - 47% as an assist is only completed after a made FG. Of the 23 times SAC shot 45 or more percent on the court they’ve won 14 of those games or 60%. 

![](nba_plots/2018-2019%20SAC%20AST.png)

Sacramento is currently 9th in the Western conference with a 29-23 record and they have two 2019 all-stars in De’Aron Fox and Buddy Hield. They’re a team to lookout for in the next few seasons and even for the second half of this year.
MIL is currently second in the eastern conference with a 41-13 record. Last season, though MIL was able to produce decent stats they were the weakest in the league for total rebounds. It was noted when MIL was able to rebound they won 75% of those games. This season with MIL being second in the east and a likely eastern conference contender, they are the top total rebound team in the league. Of the 45 times MIL has been able to produce 43 or more total rebounds they’ve won 34 of those games or 79%. 

![](nba_plots/2018-2019%20MIL%20TRB.png)

Exploring and understanding these basic stats (BLK, AST, etc.) and how they are utilized with each team gives us a better understanding of what stats are important and to which teams. A team such as Sacramento, with a young future star point guard, they are expected to do better with ball movement and setting up efficient shots. Milwaukee having a number of tall and lanky players such as the Greek Freak, Thon Maker and Brook Lopez, they’re expected to not give second shot opportunities to their opponents by rebounding better. With this information we are able to select what tags are imperative in creating a predictive model for the second half of the season.
