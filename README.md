
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Eumaeus/gifts_bearing_greek/master?filepath=index.ipynb)

# Furman University · GIFTs Bearing Greek


This repository hosts Jupyter Notebook that use Scala and some simple plain-text template-files to generate [`.gift` formatted quiz questions compatible with Moodle.](https://docs.moodle.org/38/en/GIFT_format)

Some example GIFT files are in the `gifts` directory. Documentation is "by example" for now (note the euphemism… things are busy ’round here).

These notebooks use the [Almond kernel](https://almond.sh/).  You can run a notebook server with the Almond kernel using a docker container like this:

    docker run -it --rm -p 8888:8888 almondsh/almond:0.9.0

You can also work interactively with these notebooks on [mybinder.org](https://mybinder.org/v2/gh/Eumaeus/gifts_bearing_greek/master?filepath=index.ipynb).

**If you use MyBinder, and get a "Kernel not found" notice, choose "Scala 2.12." and click "Set Kernel".**

If you have Jupyter Notebooks installed locally, with the Almond kernal, you can run this with:

    jupyter notebook

This work is based on that of [Neel Smith](https://github.com/neelsmith/nomisma-jupyter).

