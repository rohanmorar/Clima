# Clima Project

## Description

Adjusting wake up time to account for poor traffic conditions on route to work.

## Components

- Dist Matrix (A -> B) : home -> work + travel time (avg travel time to work)

- Alarm Clock : main functionality, wake up time adjusts and alerts you when to leave home to arrive to work by usual time)

- Weather data + road traffic conditions : check for changes in travel time due to traffic conditions, always adjust wake up time to account for travel time

## Ideas
- use dist matrix data from prior two weeks(M, A, E) 40 each (m_avg, a_avg, e_avg)
- incoming weather data every 30 min, 
- get traffic reports for route with weather report data 
- if traffic affected route, work arrival late: adjust wake up time -- keep monitoring traffic changes in route
- run in background while locked/sleep



