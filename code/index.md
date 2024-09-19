---
layout: page
title: Sam Tripp - Code
permalink: /code/
heading: Code
---

Most of my production-grade code is proprietary, but you can check out most of my personal
projects on [my github](https://github.com/sstripps1).

# Projects

## Interval workout app

I'm a big fan of home-workouts, particularly interval training workouts. I've found quite a
few good YouTube videos that walk me through some good routines, but as I wanted to be able to
create and follow my own custom routines (without having to constantly punch my stopwatch or timer). So, I decided to make an app that does just that.

### Create and save a workout
The app allows you to specify the name and duration of as many intervals as you'd like. You
can also add in sub-intervals for variations on the exercise within the interval (e.g. 20 seconds
of squats, 20 second hold, 20 more seconds of squats).\
![main_page](/assets/main_page.jpg){:.screenshot-img}

These exercises can also be saved to a Redis database, so you can create multiple workouts
and load up the one you want.\
![save_load](/assets/save_load.jpg){:.screenshot-img}

### Start the workout and follow along
Once the workout is started, follow the instructions on the screen, and listen for the *beep*
to signify the next interval. Check out the countdown to see how long is left in the current
interval, and see the progress bar to see how much you've completed so far.\
![workout_mode](/assets/workout_mode.jpg){:.screenshot-img}

Have a good workout!


*Check out the full code (as well as instructions on how to run the app locally) 
[on my github](https://github.com/sstripps1/workout-intervals).*