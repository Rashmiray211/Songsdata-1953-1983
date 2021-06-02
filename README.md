# Songsdata-1953-1983
I did a project called "Socio economic and political analysis through Bollywood songs" under Tatras data. That project aimed at capturing the mood of the nation through the
analysis of the top Bollywood songs and the Bollywood movies. For that, I scraped some data. I uploaded that data scraping code here.

Here I have extracted: 'Year','song_name','song_lyrics','Genre','composer','Lyricist','movie','actors','singers' of every song for year 1983 and also for period 1953-1983. I have scraped this data from "geetmala".
For every year, I looked at the number of pages( on an average, every year had 4 pages).
For each page, I extracted the hrefs of songs(after comparing with other hrefs) contained in that page. Then I appended hrefs of all pages of a year and converted into urls.
From these urls(urls of songs), I extracted out: 'Year','song_name','song_lyrics','Genre','composer','Lyricist','movie','actors','singers'.
After this, I stored all this data in a csv file.
Please look at the code, it will help you to understand.
