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