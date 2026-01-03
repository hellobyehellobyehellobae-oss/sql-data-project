# sql-data-warehouse-proj

I built this project to show how I can take raw, messy data and turn it into something a business can actually use to make decisions. It covers everything from the "boring" back-end data cleaning to the cool insights at the end.

What I wanted to achieve: I used SQL Server to build a warehouse that brings together sales info from two different places: an ERP and a CRM system. Usually, this data is all over the place, so my goal was to get it into one clean, easy-to-use spot.

How I did it:

The Data: I started with two CSV files.

Cleaning: The data wasn't perfect, so I spent time fixing errors and making sure everything matched up before I started the analysis.

The Setup: I combined both sources into one simple model so that anyone (not just tech people) could run a query and get an answer.

Note: I focused on the most recent data for this project rather than tracking every single change over time.

The Fun Part: The Analytics Once the data was ready, I used SQL to dig into the numbers. I specifically looked for:

Customer Behavior: Who is buying what?

Product Performance: Which items are the "stars" and which aren't selling?

Sales Trends: Are we doing better this month than last month?

Basically, I wanted to create a tool that helps a manager look at a dashboard and instantly know what’s going on with their business.

Option 2: The "Short & Sweet" (Casual & Direct)
This version is even more "human" and gets straight to the point, like a README for a quick personal experiment.

My Data Warehouse & Sales Analytics Project
I put this repository together to practice building a data pipeline from scratch. I wanted to see if I could take two separate datasets (Sales and CRM) and make them talk to each other.

The Engineering Side: I used SQL Server to pull in some CSV files. I had to do a good bit of data cleaning first because, as usual, the raw data had some issues. I didn't worry about historical tracking here—I just wanted a "snapshot" of the latest data that's easy to read and report on.

The Business Side: After the data was cleaned and loaded, I wrote SQL queries to find the "why" behind the numbers. I focused on three things:

How customers are acting.

Which products are actually making money.

Where the sales trends are heading.

It was a great way to practice making sure the "tech" side of data actually helps the "business" side make better choices.
