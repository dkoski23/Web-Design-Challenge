# Web-Design-Challenge

This project is my first website made with html/css/bootstrap and uses weather data gathered from over 500 countries throughout the globe (which I actually pulled in another project).The plots used compare show cloudiness, humidity, maximum temperature and windspeed vs. the latitude of said cities. The index.html is the landing page, and shows all plots on the left in addition to a brief explanation of the project at the top. 

Cities.csv in the Resources folder holds the csv file with all of the data, and the visualizations folder holds all of the plots. The htmls for cloudiness, humidity, windspeed, and max_temp all hold the html for those respective pages. The comparisons.html is the html showing the plots for these factors side by side, and each factor has one plot for the Northern Hemisphere as well as one for the Southern Hemisphere.

The csv_to_html.ipynb is a short Jupyter Notebook in which I convert the original csv file into html, which is rendered as a data frame on the webpage data.html.

This website is hosted on github, with index.html referencing all the other pages. Additionally, each webpage has a header linking to the other webpages.

The url is: https://dkoski23.github.io/Web-Design-Challenge/
