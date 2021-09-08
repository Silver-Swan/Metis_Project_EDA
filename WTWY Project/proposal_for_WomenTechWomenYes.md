# Effective Locations and Times for Collecting Emails

*Questions/Needed*
<br>
  The initial plan is to present what subway station and time or times of day are going to be optimal for gathering people's info to support WomenTechWomenYes. Considering the time or times of day with the most amount of people will help prioritize the placement of their street team.

*Data Description*
<br>
  The turnstile data gathered from the MTA database will be used. The sample will be 3-4 months of every Saturday from June 2021 to August 2021 with the number of people who entered and exited to board the train. The time of day and which streets will also be accounted into the data. This information will help narrow down the location of the street team's placement.

*Tools*
<br>
  I will use DB Browser for SQLite to review the SQL data pulled in from the MTA database. Then use Panda on Jupyter Notebook to clean the data. I will categorize by busiest station and the time of day with the highest frequency.  Then using matplotlib to create a graph.

*MVP Goal*
<br>
  The goal will be showing the stations with the highest frequency of passengers relative to the time the of day. This will further show where the street teams will be placed.
