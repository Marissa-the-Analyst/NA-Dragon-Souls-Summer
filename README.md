# NA-Dragon-Souls-Summer
This dashboard provides a statistical of the 2025 NA LTA 2nd Split, focusing on the frequency and outcome of the Dragon Soul type. By analyzing 95 professional matches, this visualization highlights which elemental souls defined the stage and how the league's top teams performed when the stakes were highest.

https://github.com/user-attachments/assets/f4deb694-2724-4cca-ab3d-a78035d48c89

# Business Questions
- Are Dragon Spawns as random as they appear or are some dragons appearing more than others?
- Are teams prioritizing dragon captures in a particular dragon soul spawn over another?
- What dragon souls were active when highest win rate teams, like Flyquest and C9, lost?

# Key Findings
- Dragon Souls maintain a random spawn pattern, but there was a higher spawn rate for infernal and hextech dragons.
- Despite not appearing the most, when Ocean Soul was active, teams made an effort to capture dragons, with the highest average dragon take of 2.58 dragons per game.
- Cloud 9 played 9 Infernal Soul games, the highest play rate of all teams for that soul, but only won 66.7% of their games with that soul.
    - They played 3 Cloud Soul games, and only won 1 of them.
    - They played 6 Ocean Soul games, and won 66.7% of them.
- Flyquest found the most success with Cloud soul and least with Mountain, only wining 1 out of 3 games played with that soul active.

# Finished Product
View the dashboard yourself on Tableau by [clicking here!](https://public.tableau.com/views/L_17765172559130/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link) <br>
**Deliverables** <br>
- A dataset of 95 individual matches from LTA North Summer Split 2025
- A dashboard featuring all of the dragon soul spawns and extensive team filters.

# Programs
- Excel for data collection/early analysis
- Word for Data viz draft ideas
- Tableau for Visualization

# Data Source
The game data was collected by me through VOD reviews. The descriptive dragon data and images were pulled from [League of Legends Wiki](https://wiki.leagueoflegends.com/en-us/). 

## Why 2025?
It’s Summer 2025, you’re watching professional esports while finishing up your data degree. You decide, why not just make this entertainment a data project too? Through data collection tribulations and inexperience, this dataset was born. Now a quarter of the way into 2026, my goal is to tackle any outstanding 2025 data projects and use it as practice before diving into more formal technical project series. 

# Data Collection — A Lession in Collection Practices
<img width="816" height="358" alt="image" src="https://github.com/user-attachments/assets/b0798cf3-e624-4078-ad83-5c9b2e7fee73" />
<br>
“It does too much and its too damn confusing.” — Me in 2025 <br>
<br>
When I started visualizing the data, I remember having to re-work the dataset a few times. This was a great lesson in collecting the right data for the job! It can be fun to say, “huh let's just start collecting data and see what happens” but once you get to the analysis phase, it can be a real pain to work with collected data without direction. On the other hand, it does more accurately reflect real life data! Constantly imperfect or in need of manipulation. I distinctly remember having to add “MatchID” because I struggled with the calculations just using entryno. This really highlights the cyclical nature of the data project cycle. 

# Time to Start Over — Visual Design
Tackling this project anew in 2026, my priorities were to go ahead and get a draft created in Word of some of the categories I could incorporate into the final visualization. These boxes represent a “clicked on”-filter interaction: 
<img width="1049" height="543" alt="image" src="https://github.com/user-attachments/assets/810459eb-c305-4c1e-bb75-ee6ad597ac77" />
<br>
The little dots in the bottom left-hand corner were also remnants of the original visualization idea. Each color was supposed to correspond to the dragon, and I wanted both team and dragon filters to be on the same dashboard. And if you filtered by dragon and team, there would be some sort of highlight or color change action of the dots to indicate which dots that team won/which ones they lost. 2026 me thinks this is silly and doesn’t really represent much on its own, so it didnt make the final cut.  
<br>
I did get to enjoy experimenting with using 2 dashboards. This helped a ton with managing the 2 filter actions I was trying to incorporate plus just gave each screen direction. I used Dashboard 1 as a landing page, describing what the viz was and basic frequency stats about the dragon spawn rates over the 11 week period. Then after the user clicks an icon, they are dashed away to the next dashboard that has all of that dragon's specific stats and a team filter. The 2 dashboard method also helped 'hiding' the ugly data when it wasn't filtered neatly. The user would never see dash2 unfiltered. To them, each soul could have had its own dash made for it! 

# Opportunities
I would have loved tracking exactly which dragons team prioritized. So instead of just the total number of dragons taken that game, how many cloud, hextech, etc etc were taken. Additionally, tracking whether Elder was taken and whether getting Elder resulted in a win no matter the gamestate. Or! If you could predict the outcome of a team's performance just based on which dragon soul spawned! As far as the viz goes, it could have been cool to show more "all teams, all dragons" data graphs instead of hyper specific stats. 

# Reflection
As previously stated, this was a interesting project when it comes to data collection, but coming back a year later, it was refereshing to see how I had stopped because I was stumped not only on project direction but techncial ability limitations. Only to in just a year, be taking the project in a different direction and tackling visualization in a mere week. Even in chart selection, I'm much more thoughtful about what value the chart is providing over just "is it pretty". A great example of this is the dot graph I discussed in my visualization section. Navigating Tableau workflows is coming so much faster too. I'm really proud of myself for continuing my development and I look forward to where I will be next year!

# Other Credits
Some of the icons, the linkedin and person icons were collected from FlatIcon.com. The photo representing this project on my website is from Pexels.com. 
