---
name: "Check your data tool"
status: "beta"
repo:
    name:
    url:
summary: "This tool plays back the data a user has produced to help them check the accuracy."
---

A tool that helps data providers determine whether the data they’ve made is valid and accurate.

[if real thing see example]

## Why we are building this

Through the work with brownfield registers, we learnt that people within local authorities who are responsible for creating and publishing their brownfield registers are not data people.

Often thought they'd done it right. E.g. GeoX GeoY, once shown on map they could see if it was in the right place.

Thought there was a need to help users work out if the data provided met the standard and if the data is accurate.

### Hypotheses

* a tool that helps users determine whether the data they’ve made is valid and accurate will lead to better quality data being published
* users creating and publishing data within local authorities are not from a data background it is therefore difficult for them to know whether they’ve recorded something correctly without seeing it represented in a different way to the data

## What we've done so far

We built an initial validator tool based on the data schema however we learnt that this was too strict and didn’t help users to create more accurate data.

We’ve iterated the tool to show an interpretation of the data as well as highlight where we were unable to process the data. Where we’ve made improvements to the data via the pipeline the user is able to download the harmonised file.

We've built a version that works on brownfield resources. The tool has been built in such a way that it could be relatively easily repurposed for use with another geography dataset.
