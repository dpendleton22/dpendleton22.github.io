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

![](https://media.giphy.com/media/8cDKaE5HFgmE3qQr2a/giphy.gif)

So to answer this question we need the right type of plot to give us a quick glance of the entire NBA league over the season. This calls for a box plot summary of the stats we wish to view. A quick summary for those who dosed off during stats about box plots and when they’re useful. A box plot provides a graphical percentage summary of the distribution of the data. With this information in mind, I’m gonna guess GSW are at the top of a shooting percentage (FG and/or 3P). Knowing where the 2-time NBA champs sat gives us a benchmark to compare how SAC and MIL are with those same stats. 

![](nba_plots/2017-2018%20NBA%20Szn.png)
