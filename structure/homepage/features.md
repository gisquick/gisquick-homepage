# Features

Configure in QGIS, publish with Gisquick

## Made for QGIS environment
[QGIS](https://qgis.org) is open source GIS software and usually it refers to
the desktop application. But there is more happening around QGIS, such as
[QGIS-server](https://docs.qgis.org/3.16/latest/docs/server_manual/index.html) for data rendering on the server side,
[QField](https://qfield.org/) mobile application and others.

There is strong connection to the [GDAL](https://gdal.org) - geodata abstraction
library, [Postgis](https://postgis.org) geospatial database extension. We rely
on the [Python](https://python.org) programming language.

## Open source, open standard

Gisquick is Free software, published under the GNU/GPL license. It is respecting
the license of the original product - QGIS - and gains from it's features.

Where possible, Gisquick relies on open standards, such as [Open Geospatial
Consoritum (OGC)](https://opengeospatial.org) (such as WMS, WFS and others), [GeoJson](https://geojson.org)
and others. This enables to the user not only use the graphical user interface,
but also connect to the published services with their applications.

## On the shoulders of the giants

Gisquick uses [QGIS-server](https://docs.qgis.org/3.16/latest/docs/server_manual/) for 
the data publishing. [OpenLayers](https://openlayes.org) for map display.
[Vue.js](https://vuejs.org) library for the graphical user interface.
[Docker](https://docker.com) for containers and orchestration.

## Publish map on the web as you designed it with QGIS
We try to bring most of the functionality of QGIS-desktop mapping platform to the web. Gisquick uses
QGIS-server for data rendering.

* Single click project publishing with the Gisquick plugin
* Prepare printing templates with QGIS, use them on the web
* Use QGIS themes on the web

## User and rights management

This feature goes behind QGIS functionality, since QGIS is single-user platform.
But it is necessary, if you want to publish data on the web and maybe want even
more.

Within Gisquick, you can define users, groups and add their rights for viewing
and feature editing. Each user (as well as public) can see different map and
advanced users will be able to edit the attributes and geometries.

## Feature editing

Gisquick enables you to edit vector data features. You can change geometries in
the map as well as change feature attributes using advanced editing forms. Data
editing for normal users, not only GIS experts is possible.

## Vector feature filtering

Finding the right features is essential. Gisquick's data table helps you to
filter out the feature(s), you are looking for using simple graphical filtering
tool. No SQL knowledge needed, just intuitive selection.

## Data export

Once Gisquick is data publishing platform: not only viewing, but also data
export is essential. Users can download copy of the data in common GIS formats
as well as e.g. CSV for further processing. Need informations for the meeting?
Filter vector features and export to table calculator with the next click.

## Customisation of the feature detail panel

We provide basic view of the feature detail, which is suitable not only for
feature representation, but also for the attribute editing, using various common
data types, such as short strings, long texts, date and time, numbers, external
links, images and more.

But for some special applications, this might not be enough. Therefore Gisguick
has option for adding custom template for feature detail, which can be adjusted
using JavaScript code. With this feature, one can display dynamic data,
interactive graphs and much more.

## Responsive design

You never know, where your map will pop up. It can be big screen of your desktop
computer, smaller screen of the laptop, tablet or even cell phone. Each device
has different screen size and resolution, every device has different way to be
controlled - with mouse or fingers.

Gisquick uses responsive design and works on all devices from the desktop to the
cell phone. Graphical interface will change accordingly.
