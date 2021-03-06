FacetWP - "Time Since" Facet
==================

A [FacetWP](https://facetwp.com/) facet for filtering posts by date / time since a specified interval.

![screenshot](http://i.imgur.com/seie2lY.png)

## Requirements
* FacetWP 2.1 or higher
* WordPress 3.8 or higher

## Installation
* Click the "Download ZIP" button on this page.
* Unzip the folder and rename it to `facetwp-time-since`
* Upload the folder into the `/wp-content/plugins/` directory
* Activate the plugin

## Setup
* **Data Source**: A date; "Post Date", "Post Modified", or a custom field in `YYYY-MM-DD` format
* **Choices**: the list of choices to display (one per line). The label and formatter are separated by a pipe "|".

```
Past Day | -1 day
Past 7 Days | -7 days
Past 30 Days | -30 days
Past 90 Days | -90 days
Past Year | -1 year
Past 5 Years | -5 years
```

The **formatter** is based on PHP's `strtotime` function ([see example](http://php.net/manual/en/function.strtotime.php#example-2417)).
