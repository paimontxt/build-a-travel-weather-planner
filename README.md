# Build-A-Travel-Weather-Planner
Lab that determines the probability of commuting

# Background
This is a freeCodeCamp project where conditional statements are used to determine whether commuting is possible based on the weather, the distance to travel, and the availability of a vehicle.

## Problem Statement
Build a Python program that takes three inputs — current weather condition, distance to travel, and whether a vehicle is available — and uses conditional statements (if / elif / else) to return a single deterministic verdict on whether the commute is possible, along with the reason for that verdict. The rule set must cover every combination of the three inputs, including boundary distances, and must produce the same output for the same inputs on every run.

| Area | Issue |
|---|---|
| Conditional logic (decision rules) | Deciding whether a commute is feasible currently requires a person to weigh weather, distance, and vehicle availability by judgment. The rule is undocumented, applied inconsistently, and cannot be reused or tested. |


## User Stories:

| Variable | Definition |
|---|---|
| distance_mi | (a number representing the distance to travel in miles) |
| is_raining | (a boolean representing if the user is currently experiencing rainy weather) |
| has_bike | (a boolean representing if the user has a bicycle) |
| has_car | (a boolean representing if the user has a car) |
| has_ride_share_app | (a boolean representing if the user has an app that allows them to request a ride) |


* Use conditional statements to determine whether commuting is possible based on the values of these variables.
* Use if, elif, and else statements to evaluate the distance categories in ascending order.
* If distance_mi is a falsy value:
  You should print False.
* If the distance is less than or equal to 1 mile:
  You should print True only if it is not raining.
  Otherwise, you should print False.
* If the distance is greater than 1 mile and less than or equal to 6 miles:
  You should print True only if the person has a bike and it is not raining.
  Otherwise, you should print False.
* If the distance is greater than 6 miles:
  You should print True if the person has a car or has a ride-share app.
  Otherwise, you should print False.
