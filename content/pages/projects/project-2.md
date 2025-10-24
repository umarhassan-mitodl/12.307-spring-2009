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

You can read about the experiment in the Weather in a Tank project: [Fronts: An Introduction](http://weathertank.mit.edu/links/projects/fronts-an-introduction)

## Atmospheric Data

Relevant Notes at the Weather in a Tank Web site: [The Polar Front](http://weathertank.mit.edu/links/projects/fronts-an-introduction/fronts-atmosphere-the-polar-front) and [Synoptic-scale Fronts](http://weathertank.mit.edu/links/projects/fronts-an-introduction/fronts-atmosphere-synoptic-scale-fronts)

### Polar Front

**Mean fields:** Use climatological data to verify thermal wind balance across the polar front.

- Use the MATLAB script ({{% resource_link "aab37320-8abd-9a83-73c1-c55e9dceed21" "M" %}}) to compute the temperature gradient and vertical wind shear.

Mid-latitude cyclones and the polar front

Instantaneous fields

1) Plot the 500 mb temperature over the Northern Hemisphere, using [GDCNTR](https://www.unidata.ucar.edu/software/gempak/man/prog/gdcntr.html) (area: nhem)

2) Using the same date, plot the Southern Hemisphere 500 mb temperature: using [GDCNTR](https://www.unidata.ucar.edu/software/gempak/man/prog/gdcntr.html) (area: shem)

3) Compare your plots to the appropriate satellite image

### Satellite Images (Polar view)

Warm and cold fronts

3) Find the corresponding [Surface Analysis](http://weather.unisys.com/archive/sfc_map/)

- Suggested dates: 11/22/07 (18z), 2/6/08 (18z), 3/2/08 (18z), 12/15/08 (00z), 3/11/09 (00z)

4) Plot the 850 mb temperature using [GDCNTR](http://cmpo4.mit.edu/gempk/gdcntr.asp)

- Suggested changes — GDFILE: regional, GLEVEL: 850, GFUNC: tmpc, CINT: 2
- To zoom in, pick state in the center of interest – enter the state abbreviation in GAREA with a dash at the end, e.g. MA - (the dash is to zoom out)

5) Using [gdcross](https://www.unidata.ucar.edu/software/gempak/man/prog/gdcross.html) might be helpful in determining the slope of the front, - gfunc=hght; cint=200 (height is in meters)

Other links:

- [Satellite images (Naval Research Laboratory- Monterey)](https://www.nrl.navy.mil/News-Media/Images/igsearch/Satellite/igsort/UploadDate/)