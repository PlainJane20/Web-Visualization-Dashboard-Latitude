# Web Design Homework - Web Visualization Dashboard (Latitude)


![Images/landingResize.png](Images/landingResize.png)

# Web-Visualization-Dashboard

## Objectives

In building this dashboard, create individual pages for each plot and a means by which we can navigate between them. These pages will contain the visualizations and their corresponding explanations. We'll also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

### Website Requirements

The website must consist of 7 pages total, including:

* A `Landing Page` containing:
  * An explanation of the project
  * Links to each visualizations page

![](Images/landing_page.png)

* Four `Visualization Pages`, each with:
  * A descriptive title and heading tag
  * The plot/visualization itself for the selected comparison
  * A paragraph describing the plot and its significance

![](Images/visualizations_page.png)

* A `Comparisons" Page` that:
  * Contains all of the visualizations on the same page so that it can be easily visually compared
  * Uses a Bootstrap grid for the visualizations
    * The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens

![](Images/comparisons_page.png)

* A `Data Page` that:
  * Displays a responsive table containing the data used in the visualizations
    * The table must be a Bootstrap table component
    * The data must come from exporting the `.csv` file as HTML, or converting it to HTML

![](Images/data_page.png)

The website must, at the top of every page, have a navigation menu that:

* Has the name of the site on the left of the nav which allows users to return to the landing page from any page
* Contains a dropdown on the right of the navbar named `Plots` which provides links to each individual visualization page
* Provides two more links on the right: `Comparisons` which links to the comparisons page, and `Data` which links to the data page
* Is responsive (using `Media Queries`). The nav's background color must change

![](Images/media_queries_page.png)

Web Visualization Dashboard of weather in 500+ cities at different latitudes relative to the equator line. The visualizations show temperature, humidity, cloudiness, and wind speed using HTML5, CSS3, and Bootstrap4.