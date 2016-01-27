# rebound on binder

I made this repo because I saw this:

<blockquote class="twitter-tweet" data-conversation="none" data-cards="hidden" data-partner="tweetdeck"><p lang="en" dir="ltr">Go to <a href="https://try.jupyter.org">https://try.jupyter.org</a> and create a new Python 3 notebook. Then copy and paste the code from <a href="https://gist.github.com/hannorein/837f53855a4120b87150">https://gist.github.com/hannorein/837f53855a4120b87150</a> to your notebook</p>&mdash; Astrotweeps: Hanno (@astrotweeps) <a href="https://twitter.com/astrotweeps/status/692019639912652800">January 26, 2016</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

[try.jupyter.org](https://try.jupyter.org) is a locked-down instance of [tmpnb](https://github.com/jupyter/tmpnb) for trying out Jupyter notebooks. You cannot install packages, or load your own notebooks, so it can be inconvenient to load your own code or data into it.

[Binder][] is a cool tool that lets you build your own tmpnb instance from any GitHub repo,
installing packages and loading your notebooks. It's basically tmpnb with custom packages and content, which is super cool.

This example installs [rebound](https://github.com/hannorein/rebound) via requirements.txt and contains one of the rebound demo notebooks copied from the repo.

[Binder]: https://mybinder.org

Try it out:

[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org/repo/minrk/rebound-binder)
