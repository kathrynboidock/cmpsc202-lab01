1. At what array size did your baseline algorithm become noticeably sluggish to execute?
At about size = 10,000, my baseline took about 5.8 seconds. Which in run time, feels like forever.

2. Based on your empirical data and the shape of your graph, estimate how long (in seconds, minutes, or hours) your baseline algorithm would take to process an array of $1,000,000$ elements. Show your reasoning.
At 10000 elements, the baseline algorithm took roughly 3.5 seconds to process, and if we apply that logic to 1,000,000, we would be looking at roughly one hour.

3. Based on your empirical data and the shape of your graph, estimate how long (in seconds, minutes, or hours) your Kadane's algorithm would take to process an array of $1,000,000$ elements. Show your reasoning.
At 10000 elements, the Kadane algorithm took 0.0008622666005976498 seconds to process, and if we apply that logic to 1,000,000, we would be looking at roughly 14 minutes.