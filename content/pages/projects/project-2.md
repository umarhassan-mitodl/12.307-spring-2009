---
content_type: page
description: This section features a project to inspect fronts crossing the country
  associated with day-to-day variations in the weather using real-time atmospheric
  observations.
draft: false
learning_resource_types:
- Projects
ocw_type: CourseSection
parent_title: Projects
parent_type: CourseSection
parent_uid: 02f674ca-fc93-9887-46a3-aa77b970ad59
title: 'Project 2: Fronts'
uid: 6e3412d8-9eb9-74a9-830a-26714d44d10d
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---
In this project, we inspect fronts crossing the country associated with day-to-day variations in the weather using real-time atmospheric observations. In the laboratory we create fronts by allowing salty (and hence dense) columns of water to collapse under rotation and gravity. We discover that the observed changes in winds and temperature across our laboratory and atmospheric fronts is consistent with Margule's formula (a discrete form of the thermal wind equation) and see that the dynamical balance at work in the atmosphere is the same as in the density fronts created in the rotating tank.

Project Description ({{% resource_link "a90f647c-277b-1526-ce52-4c62d11d4584" "PDF" %}})

Notes on relevant theory: thermal wind ({{% resource_link "b5b2713a-ee98-4296-0630-961e0e4e7a52" "PDF" %}})

## Tank Experiments

You can read about the experiment in the Weather in a Tank project: {{% resource_link "8b58d819-66ba-4d90-af92-fed191e77476" "Fronts: An Introduction" %}}

## Atmospheric Data

Relevant Notes at the Weather in a Tank Web site: {{% resource_link "45612e1c-b7fa-4dc3-ae61-e5b9afeb83c1" "The Polar Front" %}} and {{% resource_link "22ecb9d1-caaa-40b0-8096-120c060c6a00" "Synoptic-scale Fronts" %}}

### Polar Front

**Mean fields:** Use climatological data to verify thermal wind balance across the polar front.

- Use the MATLAB script ({{% resource_link "aab37320-8abd-9a83-73c1-c55e9dceed21" "M" %}}) to compute the temperature gradient and vertical wind shear.

Mid-latitude cyclones and the polar front

Instantaneous fields

1) Plot the 500 mb temperature over the Northern Hemisphere, using {{% resource_link "af17f4d8-2b45-459d-a41b-c15d89fed5d2" "GDCNTR" %}} (area: nhem)

2) Using the same date, plot the Southern Hemisphere 500 mb temperature: using {{% resource_link "af17f4d8-2b45-459d-a41b-c15d89fed5d2" "GDCNTR" %}} (area: shem)

3) Compare your plots to the appropriate satellite image

### Satellite Images (Polar view)

Warm and cold fronts

3) Find the corresponding {{% resource_link "f78b2cbb-d47d-4704-be7f-ff37483083af" "Surface Analysis" %}}

- Suggested dates: 11/22/07 (18z), 2/6/08 (18z), 3/2/08 (18z), 12/15/08 (00z), 3/11/09 (00z)

4) Plot the 850 mb temperature using {{% resource_link "963a30fd-e0b6-43e2-ae66-fc5626a6fc9a" "GDCNTR" %}}

- Suggested changes — GDFILE: regional, GLEVEL: 850, GFUNC: tmpc, CINT: 2
- To zoom in, pick state in the center of interest – enter the state abbreviation in GAREA with a dash at the end, e.g. MA - (the dash is to zoom out)

5) Using {{% resource_link "3d8664b2-5cd9-4411-b99c-bf2fe94debe2" "gdcross" %}} might be helpful in determining the slope of the front, - gfunc=hght; cint=200 (height is in meters)

Other links:

- {{% resource_link "2106e2ad-4a9a-44ac-8ca7-b06790762016" "Satellite images (Naval Research Laboratory- Monterey)" %}}