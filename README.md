# Economist_2020_Election_Forecast
This code was forked from [Elliott Morris' code](https://gist.github.com/elliottmorris/c70fd4d32049c9986a45e2dfc07fb4f0) that calculates Biden win probabilities in each state and adds a function to create a choropleth. Open up election.R and run the code to update the probabilities and produce a U.S. states choropleth with the projected winner. The main function to run is:

`update_electoral_college_map(biden_states = NULL, trump_states = NULL, biden_scores_list = NULL, target_nsim = 1000, show_all_states = TRUE)`

You can adjust biden_states or trump_states to add those states to either candidate's column as results come in. `biden_scores_list` allows you to bound Biden's vote share. Running the code with no parameters (the base map before results come in) will produce a plot that looks like this:

![Base Map as of Morning of Nov. 3, 2020](https://github.com/Akesari12/Economist_2020_Election_Forecast/blob/main/images/base%20map.png)
