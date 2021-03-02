# Udacity-Project-3-Analyze-AB-Test-Results

From the looks of it, adding countries to the dataset didn't seem to do much of anything. This further strengthens my point from earlier in regards to adding in new terms that may not be important to our current analysis. I think it's important to collect all of the data, then while parsing it out, determine what's unneeded. Adding countries to our analysis didn't move the statistics in any significant way. Actually the p_value for ab_page has not moved having added in countries. So, in this case the user's country was unneeded, and after all of this analysis, the old page is still going to be more likely to have a higher conversion rate than the new page. However, in this case, we did not see any cases of Simpson's Paradox. I'd say I just rejected a null hypothesis, but I'd have to predict Simpson's Paradox would show up a paradoxical amount of times to do so!