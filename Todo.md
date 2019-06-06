## Notes about Github:
**How to update the repo:**
```
Do work
git add .
git commit -m "update..."
git pull
git push
```



##TODO
### Data Cleaning & Prep
* merge two datasets
* GOAL
  * Billboard: albums
  * Extra cols where IF putch review exists then put data. Otherwise use NAN / NULL Values
  * Merge on Album
  * Multiple albums of same name by different artists

### Stuff to look at:
* acoustic features of songs
* Pitchfork reviews
  * What they *dont* review
  * What they *do* review that *arent* on BB200
  * Histogram of Categories (genres) are most ignored by PF
  * 


**MErggin:**
    Left Merge
Problem: Albym names

**Data**
    BB
    date    date on bb
    artist
    album
    rank
    length


    Pitchfork
    date    review date


    AF
    date    release date
    
    Idea:   DO PCA!

