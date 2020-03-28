
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Eumaeus/gifts_bearing_greek/master?filepath=index.ipynb)

# Furman University · GIFTs Bearing Greek


This repository hosts Jupyter Notebook that use Scala and some simple plain-text template-files to generate [`.gift` formatted quiz questions compatible with Moodle.](https://docs.moodle.org/38/en/GIFT_format)

Some example GIFT files are in the `gifts` directory. Documentation is "by example" for now (note the euphemism… things are busy ’round here). Please send questions, though, to <christopher.blackwell@furman.edu>.

These notebooks use the [Almond kernel](https://almond.sh/).  You can run a notebook server with the Almond kernel using a docker container like this:

    docker run -it --rm -p 8888:8888 almondsh/almond:0.9.0

You can also work interactively with these notebooks on [mybinder.org](https://mybinder.org/v2/gh/Eumaeus/gifts_bearing_greek/master?filepath=index.ipynb).

**If you use MyBinder, and get a "Kernel not found" notice, choose "Scala 2.12." and click "Set Kernel".**

Also, if [MyBinder](https://mybinder.org/v2/gh/Eumaeus/gifts_bearing_greek/master?filepath=index.ipynb) seems to give up at some point, or thows an error, close the browser window and browse to the link a second time; that often helps. I think MyBinder is getting a lot of load right now.

If you have Jupyter Notebooks installed locally, with the Almond kernal, you can run this by `cd`ing to the root of its directory, and doing a:

    jupyter notebook

This work is based on that of [Neel Smith](https://github.com/neelsmith/nomisma-jupyter).

