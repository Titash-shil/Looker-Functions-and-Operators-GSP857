# Creating a Looker Modeled Query and Working with Quick Start || [GSP984](https://www.cloudskillsboost.google/games/5429/labs/35214) ||

# # Like, comment, share & Don't forget to subscribe [Qwiklab_Explorers_ts](https://youtube.com/@titashshil?si=RgamNu1dc9jVIbJN) 👍😄🤝

## Copy and replace below code in Looker

TASK 1 :-
```
# Place in `faa` model
explore: +flights {
  query: start_from_here{
      dimensions: [depart_week, distance_tiered]
      measures: [count]
      filters: [flights.depart_date: "2003"]
    }
  }
```
TASK 2 :-
```
# Place in `faa` model
explore: +flights {
  query: start_from_here{
      dimensions: [aircraft_origin.state]
      measures: [percent_cancelled]
      filters: [flights.depart_date: "2000"]
    }
  }
```
TASK 3 :-
```
# Place in `faa` model
explore: +flights {
    query: start_from_here{
      dimensions: [aircraft_origin.state]
      measures: [cancelled_count, count]
      filters: [flights.depart_date: "2004"]
    }
}
```
TASK 4 :-
```
# Place in `faa` model
explore: +flights {
    query: start_from_here{
      dimensions: [carriers.name]
      measures: [total_distance]
    }
}
```
TASK 5 :-
```
# Place in `faa` model
explore: +flights {
    query:start_from_here {
      dimensions: [depart_year, distance_tiered]
      measures: [count]
      filters: [flights.depart_date: "after 2000/01/01"]
    }
}
```
# Congratulations ..!!🎉  You completed the lab shortly..😃💯

# *Well done..!* 👏

# Thank you for visiting.... :) 🗯️

# [Qwiklab_Explorers_ts](https://youtube.com/@titashshil?si=RgamNu1dc9jVIbJN)
