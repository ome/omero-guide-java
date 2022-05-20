# User guides for the OMERO Java API

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ome/omero-guide-java/master?filepath=notebooks)
[![Documentation Status](https://readthedocs.org/projects/omero-guide-java/badge/?version=latest)](https://omero-guides.readthedocs.io/en/latest/java/docs/index.html)
[![Actions Status](https://github.com/ome/omero-guide-java/workflows/repo2docker/badge.svg)](https://github.com/ome/omero-guide-java/actions)
[![Actions Status](https://github.com/ome/omero-guide-java/workflows/sphinx/badge.svg)](https://github.com/ome/omero-guide-java/actions)

This guide demonstrates how to use the OMERO Java API.

To run the notebooks, you can either [run on mybinder.org](https://mybinder.org/v2/gh/ome/omero-guide-java/master?filepath=notebooks) or build locally with [repo2docker](https://repo2docker.readthedocs.io/).

To build locally:

 * Create a virtual environment and install repo2docker from PyPI.
 * Clone this repository
 * Run ``repo2docker``

```
pip install jupyter-repo2docker
git clone https://github.com/ome/omero-guide-java.git
cd omero-guide-java
repo2docker .
```


This a Sphinx based documentation. 
If you are unfamiliar with Sphinx, we recommend that you first read 
[Getting Started with Sphinx](https://docs.readthedocs.io/en/stable/intro/getting-started-with-sphinx.html).

When creating a new repository, this template could be used.

The values in ``docs/conf.py`` should be replaced by the name of your project.
