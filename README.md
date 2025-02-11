# R tutorial: Working with EMODnet OGC Web Services
#### Written by Pascal Derycke (EMODnet Secretariat) and Laurent Dubroca (Ifremer), edited by Tim Collart (EMODnet Secretariat) and Lennert Schepers (VLIZ)

Instead of downloading EMODnet data to your local machine before using it for your application,  you can also access data directly from the web into your data analysis environment. In this tutorial, we will use the [statistical programming language R](https://www.r-project.org/) to access EMODnet map images, data and metadata.

The EMODnet data portals allow web acces to map images, data and metadata through [Open Geospatial Consortium (OGC) Web Services](https://www.opengeospatial.org/standards/owc). This is a set of standards which allow to transfer geospatial data and metadata over the web. We will show following services available from EMODnet:

* [Web Map Service (WMS)](https://www.opengeospatial.org/standards/wms): Allows you to download geo-referenced map images

* [Web Feature Service (WFS)](https://www.opengeospatial.org/standards/wfs): Allows you to download geospatial vector data. There is also an R client under development: [EMODnetWFS](https://emodnet.github.io/EMODnetWFS/)

* [Web Coverage Service (WCS)](https://www.opengeospatial.org/standards/wcs): Allows you to download geospatial raster data

* [Catalogue Service for the Web (CSW)](https://www.opengeospatial.org/standards/cat): Allows you to search the catalogue of metadata to find the dataset you are looking for.

For an introduction to OGC web services and a full list of URL's you can access the [web service doucmentation repository on GitHub](https://github.com/EMODnet/Web-Service-Documentation). The exercises below cover some specific examples of how to acces and search for the data you require for your applications. You are free to use and modify this code in your own work.

The tutorial exists of two parts:
* [Part 1](./EMODnet_web_services_in_R_part1.ipynb) covers interacting with web services from EMODnet Bathymetry, Human Activities, Physics, Seabed Habitats and Geology.
* [Part 2](./EMODnet_web_services_in_R_part2.ipynb) covers interacting with web services from EMODnet Biology and the EMODnet Central Portal catalogue service.

You can also run the tutorial interactively with Binder:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/EMODnet/OGC-Webservices-R-Tutorial/main?urlpath=lab/tree/EMODnet_web_services_in_R_part1.ipynb)

-----------------------------------------------------------------------------------------------------------
<center> Provided by EMODnet. See our <a href=https://emodnet.ec.europa.eu/en/terms-use-emodnet-online-services-data-and-data-products> terms of use </a>.</center>
<center><a href="https://emodnet.ec.europa.eu/"><img style="float: None" style="border-width:0" src="https://emodnet.ec.europa.eu/sites/emodnet.ec.europa.eu/files/public/emodnet_logos/web/EMODnet_standard_colour.png" /></a>
</center>