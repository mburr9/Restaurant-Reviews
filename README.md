# Front End Nanodegree Project
---

## Project Overview:

For the **Restaurant Reviews** project, I will convert a static webpage to a mobile-ready web application. I will take a static design that lacks accessibility and convert the design to be responsive on different sized displays and accessible for screen reader use. I will also add a service worker to begin the process of creating a seamless offline experience for my users.

### Viewing the App

1. In this folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer.

In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python3 -m http.server 8000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.

2. With your server running, visit the site: `http://localhost:8000`

## Leaflet.js and Mapbox:

This repository uses [leafletjs](https://leafletjs.com/) with [Mapbox](https://www.mapbox.com/).

### Using the App

On the home page the user will be presented with a map pinpointing restaurants and further information cards on the restaurants below. The user can filter the results of restaurants shown on the map and cards by using the filter results dropdowns to filter by neighborhoods or cuisines. Users can view further information such as restaurant hours and reviews by selecting a restaurant either by clicking on its map pin or clicking on its view details button. This will take the user to a separate page detailing the single restaurant chosen. The user can return to the main page by clicking on the home button or on the Restaurant Reviews heading on the top of the page.
