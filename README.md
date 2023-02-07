# Midterm_project_bandcamp

Simone Broggini and Henrik Gerhard

Repository for our midterm project which will be an analysis of 1,000,000 items from Bandcamp's sales feed between 9/9/2020 and 10/2/2020

Source: https://www.kaggle.com/datasets/mathurinache/1000000-bandcamp-sales?resource=download

Preliminary Research

0. How does bandcamp work? How does bandcamp make profit?

Data Visualization 

1. Exploratory Data Analysis with Tableau
2. Visualisation: how do Artists make money on Bandcamp?
3. A look into the future: potential recommendation for the business

Day 1

Understanding the problem and roadmapping
Cleaning the data

Day 2

EDA: what does the dataset tells us?
Identify 3 potential avenues to investigate

Day 3

Visualise business insights and build tableau stories

Day 4

Work on presentation, explain findings

Day 5 

Presentation day

Brainstorming

| Insight | Description |
| --- | --- |
| Sales volume | You can get an understanding of the total number of items sold and the breakdown of sales by type (digital albums, physical items, digital tracks). |
| Sales by country | You can analyze the geographical distribution of sales, including the number of sales in each country, the most popular countries for sales, and the average amount spent per sale by country. |
| Average transaction value | You can calculate the average transaction value by country and by item type. |
| Voluntary contributions | You can analyze the data on amount voluntarily paid over the item price to determine the average amount and the impact of these contributions on total sales revenue. |


More Brainstorming

- bandcamp is NOT a streaming service (but can stream music)
- bandcamp is a way to cut out the middle men (record labels) and connect artists with fans
- bandcamp support artists
- bandcamp takes 15% cut on digital and 10% cut on physical
- bandcamp is a music community

from the founder:

"It definitely started as a digital platform," says Diamond. "In 2007, when we started the company, streaming didn't exist in the United States and our competition essentially was piracy. And the idea in 2007 primarily was that nobody was going to pay for music anymore. And it just seemed very obvious to me that if you like some music from one of your favorite artists, you should be able to support them directly. And so we built the platform to do that. My reference point for this was blogging services. In 2007, you had Blogger, Typepad, Movable Type, services that were essentially like white label services for writers – you could set up a site within minutes and tap this direct relationship with your readers. And it seemed crazy to me that if your artistic output happened to be music instead of words, you were just out of luck."

"And the most promising thing that happened in the early days," Diamond continues, "was we immediately saw people start to actually buy music, which was very exciting. I wasn't sure that was going to happen! And then, one of the fun things that happened was we started to look at the search terms people were using that brought them to a Bandcamp artist's site that led to a purchase. And several times per hour, we were seeing search terms like the name of an album or name of a track plus the word 'torrent,' or plus the word 'Limewire' or 'Kazaa.' You know, this was somebody whose intent initially was just to get the music – I don't know if they were thinking 'I'm pirating the music' – but they were trying to get it for free. But when they saw that they could make a direct purchase to the artist, they wanted to do that. And that just warmed my heart. So that's really what we were trying to do from the beginning, was just make it clear that this was a way to show your direct support for an artist.

More potential insights:

1. Most Popular Item Types: Analyze the item_type and slug_type columns to determine the most popular type of items sold during the specified time frame.

2. Geographical Distribution of Sales: Look at the country_code and country columns to determine the geographical distribution of sales. Find the top countries with the highest sales and map the data to see the concentration of sales.

3. Most Popular Artists: Analyze the artist_name column to determine the most popular artists during the specified time frame.

4. Average Sale Price: Calculate the average sale price of items in each currency and compare them to see which currency has the highest average sale price.

5. Amount Paid Over Item Price: Analyze the amount_over_fmt column to determine the amount paid over the item price by customers. Find the average amount paid over the item price and determine if this trend is consistent across different countries.
