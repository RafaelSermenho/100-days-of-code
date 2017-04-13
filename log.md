# 100 Days Of Code - Log

### Day 1: January 30, 2017 

**Today's Progress**: Updated versions, include code to download picture and trigger media scan.

**Thoughts:** I really need to refactor this code. I struggled with outdated versions and realized that the architecture I was following really sucks. For a first day, it's good.

**What's next:** Create a MVP pattern, include data binding, refactor the code, finish settings screen.

**Link to work:** [Nasa - Picture Of The Day](https://github.com/RafaelSermenho/Nasa_PictureOfTheDay)

### Day 2: January 31, 2017 

**Today's Progress**: Refactor some code, remove eventbus and begin implementation of MVP pattern. (Code is on branch new_architecture)

**Thoughts:** Today was a good dev night! I changed some code that was bothering me and finally I saw MVP in a real project.

**What's next:** Continue the MVP pattern, include data binding, finish settings screen.

**Link to work:** [Nasa - Picture Of The Day](https://github.com/RafaelSermenho/Nasa_PictureOfTheDay)

### Day 3: February 01, 2017 

**Today's Progress**: Refactor some code, fixed some lint warnings and findbugs issues. Also started working on settings screen. (Code is on branch new_architecture)

**Thoughts:** Today was not very productive and I spent almost one hour trying to figure out how to start and activity through sharedPreferences. The refactor, lint warnings and findbugs were ok.

**What's next:** finish settings screen and shared preference code and study JobScheduler.

**Link to work:** [Nasa - Picture Of The Day](https://github.com/RafaelSermenho/Nasa_PictureOfTheDay)

### Day 4: February 02, 2017 

**Today's Progress**: Start implementation of timePreference.

**Thoughts:** The night was not productive. I've just worked on timePreference.

**What's next:** finish settings screen and shared preference code and study JobScheduler.

**Link to work:** [Nasa - Picture Of The Day](https://github.com/RafaelSermenho/Nasa_PictureOfTheDay)

### Day 5: February 04, 2017 

**Today's Progress**: Fixed a bug that was causing the application not to save a file when the folder already exists (side-effect) and worked un timepicker customization.

**Thoughts:** Just one hour coding, cause my mother is here. 

**What's next:** finish settings screen and shared preference code and study JobScheduler.

**Link to work:** [Nasa - Picture Of The Day](https://github.com/RafaelSermenho/Nasa_PictureOfTheDay)

### Day 6: February 05, 2017 

**Today's Progress**: Started JobScheduler implementation

**Thoughts:** Never worked with this class before. I'm still trying to figure out how it will work. Maybe I'll create a poc before.

**What's next:** Evaluate the necessity of a POC to study JobScheduler better.

**Link to work:** [Nasa - Picture Of The Day](https://github.com/RafaelSermenho/Nasa_PictureOfTheDay)

### Day 7: February 06, 2017 

**Today's Progress**: Implemented a PoC of JobScheduler in a new repository.

**Thoughts:** This example is very simple, but it was very useful to clarify my ideas for my other app (Nasa - Picture Of The Day).

**What's next:** Go back to my other project and implement a nice scheduler.

**Link to work:** [JobScheduler Demo](https://github.com/RafaelSermenho/JobSchedulerDemo)

### Day 8: February 07, 2017 

**Today's Progress**: Implemented JobScheduler

**Thoughts:** JobScheduler is a gift from heaven! *-*

**What's next:** Read params from sharedPreference to update jobScheduler, and fix some flow issues.

**Link to work:** [Nasa - Picture Of The Day](https://github.com/RafaelSermenho/Nasa_PictureOfTheDay)

### Day 9: February 08, 2017 

**Today's Progress**: Finished JobScheduler implementation and replaced TimePreference for a ListPreference

**Thoughts:** An UX analysis made me decide for the ListPreference. The downloadservice is now running according to what is setted on settings screen

**What's next:** Identify a photo already downloaded and show (avoid unnecessary call to service), include an option to save as wallpaper

**Link to work:** [Nasa - Picture Of The Day](https://github.com/RafaelSermenho/Nasa_PictureOfTheDay)

### Day 10: February 09, 2017 

**Today's Progress**: Implemented notification and code to set image as wallpaper

**Thoughts:** Today I wasn't in the mood for developing, but after 10 minutes I started to feel good.

**What's next:** Implement a database and review flow. 

**Link to work:** [Nasa - Picture Of The Day](https://github.com/RafaelSermenho/Nasa_PictureOfTheDay)

### Day 11: February 10, 2017 

**Today's Progress**: Fixed 1 bug on broadcastReceiver...found 99 more

**Thoughts:** Stupid receiver!!! I wanna kill you!!!

**What's next:** Fix this f#$%*king problem!

**Link to work:** [Nasa - Picture Of The Day](https://github.com/RafaelSermenho/Nasa_PictureOfTheDay)

### Day 12: February 11, 2017 

**Today's Progress**: I adjusted the flow, created the DB, renamed some fields, tried to work with DI and drew the basic flow of the application.

**Thoughts:** A good night of sleep made me think about the app's flow. After some drawing I solved my problem. I tried to implement the DI but I'm not sure how to do it.

**What's next:** Study DI

**Link to work:** [Nasa - Picture Of The Day](https://github.com/RafaelSermenho/Nasa_PictureOfTheDay)

### Day 13: February 12, 2017 

**Today's Progress**: Fixed some bugs, installed stetho to inspect the database and adjusted some flows.

**Thoughts:** Yesterday the API was returning a wrong data information that lead me to 14 wrong registers in database and today's photo was not being download.

**What's next:** Implement permissions on marshmallow.

**Link to work:** [Nasa - Picture Of The Day](https://github.com/RafaelSermenho/Nasa_PictureOfTheDay)

### Day 14: February 13, 2017 

**Today's Progress**: Adjust the code to bypass a bug in NASA APOD Api. They're returning the wrong date if I don't pass the current date as parameter

**Thoughts:** Every morning I expect a new photo on my phone, but there's always something happening. Now was a bug in NASA APOD Api...I I hope it's the last one.

**What's next:** Implement permissions on marshmallow.

**Link to work:** [Nasa - Picture Of The Day](https://github.com/RafaelSermenho/Nasa_PictureOfTheDay)

### Day 15: February 14, 2017 

**Today's Progress**: Upgraded sdk version and started implementing runtime permissions

**Thoughts:** Not a productive night. I'll have to do better tomorrow.

**What's next:** Finish runtime permissions

**Link to work:** [Nasa - Picture Of The Day](https://github.com/RafaelSermenho/Nasa_PictureOfTheDay)

### Day 16: February 15, 2017 

**Today's Progress**: Just updated job service parameters

**Thoughts:** I'm tired today...

**What's next:** Finish runtime permissions

**Link to work:** [Nasa - Picture Of The Day](https://github.com/RafaelSermenho/Nasa_PictureOfTheDay)

### Day 17: February 17, 2017 

**Today's Progress**: Testing job service, hiding some api keys and working on permissions

**Thoughts:** After missing one day, I'm back. Thinking about including sth to mock data from nasa

**What's next:** Finish application!!!

**Link to work:** [Nasa - Picture Of The Day](https://github.com/RafaelSermenho/Nasa_PictureOfTheDay)

### Day 18: February 18, 2017 

**Today's Progress**: Finish permission implementation; adjust proguard rules and some gradle properties.

**Thoughts:** I found a bug that was happening due an invisible char or sth like that. One code line was not being called, so I deleted it and wrote it again. I also had some problems with proguard (to setup and the build time, so I reduced the optimizationpasses to 3)

**What's next:** Improve the performance

**Link to work:** [Nasa - Picture Of The Day](https://github.com/RafaelSermenho/Nasa_PictureOfTheDay)

### Day 19: February 19, 2017 

**Today's Progress**: Fixed a bug in the flow that was causing app to save photo on database, but not  save file to storage.

**Thoughts:** I was chasing this bug for days, now I'll have to wait for the next photo from NASA.

**What's next:** Improve the performance

**Link to work:** [Nasa - Picture Of The Day](https://github.com/RafaelSermenho/Nasa_PictureOfTheDay)

### Day 20: February 20, 2017 

**Today's Progress**: JUst playing around with broadcast receiver. 

**Thoughts:** I should try dagger2 to inject dependencies and read more about MVP.

**What's next:** Improve the performance

**Link to work:** [Nasa - Picture Of The Day](https://github.com/RafaelSermenho/Nasa_PictureOfTheDay)

### Day 21: February 21, 2017 

**Today's Progress**: Refactoring the model package. Removing some code from presenter and including it in model

**Thoughts:** My mistake was doing to much work on presenter. I should've done it on model. But now I'm on my way to fix it.

**What's next:** Finish new architecture and improve performance.

**Link to work:** [Nasa - Picture Of The Day](https://github.com/RafaelSermenho/Nasa_PictureOfTheDay)

### Day 22: February 22, 2017 

**Today's Progress**: Still refactoring the model package. Using glide only to download image so far.

**Thoughts:** I really should start my programming session earlier. There are so many things to do...

**What's next:** Finish new architecture and improve performance.

**Link to work:** [Nasa - Picture Of The Day](https://github.com/RafaelSermenho/Nasa_PictureOfTheDay)

### Day 23: February 23, 2017 

**Today's Progress**: Started a great change in code.

**Thoughts:** I realized that I was creating a monster and using some over architecture. I refactored the project and let JobService handle some methods that were previously on presenter.

**What's next:** Finish new architecture and improve performance.

**Link to work:** [Nasa - Picture Of The Day](https://github.com/RafaelSermenho/Nasa_PictureOfTheDay)

### Day 24: February 24, 2017 

**Today's Progress**: Fixed a crash.

**Thoughts:** After 5 hours in an airport, I'm here to fix some bugs. Could only solve one before going to bed.

**What's next:** Finish new architecture and improve performance.

**Link to work:** [Nasa - Picture Of The Day](https://github.com/RafaelSermenho/Nasa_PictureOfTheDay)

### Day 25: February 25, 2017 

**Today's Progress**: Implemented a new method using glide to show picture

**Thoughts:** Last night I spent one hour to fix only one bug, but it was a nice effort. Today the app is more stable.

**What's next:** Finish new architecture and improve performance.

**Link to work:** [Nasa - Picture Of The Day](https://github.com/RafaelSermenho/Nasa_PictureOfTheDay)

### Day 26: February 26, 2017 

**Today's Progress**: Update wallpaper method

**Thoughts:** Everything is on track until now.

**What's next:** Finish new architecture and improve performance.

**Link to work:** [Nasa - Picture Of The Day](https://github.com/RafaelSermenho/Nasa_PictureOfTheDay)

### Day 27: February 27, 2017 

**Today's Progress**: Update wallpaper method using the download callback and removing some deprecated methods

**Thoughts:** Everything I did yesterday failed today and the app was crashing.

**What's next:** Finish new architecture and improve performance.

**Link to work:** [Nasa - Picture Of The Day](https://github.com/RafaelSermenho/Nasa_PictureOfTheDay)

### Day 28: February 28, 2017 

**Today's Progress**: Started layout updates.

**Thoughts:** The app worked like magic this morning. My girlfriend is here with me, so I showed her some colors to improve the layout. Beta app is available.

**What's next:** Finish layout and improve performance.

**Link to work:** [Nasa - Picture Of The Day](https://github.com/RafaelSermenho/Nasa_PictureOfTheDay)

### Day 29: March 01, 2017 

**Today's Progress**: Finished creating style and started implementation on exception flows

**Thoughts:** The app still working. The layout is defined and the app has a beta version published.

**What's next:** Finish exception flow and improve performance.

**Link to work:** [Nasa - Picture Of The Day](https://github.com/RafaelSermenho/Nasa_PictureOfTheDay)

### Day 30: March 02, 2017 

**Today's Progress**: Fixed some lint issues and included code to show last downloaded photo when there's no new photo from NASA.

**Thoughts:** Way to go! Thinking about some deployment tools.

**What's next:** Create an image grid.

**Link to work:** [Nasa - Picture Of The Day](https://github.com/RafaelSermenho/Nasa_PictureOfTheDay)

### Day 31: March 03, 2017 

**Today's Progress**: Include code to show a message when there's no photo to be show.

**Thoughts:** Not feeling ok today. I have a fever so I completed only few minutes today.

**What's next:** Create an image grid.

**Link to work:** [Nasa - Picture Of The Day](https://github.com/RafaelSermenho/Nasa_PictureOfTheDay)

### Day 32: March 04, 2017 

**Today's Progress**: Updating name and removing unused code.

**Thoughts:** Not feeling ok today. I have a fever so I completed only few minutes today.

**What's next:** Create an image grid.

**Link to work:** [Nasa - Picture Of The Day](https://github.com/RafaelSermenho/Nasa_PictureOfTheDay)

### Day 33: March 05, 2017 

**Today's Progress**: Fix upgrade issue that was causing photo not to be shown.

**Thoughts:** Not feeling ok today. I have a fever so I completed only few minutes today.

**What's next:** Create an image grid.

**Link to work:** [Nasa - Picture Of The Day](https://github.com/RafaelSermenho/Nasa_PictureOfTheDay)

### Day 34: March 06, 2017 

**Today's Progress**: Changed the flow to use GLide's callback to handle downloaded photo and changed the parameter to URL instead og HDURL

**Thoughts:** Nasa, come one! Today's image had 60Mb on HD resolution! My app was not ready for this :)

**What's next:** Create an image grid.

**Link to work:** [Nasa - Picture Of The Day](https://github.com/RafaelSermenho/Nasa_PictureOfTheDay)

### Day 35: March 07, 2017 

**Today's Progress**: Created async task to handle image download. It's on branch test.

**Thoughts:** Not feeling ok again. I have a fever so I completed only few minutes today. 

**What's next:** Create an image grid.

**Link to work:** [Nasa - Picture Of The Day](https://github.com/RafaelSermenho/Nasa_PictureOfTheDay)

### Day 36: March 09, 2017 

**Today's Progress**: Finished asyncTask implementation. Now waiting for the next test to publish this update.

**Thoughts:** I stayed less time than I should. Thanks good, I'm feeling better now, so I'll be able to get back on track soon.

**What's next:** Create an image grid.

**Link to work:** [Nasa - Picture Of The Day](https://github.com/RafaelSermenho/Nasa_PictureOfTheDay)

### Day 37: March 10, 2017 

**Today's Progress**: Implement code to show a message when there's no connection

**Thoughts:** The app is not running ok on Android 7. I still don't know why.

**What's next:** Create an image grid.

**Link to work:** [Nasa - Picture Of The Day](https://github.com/RafaelSermenho/Nasa_PictureOfTheDay)

### Day 38: March 11, 2017 

**Today's Progress**: Implemented "pull to refresh" and made some adjustments on asyncTask

**Thoughts:** Today I made a nice progress. I decided to publish the app only after the gallery. So let's wait a bit more.

**What's next:** Create an image grid.

**Link to work:** [Nasa - Picture Of The Day](https://github.com/RafaelSermenho/Nasa_PictureOfTheDay)

### Day 39: March 12, 2017 

**Today's Progress**: Started working on a bot for telegram to send a daily picture

**Thoughts:** The botr part was easy, but I'm suffering with nodejs.

**What's next:** Finish bot and go back to galaktikos

**Link to work:** [Galaktikos_bot](https://github.com/RafaelSermenho/galaktikos_bot)

### Day 40: March 13, 2017 

**Today's Progress**: Almost finished the bot implementation. I still have problems to host it.

**Thoughts:** Today I made a greate progress using nodeJs. Tks to @rafiuske

**What's next:** Finish bot and go back to galaktikos

**Link to work:** [Galaktikos_bot](https://github.com/RafaelSermenho/galaktikos_bot)

### Day 41: March 14, 2017 

**Today's Progress**: Almost finished the bot implementation.

**Thoughts:** I found out I was missing Procfile.

**What's next:** Finish bot and go back to galaktikos

**Link to work:** [Galaktikos_bot](https://github.com/RafaelSermenho/galaktikos_bot)

### Day 42: March 15, 2017 

**Today's Progress**: Still working on telegram bot.

**Thoughts:** I'm facing a problem with webhook and polling. Still don't know what to do.

**What's next:** Finish bot and go back to galaktikos

**Link to work:** [Galaktikos_bot](https://github.com/RafaelSermenho/galaktikos_bot)

### Day 43: March 16, 2017 

**Today's Progress**: Still working on telegram bot.

**Thoughts:** Found the problem on webhook/polling. Now the problem is on heroku. I think it's the post methos

**What's next:** Finish bot and go back to galaktikos

**Link to work:** [Galaktikos_bot](https://github.com/RafaelSermenho/galaktikos_bot)

### Day 44: March 17, 2017 

**Today's Progress**: Finally finished the first stable version of the bot.

**Thoughts:** Next step is firebase integration

**What's next:** Finish bot and go back to galaktikos

**Link to work:** [Galaktikos_bot](https://github.com/RafaelSermenho/galaktikos_bot)

### Day 45: March 18, 2017 

**Today's Progress**: Starting firebase integration

**Thoughts:** Include code to schedule messages

**What's next:** Finish bot and go back to galaktikos

**Link to work:** [Galaktikos_bot](https://github.com/RafaelSermenho/galaktikos_bot)

### Day 46: March 19, 2017 

**Today's Progress**: Finished telegram bot. @galaktikos is online!

**Thoughts:** It was a very good exercise!

**What's next:** Go back to android app

**Link to work:** [Galaktikos_bot](https://github.com/RafaelSermenho/galaktikos_bot)

### Day 47: March 20, 2017 

**Today's Progress**: Adjusted recurrence settings on bot

**Thoughts:** It was a very good exercise!

**What's next:** Go back to android app

**Link to work:** [Galaktikos_bot](https://github.com/RafaelSermenho/galaktikos_bot)

### Day 48: March 21, 2017 

**Today's Progress**: Created a new bot to show currency conversion using [fixer.io](http://fixer.io/)

**Thoughts:** Very easy and nice. I still have some improvements to do

**What's next:** Improve the bot feedback.

**Link to work:** [Conversor de Moedas](https://github.com/RafaelSermenho/conversordemoedas)

### Day 49: March 22, 2017 

**Today's Progress**: Worked on code to keep server awake for galaktikos_bot and conversorDeMoedas_bot

**Thoughts:** No problema at all today. I'm felling really good using nodeJs.

**What's next:** Create a new bot (water reminder)

**Link to work:** [Conversor de Moedas](https://github.com/RafaelSermenho/conversordemoedas)

### Day 50: March 23, 2017 

**Today's Progress**: Half way to go! \o/

**Thoughts:** No ideas today.

**What's next:** Create a new bot (water reminder)

**Link to work:** [Conversor de Moedas](https://github.com/RafaelSermenho/conversordemoedas)

### Day 51: March 24, 2017 

**Today's Progress**: Another bot! Now I'm working on a remider to drink water

**Thoughts:** I'm addicted to telegram bots.

**What's next:** Finish bot and return to android app.

**Link to work:** [BebeAgua_bot](https://github.com/RafaelSermenho/bebeagua_bot)

### Day 52: March 25, 2017 

**Today's Progress**: Still working on the bot.

**Thoughts:** I had a hard time trying to work with firebase structure. The current state is not good.

**What's next:** Finish bot and return to android app.

**Link to work:** [BebeAgua_bot](https://github.com/RafaelSermenho/bebeagua_bot)

### Day 53: March 26, 2017 

**Today's Progress**: Still working on the bot.

**Thoughts:** Stop using the scheduler and using setInterval...stll have to do some improvements on data structure.

**What's next:** Finish bot and return to android app.

**Link to work:** [BebeAgua_bot](https://github.com/RafaelSermenho/bebeagua_bot)

### Day 54: March 27, 2017 

**Today's Progress**: Worked on bot setInterval functions.

**Thoughts:** The interval function is not working...I got a timeout error and don't know why.

**What's next:** Finish bot and return to android app.

**Link to work:** [BebeAgua_bot](https://github.com/RafaelSermenho/bebeagua_bot)

### Day 55: March 28, 2017 

**Today's Progress**: Added some emoji to bot buttons.

**Thoughts:** The interval is working fine. 

**What's next:** I still have to create a method to update the registry.

**Link to work:** [BebeAgua_bot](https://github.com/RafaelSermenho/bebeagua_bot)

### Day 56: March 29, 2017 

**Today's Progress**: Adjusted some keyboard configurations.

**Thoughts:** Could not hide the keyboard after the last option is setted. I have to study more.

**What's next:** I still have to create a method to update the registry.

**Link to work:** [BebeAgua_bot](https://github.com/RafaelSermenho/bebeagua_bot)

### Day 57: March 30, 2017 

**Today's Progress**: Adjusted again some keyboard configurations.

**Thoughts:** I found out how to hide the keyboard. There are a lot of examples in python and go, but there's a lack of examples using NodeJs.

**What's next:** I still have to create a method to update the registry.

**Link to work:** [BebeAgua_bot](https://github.com/RafaelSermenho/bebeagua_bot)

### Day 58: March 31, 2017 

**Today's Progress**: Trying to work on method to delete data

**Thoughts:** I have to study more this part. I still don't know how to retrieve the key from firebase.

**What's next:** I still have to create a method to update the registry.

**Link to work:** [BebeAgua_bot](https://github.com/RafaelSermenho/bebeagua_bot)

### Day 59: April 01, 2017 

**Today's Progress**: Still trying to work on method to delete data

**Thoughts:** I have to study more this part. I still don't know how to retrieve the key from firebase.

**What's next:** I still have to create a method to update the registry.

**Link to work:** [BebeAgua_bot](https://github.com/RafaelSermenho/bebeagua_bot)

### Day 60: April 02, 2017 

**Today's Progress**: I found a way to retrieve the key from firebase. And the delete method is working.

**Thoughts:** After almost 3 days I found a way to retrieve the key from fb. It was a great advance.

**What's next:** I have to integrate the delete method on the app.

**Link to work:** [BebeAgua_bot](https://github.com/RafaelSermenho/bebeagua_bot)

### Day 61: April 03, 2017 

**Today's Progress**: Worked a little bit on deletion method. It's not working and I don't know why...

**Thoughts:** I think the delete method is racing with the insert method...

**What's next:** I have to integrate the delete method on the app.

**Link to work:** [BebeAgua_bot](https://github.com/RafaelSermenho/bebeagua_bot)

### Day 62: April 04, 2017 

**Today's Progress**: Changed the moment I was calling the delete method. Now it's ok.

**Thoughts:** Tomorrow I will test the bot and publish it on heroku.

**What's next:** Go back to Galaktikos app on android.

**Link to work:** [BebeAgua_bot](https://github.com/RafaelSermenho/bebeagua_bot)

### Day 63: April 05, 2017 

**Today's Progress**: Did some tests, remove some unused code and tried to upload it on heroku, but it was failling.

**Thoughts:** There's something wrong with my internet or with heroku.

**What's next:** Go back to Galaktikos app on android.

**Link to work:** [BebeAgua_bot](https://github.com/RafaelSermenho/bebeagua_bot)

### Day 64: April 06, 2017 

**Today's Progress**: @bebeagua_bot is online now.

**Thoughts:** I forgot to commit some files that were on .gitignore.

**What's next:** Go back to Galaktikos app on android.

**Link to work:** [BebeAgua_bot](https://github.com/RafaelSermenho/bebeagua_bot)

### Day 65: April 07, 2017 

**Today's Progress**: Started initial version of a twitter bot 

**Thoughts:** No problem until now. I'm able to post a simples "Hello, world!"

**What's next:** Finish twitter bot implementation

**Link to work:** [NivelBarragemDF_bot](https://github.com/RafaelSermenho/nivelBarragemDF_bot)

### Day 66: April 08, 2017 

**Today's Progress**: Included code to get data from external API (tks to [flavio] (https://github.com/flaviojmendes)

**Thoughts:** No problem until now, but I think I'll have to use firebase to save the last tweet so I can avoid send it multiple times.

**What's next:** Finish twitter bot implementation

**Link to work:** [NivelBarragemDF_bot](https://github.com/RafaelSermenho/nivelBarragemDF_bot)

### Day 67: April 09, 2017 

**Today's Progress**: Twitter bot @nivelBarragemDF is published. Tomorrow will be the first test.

**Thoughts:** I always have problems to create an app on heroku.

**What's next:** Create a twitter bot for galaktikos

**Link to work:** [NivelBarragemDF_bot](https://github.com/RafaelSermenho/nivelBarragemDF_bot)

### Day 68: April 10, 2017 

**Today's Progress**: I had to change the schedulling parameter for @NivelBarragemDf. Started creation of @Galaktikos_bot_twitter

**Thoughts:** I have to study how to download a picture and send it on twitter

**What's next:** Create code to download picture and send it

**Link to work:** [Galaktikos_bot_twitter](https://github.com/RafaelSermenho/galaktikos_bot_twitter)

### Day 69: April 11, 2017 

**Today's Progress**: Unfortunally, the external api is out of service due to a change in adasa's website. Now I'm working on a crawler.

**Thoughts:** Bad news...

**What's next:** Finish the crawler...

**Link to work:** [NivelBarragemDF_bot](https://github.com/RafaelSermenho/nivelBarragemDF_bot)

### Day 70: April 12, 2017 

**Today's Progress**: Fixed the twitter bot after the API was updated. Also forked the api project to include a new method.

**Thoughts:** It was very good to get some support from my friends after a bay night of coding,,,

**What's next:** Create a new method on aguabsb api.

**Link to work:** [NivelBarragemDF_bot](https://github.com/RafaelSermenho/nivelBarragemDF_bot)

