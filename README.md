# Gain Stepper

A JSFX gain utility for mixing in Reaper.

## Background

In the August 2018 edition of Nail the Mix, Machine the producer details his technique for sanity checking his vocal levels by boosting or cutting the level in 1.5 dB increments using a series of trim plugins in his DAW. The idea is that if the level is about right, a cut of 1.5 dB will make it sound a little buried and a boost of 1.5 dB will make it sound a little over the top. Cutting or boosting by 3 dB will accentuate the effect further, allowing you to zero in on the perfect balance. I've found this helpful on many other tracks in my sessions as well.

Since Reaper doesn't have a great trim plugin built in, I've written Gain Stepper to make this workflow as simple as possible. It's a slider with 5 positions: -3 db, -1.5 dB, 0 dB (Default, unity gain,) 1.5 dB, and 3 dB. With this, you can very quickly boost or cut in precise increments to implement Machine's workflow for checking that a track's relative level is approximately where it should be.

## Installation

1. [Download a zip file of this repository](https://github.com/scottnelle/gainstepper/archive/master.zip) and unzip it.

2. Find the Reaper Resources directory. Under the Options menu click "Show REAPER’s resource path in explorer/finder…" to have Reaper find this folder for you.

3. Open the Effects directory within the Reaper Resources directory and copy the `Gain Stepper` file to that directory (or a subdirectory within.)

4. In Reaper, scan for new plugins.

[A video demonstration of how to install JS FX plugins can be seen at the Reaper Blog](https://reaperblog.net/2015/06/quick-tip-how-to-install-js-plugins/).
