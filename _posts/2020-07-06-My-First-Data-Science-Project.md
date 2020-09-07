---
layout: post
title: My First Blog Post
---

I just finished my first week of Data Science Bootcamp at [Metis](https://www.thisismetis.com/) (woohoo!). I began my journey 3 months ago when I quit my job in Microbiology to pursue a career in Data Science. After committing to learning Python full-time (shoutout to [DataQuest](https://www.dataquest.io/), I was ready to apply to Metis Data Science in May and got in! Upon acceptance, I quickly moved into the prework for the bootcamp which consisted of around 60 hours of learning and applying python, linear algebra, and statistics. Before I knew it, bootcamp had begun!

We hit the ground running on the first day of class, where we were assigned our first data science project: WomenTechWomenYes, a non-profit organization seeking to increase the participation of women in technology, is holding a gala at the beginning of the summer and wants our input as to how to best place their street team to gather signatures of people who would want to attend the gala and contribute to this organization. They want to place their street teams near entrances of subway stations, but aren't sure which ones or when - this is where they need our help.

At the start of this project, my team discussed several ideas of what we could do to optimize the placememt of the street teams:
1. Which subway stations are the busiest?
2. What time of the day are these stations busiest?
3. What day of the week are they busiest?
4. Which stations do we want to target based on the likelihood of our target audience (people interested in technology, especially women) being at these subway stations?

Once we had a general idea of what sort of insights we wanted to discover, we needed to find a dataset (or several data sets) that we could analyze to transform these insights. The first, and main, dataset that we used is [Turnstile Data](http://web.mta.info/developers/turnstile.html), which contains ridership information for the MTA Subways in New York City for all weeks from 10/18/14 to the current week. We decided to look specifically at the 2 months leading up to the gala (April and May 2019), as people riding the subway during these dates are more likely to still be around in a month or two when the gala is taking place.

After quite a bit of cleaning the data, we were able to provide some key insights for Women Tech Women Yes to guide them with the best days, times, and locations to deploy their street team. 

We suggested prioritizing weekday afternoons (between 6 and 8 pm), as these times are typically the busiest at most stations.

![Best Days](tech1.png)

![Best Times](tech2.png)

We also identified 8 key stations to focus on, based on both the traffic volume at those stations (Grand Central-42 St, 34 St-Herald Sq, 42 St-Port Authority, 14 St-Union Sq, Times Sq-42 St, Broadway-Laffayette, Spring St, and 3 Ave.) , as well as the proximity to tech centers and Universities.

![Key Stations]()

If there was only one station to place their team, we suggested deploying them to 14 St-Union Sq as this location was both close to tech centers and Universities and it is one of the busiest MTA stations overall.


