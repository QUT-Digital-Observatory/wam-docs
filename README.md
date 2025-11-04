# wam - Web Archive Manager 

The Web Archive Manager (WAM) is part of the toolkit to aid researchers in working
with web archives. Our aim is to enable usage of archives as a research data source.

WAM allows you to organise, replay, and annotate your archive files (.wacz or .warc). You can also use WAM to scrape data into structured formats.

WAM is developed by [QUT Digital Observatory](https://www.digitalobservatory.net.au/), as part of the [Australian Internet Observatory (AIO)](https://internetobservatory.org.au/). AIO received co-investment ([doi.org/10.3565/hjrp-b141](https://doi.org/10.3565/hjrp-b141)) from the Australian Research Data Commons (ARDC) through the [HASS and Indigenous Research Data Commons](https://ardc.edu.au/hass-and-indigenous-research-data-commons/). The ARDC is enabled by the National Collaborative Research Infrastructure Strategy (NCRIS).

Please share your feedback by emailing us at digitalobservatory@qut.edu.au.

## User guide

Visit https://wam.digitalobservatory.net.au/ for detailed user documentation.

## Maintaining the user guide

To preview the site locally, Quarto is required. If you don't have it already, you can install it from https://quarto.org/docs/get-started/.

To preview the site, in this directory, run:

```bash
quarto preview
```

To publish changes to the site, in the main directory of the repository, run:

```bash
quarto publish gh-pages
```