# HackBMU2019_Infinity
# LAZY MAN
## Problem

Statistics show that most of the people are not sure about when they need to start in order to reach their destination on time. They are generally either late or early, but being on time is hard to predict for the memebrs of these studies. They also weren't sure how to handle the weather changes and reflect that upon their driving. For this, the “Lazy Man” is an application that allows the end users to get a calculated estimate on when they need to start at their origin to reach to their destination on time. 

# Solution
We are using Google API and OpenWeather API to predict the status quo of the traffic in a patch of land, and then calculate the Δt  which is the net change due to the change in weather. We studied a few research papers on crowd flow and traffic flow when subjected to weather changes of all magnitudes. A few of the parameters in predicting are traffic density of the route and its irregularity, the optimality of the route, the weather conditions, weather confidence, traffic estimates, etc. Locality is mostly constrained to Americas due to unavailability of data.
