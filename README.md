# Aggregates in R

## Load Packages and Data

- Load required packages: readr, dplyr.
- Load the ad clicks data.

## Inspect Data

- Display the first few rows of the ad clicks dataset.

## Views by UTM Source

- Group the ad clicks data by UTM source.
- Summarize the count of views for each UTM source.

## Clicks by UTM Source

- Group the ad clicks data by UTM source and whether the ad was clicked.
- Summarize the count of clicks for each combination of UTM source and ad click status.

## Percentage of Clicks by UTM Source

- Calculate the percentage of clicks for each UTM source.
- Filter for rows where the ad was clicked.

## Experiment Split

- Group the ad clicks data by experimental group.
- Summarize the count of entries for each experimental group.

## Clicks by Experiment Group

- Group the ad clicks data by ad click status and experimental group.
- Summarize the count of clicks for each combination of ad click status and experimental group.

## Clicks by Experimental Group (A and B)

- Filter the ad clicks data for experimental group A and B separately.

## Clicks by Day for Experimental Group A and B

- Group the filtered data for experimental group A and B by day and ad clicked status.
- Summarize the count of clicks for each day and ad clicked status.

## Percentage of Clicks by Day for Experimental Group A and B

- Calculate the percentage of clicks for each day within experimental group A and B.
- Filter for rows where the ad was clicked.
