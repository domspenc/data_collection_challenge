<h1>Mars Data Collection Challenge</h1>
<img
        src="https://www.nasa.gov/wp-content/uploads/2019/08/mars_landscape_dry_wet_0.png?resize=768,432"
        alt="Rendering of Mars, Earth and the Sun"
        width="650"
      />
</br>
<h3><u>Description</u></h3>
<p>
This repository contains two parts, both of which contain data from websites about the planet Mars.</br>
BeautifulSoup, Splinter, Pandas and HTML Parsing were utilised to perform web scraping and data analysis on these websites.
</p>
</br>
<h3><u>Part 1: Mars News</u></h3>
</br>
<p>A Mars news website was scraped to retrieve certain HTML elements and build them into a list of json dictionaries. These dictionaries contain the header and preview text of each news story.</p> 
</br>
<h5>The following steps were taken:</h5> 
</br>
<p>🌏 Use automated browsing to visit the Mars News site. Inspect the page to identify which elements to scrape.</p> 
</br>
<p>🌏 Create a Beautiful Soup object and use it to extract text elements from the website.</p> 
</br>
<p>🌏 Extract the titles and preview text of the news articles that you scraped, then store each title-and-preview pair in a Python dictionary.</p> 
</br>
<p>🌏 Store all the dictionaries in a Python list.</p> 
</br>
<p>🌏 Print the list in your notebook.</p> 
</br>
<p>🌏 Optional: export the scraped data to a JSON file.</p>
</br>
<h3><u>Part 2: Mars Weather</u></h3></br>
<p>A website containing a table of weather data taken from Mars over a period of time was scraped and put into a Pandas dataframe for further analysis.
</br>
The following steps were taken:</p> 
</br>
<p>🌏 Use automated browsing to visit the Mars Temperature Data site. Inspect the page to identify which elements to scrape.</p> 
</br>
<p>🌏 Create a Beautiful Soup object and use it to scrape the data in the HTML table.</p> 
</br>
<p>🌏 Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website.</p> 
</br>
<p>🌏 Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate datetime, int, or float data types.</p> 
</br>
<p>🌏 Analyse your dataset by using Pandas functions to answer the following questions:</p>
<ol><li>How many months exist on Mars?</li> 
<li>How many Martian (and not Earth) days worth of data exist in the scraped dataset?</li>
<li>What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:</li>
<ul><li>Find the average minimum daily temperature for all of the months.</li>
<li>Plot the results as a bar chart.</li>
</ul>
<li>Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:</li>
<ul><li>Find the average daily atmospheric pressure of all the months.</li>
<li>Plot the results as a bar chart.</li>
</ul>
<li>How many Martian (and not Earth) days worth of data exist in the scraped dataset?</li> 
<ul><li>Consider how many days elapse on Earth in the time that Mars circles the Sun once.</li>
<li>Visually estimate the result by plotting the daily minimum temperature.</li>
</ul>
</ol>
</br>
<p>🌏 Export the DataFrame to a CSV file.</p>
</br>
<p>----------------------------------------------------------</p> 
</br>
<p>Thank you for reading!</p> 
<h3>🚀🚀🚀</h3>
</br>
<p><a>I utilised some additional resources for this project, in particular AskBCS.</a></p>
</br>
<p><a>Image sourced from nasa.gov</a></p>
</br>
<p><a>NASA quote sourced from https://www.jpl.nasa.gov/edu/learn/video/mars-in-a-minute-how-long-is-a-year-on-mars/#:~:text=The%20Earth%20zips%20around%20the,days%20%E2%80%93%20or%20one%20Mars%20year.</a></p>
