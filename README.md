# Climate-Web

Using HTML and CSS, I created a dashboard to show off an analysis I completed in an earlier repo.  The earlier repo used Python requests, APIs, and JSON traversals to explore the link between weather patterns and latitude.  In building this dashboard, I created individual pages for each plot and a means by which the user can navigate between them. These pages will contained the visualizations and their corresponding explanations. I also included a landing page, a page to view a comparison of all of the plots, and another page to view the data used to build them.

See my final product here: [Climate Web](https://robeaseab.github.io/Climate-Web/index.html)

The website contains 7 pages total, including:

* A [landing page https://robeaseab.github.io/Climate-Web/) containing:
  * An explanation of the project.
  * Links to each visualizations page.
* Four visualization pages ([temperature](https://robeaseab.github.io/Climate-Web/temp.html), [cloudiness](https://robeaseab.github.io/Climate-Web/cloud.html), [humidity](https://robeaseab.github.io/Climate-Web/humid.html), and [wind speed](https://robeaseab.github.io/Climate-Web/wind.html)), each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
  * A ["Comparisons" pagehttps://robeaseab.github.io/Climate-Web/comparisons.html) that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a bootstrap grid for the visualizations with variable configurations based on screen size.
* A ["Data" page](https://robeaseab.github.io/Climate-Web/data.html) that displays a responsive table containing the data used in the visualizations using bootstrap table components.  The data on this page came from converting a CSV file to HTML using a CSV to HTML conversion tool.

The website includes at the top of each page a navigation menu that:
* Is responsive (using media queries).
* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown on the right of the navbar named "Plots" which provides links to each individual visualization page.
* Provides two more links on the right: "Comparisons" which links to the comparisons page, and "Data" which links to the data page.

Finally, the website was deployed to GitHub pages.

