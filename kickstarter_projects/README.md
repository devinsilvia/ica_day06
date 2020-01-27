Kickstarter project statistics, from Kaggle.com

[https://www.kaggle.com/socathie/kickstarter-project-statistics](https://www.kaggle.com/socathie/kickstarter-project-statistics)

4000 live projects plus 4000 most-backed projects

### Description from the website:

Crowdfunding has become one of the main sources of initial capital for small businesses and start-up companies that are looking to launch their first products. Websites like Kickstarter and Indiegogo provide a platform for millions of creators to present their innovative ideas to the public. This is a win-win situation where creators could accumulate initial fund while the public get access to cutting-edge prototypical products that are not available in the market yet.

At any given point, Indiegogo has around 10,000 live campaigns while Kickstarter has 6,000. It has become increasingly difficult for projects to stand out of the crowd. Of course, advertisements via various channels are by far the most important factor to a successful campaign. However, for creators with a smaller budget, this leaves them wonder,

"How do we increase the probability of success of our campaign starting from the very moment we create our project on these websites?"

Data Sources
All of my raw data are scraped from Kickstarter.com.

First 4000 live projects that are currently campaigning on Kickstarter (live.csv)

Last updated: 2016-10-29 5pm PDT
amt.pledged: amount pledged (float)
blurb: project blurb (string)
by: project creator (string)
country: abbreviated country code (string of length 2)
currency: currency type of amt.pledged (string of length 3)
end.time: campaign end time (string "YYYY-MM-DDThh:mm:ss-TZD")
location: mostly city (string)
pecentage.funded: unit % (int)
state: mostly US states (string of length 2) and others (string)
title: project title (string)
type: type of location (string: County/Island/LocalAdmin/Suburb/Town/Zip)
url: project url after domain (string)
Top 4000 most backed projects ever on Kickstarter (most_backed.csv)

Last updated: 2016-10-30 10pm PDT
amt.pledged
blurb
by
category: project category (string)
currency
goal: original pledge goal (float)
location
num.backers: total number of backers (int)
num.backers.tier: number of backers corresponds to the pledge amount in pledge.tier (int[len(pledge.tier)])
pledge.tier: pledge tiers in USD (float[])
title
url
See more at [http://datapolymath.paperplane.io/](http://datapolymath.paperplane.io/)



