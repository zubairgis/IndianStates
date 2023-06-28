# Changelog

## v0.23.2 - Jun 28, 2023

**Improvement**

-   Improve exception handling (#1587)
-   Fixed function typo

## v0.23.1 - Jun 24, 2023

**New Features**

-   Added create_grid function for zonal stats (#1582)

**Improvement**

-   Fixed toolbar GUI bug (#1584)

## v0.23.0 - Jun 22, 2023

**Improvement**

-   Separated ee plot gui from the Map class (#1576)
-   Separated toolbar GUI from Map class (#1575)
-   Improved Map.add_netcdf method (#1574)
-   Suppress gdal open raster warning (#1573)
-   Improved Map.add_raster method (#1572)
-   Fixed js-py conversion bug (#1571)
-   Used sorted function instead of if statements (#1569)
-   Added support for downloading images in parallel (#1564)
-   Improved ee_initialize function (#1563)
-   Added typehinting function parameter for better clarity (#1555)
-   Updated layer manager GUI (#1553)

**Contributors**

@slowy07

## v0.22.1 - Jun 1, 2023

**Improvement**

-   Fixed the ipyleaflet SplitControl bug (#1550)
-   Added decimals param for Inspector GUI (#1548)
-   Added decimals param for Inspector GUI (#1548)
-   Add opened param for tool template (#1546)
-   Updated SciPy notebook (#1545)

## v0.22.0 - May 29, 2023

**New Features**

-   Added `Map.add_inspector()` method (#1544)
-   Added `Map.add_layer_manager()` method (#1544)

**Improvement**

-   Simplified the geemap module (#1544)
-   Deprecated the heremap module (#1543)

## v0.21.0 - May 29, 2023

**New Features**

-   Added support for Solara (#1541)
-   Added segmentation notebook (#1539)
-   Added SciPy workshop notebook (#1538)

## v0.20.7 - May 16, 2023

**New Features**

-   Added ee_to_geotiff function (#1519)
-   Added netlify deployment for pull requests (#1516)

**Improvement**

-   Added ee.data.setUserAgent (#1535)
-   Fixed dimensions in timelapse module not accepting number pairs (#1534)
-   Fixed ArcGIS add layer bug (#1518)
-   Fixed for faulty exception handling when request.get raises an exception

## v0.20.6 - Apr 18, 2023

**New Features**

-   Added landsat_scaling function (#1503)

**Improvement**

-   Improved data catalog search GUI (#1496)
-   Fixed ee.Geometry visualization bug (#1495)
-   Fixed plotly import error
-   Updated docker image url

## v0.20.5 - Apr 6, 2023

**Improvement**

-   Moved the repo to gee-community and updated the Repo URL (#1490)
-   Reorganized dependencies (#1489)
-   Dropped support for Python 3.7 (#1486)

## v0.20.4 - Mar 27, 2023

**Improvement**

-   Fixed image export file per band bug (#1481)
-   Added filenames parameter to export image collection (#1478)
-   Removed ipykernel import

## v0.20.3 - Mar 22, 2023

**Improvement**

-   Fixed ipywidgets comm error ([#1474](https://github.com/gee-community/geemap/pull/1474))

## v0.20.2 - Mar 19, 2023

**New Features**

-   Added AmericaView workshop notebook ([#1459](https://github.com/gee-community/geemap/pull/1459))
-   Added geemap docker image ([#1456](https://github.com/gee-community/geemap/pull/1456))
-   Added geemap logo ([#1448](https://github.com/gee-community/geemap/pull/1448))

**Improvement**

-   Cleaned up notebooks ([#1469](https://github.com/gee-community/geemap/pull/1469))
-   Fixed zonal stats by group bug ([#1441](https://github.com/gee-community/geemap/pull/1441))
-   Disable docs search due to large file [#1437](https://github.com/gee-community/geemap/issues/1437)
-   Fixed datapane bug #1450 ([#1452](https://github.com/gee-community/geemap/pull/1452))

## v0.20.0 - Feb 18, 2023

**New Features**

-   Added support for gradio for developing interactive web apps ([#1436](https://github.com/gee-community/geemap/pull/1436))

**Improvement**

-   Updated JRC water product to v1.4 ([#1428](https://github.com/gee-community/geemap/pull/1428))
-   Fixed tar file bug CVE-2007-4559 ([#1419](https://github.com/gee-community/geemap/pull/1419))
-   zonal_stats_by_group patch ([#1418](https://github.com/gee-community/geemap/pull/1418))

## v0.19.6 - Jan 23, 2023

**Improvement**

-   Automatically copy converted JavaScript to Python script to clipboard ([#1411](https://github.com/gee-community/geemap/issues/1411))

## v0.19.5 - Jan 19, 2023

**Improvement**

-   Pin ipywidgets version <8.0 as VS Code does not support ipywidgets 8.x ([#1408](https://github.com/gee-community/geemap/pull/1408))

## v0.19.4 - Jan 19, 2023

**Improvement**

-   Added layer control to split map ([#1405](https://github.com/gee-community/geemap/pull/1405))
-   Improved JavaScript to Python conversion ([#1405](https://github.com/gee-community/geemap/pull/1405))

## v0.19.3 - Jan 17, 2023

**Improvement**

-   Updated timelapse default end year [#1400](https://github.com/gee-community/geemap/pull/1400)

## v0.19.2 - Jan 11, 2023

**Improvement**

-   Fixed add_labels bug ([#1391](https://github.com/gee-community/geemap/pull/1391))
-   Removed LGTM badge ([#1389](https://github.com/gee-community/geemap/pull/1389))
-   Improved cartoee legend and savefig ([#1380](https://github.com/gee-community/geemap/pull/1380))
-   Updated vector_to_gif notebook

## v0.19.1 - Dec 22, 2022

**New Features**

-   Added colorbar support for folium ([#1372](https://github.com/gee-community/geemap/pull/1372))

## v0.19.0 - Dec 5, 2022

**New Features**

-   Added support for ArcGIS Pro ([#1361](https://github.com/gee-community/geemap/pull/1361))

## v0.18.3 - Dec 1, 2022

**Improvement**

-   Fixed draw control bug ([#1352](https://github.com/gee-community/geemap/pull/1352))

## v0.18.2 - Dec 1, 2022

**New Features**

-   Added support for print objects using eerepr ([#1354](https://github.com/gee-community/geemap/pull/1354))
-   Added support for using custom TiTiler endpoint ([#1353](https://github.com/gee-community/geemap/pull/1353))

**Improvement**

-   Fixed `geojson_to_ee` bug ([#1351](https://github.com/gee-community/geemap/pull/1351))

## v0.18.1 - Nov 28, 2022

**New Features**

-   Added `vector_to_gif()` function ([#1348](https://github.com/gee-community/geemap/pull/1348))
-   Changed jupyterlab dependency to optional. Now compatible with Colab. No need to restart runtime after installation ([#1347](https://github.com/gee-community/geemap/pull/1347))

## v0.18.0 - Nov 27, 2022

**New Features**

-   Added functions for creating legends and adding widgets to the map ([#1345](https://github.com/gee-community/geemap/pull/1345))([#1346](https://github.com/gee-community/geemap/pull/1346))
-   New functions include `create_legend()`, `add_legend()`, `add_text()`, `add_image()`, `add_html()`, and `add_widget()`
-   Added two notebook examples for using newly added functions
-   Split-map now supports adding multiple legends
-   Added ESA World Cover 2021 basemaps
-   Added mkdocs dark mode ([#1338](https://github.com/gee-community/geemap/pull/1338))

**Improvement**

-   Removed misc notebook to reduce mkdocs size

## v0.17.3 - Nov 19, 2022

**Improvement**

-   Added GEE workshop notebooks ([#1337](https://github.com/gee-community/geemap/pull/1337))
-   Updated KML methods ([#1335](https://github.com/gee-community/geemap/pull/1335))
-   Fixed ipyleaflet.Map broken link ([#1321](https://github.com/gee-community/geemap/pull/1321))

## v0.17.2 - Oct 31, 2022

**Improvement**

-   Added NASA funding acknowledgment
-   Added unmask_value parameter to download image [#1270](https://github.com/gee-community/geemap/pull/1270)
-   Added Japan GEE workshop notebook
-   Improved Colab error message
-   Added support for Python 3.11
-   Added asset type to search result
-   zonal_stats: additions to allowed_statistics [#1308](https://github.com/gee-community/geemap/pull/1308)
-   Fixed max zoom bug
-   Improved split control
-   Improved local tile

## v0.17.1 - Sep 18, 2022

**New Features**:

-   Added new Inspector GUI [#1264](https://github.com/gee-community/geemap/pull/1264)
-   Added more sample datasets
-   Added codeql.yml
-   Added dependency-review.yml

**Improvement**

-   Improved chart options

## v0.17.0 - Sep 11, 2022

**New Features**:

-   Added reproject image function [#1245](https://github.com/gee-community/geemap/pull/1245)
-   Added Map.show_layer() function
-   Added plotly charts to import
-   Added cropland mapping notebook [#1251](https://github.com/gee-community/geemap/pull/1251)

**Improvement**

-   Improved chart and legend and colormap [#1250](https://github.com/gee-community/geemap/pull/1250)

## v0.16.9 - Sep 6, 2022

**Improvement**

-   Fixed download NED bug

## v0.16.8 - Sep 6, 2022

**Improvement**

-   Added bands param goes_timelapse [#1242](https://github.com/gee-community/geemap/issues/1242)
-   Improved download image function [#1238](https://github.com/gee-community/geemap/discussions/1238)
-   Improved download NED function

## v0.16.7 - Aug 19, 2022

**Improvement**

-   Fixed ee service account authentication bug

## v0.16.6 - Aug 19, 2022

**New Features**:

-   Added auth support for ee service account [#1220](https://github.com/gee-community/geemap/pull/1220)
-   Added a mosaic function [#1219](https://github.com/gee-community/geemap/pull/1219)
-   Added download_ned function [#1218](https://github.com/gee-community/geemap/pull/1218)

## v0.16.5 - Aug 16, 2022

**Improvement**

-   Add band param for image_count [#1209](https://github.com/gee-community/geemap/issues/1209)
-   Improved exporting image to asset [#1208](https://github.com/gee-community/geemap/issues/1208)
-   Fixed Sentinel-1 timelapse bug [#1210](https://github.com/gee-community/geemap/issues/1210)
-   Fixed pie chart Windows bug
-   Added popup fields for add_geojson
-   Updated zonal stats function

## v0.16.4 - Aug 11, 2022

**New Features**:

-   Added support for searching Awesome GEE Community Datasets [#1197](https://github.com/gee-community/geemap/pull/1197) [#1201](https://github.com/gee-community/geemap/pull/1201) [#1202](https://github.com/gee-community/geemap/pull/1202)
-   Added support for retrieving GEE JS code examples and converting to Python
-   Added colorbar background color and image convolution
-   Added html_to_streamlit function

**Improvement**

-   Improved the search data GUI

## v0.16.3 - Aug 9, 2022

**Improvement**

-   Fixed colab import issue [#1192](https://github.com/gee-community/geemap/issues/1192)
-   Allow single color rather than list [#1191](https://github.com/gee-community/geemap/pull/1191)
-   Use json to parse the gee credentials [#1178](https://github.com/gee-community/geemap/pull/1178)

## v0.16.2 - Aug 4, 2022

**New Features**:

-   Added image_histogram and jrc_hist_monthly_history functions

## v0.16.1 - Jul 31, 2022

**New Features**:

-   Added support for plotly.express charts (bar, line, histogram, pie) [#1170](https://github.com/gee-community/geemap/pull/1170)

## v0.16.0 - Jul 30, 2022

**New Features**:

-   Added support for creating S1 timelapse [#752](https://github.com/gee-community/geemap/issues/752) [#1168](https://github.com/gee-community/geemap/pull/1168)
-   Added cloud_pct option for dynamic world ts [#1165](https://github.com/gee-community/geemap/issues/1165)
-   Added get_ee_path function

**Improvement**

-   Renamed region to roi for timelapse func
-   Added lidar tutorial
-   Improved support for Colab
-   Fixed js py conversion bug
-   Improved COG and STAC for short URL
-   Improved requireJS function
-   Added book link
-   Added vector_styling explicit args [#1155](https://github.com/gee-community/geemap/pull/1155)

## v0.15.5 - Jul 22, 2022

**New Features**:

-   Added get_direct_url function
-   Added more lidar functions [#1149](https://github.com/gee-community/geemap/pull/1149)

**Improvement**

-   Improved load_GeoTIFF function
-   Fixed image palette bug
-   Updated vector styling notebook

## v0.15.4 - Jul 15, 2022

**New Features**:

-   Added support for vector styling [#1148](https://github.com/gee-community/geemap/pull/1148)
-   Added csv_to_vector function [#1144](https://github.com/gee-community/geemap/pull/1144)

**Improvement**

-   Improved add_legend and points_from_xy
-   Updated data conversion functions
-   Renamed datasets from hyphen to underscore
-   Updated sample datasets
-   Fixed folium split map bug

## v0.15.3 - Jul 11, 2022

**Improvement**

-   Pin ipyleaflet version for Colab [#1132](https://github.com/gee-community/geemap/issues/1132) [#1143](https://github.com/gee-community/geemap/pull/1143)
-   Improved add vector functions

## v0.15.2 - Jul 9, 2022

**New Features**:

-   Improved support for loading JavaScript modules with `require()` functions [#1140](https://github.com/gee-community/geemap/pull/1140)

## v0.15.1 - Jul 8, 2022

**New Features**:

-   Added support for Open Earth Engine Library (OEEL) #1137

## v0.15.0 - Jul 8, 2022

**New Features**:

-   Added support for changing geojson layer opacity [#1135](https://github.com/gee-community/geemap/pull/1135)
-   Added Map user roi bbox function [#1134](https://github.com/gee-community/geemap/pull/1134)

**Improvement**

-   Fixed colormap bug [#1133](https://github.com/gee-community/geemap/issues/1133)
-   Cleaned notebook output [#1129](https://github.com/gee-community/geemap/pull/1129)
-   Fixed clip image bug

## v0.14.3 - Jul 1, 2022

**New Features**:

-   Added plotting raster in 3D [#1127](https://github.com/gee-community/geemap/pull/1127)
-   Added scooby report [#1127](https://github.com/gee-community/geemap/pull/1127)
-   Added sankee datasets [#1126](https://github.com/gee-community/geemap/pull/1126)

## v0.14.2 - Jun 27, 2022

**New Features**:

-   Added more ee export functions [#1121](https://github.com/gee-community/geemap/pull/1121)
-   Added COG/STAC Inspector GUI for getting pixel values interactively [#1123](https://github.com/gee-community/geemap/pull/1123)

## v0.14.1 - Jun 26, 2022

**Improvement**

-   Added support for Python 3.10 [#1119](https://github.com/gee-community/geemap/pull/1119)
-   Made mapclassify pkg optional [#1120](https://github.com/gee-community/geemap/pull/1120)

## v0.14.0 - Jun 18, 2022

**New Features**:

-   Added fishnet function [#1111](https://github.com/gee-community/geemap/discussions/1111)
-   Added download image with geedim [#1110](https://github.com/gee-community/geemap/pull/1113)

**Improvement**

-   Improved zonal stats

## v0.13.11 - Jun 14, 2022

**New Features**:

-   Added function for creating Dynamic World land cover timeseries [#1108](https://github.com/gee-community/geemap/pull/1108)
-   Added land cover comparison notebook [#1106](https://github.com/gee-community/geemap/pull/1106)

## v0.13.10 - Jun 10, 2022

**New Features**:

-   Added support for Dynamic World Land Cover [#1098](https://github.com/gee-community/geemap/pull/1098)

## v0.13.9 - Jun 7, 2022

**Improvement**

-   Improved palette support, accepting a string palette (e.g., terrain, ndvi) vis_params for Map.addLayer().

## v0.13.8 - Jun 5, 2022

**New Features**:

-   Added check_cmap function [#1084](https://github.com/gee-community/geemap/pull/1084)
-   Added ESA and USGS basemaps [#1089](https://github.com/gee-community/geemap/pull/1089)
-   Added Earth Engine support for pydeck [#1090](https://github.com/gee-community/geemap/pull/1090)

**Improvement**

-   Fixed add local tile bug
-   Fixed image_area_by_group bug
-   Improved blend function
-   Fixed links redirect
-   Fixed basemap docs [#1075](https://github.com/gee-community/geemap/pull/1075)
-   Upgraded add_raster function [#1083](https://github.com/gee-community/geemap/pull/1083)
-   Fixed raster GUI band bug

## v0.13.7 - May 25, 2022

**New Features**:

-   Added image_area_by_group function [#1073](https://github.com/gee-community/geemap/pull/1073)

**Improvement**

-   Updated cartoee basemap notebook [#1067](https://github.com/gee-community/geemap/issues/1067)
-   Refactored basemap [#1075](https://github.com/gee-community/geemap/pull/1075)
-   Sorted raster colormap options
-   Fixed colormap GUI bug
-   Fixed stac stats bug

## v0.13.6 - May 22, 2022

**Improvement**

-   Added cartoee basemap support [#1067](https://github.com/gee-community/geemap/issues/1067)
-   Updated Landsat LE7_TOA_5YEAR Image ID

## v0.13.5 - May 17, 2022

**Improvement**

-   Improved JS-PY conversion [#1061](https://github.com/gee-community/geemap/pull/1061)
-   Updated FAQ
-   Improved get wms layers
-   Updated NLCD notebook
-   Added proxy settings to export data functions
-   Added colorbar to image count notebook
-   Added image_count function and notebook

## v0.13.4 - Apr 27, 2022

**New Features**:

-   Added support for creating interactive choropleth maps with a variety of classification schemes [#1043](https://github.com/gee-community/geemap/pull/1043)

## v0.13.3 - Apr 25, 2022

**New Features**:

-   Added an examples module
-   Added creating coordinate grids notebook
-   Added image zonal stats notebook

**Improvement**

-   Improved chart module [#1026](https://github.com/gee-community/geemap/pull/1026)
-   Improved chart histogram [#1032](https://github.com/gee-community/geemap/discussions/1032)

## v0.13.2 - Apr 15, 2022

**New Features**:

-   Added image_value_list function [#1010](https://github.com/gee-community/geemap/pull/1010)
-   Added image_stats_by_zone [#1012](https://github.com/gee-community/geemap/pull/1012)
-   Added support for creating grids [#1014](https://github.com/gee-community/geemap/pull/1014)
-   Added landforms legend

**Improvement**

-   Updated cartoee add_colorbar [#1006](https://github.com/gee-community/geemap/pull/1006)
-   Added layer control for ipyleaflet [#1017](https://github.com/gee-community/geemap/issues/1017)
-   Updated authentication method [#1018](https://github.com/gee-community/geemap/issues/1018)
-   Fixed add_colorbar bug

## v0.13.1 - Apr 2, 2022

**Improvement**

-   Fixed heremap import error

## v0.13.0 - Apr 2, 2022

**Improvement**

-   Reduced number of dependencies, making plotting backends optional except ipyleaflet and folium [#1003](https://github.com/gee-community/geemap/pull/1003)
-   Improved cartoee.add_legend [#997](https://github.com/gee-community/geemap/pull/997)
-   Added deck and kepler to docs
-   Skip export with GitHub Actions
-   Update folium module
-   Updated clip image notebook

## v0.12.1 - Mar 22, 2022

**New Features**:

-   Added support for pydeck and kepler.gl [#993](https://github.com/gee-community/geemap/pull/993)

**Improvement**

-   Renamed basemaps
-   Added GEE-Courses link
-   Updated folium module

## v0.12.0 - Mar 19, 2022

**New Features**:

-   Added support for NetCDF data [#991](https://github.com/gee-community/geemap/pull/991)
-   Converting NetCDF data to GeoTIFF
-   Adding velocity map with NetCDF data
-   Added clip image by mask [#986](https://github.com/gee-community/geemap/pull/986)
-   Added streamlit bidirectional functionality [#985](https://github.com/gee-community/geemap/pull/985)

**Improvement**

-   Added requests timeout [#989](https://github.com/gee-community/geemap/issues/989)
-   Renamed folium basemaps [#978](https://github.com/gee-community/geemap/pull/978)
-   Set draw export to False by default
-   Added font family setting for cartoee [#863](https://github.com/gee-community/geemap/issues/863) [#977](https://github.com/gee-community/geemap/pull/977)

## v0.11.8 - Mar 12, 2022

**New Features**:

-   Added split map for folium and streamlit [#970](https://github.com/gee-community/geemap/pull/970)
-   Updated Landsat timelapse to Collection 2 [#974](https://github.com/gee-community/geemap/pull/974)

**Improvement**

-   Fixed typos and broken links [#971](https://github.com/gee-community/geemap/issues/971)
-   Updated netCDF notebook

## v0.11.7 - Mar 8, 2022

**New Features**:

-   Added blend function for creating shaded relief maps blended with hillshade

**Improvement**

-   Added mode reducer to zonal stats [#960](https://github.com/gee-community/geemap/issues/960)

## v0.11.6 - Mar 3, 2022

**New Features**:

-   Added support for visualizing LiDAR data in 3D [#957](https://github.com/gee-community/geemap/pull/957)
-   Added date option for gdf_to_ee [#950](https://github.com/gee-community/geemap/issues/950)

**Improvement**

-   Improved chart histogram [#953](https://github.com/gee-community/geemap/pull/953)
-   Fixed LGTM false alarm [#939](https://github.com/gee-community/geemap/pull/939)

## v0.11.5 - Feb 22, 2022

**New Features**:

-   Added numpy to COG [#945](https://github.com/gee-community/geemap/pull/945)
-   Added gdf_bounds [#939](https://github.com/gee-community/geemap/pull/939)
-   Added [Landsat 9 notebook](https://geemap.org/notebooks/99_landsat_9)
-   Added ESRI Global Land Cover legend

**Improvement**

-   Fixed stac tile bug [#944](https://github.com/gee-community/geemap/pull/944)
-   Added None to vis_params as optional [#943](https://github.com/gee-community/geemap/pull/943)
-   Reformatted code using black

## v0.11.4 - Feb 14, 2022

**New Features**:

-   Added timelapse fading effect [#925](https://github.com/gee-community/geemap/pull/925)

## v0.11.3 - Feb 7, 2022

**New Features**:

-   Added support for joining attribute tables `ee_join_table()` [#916](https://github.com/gee-community/geemap/issues/916)
-   Added `gdf_to_df()` and `geojson_to_df()` functions

## v0.11.2 - Feb 4, 2022

**New Features**:

-   Added remove_colorbars function [#881](https://github.com/gee-community/geemap/discussions/881)
-   Added remove_legends function [#881](https://github.com/gee-community/geemap/discussions/881)

**Improvement**

-   Update get_image_collection_gif() [#905](https://github.com/gee-community/geemap/pull/905)
-   Fixed timelapse ND bug [#904](https://github.com/gee-community/geemap/issues/904)
-   Improved open raster [#902](https://github.com/gee-community/geemap/issues/902)
-   Fixed zonal stats bug [#899](https://github.com/gee-community/geemap/issues/899)
-   Fixed Landsat timelapse bug [#885](https://github.com/gee-community/geemap/issues/885)

## v0.11.1 - Jan 24, 2022

**New Features**:

-   Added ee_extra to algorithms [#868](https://github.com/gee-community/geemap/pull/868)
-   Added COG creation [bc83fdf](https://github.com/gee-community/geemap/commit/bc83fdf959dd91bdeb40de6af41fea79933c57c2)
-   Added heremap plotting backend [#382](https://github.com/gee-community/geemap/issues/382)
-   Added COG Inspector GUI [#841](https://github.com/gee-community/geemap/issues/841)

**Improvement**

-   Improved GitHub workflows [#879](https://github.com/gee-community/geemap/pull/879)
-   Fixed ee_stac_list bug [#873](https://github.com/gee-community/geemap/issues/873)
-   Fixed js py conversion [ce7fee0](https://github.com/gee-community/geemap/commit/ce7fee0e87ab2a35069e45d141fb2c84333f392b)
-   Updated notebook 07 [#871](https://github.com/gee-community/geemap/pull/871)
-   Added IR band to goes_timelapse [#870](https://github.com/gee-community/geemap/pull/870)
-   Updated ee_basemaps [#869](https://github.com/gee-community/geemap/pull/869)
-   Removed COG mosaic
-   Fixed cartoee legend bug
-   Updated installation instructions

## v0.11.0 - Jan 7, 2022

**New Features**:

-   Added support for plotly [#842](https://github.com/gee-community/geemap/issues/842)
-   Added colorbar to timelapse [#846](https://github.com/gee-community/geemap/issues/846)
-   Added save_colorbar function [#846](https://github.com/gee-community/geemap/issues/846)
-   Added ocean color timelapse [#845](https://github.com/gee-community/geemap/issues/845)
-   Added support for xyzservices basemaps [#795](https://github.com/gee-community/geemap/issues/795)
-   Added labeling gdf shp geojson [#815](https://github.com/gee-community/geemap/issues/815)
-   Added remove_labels [#815](https://github.com/gee-community/geemap/issues/815)
-   Added Planetary Computer STAC support
-   Added bbox_to_gdf function

**Improvement**

-   Fixed cartoee projection bug [#843](https://github.com/gee-community/geemap/discussions/843)
-   Improved COG visualization [#844](https://github.com/gee-community/geemap/issues/844)
-   Updated STAC notebook example [#841](https://github.com/gee-community/geemap/issues/841)
-   Improved stac tile functions [#839](https://github.com/gee-community/geemap/pull/839)
-   Removed pangeo broken binder links

## v0.10.2 - Dec 23, 2021

**New Features**:

-   Add locate control to folium [#809](https://github.com/gee-community/geemap/issues/809)
-   Added add_points_from_xy function [#812](https://github.com/gee-community/geemap/issues/812)
-   Added heatmap function
-   Added add_labels function [#815](https://github.com/gee-community/geemap/issues/815)
-   Added NAIP timelapse [#789](https://github.com/gee-community/geemap/issues/789)

**Improvement**

-   Improved js_to_py function [#805](https://github.com/gee-community/geemap/discussions/805)
-   Renamed popups to popup [#812](https://github.com/gee-community/geemap/issues/812)
-   Changed default map view [#821](https://github.com/gee-community/geemap/issues/821)
-   Fixed centerObject bug [#823](https://github.com/gee-community/geemap/issues/823)
-   Fixed typo [#824](https://github.com/gee-community/geemap/pull/824)

## v0.10.1 - Dec 6, 2021

**Improvement**

-   A temporary fix for ipyleaflet basemap error [#795](https://github.com/gee-community/geemap/issues/795)

## v0.10.0 - Nov 28, 2021

**New Features**:

-   Added remove_legend function [#761](https://github.com/gee-community/geemap/issues/761)
-   Added add_marker function [#765](https://github.com/gee-community/geemap/pull/765)
-   Added support for local tile and raster GUI [#758](https://github.com/gee-community/geemap/issues/758), [#769](https://github.com/gee-community/geemap/pull/769)
-   Added a new osm module [#770](https://github.com/gee-community/geemap/issues/770) [#772](https://github.com/gee-community/geemap/pull/772)
-   Added support for PostGIS [#771](https://github.com/gee-community/geemap/issues/771) [#772](https://github.com/gee-community/geemap/pull/772)
-   Added ImageOverlay from local files [#773](https://github.com/gee-community/geemap/issues/773)

## v0.9.5 - Nov 22, 2021

**New Features**:

-   Added timelapse module
-   Added quarter and monthly timelapse [#746](https://github.com/gee-community/geemap/issues/746)
-   Improved create timeseries [#736](https://github.com/gee-community/geemap/issues/736)
-   Added Sentinel-2 timelapse [#733](https://github.com/gee-community/geemap/issues/733) [#736](https://github.com/gee-community/geemap/issues/736)
-   Added MODIS NDVI timelapse [#728](https://github.com/gee-community/geemap/issues/728)
-   Added GOES timelapse [#717](https://github.com/gee-community/geemap/issues/717)
-   Added time slider opacity param [#720](https://github.com/gee-community/geemap/discussions/720)
-   Added contour function [#688](https://github.com/gee-community/geemap/issues/688)
-   Added more gif functions
-   Added make_gif and gif_to_mp4 functions
-   Improved date sequence
-   Added Alibaba font type
-   Added ESA Land Cover legend
-   Added zoom to bounds function
-   Added streamlit download button

**Improvement**

-   Fixed encoding bug [#747](https://github.com/gee-community/geemap/issues/747)

## v0.9.4 - Oct 23, 2021

**New Features**:

-   Made streamlit map width responsive [#713](https://github.com/gee-community/geemap/issues/713)
-   Added function read file from url

**Improvement**

-   Fixed map width bug [#712](https://github.com/gee-community/geemap/issues/712)
-   Fixed algorithms module bug
-   Updated environment.yml

## v0.9.3 - Oct 23, 2021

**New Features**:

-   Added streamlit support [#697](https://github.com/gee-community/geemap/issues/697)
-   Added point layer function [#702](https://github.com/gee-community/geemap/issues/702)
-   Added river width module [#682](https://github.com/gee-community/geemap/issues/682)
-   Added census data and xyzservices
-   Added nlcd notebook
-   Added river width module notebook
-   Added GEE workshop notebook

**Improvement**

-   Fixed geojson style callback bug [#692](https://github.com/gee-community/geemap/issues/692)
-   Fixed open vector bug [#124](https://github.com/gee-community/geemap/issues/124)
-   Removed py36 due to xyzservices

## v0.9.2 - Oct 1, 2021

**New Features**:

-   Added RivWidthCloud module [#682](https://github.com/gee-community/geemap/issues/682)
-   Added RivWidthCloud notebook [#682](https://github.com/gee-community/geemap/issues/682)
-   Added [NLCD notebook](https://geemap.org/notebooks/nlcd_app/)
-   Added a close button to timeseries inspector

**Improvement**

-   Fixed hover countries notebook [#686](https://github.com/gee-community/geemap/pull/686)
-   Improved cartoee colorbar with custom label size [#681](https://github.com/gee-community/geemap/discussions/681)

## v0.9.1 - Sep 17, 2021

**New Features**:

-   Added `sandbox_path` option allowing users to restrict Voila app access to system directories [#673](https://github.com/gee-community/geemap/issues/673)

## v0.9.0 - Sep 10, 2021

**New Features**:

-   Get current device latlon [#618](https://github.com/gee-community/geemap/issues/618)

**Improvement**

-   Improved Colab support [#661](https://github.com/gee-community/geemap/issues/661)
-   Improved folium colorbar [#586](https://github.com/gee-community/geemap/issues/586)
-   Fixed broken link [#653](https://github.com/gee-community/geemap/issues/653)
-   Fixed extract pixel values bug [#610](https://github.com/gee-community/geemap/issues/610)
-   Fixed color palette bug [#605](https://github.com/gee-community/geemap/pull/605)
-   Fixed typos [#589](https://github.com/gee-community/geemap/pull/589)

## v0.8.18 - Jul 8, 2021

**New Features**:

-   Added df_to_geojson [#557](https://github.com/gee-community/geemap/discussions/557)
-   Added feature_histogram function to chart module [#553](https://github.com/gee-community/geemap/pull/553)
-   Added feature_groups function to chart module [#539](https://github.com/gee-community/geemap/pull/539)
-   Added random forest probability output [#550](https://github.com/gee-community/geemap/pull/550)

**Improvement**

-   Renamed eefolium module to foliumap
-   Changed COG and STAC to lowercase
-   Changed .format() to fstring [#561](https://github.com/gee-community/geemap/pull/561)
-   Fixed random forest string to label bug [#545](https://github.com/gee-community/geemap/pull/545)
-   Improved split-panel map [#543](https://github.com/gee-community/geemap/discussions/543)
-   Updated otsu example [#535](https://github.com/gee-community/geemap/discussions/535)

## v0.8.17 - Jun 20, 2021

**New Features**:

-   Added Planet global mosaic [#527](https://github.com/gee-community/geemap/issues/527)
-   Add LCMS dataset option for sankee [#517](https://github.com/gee-community/geemap/issues/517)
-   Added add_osm function [#503](https://github.com/gee-community/geemap/discussions/503)

**Improvement**

-   Added otsu example [#535](https://github.com/gee-community/geemap/discussions/535)
-   Fixed timeseries plotting bug [#513](https://github.com/gee-community/geemap/discussions/513)
-   Fixed shp deletion bug [#509](https://github.com/gee-community/geemap/discussions/509)
-   Fixed csv_to_points bug [#490](https://github.com/gee-community/geemap/discussions/490)
-   Improved ee_to_geojson [#486](https://github.com/gee-community/geemap/pull/486)
-   Improved random sampling notebook [#479](https://github.com/gee-community/geemap/discussions/479)
-   Fixed link bug [#480](https://github.com/gee-community/geemap/issues/480)
-   Improved sankee notebook [#471](https://github.com/gee-community/geemap/issues/471)
-   Updated installation docs
-   Added binder env

## v0.8.16 - May 10, 2021

**New Features**:

-   Added csv_to_points GUI [#461](https://github.com/gee-community/geemap/issues/461)
-   Added GUI for creating transects [#454](https://github.com/gee-community/geemap/issues/454)
-   Added csv_to_ee and csv_to_makers [#461](https://github.com/gee-community/geemap/issues/461)
-   Added geopandas support [#455](https://github.com/gee-community/geemap/issues/455)

**Improvement**

-   Improved geojson style [#459](https://github.com/gee-community/geemap/issues/459) [#460](https://github.com/gee-community/geemap/issues/460)
-   Improved vector support [#455](https://github.com/gee-community/geemap/issues/455)
-   Improved add_colorbar function [#450](https://github.com/gee-community/geemap/issues/450)
-   Improved add_raster function [#449](https://github.com/gee-community/geemap/pull/449)
-   Updated notebooks

## v0.8.15 - Apr 28, 2021

**Improvement**

-   Improved shp_to_geojson function [#430](https://github.com/gee-community/geemap/discussions/430)
-   Improved add_styled_vector function [#432](https://github.com/gee-community/geemap/discussions/432)
-   Fixed map publish bug [#445](https://github.com/gee-community/geemap/issues/445)
-   Improved add_colorbar function [dc7e548](https://github.com/gee-community/geemap/commit/dc7e54856694a1994b6d4f4044385babe04bd086)

## v0.8.14 - Apr 20, 2021

**New Features**:

-   Added timelapse GUI [#359](https://github.com/gee-community/geemap/issues/359)
-   Added timeslider GUI [#359](https://github.com/gee-community/geemap/issues/359) [#387](https://github.com/gee-community/geemap/issues/387)

**Improvement**

-   Improved add_geojson function [731e59e](https://github.com/gee-community/geemap/commit/731e59efc4a1f629db13f6b6cc4e9ef6b06cbe8f)
-   Added GeoPython workshop notebook [6efd5e](https://geemap.org/workshops/GeoPython_2021)
-   Improved cartoee colorbar [#413](https://github.com/gee-community/geemap/discussions/413)
-   Improved cartoee add_layer function [#368](https://github.com/gee-community/geemap/issues/368)

## v0.8.13 - Mar 22, 2021

**New Features**:

-   Added linked maps [#375](https://github.com/gee-community/geemap/issues/375)
-   Added cartoee legend [#343](https://github.com/gee-community/geemap/issues/343)
-   Added chart by feature property [#339](https://github.com/gee-community/geemap/issues/339)
-   Added tool gui template [#239](https://github.com/gee-community/geemap/issues/239)
-   Added GEE Toolbox GUI [#362](https://github.com/gee-community/geemap/issues/362)
-   Added support for multiple legends [#365](https://github.com/gee-community/geemap/discussions/365)

**Improvement**

-   Improved dataset module to use GEE STAC [#346](https://github.com/gee-community/geemap/issues/346)
-   Improved training sample tool [#326](https://github.com/gee-community/geemap/issues/326)
-   Added netcdf_to_ee example [#285](https://github.com/gee-community/geemap/issues/285)
-   Improved to_html function [#361](https://github.com/gee-community/geemap/discussions/361)
-   Changed colorbar plotting backend [#372](https://github.com/gee-community/geemap/issues/372)
-   Improved get_colorbar function [#372](https://github.com/gee-community/geemap/issues/372)
-   Added vector styling example
-   Improved zonal statistics

## v0.8.12 - Mar 8, 2021

**New Features**:

-   Added a dataset module for accessing the Earth Engine Data Catalog via dot notation [#345](https://github.com/gee-community/geemap/issues/345)
-   Added a chart module for creating interactive charts for Earth Engine data [#343](https://github.com/gee-community/geemap/issues/343)
-   Added a time slider for visualizing Earth Engine time-series images [#335 ](https://github.com/gee-community/geemap/issues/335) [#344](https://github.com/gee-community/geemap/issues/344)
-   Added a `netcdf_to_ee` function [#342](https://github.com/gee-community/geemap/pull/342)
-   Added a `numpy_to_ee` function [#337](https://github.com/gee-community/geemap/pull/337)
-   Added vertical colorbar support [#322](https://github.com/gee-community/geemap/issues/322)
-   Added GUI for creating training samples [#326](https://github.com/gee-community/geemap/issues/326)

**Improvement**

-   Added layer control by default to folium map [#323](https://github.com/gee-community/geemap/issues/323)
-   Added geemap matplotlib example [#319](https://github.com/gee-community/geemap/discussions/319)
-   Added lgtm continuous integration [#330](https://github.com/gee-community/geemap/issues/330)
-   Fixed layer palette bug [#334](https://github.com/gee-community/geemap/issues/334)
-   Fixed minimap zoom parameter [#329](https://github.com/gee-community/geemap/pull/329)
-   Fixed centerObject bug

## v0.8.11 - Feb 23, 2021

**New Features**:

-   Added a colormap module [#302](https://github.com/gee-community/geemap/issues/302)
-   Added a new cartoee scale bar function [#313](https://github.com/gee-community/geemap/pull/313)
-   Added extract pixel values function [#315](https://github.com/gee-community/geemap/issues/315)
-   Visualizing Earth Engine image with >200 matplotlib colormaps via dot notation ([example](https://geemap.org/notebooks/60_colormaps/))

**Improvement**

-   Improved the basemap module accessible via dot notation [#302](https://github.com/gee-community/geemap/issues/302)
-   Added googledrivedownloader and python-box to requirements [#310](https://github.com/gee-community/geemap/discussions/310)
-   Fixed folium layer name bug [#314](https://github.com/gee-community/geemap/issues/314)

## v0.8.10 - Feb 16, 2021

**New Features**:

-   Added default basemap options when creating the Map [#293](https://github.com/gee-community/geemap/issues/293)
-   Added GUI for change basemaps [#294](https://github.com/gee-community/geemap/issues/294)
-   Added GUI for js2py conversion [#296](https://github.com/gee-community/geemap/issues/296)
-   Added geemap cheat sheet [#276](https://github.com/gee-community/geemap/issues/276)
-   Added `Map.zoomToObject()` method [#303](https://github.com/gee-community/geemap/issues/303)

**Improvement**

-   Improved `Map.centerObject()` method [#303](https://github.com/gee-community/geemap/issues/303)

## v0.8.9 - Feb 4, 2021

**New Features**:

-   Added [whiteboxgui](https://github.com/giswqs/whiteboxgui) with 477 geoprocessing tools [#254](https://github.com/gee-community/geemap/issues/254)

**Improvement**

-   Fixed file open encoding bug

## v0.8.8 - Jan 17, 2021

**New Features**:

-   Added support for converting Pandas/GeoPandas DataFrame to ee.FeatureCollection and vice versa [#268](https://github.com/gee-community/geemap/issues/268)
-   Added KML/KMZ support [#247](https://github.com/gee-community/geemap/issues/247)
-   Added Code of Conduct

**Improvement**

-   Fixed CSV encoding bug [#267](https://github.com/gee-community/geemap/issues/267)
-   Improved downloading shp support [#263](https://github.com/gee-community/geemap/issues/263)
-   Fixed WMS bug [#250](https://github.com/gee-community/geemap/discussions/250)
-   Added cartoee subplots example [#238](https://github.com/gee-community/geemap/discussions/238)
-   Reformatted code using black formatter
-   Improved support for shp and geojson [#244](https://github.com/gee-community/geemap/issues/244)
-   Fixed layer control bug
-   Added cartoee blend tutorial [#241](https://github.com/gee-community/geemap/issues/241)
-   Improved drawing tools [#240](https://github.com/gee-community/geemap/issues/240)
-   Improved Inspector tool

## v0.8.7 - Dec 27, 2020

**New Features**:

-   Added toolbar GUI [#215](https://github.com/gee-community/geemap/issues/215)
-   Added layer vis [#215](https://github.com/gee-community/geemap/issues/215)
-   Added raster/vector colormap [#215](https://github.com/gee-community/geemap/issues/215)
-   Added support for linking legend with layer [#234](https://github.com/gee-community/geemap/issues/234)
-   Added styled vector function [#235](https://github.com/gee-community/geemap/issues/235)
-   Added mouse click observe to toolbar [#215](https://github.com/gee-community/geemap/issues/215)
-   Added new tool for opening local data [#239](https://github.com/gee-community/geemap/issues/239)

**Improvement**

-   Fixed COG mosaic bug [#236](https://github.com/gee-community/geemap/issues/236) and [#237](https://github.com/gee-community/geemap/issues/237)

## v0.8.6 - Dec 22, 2020

**New Features**:

-   Added GUI for changing layer visualization interactively [#215](https://github.com/gee-community/geemap/issues/215)
-   Added a toolbar [#215](https://github.com/gee-community/geemap/issues/215)
-   Added color bar support [#223](https://github.com/gee-community/geemap/issues/223)
-   Added draggable legend to folium maps [#224](https://github.com/gee-community/geemap/issues/224)
-   Added `get_image_collection_gif()` function [#225](https://github.com/gee-community/geemap/issues/225)
-   Added `image_dates()` function [#216](https://github.com/gee-community/geemap/issues/216)

**Improvement**

-   Added `max_zoom` parameter to `add_tile_layer()` [#227](https://github.com/gee-community/geemap/issues/227)
-   Added mouse latlon to insepctor tool [#229](https://github.com/gee-community/geemap/discussions/229)
-   Added download icon to notebooks [#202](https://github.com/gee-community/geemap/issues/202)
-   Added GitHub issue template [#202](https://github.com/gee-community/geemap/issues/202)
-   Added more tutorials (cartoee gif, legend, color bar, vis GUI, etc.)
-   Fixed remove control bug [#218](https://github.com/gee-community/geemap/discussions/218)
-   Fixed split-panel map bug
-   Improved Exception handling

## v0.8.5 - Dec 12, 2020

**New Features**:

-   Add toolbar [#6](https://github.com/gee-community/geemap/issues/6)
-   Add functions for downloading imgae thumbnails [#214](https://github.com/gee-community/geemap/issues/214)
-   Add func for getting image collection dates [#216](https://github.com/gee-community/geemap/issues/216)
-   Add cartoee scale bar and north arrow [#191](https://github.com/gee-community/geemap/issues/191)
-   Add support for COG mosaic [#200](https://github.com/gee-community/geemap/issues/200)

**Improvement**

-   Improve support for locally trained models [#210](https://github.com/gee-community/geemap/issues/210)
-   Add verbose option of downloading functions [#197](https://github.com/gee-community/geemap/pull/197)
-   Improve Inspector tool for point geometry [#198](https://github.com/gee-community/geemap/issues/198)
-   Add tutorials (COG, STAC, local RF, image thumbnails)

## v0.8.4 - Dec 6, 2020

**New Features:**

-   Add support for Cloud Optimized GeoTIFF (COG) and SpatioTemporal Asset Catalog (STAC) #192
-   Add [Map.add_cog_layer()](https://geemap.org/geemap/#geemap.geemap.Map.add_cog_layer) and [Map.add_stac_layer()](https://geemap.org/geemap/#geemap.geemap.Map.add_stac_layer)
-   Add new COG functions, e.g., `cog_tile()`, `cog_bounds()`, `cog_center()`, `cog_bands()`
-   Add new STAC functions, e.g., `stac_tile()`, `stac_bounds()`, `stac_center()`, `stac_bands()`

**Improvements:**

-   Improve Google Colab support #193. Use `import geemap` rather than `import geemap.foliumap as geemap`
-   Add `Open in Colab` button to notebooks #194

## v0.8.3 - Dec 2, 2020

**New Features:**

-   Add button for removing user-drawn features #182
-   Add function for moving drawn layer to top
-   Add remove_last_drawn() function #130
-   Add support for QGIS Layer Style File #174
-   Add mouse click get coordinates example #173
-   Add cartoee colab example #157
-   Add notebooks to mkdocs

**Improvements:**

-   Improve ee_Initialize() #189 #190
-   Fix cartoee map orientation bug #177 #183
-   Fix problematic Date field in shapefile #176
-   Fix Windows unzip bug

## v0.8.2 - Nov 6, 2020

**Improvements**

-   Reorganize modules
-   Add a new module common.py
-   Add new domain geemap.org
-   Format code using black
-   Add more init options for Map class

## v0.8.1 - Oct 27, 2020

**New Features:**

-   Add machine learning module #124 #156
-   Add cartoee module #157 #161
-   Add more tutorials (e.g., timelapse, water app, ipywidgets)

**Improvements:**

-   Make ee_Initialize() optional for Map class

BIG THANK YOU to [Kel Markert](https://github.com/kmarkert) for adding the cartoee and ml modules!!

## v0.8.0 - Oct 10, 2020

**Improvements**

-   Add support for loading Cloud Optimized GeoTIFFs as ee.Image and ee.ImageCollection
-   Make fmask optional when creating Landsat timelapse
-   Add support for creating timelapse of spectral indices (e.g., NDWI, NDVI)
-   Add geemap Colab tutorial
-   Add timelapse download option for voila
-   Add pydeck tutorial for visualizing 3D terrain data
-   Add qualityMosaic() tutorial

**Fixes**

-   Fix Windows zipfile bug

## v0.7.13 - Sep 15, 2020

**Improvements**

-   Improve ee authentication in Colab #145
-   Improve non-interactive mode #138
-   Add Colab notebook example

**Fixes**

-   Fix automated testing error
-   Fix Windows ee_search() bug

## v0.7.12 - Sep 1, 2020

**Improvements**

-   Rebuild docs using mkdocs-material
-   Add Internet proxy function
-   Add support for exporting shp and geojson #63

**Fixes**

-   Fix heroko config bug
-   Fix landsat timelapse bug #99 #134
-   Fix js_py conversion bug #136

## v0.7.11 - Aug 16, 2020

**Improvements:**

-   Add function for removing drawn features #130
-   Add function for extracting pixel values #131
-   Add function for interactive region reduction #35
-   Add machine learning tutorials

**Fixes:**

-   [Fix js_py conversion bug](https://github.com/gee-community/geemap/commit/6c0ebe4006d60f9ebb4390d0914400fc276e2c7d)
-   Fix typos

## v0.7.10 - Aug 5, 2020

**Improvements:**

-   Add function for getting image properties
-   Add function for calculating descriptive statistics (i.e., min, max, mean, std, sum)
-   Add more utils functions

## v0.7.7 - Aug 5, 2020

**Improvements:**

-   Add support for publishing maps #109
-   Add `find_layer()` function
-   Add `layer_opacity()` function
-   Update Readthedocs

**Fixes:**

-   Fix duplicate layer bug

## v0.7.0 - May 22, 2020

## v0.6.0 - Apr 5, 2020

## v0.5.0 - Mar 23, 2020

## v0.4.0 - Mar 19, 2020

## v0.3.0 - Mar 18, 2020

## v0.2.0 - Mar 17, 2020

## v0.1.0 - Mar 8, 2020
