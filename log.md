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
