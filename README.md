# SALIDO React Challenge

This challenge is provided to help assess a candidate's development skills. There is no time limit, but we ask that you be prompt in submitting your solution.

## Submission Instructions

1. Complete the challenge according to the Challenge Instructions below.
1. Deploy your code on the internets so we can see it in action.
1. Post your solution in a Github repo. Be sure to include a README to explain and document your solution.
1. Send a link to your solution to challenge-accepted@salido.com.


## Challenge Instructions

### Objective
Build a simple React app that sources data from a third party API and provides a clean and usable UI to interact with and display the data.

### Context
Salido is concerned about losing productivity due to the flu and wants to monitor potential flu outbreaks near its headquarters (518 Broadway, NY NY)

### Tech Notes
* Use the http://www.flutrack.org API to obtain the necessary data
* The app should use React and Redux

### Business Requirements
* Display a table of tweets indicating the flu in the past 7 days within 50 miles of headquarters (518 Broadway, NY NY)
* There should be a separate count showing the total number of flu-related tweets, and a simple line graph showing the trend for the past 7 days
* Users should be able to filter the results by a keyword. This should be fast (without going to the API)
* Users should be able to change the number of days of results returned from 7 to an arbitrary number
