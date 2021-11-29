# Web-Design-Challenge

# Intro

The purpose of this project was to use HTML and CSS to create a web page and display comparative information about the change in certain weather conditions/attributes as one approaches the equator. There will be a total of seven pages to display:
- A homepage
- A data table of all cities
- A page to actively display all 4 major visualizations
- 4 individual pages for each of the plots constructed.

# Data Set 

![Cities.csv](data/cities.csv)

The data set was a collection of 500 cities with data on location and various weather conditions, but namely the latitude, wind speed, maximum recorded temperature, cloudiness and humidity.

# Method

*Since this project is focused on teaching/reinforcing the concepts of HTML/CSS & web development this method section will be quite detailed.*

I began this project by making a home page and laying out a skeleton of sorts with all of the aspects I figured I would need at the time including blank files in the right folders so i could avoid laying data paths out later, as well as an HTML table constructed using Pandas CSV_to_HTML().

The navbar is a key component in this assignment so I started with that. I laid out the area it would occupy and added parameters to have it scale with the browser window while also having a pop-up box containing links to the 4 individual plots. I finished out the navigation with links to the comparison and data table page then moved to creating the pages that would be linked to that navbar.

Having this navbar as a starting point was crucial because it would be included in every single page so it would serve as a base, being copied at the start of all other HTML documents. Afterwards it was simply a matter of setting up the div's to contain the information needed and be styled as needed for a neat, semi-professional appearance.

# Analysis
There was a small amount of data used in this assignment but the purpose was focused towards HTML & CSS so this section will be more about analysis and thoughts pertaining to the languages used in this assignment.

HTML & CSS make a fantastic pair, being able to customize classes and attributes of HTML for use later makes things much easier than hard coding all styles through the production of the web pages and having to keep track of, and edit styles individually. Understanding how the attributes of HTML behave goes a long way in being able to manipulate them using CSS with code like,

>primary_class > secondary_class

allowing one to setup some rather fantastic and intuitive pages.

There were some challenges where despite two div's having the same class they just could not be the same width. I spent a good portion of time attempting to locate where I may have gone wrong in the styling of a particular web page but for the life of me I could not discover why they would behave differently when they're styled in the same manner. Gaining the understanding of how and why the code behaves the way that it does will be an invaluable skill when constructing much more complex HTML structures. 

Using the Bootstrap was a required part of this assignment and the collection of CSS turned out to be quite helpful but I (as far as a novice could tell) could not locate how to see what the Bootstrap was changing when using the CSS styles from the sheet. For example the basic 'container' class was used most often but I couldn't alter the background of the web pages if I used that style from the bootstrap, however at the point of discovery, changing the load-order of the Bootstrap altered the appearance/behavior of the HTML pages so drastically that they ceased to function and would need to be reconstructed to operate as desired. Becoming familiar with how Bootstrap operates behind the scenes (the code hierarchy when compared to other CSS files) will be crucial for using such a vast collection of CSS styles. *How does one even learn all that the bootstrap contains?*

# Conclusion

Using HTML and CSS to display information is a major component of the age we live in. anytime someone searches for information or even used the web they're looking at a programs interpretation of styles and code to transfer information. After completing this assignment, I don't think that I'll be able to see a web page without think about the code and styles used to make the page appear as it does.

Making sure that the aspects needed in each page were behaving as desired or pinpointing the part of the code I wanted to style using CSS was a challenge due mostly to my novice-level experience in this coding language. I enjoyed overcoming obstacles that were almost certainly constructed by myself and also by accident. The relief of getting something to work after fiddling with it for an hour was a confusing mix of accomplishment and shame.

In the end, once I had all seven pages set up with links to each and feature such as click-able photos that take one to the corresponding web page and a pop-out button on the Nav-bar, it felt pretty nice to have tackled what at this point in time is a big concept but in retrospect will probably be the equivalent to a "Hello World!" statement.


