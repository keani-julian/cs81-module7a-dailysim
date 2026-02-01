# Reflection – Daily Schedule Simulator

## What was your approach to designing the schedule?
I chose activities that reflect my personal routine and for fun, added things like creative writing and a walk. I set timings in milliseconds to simulate a day, with longer delays for “work” periods and shorter ones for quick break to mimic reality. 

## What was one challenge or unexpected behavior you encountered?
Initially, I forgot that setTimeout is asynchronous, so the last activity sometimes overwrote earlier activities. I realized each timeout must have its unique delay, or activities will appear at the wrong time.

## What does this assignment teach you about async code?
It shows that asynchronous code does not pause script execution. Unlike regular top-to-bottom scripts, events are scheduled and executed later, which is critical for UI updates and animations.

## What creative element did you add?
I added a surprise random mood emoji after the last activity and changed the background color during lunch. To see how multiple asynchronous events can occur in a single flow.

## How does this project simulate or differ from real-world schedules?
It simulates the sequence of events but in condensed time. Real-world timing would require hours between activities, whereas the simulation compresses the day into seconds.