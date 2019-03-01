---

### ![](https://cdn4.iconfinder.com/data/icons/feather/24/code-24.png) Summary

This project was created as part of a presentation. 

I wanted to create something special, so I thought that an interactive map with pie charts, instead of a simple one with points, would work nicely since it would make the presentation more comprehensible for my audience (pies and bars are more easily interpreted). 

Recently, I have been trying out d3, a javascript data visualization library, which can lead to the creation of really exceptional data visualizations.  I found working with it quite enjoyable, thanks to the variety of examples available and the guidance provided by its creator, Mike Bostock.

This software was created as part of a presentation of CO<sub>2</sub> emission levels per point of reference. Firstly, the choropleth map[^footnote] is created, by using the average value of emissions per country or state. Afterwards, the pie charts, showing the different emission indexes, are created on specific coordinates, which correspond to the location of each point. The user can change the selected month with a simple click of a button.

[^footnote]:  Choropleth map is a thematic map, in which areas are shaded or patterned in proportion to the measurement of the statistical variable being displayed on the map, such as population density or per-capita income.

-------------

### ![](https://cdn1.iconfinder.com/data/icons/material-core/20/settings-24.png) Setup


These instructions will get you a copy of the project up and running on your local machine for development and/or testing purposes.

> **Installation note:**
>
> - The d3 library can be downloaded at https://github.com/d3/d3 or accessed **online** in your program by using  :
>  `` <script src="https://d3js.org/d3.v4.min.js"></script>`` 
> - d3 is also accessible **offline** once it is installed in a local folder, for which you must designate the path!


![](https://cdn4.iconfinder.com/data/icons/ionicons/512/icon-folder-20.png) /  ![](https://cdn0.iconfinder.com/data/icons/octicons/1024/link-20.png)

 You should setup your folders or your folders' path so that the `GeoJSON` (ending on .json), and the needed `.CSV` files <i class="icon-file"></i> are imported correctly.

![](https://cdn3.iconfinder.com/data/icons/glypho-free/64/share-20.png)

The web page is served @ localhost:8000. Change the port according to your needs.

----------

### More info

A short list of the d3 functions used is presented below. In the table section “Documentation link”, there are hyperlinks that redirect you to the official d3 documentation website. 

| d3 libraries used| Documentation link|
| :------- | :----: | 
| d3.select / d3.selectAll | [d3 selections][]|
| d3.geoMercator / d3.geoPath | [d3 geography][]   |
| d3.scaleQuantize / d3.scaleOrdinal  | [d3 scale][]    |
| d3.arc / d3.pie  | [d3 shapes][]    |
| d3.csv / d3.json  | [d3 fetches][]   |
| d3.min / d3.max  | [d3 min/max][]    |
| d3.format  | [d3 format][]  |

[d3 selections]: https://github.com/d3/d3/blob/master/API.md#selections-d3-selection
[d3 geography]: https://github.com/d3/d3/blob/master/API.md#geographies-d3-geo
[d3 scale]: https://github.com/d3/d3/blob/master/API.md#scales-d3-scale
[d3 shapes]: https://github.com/d3/d3/blob/master/API.md#shapes-d3-shape
[d3 fetches]: https://github.com/d3/d3/blob/master/API.md#fetches-d3-fetch
[d3 min/max]: https://github.com/d3/d3-array/blob/master/README.md#statistics
[d3 format]: https://github.com/d3/d3/blob/master/API.md#number-formats-d3-format

----------

### ![](https://cdn0.iconfinder.com/data/icons/simple-darkcon-1/99/book-24.png) License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

----------

### ![](https://cdn4.iconfinder.com/data/icons/developer-set-3/128/edit2-24.png) Authors 

*Dimitrios Petkidis*  -  [dpetkidis](https://github.com/dpetkidis)
