# Accelerate GIS data processing by up to 10000x.

This [presentation](https://www.eventbrite.ca/e/accelerate-gis-data-processing-by-up-to-10000x-tickets-224151722837) was given on 16Dec2021. It shows how to switch from Pandas to cuDF.

### 1. cuDF compared to Pandas

The [movies](movies.ipynb) notebook compares the cuDF API to the Pandas API. In many cases switching code from CPU to GPU is seamless. In other cases some adjustments are required. Click here to [download](https://bsql.s3.amazonaws.com/data/rapids_intro/movies.csv) the data.

### 2. GPU compared to CPU

The [babynames](babynames.ipynb) notebook compares performance between a single GPU and a single CPU. All tests showed double digit performance improvements when run on a Tesla P4. Results will vary depending on the system environment. Click here to [download](https://www.ssa.gov/oact/babynames/state/namesbystate.zip) the data.
