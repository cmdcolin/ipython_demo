## Quick-start Tutorial

Here we will start with some basic steps to start you down the road
for becoming a developer!

Let's start by forking the repo on github, and then creating a clone.

    git clone https://github.com/yourusername/ipython_demo.git

You can try changing the text of this README, then using `git commit`
and `git push` to upload your changes

    git add README.md
    git commit -m "Updated README"
    git push

If all goes well, this will be pushed to your repo!

## IPython demo

To test out the IPython notebook functions in github, we will look at
the recent news about this nice synergy.

https://github.com/blog/1995-github-jupyter-notebooks-3

Then let's just try and install IPython notebook (aka Jupyter) and
Matplotlib:

    pip install ipython[notebook]
    pip install matplotlib
    ipython notebook


This will launch a web-based based jupyter shell and we can use this
for interactively coding our demo.


Note: if you have trouble with these steps, feel free to ask me but
also note that the demo notebook will run on github even if you don't
have these packages installed to your computer


Mac OSX note: It is likely better to use a homebrew version of python
because otherwise there are errors about missing "Python.h"
