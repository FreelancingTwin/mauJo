# [mauJo](https://maujo.netlify.app/)
## Table of Contents
1. [General Info](#general-info)
2. [Technologies](#technologies)
3. [Installation](#installation)
4. [Collaboration](#collaboration)
5. [Bugs](#bugs)
### General Info
***
A Cafe website I built for one I found on Instagram, just a passion project. Played with the Google Places API, and brushed up fundamentals with UI/UX, and CSS responsiveness.
[Alt link to site](http://maujo.surge.sh)

___Note___: App depends on the [Maujo-api](https://github.com/FreelancingTwin/mauJo-api) repo to fetch reviews and fonts.
### Screenshot
![Screenshot](https://github.com/FreelancingTwin/mauJo/blob/main/assets/screenshot.png)
## Technologies
***
A list of technologies used within the project:
* [Cors](https://www.npmjs.com/package/cors): Version 2.8.5 
* [Express](https://www.npmjs.com/package/express): Version 4.18.2
* [Node-fetch](https://www.npmjs.com/package/node-fetch): Version 3.3.1
* [DateRangePickerCalendarCssCdn](https://cdn.jsdelivr.net/npm/daterangepicker/daterangepicker.css)
*[DateRangePickerCalendarJSCdn](https://cdn.jsdelivr.net/npm/daterangepicker/daterangepicker.min.js): For the bookings Calendar css and behaviour
* [Jquery](https://cdn.jsdelivr.net/jquery/latest/jquery.min.js): Dependency for the DateRangePicker cdn, helps write behaviour.
* [MomentJs](https://cdn.jsdelivr.net/momentjs/latest/moment.min.js): Dependency for DateRangePicker, gives timings.
* [ChartJs](https://cdn.jsdelivr.net/npm/chart.js): For the Bar Graphs.
* [GoogleMapsPlacesAPI](https://console.cloud.google.com/): (Link to GCP, find APIs to play with here.)
* [FontAwesome](https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css): Version 6.4.0. For Icons.
* [Netlify](https://netlify.com) / [Surge](https://surge.sh): For hosting client-side 
* [Render](https://render.com): for server side api.
## Installation
*** 
<!-- ```
$ git clone git@github.com:FreelancingTwin/mauJo.git 
$ cd maujo
$ npm install
``` -->
(Install live server VS code extension and) Go live on live server.

<!-- ## Collaboration -->
***
<!-- Give instructions on how to collaborate with your project.
> Maybe you want to write a quote in this part. 
> Should it encompass several lines?
> This is how you do it. -->
## Collaboration
***
I had a minor breakdown making google apis work. Trouble was my server wasn't going live, so, no fetching happening. Turned out, I'd needed to host the server separately. Or, now that I think of it, maybe make this an express app. 

### Thanks to [Abhigyan](https://github.com/ABHIGYAN-MOHANTA) for pointing me to [The MERN stack vid](https://www.youtube.com/watch?v=CvCiNeLnZ00) from Dave Gray.

## Bugs
***

1. __Video tags won't autoplay on load in some browsers__ 
>On some browsers* The video tags default to the poster. If you know fixes, I'm ears.

