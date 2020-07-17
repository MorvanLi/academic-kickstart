+++
# Date this page was created.
date = "2016-10-27"
lastmod = "2018-03-22"

# Project title.
title = "sppt: Spatial Point Pattern Test"

# Project summary to display on homepage.
summary = "Implements several area-based tests that measure the degree of similarity at the local level between two spatial point patterns."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "software-previews/kelsey-knight-452154.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["sppt"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/kelsey-knight-452154.jpg"
caption = ""

+++

[sppt](https://github.com/wsteenbeek/sppt) is an R package that implements several Spatial Point Pattern Tests. The first version of the package started with Martin Andresen's original [Spatial Point Pattern Test](http://www.sfu.ca/~andresen/spptest/spptest.html), but several other functions have been implemented since.

The tests in this package measure the degree of similarity at the local level between two spatial point patterns and is an area-based test. They are not used for the purpose of testing point patterns with the null hypotheses of random, uniform, or clustered distributions, but may be used to compare a particular point pattern with these distributions. One advantage of the tests is that they can be performed for a number of different area boundaries using the same original point datasets.

Apply these tests if you are fundamentally interested in the similarity of two (or more) spatial point patterns for a specified areal unit. Do incidences of some form of cancer have a similar spatial pattern to the locations of known risk factors? Does crime have a similar spatial pattern as drinking establishments? Is the spatial pattern of exports similar to the spatial pattern of imports? Additionally, this spatial point pattern test can be used in longitudinal contexts as well: Is the spatial pattern of crime this year similar to the spatial pattern of crime last year, or ten years ago?

To install the package, follow the instructions on its [GitHub repository](https://github.com/wsteenbeek/sppt).
