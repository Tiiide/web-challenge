# web-challenge
Homework for Module 11 - Data Collection


For this challenge, we are provided with two static websites containing data in table format that we need to scrape, transform, and analyze.

In Part 1, I located news article titles and text previews by identifying the html class identifying each list.

After verifying the text from the first article scraped returns the expected results, I created a loop to scrape each article and add the data into a separate dictionary within a list.

Once my list of dictionaries is finished, I convert it into a DataFrame and output it to a JSON file before quitting the browser.

In Part 2, I have a web page with a single table containing a large list of data regarding Mars weather.

Similar to Part 1, I identify the text by locating the html class identifying each row of data.

With the rows identified, I separated each value based on index location within the row to return as separate variables.

Then, the data is converted into a DataFrame, I converted data types as necessaray, and created some visualizations around the data.

Sources
https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.to_json.html