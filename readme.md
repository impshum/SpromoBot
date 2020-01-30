## SPROMOBOT

Posts submissions to chosen subreddit at chosen times of the day

![](ss.jpg)

### Instructions

-   Install requirements `pip install -r requirements.txt`
-   Create Reddit (script) app at <https://www.reddit.com/prefs/apps/> and get keys
-   Edit conf.ini with your details
-   Create posts as .md files in the `/posts` directory
-   Run it `python run.py`

### Settings Info

-   `target_subreddit` - Bot account must be mod
-   `schedule_times` - Times of day to post (comma separated) e.g `09:30,22:15`
-   `test_mode` - Run the script without posting

### Notes

-   If there is more than 1 .md file in the `/posts` directory a post will be chosen randomly each run.
-   There are 2 example post files in `/posts` for you to edit/copy/delete.
-   If you're not using Unix you won't see the colours in the terminal (command prompt). Follow [THIS](https://recycledrobot.co.uk/words/?print-python-colours) tutorial to get them working.
-   I will not be held responsible for any bad things that might happen to you or your Reddit account whilst using this bot. Follow Reddiquette and stay safe.

### Tip

BTC - 1AYSiE7mhR9XshtS4mU2rRoAGxN8wSo4tK
