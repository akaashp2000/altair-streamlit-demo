# Altair & Streamlit Demo

This repo contains examples of Altair visualisations and Streamlit dashboards.

It aims to show:
* interactive Altair visualisations in notebooks compared to static their static counterparts in Seaborn
* Streamlit dashboard built on Altair Chart objects, and with some widgets native to Streamlit

Here are two examples based on dummy/example datasets:

* Cars dataset (Vega datasets): 
  * based on a [blog post](https://sakizo-blog.com/en/586/)
  * creates a Streamlit dashboard, using Streamlit widgets like sliders.
  * added a notebook to show a corresponding plot and slider in Altair
* Dummy sales data: 
  * based on a [blog post](https://blog.streamlit.io/drill-downs-and-filtering-with-streamlit-and-altair/)
  * creates a Streamlit dashboard based on a single Altair chart...
  *   ... with selection filters are for the Altair chart (rather than the Streamlit selectors as in cars_examples)
  * added a notebook to show corresponding plots in Altair

## Instructions for use:

### Setup

1. Clone the repo.

``` git clone https://github.com/akaashp2000/altair-streamlit-demo.git ```

2. Navigate to the repo and install the requirements (in a virtual environment if you wish).

``` pip install -r requirements.txt ```
