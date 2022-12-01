# Web-Design-Challenge

**Background**

Data becomes more powerful when you share it with others! That’s because people can use your data only if they can access it. So, you’ll use HTML and CSS to create a dashboard featuring the Latitude vs. X analysis of weather.

**Website Requirements**
 
The website must consist of 7 pages total,

* Landing Page

  1. An explanation of the project.

  2. A link to each visualization page and a preview image of each visualization. 
 
* Four visualization pages, stored in the visualizations folder, each with the following elements:

  1.A descriptive title and a heading tag.

  2.The visualization for the selected comparison (latitude vs. max temperature, latitude vs. humidity, latitude vs. cloudiness, or latitude vs. wind speed). The images   that these pages display should be stored in the assets/images folder.

  3.A paragraph describing the visualization and its significance.
 
* Comparison Page
 
  1.Contains all the visualizations on the same page so that people can easily compare them.

  2.Used a Bootstrap grid for the visualizations. This grid contains two visualizations across a large screen and one visualization across a small screen.
  
* Data Page
  
   A data page that displays a responsive table containing the data that the visualizations use, as follows:

    1.The table must be a Bootstrap table component.

    2.The data is used by exporting the CSV file to HTML. To do so used the **to_html** method that generates an HTML table from a Pandas DataFrame. 
    
At the top of every page, the website has a navigation bar that does the following:
    
  * Contains the name of the site on the left side of the navigation bar, allowing users to return to the landing page from any page.

  * Contains a drop-down menu, named Plots, on the right side of the navigation bar that contains a link to each visualization page.

  * Provides two more text links on the right side: Comparisons, which links to the comparisons page, and Data, which links to the data page.
  
 The website is deployed to GitHub Pages:
  
   https://jananeesaranraj.github.io/Web-Design-Challenge/


 
