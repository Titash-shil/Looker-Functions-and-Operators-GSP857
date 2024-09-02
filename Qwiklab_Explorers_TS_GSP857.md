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

## Go to Looker from [here](https://t56fxdcyksox5tur34jbqk76ntszop4g27h5woxaxqt5xn7wl42q.us-central1-c.resources.bumper-boats-00.services.qwiklabs.com/explore/faa/flights)

### Follow next steps for Task-1 Carefully

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

## Go to Looker from [here](https://t56fxdcyksox5tur34jbqk76ntszop4g27h5woxaxqt5xn7wl42q.us-central1-c.resources.bumper-boats-00.services.qwiklabs.com/explore/faa/flights)

### Follow next steps for Task-2 Carefully

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

## Go to Looker from [here](https://t56fxdcyksox5tur34jbqk76ntszop4g27h5woxaxqt5xn7wl42q.us-central1-c.resources.bumper-boats-00.services.qwiklabs.com/explore/faa/flights)

### Follow next steps for Task-3 Carefully

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

## Go to Looker from [here](https://t56fxdcyksox5tur34jbqk76ntszop4g27h5woxaxqt5xn7wl42q.us-central1-c.resources.bumper-boats-00.services.qwiklabs.com/explore/faa/flights)

### Follow next steps for Task-4 Carefully

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

## Go to Looker from [here](https://t56fxdcyksox5tur34jbqk76ntszop4g27h5woxaxqt5xn7wl42q.us-central1-c.resources.bumper-boats-00.services.qwiklabs.com/explore/faa/flights)

### Follow next steps for Task-5 Carefully



# Congratulations ..!!🎉  You completed the lab shortly..😃💯

# *Well done..!* 👏

# Thank you for visiting.... :) 🗯️

# [Qwiklab_Explorers_ts](https://youtube.com/@titashshil?si=RgamNu1dc9jVIbJN)
