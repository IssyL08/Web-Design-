# Web-Design-Challenge
Web design challenge
Created the Weather webpage that follows the following below conditions:
### Website Requirements
For reference, see the ["Screenshots" section](#screenshots) below.
The website must consist of 7 pages total, including:
* A [landing page](http://127.0.0.1:5500/landingpage.html) containing:
  * An explanation of the project.
  * Links to each visualizations page. There should be a sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.
* Four [visualization pages], each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.

  Cloudiness visualization page: http://127.0.0.1:5500/cloudiness.html

  Humidity visualization page: http://127.0.0.1:5500/humidity.html

  Max Temperature Visualization page: http://127.0.0.1:5500/max_temperature.html

  Wind Speed Visualization page: http://127.0.0.1:5500/wind_speed.html


* A ["Comparisons" page](http://127.0.0.1:5500/comparison.html) that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a Bootstrap grid for the visualizations.
    * The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
* A ["Data" page](http://127.0.0.1:5500/data.html) that:
  * Displays a responsive table containing the data used in the visualizations.
    * The table must be a bootstrap table component. [Hint](https://getbootstrap.com/docs/4.3/content/tables/#responsive-tables)
    * The data must come from exporting the `.csv` file as HTML, or converting it to HTML. Try using a tool you already know, pandas. Pandas has a nifty method approprately called `to_html` that allows you to generate a HTML table from a pandas dataframe. See the documentation [here](https://pandas.pydata.org/pandas-docs/version/0.17.0/generated/pandas.DataFrame.to_html.html)
The website must, at the top of every page, have a navigation menu that:
* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
* Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
* Is responsive (using media queries). The nav must have similar behavior as the screenshots ["Navigation Menu" section](#navigation-menu) (notice the background color change).
Finally, the website must be deployed to GitHub pages.
When finished, submit to BootcampSpot the links to 1) the deployed app and 2) the GitHub repository.
Ensure your repository has regular commits (i.e. 20+ commits) and a thorough README.md file


The Bonus Website

The bonus website was created using the previous homework exported data sets for Hawaii weather and the trip data.  The website followed the same pattern as above but with a slightly different layout and colors. 

It shows the different graphs with the explanation of each one and everything can link back to the homepage as needed.
