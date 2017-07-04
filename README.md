Thesis Tracker – instant gratification from the command line
============================================================

One tip for writing something substantial such as a thesis is to make sure you write a certain amount of text every day.
But tracking your daily progress manually would be a waste of time:
instead, just add a post commit hook to git and let `daily_progress_report.py` do all the work (a little thumps up for hitting your goal included):

[![asciicast](https://asciinema.org/a/K1fx1GmhI7mvNJELb0mu8GB8W.png)](https://asciinema.org/a/K1fx1GmhI7mvNJELb0mu8GB8W)

![](https://vignette4.wikia.nocookie.net/spongebob/images/5/5a/Hours_later.jpg/revision/latest?cb=20160407232054)

[![asciicast](https://asciinema.org/a/rjhSXiuCzBXFSoxdE5XANaDsw.png)](https://asciinema.org/a/rjhSXiuCzBXFSoxdE5XANaDsw)
It is just a proof of concept and has quite strong dependencies (`pandoc` available from source, `wdiff` as well as python packages `gitpython`, `Click`, and `colorama`).
This will not change soon since the time for procrastination is over now...
