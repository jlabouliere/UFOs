# UFOs: I want to believe.
## Overview
The Universe is vast and unexplored.  To assume that we're alone in the Cosmos is perhaps a more extraordinary claim than claiming to have encountered the extraterrestrial.  For this project, a dataset of UFO/UAP sightings was supplied with the intent of creating a filterable experience to sort and view the dataset by date, city, state, country, shape or any combination of these criteria.  The html and js files should ensure that filters are updated correctly and multiple criteria can be implemented together.
## How to use the filters
Navigating to the site from our html, we can see NASA graphic in the background of the titling with the introductory paragraph.

![Screen Shot 2022-06-19 at 4 24 02 PM](https://user-images.githubusercontent.com/98665941/174500946-01602adc-ee51-48ae-b926-725241ccf786.png)

Scrolling down, the filters come in to view on the left with the dataset of sightings in a table format.

![Screen Shot 2022-06-19 at 4 30 13 PM](https://user-images.githubusercontent.com/98665941/174501017-0f19bfd7-77f5-4c14-a519-c44e84c62ab9.png)

Let's begin by entering one filter criteria.  We'll choose country and enter "us" and narrow down from there.  Observe that there are still a substantial quantity of results and not much of a workable set.

![Screen Shot 2022-06-19 at 4 34 39 PM](https://user-images.githubusercontent.com/98665941/174501200-c5ddb696-dfdc-441d-b838-d94cf32d7a15.png)

Next let's enter in a state.  We'll keep the us in the country box and this will keep our original filtration and put fl in as the state to ensure some quality results.

![Screen Shot 2022-06-19 at 4 37 12 PM](https://user-images.githubusercontent.com/98665941/174501272-8522ee9b-29aa-44f7-a526-341c22d02a62.png)

Now we can see that there are several "fireball" shapes from the US state of Florida.  Let's filter for that shape and we'll only be seeing Floridian Fireballs in our dataset.

![Screen Shot 2022-06-19 at 4 40 53 PM](https://user-images.githubusercontent.com/98665941/174501349-7eb03b1b-11df-4781-9563-b46ad3a506a0.png)

For the final trick, we'll remove the state and country while leaving the fireball shape to show the dynamic search ability and view all fireballs.

![Screen Shot 2022-06-19 at 4 42 44 PM](https://user-images.githubusercontent.com/98665941/174501441-6f023ea8-8e1f-4ecd-9c4d-456872e78845.png)

## Summary
The site does a good job of filtering the dataset with the given criteria.  Results can be narrowed and expanded without having to reset or clear the filters.  There is some minor functionality that could improve if the search criteria were more forgiving.  For example, the filter criteria are case sensitive and the dataset is entirely lower case.  Intuitively, country and state abbreviations are capitalized and this generates some frustration.
### Recommendations:
1. Make the criteria filtering more forgivable by eliminating case sensitivity
2. Add the ability for the criteria to filter partial matches
3. Add a button to clear all criteria from the entry fields.


