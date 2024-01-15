#Challenge 11 - HTML Challenge
## part_1_mars_news
### article list:
[{'title': "NASA's MAVEN Observes Martian Light Show Caused by Major Solar Storm", 'preview': 'For the first time in its eight years orbiting Mars, NASA’s MAVEN mission witnessed two different types of ultraviolet aurorae simultaneously, the result of solar storms that began on Aug. 27.'}, {'title': "NASA Prepares to Say 'Farewell' to InSight Spacecraft", 'preview': 'A closer look at what goes into wrapping up the mission as the spacecraft’s power supply continues to dwindle.'}, {'title': 'NASA and ESA Agree on Next Steps to Return Mars Samples to Earth', 'preview': 'The agency’s Perseverance rover will establish the first sample depot on Mars.'}, {'title': "NASA's InSight Lander Detects Stunning Meteoroid Impact on Mars", 'preview': 'The agency’s lander felt the ground shake during the impact while cameras aboard the Mars Reconnaissance Orbiter spotted the yawning new crater from space.'}, {'title': 'NASA To Host Briefing on InSight, Mars Reconnaissance Orbiter Findings', 'preview': 'Scientists from two Mars missions will discuss how they combined images and data for a major finding on the Red Planet.'}, {'title': 'Why NASA Is Trying To Crash Land on Mars', 'preview': 'Like a car’s crumple zone, the experimental SHIELD lander is designed to absorb a hard impact.'}, {'title': 'Curiosity Mars Rover Reaches Long-Awaited Salty Region', 'preview': 'After years of climbing, the Mars rover has arrived at a special region believed to have formed as Mars’ climate was drying.'}, {'title': 'Mars Mission Shields Up for Tests', 'preview': 'Protecting Mars Sample Return spacecraft from micrometeorites requires high-caliber work.'}, {'title': "NASA's InSight Waits Out Dust Storm", 'preview': 'InSight’s team is taking steps to help the solar-powered lander continue operating for as long as possible.'}, {'title': "NASA's InSight 'Hears' Its First Meteoroid Impacts on Mars", 'preview': 'The Mars lander’s seismometer has picked up vibrations from four separate impacts in the past two years.'}, {'title': "NASA's Perseverance Rover Investigates Geologically Rich Mars Terrain", 'preview': 'The latest findings provide greater detail on a region of the Red Planet that has a watery past and is yielding promising samples for the NASA-ESA Mars Sample Return campaign.'}, {'title': 'NASA to Host Briefing on Perseverance Mars Rover Mission Operations', 'preview': 'Members of the mission will discuss the rover’s activities as it gathers samples in an ancient river delta.'}, {'title': "NASA's Perseverance Makes New Discoveries in Mars' Jezero Crater", 'preview': 'The rover found that Jezero Crater’s floor is made up of volcanic rocks that have interacted with water.'}, {'title': "10 Years Since Landing, NASA's Curiosity Mars Rover Still Has Drive", 'preview': 'Despite signs of wear, the intrepid spacecraft is about to start an exciting new chapter of its mission as it climbs a Martian mountain.'}, {'title': "SAM's Top 5 Discoveries Aboard NASA's Curiosity Rover at Mars", 'preview': '“Selfie” of the Curiosity rover with inset showing the SAM instrument prior to installation on the rover.'}]

##Scrape table
	id	terrestrial_date	sol	ls	month	min_temp	pressure
0	2	2012-08-16	10	155	6	-75.0	739.0
1	13	2012-08-17	11	156	6	-76.0	740.0
2	24	2012-08-18	12	156	6	-76.0	741.0
3	35	2012-08-19	13	157	6	-74.0	732.0
4	46	2012-08-20	14	157	6	-74.0	740.0
...	...	...	...	...	...	...	...
1862	1889	2018-02-23	1973	133	5	-78.0	730.0
1863	1892	2018-02-24	1974	134	5	-77.0	729.0
1864	1894	2018-02-25	1975	134	5	-76.0	729.0
1865	1893	2018-02-26	1976	135	5	-77.0	728.0
1866	1895	2018-02-27	1977	135	5	-77.0	727.0
1867 rows × 7 columns

## Analyse your dataset by using Pandas functions to answer the following questions:

How many months exist on Mars? 12 months
How many Martian (and not Earth) days worth of data exist in the scraped dataset? 1867
What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
![image](https://github.com/pmadata/HTML_Challange/assets/143486132/41b46f56-f3dc-494b-a6f2-4f05c9700f35)
On average, the third month has the coldest minimum temperature on Mars, and the eighth month is the warmest. But it is always very cold there in human terms!

Which months have the lowest and the highest atmospheric pressure on Mars? 
![image](https://github.com/pmadata/HTML_Challange/assets/143486132/fddef2b2-cd12-4790-9c25-b78766e79abf)
Atmospheric pressure is, on average, lowest in the sixth month and highest in the ninth

About how many terrestrial (Earth) days exist in a Martian year? Was not able to answer this question.

## Export to csv file 
mars_df.csv
