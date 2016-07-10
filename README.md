#US state highway shield map icons

HighwayShields is a collection of state highway icons designed for cartography

View see the icons in action [here](https://api.mapbox.com/styles/v1/willpots/cipbjwgd20051bdm6lk7uqovy.html?title=true&access_token=pk.eyJ1Ijoid2lsbHBvdHMiLCJhIjoiSTJYS0RCNCJ9.jPqwSxzqRHyjLAUoFS3vgQ#5.061015922518128/38.886906854081275/-91.14984067290843/0).

##Sketch Layers
###Signs
Contains raw state highway sign examples downloaded from [Wikipedia](https://en.wikipedia.org/wiki/Numbered_highways_in_the_United_States#State_highways).

###Icons-2
Contains icons designed for 1 and 2 digit highways.

###Icons-3
Contains icons designed for 3 digit highways.


##Usage
These icons are meant to go with the [Mapbox streets style](https://www.mapbox.com/vector-tiles/mapbox-streets-v7/). They belong on the `road_labels` layer and correspond to the `shield='us-states'`. These icons have been specifically named with the format: `{iso_3166_2}-{reflen}` (both attributes of the `road_labels` layer).