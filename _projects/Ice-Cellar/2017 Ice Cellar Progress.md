---
Title: 2017 Ice Cellar Progress update(s)
layout: default
---
# This project is protected under the MIT License. 
Ice Cellar project is funded by ASRC-Federal and developed by Ianjon Brower and GINA co-workers. The ice cellar project was started in mind with north slope hunters food storage in mind, since climate has been changing drastically over the years. Their food storage are at potential risk of failures by climate change, since an ice cellar is a natural ice chest freezer, but able to customize to any length you want. Essentially it uses the grounds permafrost to keep everything at frozen temperature for storing. It's made by diggings into the ground, ranging anywhere from 5 feet below to 40 below. Climate change has claimed a few of these natural storage, thawing them out to a point where the food becomes unable to be eaten and flooded.

The project is geared to help those near a home and out of town, so that the owners can get an update/feedback on the conditions of their ice cellar so that they can determine move their hunted game somewhere safer so that all their hard work isn't lost by thawed/failed ice cellars. 


June 14, 2017: 
Managed to create a external power source for my raspberry pi to power it. The down arrow indicates that the temperature is lower than the last recorded temp. 
![Here's the image](http://i.imgur.com/ujtKcgH.jpg)  


June 14,2017:
Update on Battery Pack: 4 D sized duracell batteries( To my conclusion that they're 14,000 mAh batteries) last about 19 hours while doing two recordings. One to a text file while the other uploaded it to an underground weather station. 

Got a graph working at the moment for temperature and time. Working on making it so that it'll update the graph by itself instead of having to re-run the program to get an updated graph. 

![Raspberry Pi Image](http://i.imgur.com/MFdY0VO.png) 


June 16, 2017: Social meadia post. Got contacted from an NSB-Mayors office persononel asking to send as a widespread email across the northslope

Alaska Eskimo Whaling Commission manager/employee asking if she could try and get us on the agenda for a meeting being held her in fairbanks in the month of July about the projects. As in try and present it at AEWC. 

June 19,2017: Figuring out why matplotlib.pyplot isn't functioning on the pi. Function runs but the inteded source that I followed shows a live graph, while mine just shows a blank screen. 

June 20, 2017: With the help of Ross a bit, I got the code to work on python 2.7.9 for a live graph running but not for python 3. 

June 21, 2017: Copy and pasted the code for python 3 into a python 2 script and changed a weee bit on the code to get proper temperature.
![Image of Live Graph](http://i.imgur.com/kUcKDAH.jpg) 

June 26,2017: First time messing around with a raspberry pi bread board and getting to know some of it's features. Trying/going to implement a cat 5 cable so that we can put a sensor into the cellars without the pi having to be down there itself. Also finished my first draft for a questionaire to ask the public about their ice cellars so that we can get an idea of what materials we need for some and what materials we need for the length of cables. 

June 29, 2017: Messing around with the DHT11 sesnor and kinda fried it because I didn't know the breadboard needed a resistor. Met up with Vladimir R. . Back and forth on the project and ideas of to exapnd into different projects, such as permafrost ice. Was a little surprised when I told him I got a large community feedback that people are interested. Overall said this project looks very good. So woo! Looking at my presentation and I'm wondering what else to add to it.

July 06 2017: Finished my draft presentation. Updating the presentation and making an outline to what I'll be saying on paper for the presentation. 

July 13 2017: Learned about a application/web service called thingsboard.io. Essentially it is a very friendly user interface that anyone can navigate and apply to your needs, as long as you have a network connection and the device(s) needed to start monitoring. 

Sam and I setup a raspberry pi with a DHT11 sensor and managed to get it running on the webservice in about 15 minutes. This will help out with the Ice Cellar Project for cellars near a home, which hopefully has a network. With those that are near a network, it will be able to send data to the webservice. Depending on the setup of the webservice, it could send an alert to the client/owner of the cellar when the temperature dips/passes a certain threshold, which in terms can save the meat through an automated alert system. The alarm can be email, text, or however you setup. Though it can get a bit complicated if it's other than those two. The draw back on using this system though is that some of the cellars will not be near a network. Through modifying the scripts, we then can have it log into a text file and plot a live graph.It's lags about 5-10 minutes on updating to the site, so give it a little time and you'll see the change if there is any. Held a lighter to check and see if the temperature changed on the sensor, behold it does affect the temperature sensor. Here's what the initial widget looks like without changing anything to it: 

![Widget image of Thingsboard](http://i.imgur.com/l5zSY8E.png) 

July 18 2017: Looking over the presentation a bit and practiced some live runs with the staff today and on July 14, 2017. Great feedback, though on the 14th the practice run I used a piece of paper. Today I didn't use it and it went more smoothly. Started working on a brand new pi to write down some of the work it takes to get to work at the moment. 

July 19 2017: Went in and did the presentation infront of the AEWC board. They seemed very interested in the project and pleased with the presentation that I gave. Offered to follow out on a village trip to talk to students/kids about the S.T.E.M. program. I said yes and will be heading out on July 30th to Barrow for a day then off to Point Hope the next day. Will be meeting up with some of the other workers and give them.

July 26 2017: Almost done with a live demo kit to bring along with me to the village of Point Hope. 

July 30, 2017- August 04 : Traveled to Barrow for a day to meet up with the ASRC Federal STEM crew, great people that I've met and will be in contact with. Helped out with the many activities for the children. After the children activities were over, I would reach out to the community to see who would like to be involed with the Ice Cellar Project. Managed to talk to a few whaling captains and surveyed 3 ice cellars. 

![Photo of the Crew](http://i.imgur.com/I7KPJix.jpg) From left to right: Scott Howard, Drew Regner, Lisa Sedares, Lance Faust, and yours truly Ianjon Brower. Photo credit to Lisa Sedares

Here is going to be some photos of the ice cellars. 

![Photo of the entrance](http://i.imgur.com/qK03hLi.jpg) This is an entrance to many of the ice cellars in point hope. 

![Photo of the inside](http://i.imgur.com/ote1m5t.jpg) This is what it looks like in the inside of the ice cellars, while some are worse, this was an okay ice cellar in the standards of the three that I checked out. Tad bright makes it hard to distinguish what's inside but that's part of the flipper that they're aging. Most of the ice cellars are about 5-10 feet deep and 5x8 in area for storage. 

![Photo of an area around the ice cellar](http://i.imgur.com/3Kh5C2E.jpg) This is what it looks like for an ice cellar that's about to be eaten away by erosion. Different ice cellar than the other two photos. According to the owner that it's going to be gone either by this summer by the ocean or early next year. 


August 7-10 2017: Wrote a trip report about my expedition and started to play around with the new equipment that was waiting for me while I was gone. Played around with the solar panel with no power bank. It would stay on without the low power indicator, but when a cloud came over the sun the device would restart a few times. Soldered some solid wires onto a ground sensor and will be testing it soon. The DHT 22 sensors are looking great, though I will be messing around with them to find the sweet spot for accuracy with resistors. Also played around with the new cases

![Photo of the case lineup](http://i.imgur.com/aByt4cZ.jpg) 
The case lineup with the devices connected to them.  My favorite/most versatile case is the one with the hinge, though it may be a bit bulky and a little more patience to work with. The 2nd case would be my runner up because it fits snug. Next one is the bamboo case, which is kinda bareback but it would be able to squeeze in smaller places. Last of of all is the screen itself with no case. 

![Photo of the case lineup's back](http://i.imgur.com/fWsIja7.jpg) 
Here is what it looks like for the back of these cases.


August 15,16 2017: Playing around with the ground temperature. Managed to get an easy detach like the DHT sensor. Resistor soldered in and connected to an ethernet cable. Here's an image of it connected. 

![Photo of ground sesnor](http://i.imgur.com/xVFw43g.jpg) 
Took a bit of work, had to rewire it once because I soldered the resistor the two wrong cables.

August 17,2017 : With the help of Sam George, managed to get the ground temperature data uploaded to thingsboard. Here's an image of it

![Thingsboard ground sensor](http://i.imgur.com/Mn6qFL3.png)

August 28, 2017: Tested the DHT 22 sensor with about a 80 foot ethernet extension cable soldered onto it. Works fine with a 2.2k ohm resistor. 

September 5, 2017: Writing a step by step guide on how to setup the raspberry pi with pictures and clear instructions. 

September 14, 2017: Invited last minute to present at the student section for the Ocean 17 conference. 

September 20, 2017: Presented at the Ocean 17 conference. Should be getting some emails about the project. One question in particular that stood out was that there is people in the lower part of Alaska aging there fish through the ground. He told me that quite a few people are dying because they are eating the wrongly aged fish due to temperature risings. He hinted at how my project could be aimed towards that. 

September 27, 2017: Setup a live cold environment testing for the battery pack in the GINA refridgerator to simulate North Slope summers. Precisely to see how well the power bank does in semi-cold weather. 

September 28, 2017: 
Retrieved the first power bank test from the fridge. Lasted 26.61 hours, which is about an hour and a half under idle. DHT 22 sensor stopped recording for some reason during the same day, but thankfully the ground sensor was still tracking along. Going to see if II can tweak it for the next power bank testing which will commence next week along with the DHT22 Sensor casing. 

3D Printed 2 cases for the DHT 22 Sensor, since going in and out with blubbery stuff can gunk a lot of things. Here's an image of the 3D printer and here's an actual image of the finished printing : 

![Image of the 3D printing](https://i.imgur.com/SqY3IDL.jpg)  
![Image of Cases](https://i.imgur.com/8s7ugCY.jpg) 
Little mishap... Need to modify the dimensions because I didn't factor in the board connected to the DHT 22 Sensor. 

September 29- October 2, 2017: 
Battery bank test number 2: Lasted about 20.06 hours overall. About 6 hours less than the other battery bank, but when it's in the sunlight it'll also be charging. 
![yes](https://i.imgur.com/mD1DHrw.jpg)

Getting another raspberry pi setup going today. 


October 5,6,10 2017: Dived into a little bit of research for wind energy to recharge a power bank for the the devices. Updated the ice celler paper a little bit with my thoughts/comments on parts of the process. Waiting on some other supplies to come in. 

October 23, 2017: Article published about the Ice Cellar project in the [Alaska Business monthly](http://www.akbizmag.com/Education/North-Slope-Subsistence-Hunters-to-Use-Tech-for-Ice-Cellar-Temperature-Monitoring/). 

December 14-January 4th : Got a live prototype working for about 9 days! The downside is that I forgot to put a weight down on it and during a windy snow day it blew open, which snow got in and it turned off. After half a day of drying it was in working conditions again. 

Few notes to take from this is that the cabling used is not meant for cold weather usage. First few attempts at the first installation is that cabling snapped a few times while cooiled.After that I went and grabbed the backup cable that was 3-5 feet shorter but still managed to get it about a foot away from the ground. Before that happened, I wrapped the cabling in a weatherproofing/water resistant tape which took awhile to cover a 40 foot cord. 


February 20-25 2018: Went out to Reno Nevada and helped out with a raspberry pi workshop for the upperbound program. Gave a little real world demonstration of where the pi can be used since the ice cellar project is geared in that direction. 

Met some people who have done some awesome things with the devices and asked about some cabling ideas since my original idea for just plain ethernet cabling went in a not so good direction. 

During the trip, I did a real world example by presenting my current project, to show people from across the United State and Peurto Rico that raspberry pi's can be very versatile. 

March 2018: Re-affirming myself with the work that I've been doing since I strayed away a bit since schooling, life issues came up. 
