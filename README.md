# belly-button-challenge

This challenge involved using JavaScript to explore the Belly Button Diversity dataset https://robdunnlab.com/projects/belly-button-biodiversity/ which looks at the presence of microbes in human navels. Some species were found to be very common (occurring in more than 70% of individuals) and others more rare. Social and demographic data are also included for each of the study participants to aid in predicting the likelihood of detecting the particular species in an individual. Those factors are age, ethnicity, gender, location, frequency of washing, and type of bellybutton (innie vs. outie). 

We were given the HTML for our webpage and a JSON file with the data. Using the D3 library, I read in the JSON file, initialized the dashboard, created a bar chart using the slice method to show the 10 most common OTU's (operational taxonomic units) or microbial species present in the sample, and a bubble chart that shows the relative presence of the bacteria represented by the size of the bubbles. The dashboard also displays the personal data for the 60 individual participants. The charts update when a new sample is selected. I deployed the app to GitHub Pages.

