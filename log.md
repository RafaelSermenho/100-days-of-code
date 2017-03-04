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
