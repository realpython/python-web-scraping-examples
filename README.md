# python-web-scraping-examples

## BandLeader

The code sample found in `bandleader.py` accompanies [this](hhttps://realpython.com/modern-web-automation-with-python-and-selenium/) post on [realpython.com](https://realpython.com).  It introduces the reader to using Python to control headless web browsers. Specifically, `bandleader.py` lets you play music from [bandcamp](https://bandcamp.com) through your Python shell!

To play around with `bandleader.py`, see the [the tutorial](https://realpython.com/modern-web-automation-with-python-and-selenium/) for setting up, then run something like:


```python

>>> from bandleader import BandLeader
>>> bl = BandLeader('myhistory.csv')
>>> bl.play()            # should start playing a track

>>> bl.play(3)           # plays the third track in the listing

>>> bl.play_next()       # advances the track
 
>>> bl.more_tracks()     # see more music to play with

>>> bl.browser.quit()    # close the webdriver instance

```
