some fun NBA data
---

interesting data that I've scraped from stats.nba.com

---

Shots data
---
The NBA has been tracking the exact location (x, y coordinates) of every single shot that's been taken since the 2001-02 season.

shotsdata.txt is a dump of this data from a Postgres database. 

This is the data that is used to generate visualizations like the one below.

![chart]

[chart]: Shotchart_1474848712899.png

To import it, run:

```
psql yourdb < shotsdata.txt 
```
