# Covid

https://covid19.who.int

Covid 19 is a completely unprecendented event in our lifetime. On a global level, hundreds of thousands of people have died and more than a million infected. But what about the small level, our neighbourhoods? 

This project aims to survey one local neighbourhood (Sant Antoni) in Barcelona, to capture business closures during 2020. Many of my local businesses don't even appear on googlemaps - how did they survive the pandemic, or did they? This project is interested in *hidden data* - that which can only be captured in the time-honoured John Snow tradition of surveys. My starting hypothesis is that certain kinds of businesses, and especially those which do not appear on googlemaps, were more vulnerable to closure. They were less able to, for example, pivot to online selling because of their lack of online prescence. 

The first step is to literally obtain the data. I will first explore different ways to capture the information (co-ordinates, business name, status, business type etc), and do a test of a small part of the neighbourhood to uncover any issues. 

Possible mapping applications: 
Useful article on data collection technologies  : https://www.sciencedirect.com/science/article/pii/S2351989420302468

Downloaded:  Input,  GISMDC : these two require sign-ins / accounts 
Collector - not sure how this one works 
TerraGo Edge - this one a bit complicated. It clearly does allow to have a form to fill in at each destination but I can only find preset forms, not sure how to make one. 
OsmAnd Maps Travel & Navigate, Maps.me : these two aren't really for surveying 

In the end I chose the Input - Mergin - QGIS pathway. This is a bit complicated. It requires you to build the survey features in QGIS, upload them to the cloud (Mergin) and then sync it with your Input app. 

I did a preliminary survey and found many interesting observations, as well as making 95 records (2 blocks). 
- The barcelona business codes are sometimes ambiguous or unclear. 
-Sometimes it's difficult to know if the business is really closed or just currently (opening hours issue).
- some businesses which are closed have left no previous name. 
-some businesses are unclear - "private club" - is it a cannabis sales association? 
-it's difficult for me to approach some businesses to ascertain whether they are open - eg. gay sex venues. 
- some businesses are clearly advertising trade that they are not carrying out eg various "massage / manicure centres" are brothels. 
-some businesses overlap eg, tailoring and laundry services.
-there is a clear and obvious distinction to me between spas and medical aesthetic venues, how is this accounted for? 
-it was fun and very useful to always attach a photo of the business. 

My second survey (52 records, 1 block) did not sucessfully load through the pipeline to Mergin and QGIS. The photos saved to the file, but the rest of the data was lost somehow. I will try to retrieve it later. 

My third survey (2 blocks) loaded sucessfully through the whole pipeline, with assistance from Jo and the cloud/app owners who loaded additional capacity for me, as my data had exceeded the community level limit. I decided to examine the business codes more carefully to clear up ambiguity. While researching this, we found an exact match to my survey that Barcelona Council did in 2019, which is accessible here: 
https://ajuntament.barcelona.cat/comerc/en/analysis-data-inventory-premises-barcelona
I will examine this carefully to see how they have solved the issues that have come up for me in my surveys. 


