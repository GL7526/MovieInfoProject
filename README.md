# Show Genres
This is a project that looks into the most popular genres today for TV shows, worked on by Lucas Myer and George Lin. 
<!--
# \***GIT FILES ARE CURRENTLY A WORK IN PROGRESS\***
-->
<!--files are currently hard to read on git but a lot more easily readable in a jupyter notebook //// currently removed ipynb, will replace in a bit-->


<br>

## Gathering Data
<p> Information on the top 100 shows were webscraped from the IMDb website. The rankings were averaged for each genre. To do this, each show that had multiple genres had its ranking taken into account for each of its genres. Although this is a rough metric to use, it was able to provide insight into what genres are currently trending. </p> 
<p> Afterwards, information on the top 380 shows was gathered from The Movie Database's API. The metric for popularity used here is The Movie Database's "Popularity Score," whose calculations are hidden but told to be from various relevant stats, which include: </p>

<ul>
  <li>"Number of votes for the day</li>
  <li>Number of views for the day</li>
  <li>Number of users who marked it as a "favourite" for the day</li>
  <li>Number of users who added it to their "watchlist" for the day</li>
  <li>Next/last episode to air date</li> 
  <li>Number of total votes</li> 
  <li>Previous days score</li>
</ul>
<br>

## Results

### IMDb
Below is a bar graph showing the average ranking for each genre. The lower the ranking's value, the more popular the genre is\:
<br>
<img src = "/graphs/avg%20popularity%20rating%20per%20genre%20bar.jpg" width = 700>
<br>
According to The top 5 most popular genres are Fantasy, Animation, Horror, Romance, and Adventure.


<br>

### The Movie Database (TMDb)
<br>
Below is a graph showing the average popularity scores for each genre. The higher the popularity score, the more popular the genre is:
<br>
<img src = "/graphs/avg%20popularity%20score%20per%20genre%20bar.jpg" width = 700>
<br>
As you can see, the top five most popular genres are Science Fiction, Romance, Horror, Fantasy, and Sci-Fi & Fantasy, where Sci-Fi & Fantasy is actually a separate category from both Science Fiction and Fantasy. One potential implication of this is that if Fantasy is added to Science Fiction or vice versa, the popularity would drop compared to the popularity the show would have had if either genre were alone.
<br><br>
Below shows a box plot that compares the popularity scores for each genre: 
<br>
<img src = "/graphs/avg%20popularity%20score%20per%20genre%20box.jpg" width = 700>
<br>
The genres that stand out with the highest medians are Science Fiction, Romance, Horror, and Fantasy.

<br><br>Zoomed into the top 9 ranked by median:
<br>
<img src = "/graphs/avg%20popularity%20score%20per%20genre%20box%20zoomed.jpg" width = 700>
<br>

## Conclusion
The information from both IMDb and TMDb tells us that the most popular genres are Fantasy, Horror, Science Fiction, Romance, and Animation, with a few other genres in very close competition. If we were to create a new show for a streaming platform similar to Netflix, these genres would be safe to stick to. 
<br>
One thing to note, however, is that there are relatively few shows that are considered Science Fiction, Romance, and Horror from the data. You can even see that there is only one observation of a Science Fiction show from the box plots. Another way to view this is that this is an emerging niche. Even though there are currently few shows at the top, those that do become popular do relatively "well." 
