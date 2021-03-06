# 100 Days Of Code - Log

### Day 0: January 2, 2018

**Today's Progress**: Installed visual studio, researched difference between java applet/servlet/application…it seems like JavaScript replaces applets. I then played around with the basic greeting rest API.

**Thoughts:** I struggled with understanding how to run a rest api outside of eclipse, had to package as a fat jar but still had issues running it as a standalone.

**Link to work:** [Hello World Rest Service](https://github.com/pnadolny13/RestService/commit/5abbca4a0737d6b56772680972fa2ef7a979cba7)

### Day 1: January 3, 2018

**Today's Progress**: Researched Rest APIs and when you would use them vs frameworks. Angular.js is a front end client-side development tool that can ping a Rest API for backend stuff while Node.js is a server-side Javascript framework/language. 
I had trouble getting my main to run in the rest service because I moved it to a new directory. Tried updating it to receive bill split info but wasn’t able to test. Instead jumped to Python and wrote a basic calculator that accepts user input to split a bill.


**Thoughts**: I had trouble figuring out what to work on, everything seems like a bigger project and requires research. I need to get out of the mind set of pushing code every day and into the set of research and starting somewhere, not pushing bad code.

**Link(s) to work**: [Bill Split Calculator](https://github.com/pnadolny13/Bill-Split-Calculator/commit/8f9fdfbd3429f901b77ae3b57da50eb3d3ba1e29)


### Day 2: January 4, 2018

**Today's Progress**: Researched and started a simple Flask app that was Hello world but now can collect email addresses and display them. Transfered log file to github for simplicity. (http://opentechschool.github.io/python-flask/core/data.html)

**Thoughts** Flask is much easier than Django. I would like to create app for inputing these log files so I dont have to come in here every night and manually edit it.

**Link(s) to work:**[FirstFlaskApp](https://github.com/pnadolny13/FirstFlaskApp/commit/8a5f42f364e01a1a42bb345c5197df2e92017c86)

 
### Day 3: January 05, 2018
 
**Today's Progress**: I updated the Flask form to accept inputs for my 100 days of code log file. It then update the log file in the appropriate format so I can just push to GitHub. I will probably have to limit it so that it restricts me more because I dont want to submit twice in a day.
 
**Thoughts** I think this is cool but I will probably have to make it look better and do more validation. Today is a Friday and I got home at 630 so its tough to sit down and code...almost skipped a day but resisted
 
**Link(s) to work:** [First Flask App -Updated] https://github.com/pnadolny13/FirstFlaskApp/commit/25ac223a79fe5f3fe90162a7779872f2970bbab4


### Day 4: January 06, 2018
 
**Today's Progress**: I updated the 100 days flask app to throw a warning if the day already exists so that I dont have duplicate days. It can be done better but the hack worked. 
 
**Thoughts** Nothing today...not a lot of time to work on this.
 
**Link(s) to work:** NA


### Day 5: January 07, 2018

**Today's Progress**: I spent far over 1 hr but I updated the Flask log app with page for viewing full log file, a home page with radio buttons to select an action, a delete today's post button in case it needs to be updated, input page notification for which was the most recent post, removed manual day input so users doesnt mess it up by accident.

**Thoughts** My app is a mess right now because its in one script file with global and local variables mixed around very unorganized. I need to spend time refactoring to make variables more clear. Also debugging in Spyder/Python is different than Eclipse/Java so I need to spend time getting used to it.

**Link(s) to work:** https://github.com/pnadolny13/FirstFlaskApp/commit/d19e4ac97db25875078420ca1275c5effc762515


### Day 6: January 09, 2018

**Today's Progress**: I refactored the app to be a little bit more organized. Still all in one app.py so its not totally organized but its a start. I also learned about Flask-Bootstrap to make some of the FE design stuff easier. I implemented a simple nav bar that move around the app easily. Still need to update the content to look better.

**Thoughts** I missed two days because I had a pipe burst and will have to manually update this date. To make up for it, I spent an extra hour today on 1/10 to make up for 1/9...so I'm logging this for 1/9. 

**Link(s) to work:** https://github.com/pnadolny13/FirstFlaskApp/commit/7a36955bebceb1d5e400c793d465e65a360b97bb


### Day 7: January 10, 2018

**Today's Progress**: I didnt get a lot done. I spent a long line trying to get a bootstrap template to work. It did but it was only a one pager so it wasnt going to work. Bootstrap is easy until you have to customize it. Rolled back to old code. I researched github integration and their wasnt too much, sounds like it might be tough.

**Thoughts** I had an idea that I could use the bootstrap template to showcase all of the things I do during the 100 days of coding. I could update as I finish projects and write a little description with links to github.

**Link(s) to work:** https://github.com/pnadolny13/FirstFlaskApp/commit/2f8d22b7ccad8cdf63ecd5a4bb50cd604fa04f7f


### Day 8: January 11, 2018

**Today's Progress**: I worked on the delete log functionality to be able to show the entry you are about to delete, then you can click a delete button. I'm still having trouble with the extra line at the end of the csv after the entry was deleted. It sounds like it is a windows issues, so I need to open/edit as bytes. https://stackoverflow.com/questions/3348460/csv-file-written-with-python-has-blank-lines-between-each-row

**Thoughts** I came to work an hour early to do this. I will probably start doing it everyday. I'm understanding now why Flask is known as a simple framework with many add-ons. It doesnt force you to be as organized as Django does which is better if the app is simple but worse as the app grows.

**Link(s) to work:** https://github.com/pnadolny13/FirstFlaskApp/commit/2460e8c3a74e5feae512d23fd3a5b1f369d3c09d


### Day 9: January 12, 2018

**Today's Progress**: Today I researched how to create an Alexa skill and created a basic tutorial hello world version. I had to install ngrok and an iphone app to talk to Alexa but it worked and it was awesome. Hoping to convert the sample template to something custom for me to use, like read some local file or something.

**Thoughts** Ngrok blew my mind, now I can run local code and view from anywhere. I viewed my Flask app on my phone to test out how it views as mobile size. Really cool for development.
**Link(s) to work:** https://github.com/pnadolny13/AlexaSkill_FlaskAsk/commits/master


### Day 10: January 13, 2018

**Today's Progress**: I created my own Alexa skill from the tutorial version I did yesterday. I was able to get it to accept all the group member names and respond back. Now have to start inputting the group members beer count. I dont have dates working either so it just always says 530.

**Thoughts** Alexa skills are really cool and fun to make because it seems like they are hard but they arent and nobody knows that....haha. I'm going to build out this app and see if I can push i to the store.

**Link(s) to work:** https://github.com/pnadolny13/SplitTheBill_AlexaSkill_FlaskAsk


### Day 11: January 14, 2018

**Today's Progress**: I updated my Alexa skill to accept 9 people, beer price, tax, tip, and calculate the amount per person and total based on how many everyone had. 2 new intents done for summary and input for prices. Doesnt accept decimal beer price yet, and should let you define whichever inputs you want. Beer, taquitos, zinger, etc. Should be able to add to each instead of overwrite and say everyone had something. 

**Thoughts** Flask Ask is really helpful with the Jinja templates. Building a cool Alexa app is really helping me to get a better understanding of Flask in general. I had a ton of time to work today so I made big progress!! Really fun to make skills.

**Link(s) to work:** https://github.com/pnadolny13/SplitTheBill_AlexaSkill_FlaskAsk/commit/c405e561e06baa2018d6f6a9e205e75339cdf856


### Day 12: January 15, 2018

**Today's Progress**: I updated the Alexa skill to accept drinks and price inputs. Then they get looked up by name when they say how many drinks someone had. Also added updated totals instead of overwriting. I then spent a bunch of time getting it deployed to an AWS lambda because its free and then i dont need to use ngrok anymore. I had trouble with the deployment part because a utilities.py file was not correct in the zappa deploy. So I found a solution and updated it. It then worked but I still need to test the skill to make sure it works. Didnt want to test in Starbucks lol.

**Thoughts** I worked in a Baltimore Starbucks because the plumber/carpet guys were here. Zappa and AWS lambdas are not that difficult once you do it once. It is also free for like way more than i will use it. I might switch my Django app to Lambdas if thats even possible. Would save some work.

**Link(s) to work:** https://github.com/pnadolny13/SplitTheBill_AlexaSkill_FlaskAsk/commit/b0ff0c9878dc135786be56f0d988554113d31463


### Day 13: January 16, 2018

**Today's Progress**: I spent all of today trying to deploy this flask app to an aws lambda so that I dont have to keep starting and stopping it on my local. I just realized that I wont be able to update the local log file though so i cant push to github every day.

**Thoughts** I didnt really want to code today. I spent the whole day struggling on some Java stuff and was kind of sick of code for the day. After I get my apps to Lambdas it will be much easier to use and deploy. 

**Link(s) to work:** 


### Day 14: January 18, 2018

**Today's Progress**: I started researching javascript but its not really anything special. Just need to learn new syntax. I brainstormed more Alexa app ideas. Went to the market place to see where the gaps were. I was able to setup a AWS RDS database and connect to it using python/Flask/Alexa. I think im going to make a movie quotes game, gives a quote and you have to guess the movie. 

**Thoughts** I missed yesterday. I tried to work on stuff but I didnt have any motivation at all. I think its a cool idea that all users of Alexa skill interact with the same database so a "king of the hill" thing could be fun. Everyone has write access and we all fight over who gets their name in there last. Everyone just overwrites each other.

**Link(s) to work:** https://github.com/pnadolny13/Python_Utility_Scripts/blob/master/connect_mysql.py


### Day 15: January 20, 2018

**Today's Progress**: I missed a day. I spent today making the new Alexa skill to give a movie quote and ask what its from. I only have a few in the DB but it reads directly from an AWS RDS. It worked first try. It great how simple it is. I probably need to add more features but its cool for now.

**Thoughts** Alexa skills are really quick once you know how to make them. I made this one in about an hour and a half.

**Link(s) to work:** https://github.com/pnadolny13/Alexa_Movie_Quote_Game/commits/master


### Day 16: January 21, 2018

**Today's Progress**: Today i deployed the movie app as an AWS Lambda and update the database to hold text instead of varchar. I think ill add some sort of scoring to it so people can get high scores. I also had trouble with re-prompts. 

**Thoughts** I should start on Javascript stuff. 

**Link(s) to work:** 


### Day 17: January 22, 2018

**Today's Progress**: I'm submitting this a day late but i spent most of the day learning some basic javascript and getting familiar with Visual Studio. I tried installing NativeScript to develop mobile apps but had some trouble with the install. I didnt push any code because it was just basic hello world apps. 

**Thoughts** Tried using Angular and Django together and wouldnt work which seems obvious now. Angular seems very similar to Django/Flask layouts. Also Javascript is relatively easy to read. 

**Link(s) to work:** NA


### Day 18: January 23, 2018

**Today's Progress**: Again submitting a day late but I spent last night and this morning still working on getting setup with javascript. Its overwhelming right now so I think the best route is to take step back and learn basics. I'm going to go through the 30 days of vanilla javascript and CS50 javascript.

**Thoughts** In order to use javascript I feel like i need to know HTML and CSS as well. I should learn all the basics before I start working with a framework like Angular.

**Link(s) to work:** NA


### Day 19: January 25, 2018

**Today's Progress**: I picked up CodeViz again and added a REST service so you can call it with a web call. Next I want to make a FE to allow you to call the start/stop. I also think instead of logging data to a file, I should embed a REST call to collect calls from methods. It might be a lot a once, so gotta check. No more IOExceptions issues.

**Thoughts** Glad I could connect the REST stuff to CodeViz, it was cool to see it work. Also found out from Python Bytes that CodeViz exists lol...its called Hunter. I will still work on it for practice though. Validates the idea was good. 

**Link(s) to work:** https://github.com/pnadolny13/CodeViz/commit/e12482bd917d5fa7f92ee5a382d1606b34cf4a2c


### Day 20: January 27, 2018

**Today's Progress**: I setup a web server with my CodeViz app so I can run it in Eclipse. I will add the FE Angular part but I needed the server to test it for now. Did research on Angular and how I will use it.

**Thoughts** I got confused about running spring in eclipse vs in the tomcat server. They are still both on 8080 localhost so whats the difference...

**Link(s) to work:** NA


### Day 21: January 30, 2018

**Today's Progress**: I tried to update the movie quotes alexa skill to whisper and do other special voices but it wouldnt work for amazon types, only normal ssml types like loud or high pitch etc. I then re-organized CodeViz...again. So now it has a good directory structure. I was able to run it in eclipse and render the js/html but cant hit the endpoint through the browser, only through postman.

**Thoughts** Spring doesnt need your app to be deployed on a tomcat server, its already baked in, like flask/django's uwsgi. The structure of Java applications and working with Eclipse is much more difficult than Python frameworks. I learned Django really quick, Spring/Angular are harder to learn. I'm not sure what the real advantages are of Java based apps. 

**Link(s) to work:** https://github.com/pnadolny13/CodeViz/commit/e12482bd917d5fa7f92ee5a382d1606b34cf4a2c


### Day 22: January 31, 2018

**Today's Progress**: Tonight I customized the calls from the FE to hit my Spring back end service. The test worked so I was able to call the backend and receive json back with the windows user name, which can only be determined by the BE!! I then tried adding some other javascript functionality like swapping images and click events but the swap was only working sometimes.

**Thoughts** Javascript is difficult to get working. I have a hard time because i dont really know how to debug yet, other than just looking at network calls. 

**Link(s) to work:** https://github.com/pnadolny13/CodeViz/commits/master


### Day 23: February 01, 2018

**Today's Progress**: Started playing with Angular in Flask, turns out they use the same syntax to receive variables in HTML. You can configure to change the syntax but I still wasnt able to use Jinja and Angular together. My JS worked but it never made the call to the BE python view to receive data. 

**Thoughts** No real progress but messing around with Javascript and testing out how things work will probably help me understand it better.

**Link(s) to work:** NA


### Day 24: February 05, 2018

**Today's Progress**: I got SQL Alchemy working to write some data to a database. I also spent a bunch of time debugging an error with the bootstrap base.html but it turns out i just had an extra app declaration which was messing it up. I missed the weekend but I spent some time reading the Java documents too.

**Thoughts** SQL Alchemy is almost more confusing for me to use vs just making a simple MySQL and running queries on it. I think im used to doing it the hard was so its easy for me now, or I just dont fully understand Alchemy yet. I need to look up the advantage of using it, might be better to stick with a real DB. Also delete has a bug, its something to do with not closing.

**Link(s) to work:** https://github.com/pnadolny13/FirstFlaskApp/commit/877c83b7e7b94c0384c368a88c596fa1fc7ce5d0


### Day 25: February 06, 2018

**Today's Progress**: I got a sample index.html and javascript file running on my apache server. I spent time with Javascript 30 but it made me realize I need to do more basic HTML/CSS/JS before doing my own apps. Code academy has 3 hr html, 11 hr css and 35 hrs JS. I need to complete them.

**Thoughts** Learning is going to take a long time but I need to understand this stuff to have a better general knowledge.

**Link(s) to work:** NA


### Day 26: February 07, 2018

**Today's Progress**: I did HTML training in code academy. I learned HTML fundamental structures ive used but never quite understood. I have a bear page. I also spent time continuing to read the Java documentation.

**Thoughts** I should make a resume static website with all of the my deployed apps linked. I can practice with HTML.

**Link(s) to work:** https://github.com/pnadolny13/HTML_Practice/commits/master


### Day 27: February 08, 2018

**Today's Progress**: I continued HTML/CSS code academy stuff. I created an html page with a table and made some custom CSS for it. 

**Thoughts** Knowing more about HTML/CSS makes me want to go update the budget app so it is better. It will be much easier to customize once i understand how the templates are working.

**Link(s) to work:** https://github.com/pnadolny13/HTML_Practice/commit/79198728a8c69dac055c027bc8540275c9de1a3e


### Day 28: February 11, 2018

**Today's Progress**: I spent about 8 hours today. I did CSS training (75% done) then I was inspired to start working on my Django app again but I realized it was a mess. The code on the server was different than github which was different than my local. I ended up getting it all i sync, created a script to refresh and restart the uwsgi server, and added github webhooks to pull data every time a commit happens.

**Thoughts** The website doesnt look any different but the operations under the hood are so much cleaner. I wont have to log into the server anymore when i make update....crazy auto deployments.

**Link(s) to work:** https://github.com/pnadolny13/RestService/commit/18bc0ac04cd79812b068f32167fb7f21eadc2929 https://github.com/pnadolny13/BudgetDjangoApp/commit/24ef43505dfc514a3a3da51fde1a57a1a6c39aa2


### Day 29: February 12, 2018

**Today's Progress**: I did 30 mins of CSS training then started working on customizing the Django app. I created all new views and urls then messed with CSS for the rest of time. I think I need to just restart from scratch because its becoming really difficult to customize the template CSS. Somehow my local version was different than whats on AWS now. 

**Thoughts** Customizing templates is really annoying. I got the hang of using the chrome dev tools for editing css which is helpful.

**Link(s) to work:** https://github.com/pnadolny13/BudgetDjangoApp/commit/5d677baa2cf3e091113cdad088ab90994e9a714b


### Day 30: February 13, 2018

**Today's Progress**: I added git integration for this app. Now in the github tab I pull the status of the 100-days-of-code dir. The user can see what is updated and chose to push using a button. The push functionality doesnt work yet but GitHub makes you sign in so it must be close. The GitPython API is really hard to work with and their are no examples online.

**Thoughts** Git seems to have been made for Unix environments. There isnt a ton of support for Windows and things are harder. I had to add an Environment Variable so GitPython could find my git.exe file (GitPython's fault)

**Link(s) to work:** https://github.com/pnadolny13/FirstFlaskApp/commit/e7b4d838a2bc635106be1183b3a2c59f18c557f8


### Day 31: February 17, 2018

**Today's Progress**: I worked on user authentication with little luck. Everything I tried ended up telling me the view didnt exist. I didnt end up getting it to work. 

**Thoughts** Django is much more work to get working but seems to be more powerful.

**Link(s) to work:** 


### Day 32: February 18, 2018

**Today's Progress**: I spent a lot of time getting the user authentication working. Now a user cant see any of the tracking/analyzing/etc pages until they login or create an account. I deployed it to AWS so people can make accounts if they want. Seemed like it needed to be locked down before I built out the functionality. I also updated the deployment scripts to not deploy the settings file because its specific to production so it should only be updated manually.

**Thoughts** I now need to start working with the models and forms to input and receive data back.

**Link(s) to work:** https://github.com/pnadolny13/BudgetDjangoApp


### Day 33: February 19, 2018

**Today's Progress**: I added legit forms to my Django app. It validates the inputs before doing something. I now need to have it inserted into the db. Github desktop got all jacked up because the internet went out so i needed to manually upload the files to github.

**Thoughts** I think it would be good to have the forms at the top and like the last 10 inputs below so you can tell that your input made it. 

**Link(s) to work:** https://github.com/pnadolny13/BudgetDjangoApp/commit/b64af93cade9d2918c1ae5702b5db4592c1a137d


### Day 34: February 21, 2018

**Today's Progress**: The budget app writes data to the DB and pulls the top ten rows to the track page so the user can see them. The CSS isnt good yet but it works and the users can see their custom inputs. 

**Thoughts** The models are a bit hard to work with but I can see how it will make it easier vs running direct SQL once I get used to the query syntax.

**Link(s) to work:** https://github.com/pnadolny13/BudgetDjangoApp/commit/2b6b7edfb279aa830b8d8d59677614db823ae258


### Day 35: February 23, 2018

**Today's Progress**: I spent time trying to get pandas table to be a nice html table with different packages but never really got it working. It just converts the df to html and sends to the template. 

**Thoughts** None

**Link(s) to work:** NA


### Day 36: February 25, 2018

**Today's Progress**: I integrated django-tables2 so the table feature shows up. You can filter and do other cool stuff but dont know how to pre-filter to only allow personal user data and 1 month. I also added categories as a drop down with options. I need to pass in the username to query for their categories. Also right now its hardcoded because the model choice field was displaying object names not values. Need to update AWS dependencies.

**Thoughts** I need to update AWS dependencies. That should be part of the CI/CD pipeline.

**Link(s) to work:** 


### Day 37: February 26, 2018

**Today's Progress**: I got the forms category drop down to finally filter using the user name. So users can define categories as needed. Also the table uses django_tables2 but it cant filter/sort dynamically because I already filter for user and date. 

**Thoughts** I need to expose the category additions. I also need to allow users to add and remove entries without having admin access.

**Link(s) to work:** https://github.com/pnadolny13/BudgetDjangoApp/commit/8daf7cf377dc5ad73689f933606278c0be304304


### Day 38: February 27, 2018

**Today's Progress**: I looked into getting analysis form to show sum data for a specific user and for specific month. 

**Thoughts** I submitted this a few days late.

**Link(s) to work:** NA


### Day 39: March 9, 2018

**Today's Progress**: I created a simple Angular seed app to see how they work. It seems a lot like django but just JS instead and its a bit of a mind shift to put everything on the front end.

**Thoughts** I need to dig into JS in order to build out that app further. 

**Link(s) to work:** 


### Day 40: March 10, 2018

**Today's Progress**: I updated the Budget app to pull sum of monthly data with percentages. It also allows you to select the month you want to analyze in case you want to look back or anything. I also looked into pulling data from bank APIs similar to Mint app. One main way is through a paid API called Yodlee but $250 a month is too much for me.

**Thoughts** None

**Link(s) to work:** https://github.com/pnadolny13/BudgetDjangoApp/commit/c7b53fdda92ea15e36c686038ce7276fe2e84df9


### Day 41: March 11, 2018

**Today's Progress**: Budget App - I updated the table CSS in analyze to look better and added functionality for income and monthly totals as well. Every user now has an income category. I need to add checks for when a user hasnt entered an income, it just throws and error now.
AWS - troubleshooted the server not working. I forgot to push the new forms updates. I figured out how to troubleshoot though.

**Thoughts** None

**Link(s) to work:** https://github.com/pnadolny13/BudgetDjangoApp/commit/14b743775b67c8e9dc097c2097e3334ebbae3af2


### Day 42: March 13, 2018

**Today's Progress**: I updated the links on the home page as a temporary fix for the nav bar not working on mobiles. I customized some margins trying to find a place to put a delete functionality...still thinking. I spent a lot of time thinking about how to query and organize the data that will be populating the monthly custom table with breakdown by category. I think i have a good approach by transposing each category list by week. I cant get the elements out of the model object yet though. 

**Thoughts** I still have issues with the model objects and how to retrieve data. I need to work on python fundamentals. I would expect to use a getter/setter but i think thats specific to java.

**Link(s) to work:** 


### Day 43: March 15, 2018

**Today's Progress**: I worked this morning on getting the analyze data structure (list of lists) to work properly and pivot like I needed. It finally showed up. I had issues because AWS has python 2.7 but my local is 3.6 so I need to fix that somehow. Current work around is to include try except so it works in both. At night I removed None values from the table, added headers, added filter functionality, and fixed the bug for when a month has no values.

**Thoughts** There seems like there is a better way to structure the list of lists to simplify but I couldnt find one. 

**Link(s) to work:** https://github.com/pnadolny13/BudgetDjangoApp/commit/4345639b96faf3fa0e09585849b2118c48aa63f2


### Day 44: March 16, 2018

**Today's Progress**: I didnt do a whole hour but I fixed a bug with the budget app, the categories cant be added together like I had them but I never noticed because I always signed in as admin.

**Thoughts** NA
**Link(s) to work:** https://github.com/pnadolny13/BudgetDjangoApp/commit/8ea8bd2556e0f7f52723459ca0fbbf50a54f6365


### Day 45: March 17, 2018

**Today's Progress**: Started working on getting the merged week column in the analyze table so it is obvious why the data is split up and some has nulls. I wasnt able to get it fully working but I learned about index.count in Jinja templates.

**Thoughts** NA

**Link(s) to work:** NA


### Day 46: March 19, 2018

**Today's Progress**: I studied Java concepts and brushed up on what I've done with it so far. How to create a quick CRUD app. I've done it in python but not a full one in Java.

**Thoughts** NA

**Link(s) to work:** NA


### Day 47: March 20, 2018

**Today's Progress**: I read a ton of the Java study guide documentation and explored rest service frameworks in Java. Practiced non IDE java coding and simple things like finding largest value in a list. Basic fundemetals review.

**Thoughts** Need to fix the python version issue and home page text links if user isnt logged in.

**Link(s) to work:** NA