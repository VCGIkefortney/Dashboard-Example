# Dashboard-Example
This is an exploration of JavaScript driven data visualizations utilizing Vega-Lite, Vega, Cedar and D3 to explore Vermont data. This is not intended as a finished product but rather a framework to understand the functionality of interactive data visualizations.

## Vega
Vega is a visualization grammar, a declarative language for creating, saving, and sharing interactive visualization designs. With Vega, you can describe the visual appearance and interactive behavior of a visualization in a JSON format, and generate web-based views using Canvas or SVG.

Vega provides basic building blocks for a wide variety of visualization designs: data loading and transformation, scales, map projections, axes, legends, and graphical marks such as rectangles, lines, plotting symbols, etc. Interaction techniques can be specified using reactive signals that dynamically modify a visualization in response to input event streams.

A Vega specification defines an interactive visualization in a JSON format. Specifications are parsed by Vega’s JavaScript runtime to generate both static images or interactive web-based views. Vega provides a convenient representation for computational generation of visualizations, and can serve as a foundation for new APIs and visual analysis tools.

https://vega.github.io/vega/

## Vega-Lite
Vega-Lite is a high-level grammar of interactive graphics. It provides a concise JSON syntax for rapidly generating visualizations to support analysis. Vega-Lite specifications can be compiled to Vega specifications.

Vega-Lite specifications describe visualizations as mappings from data to properties of graphical marks (e.g., points or bars). The Vega-Lite compiler automatically produces visualization components including axes, legends, and scales. It then determines properties of these components based on a set of carefully designed rules. This approach allows specifications to be succinct and expressive, but also provide user control. As Vega-Lite is designed for analysis, it supports data transformations such as aggregation, binning, filtering, sorting, and visual transformations including stacking and faceting. Moreover, Vega-Lite specifications can be composed into layered and multi-view displays, and made interactive with selections.

https://vega.github.io/vega-lite/

## Cedar.js

Cedar is a Javascript library for crafting visualizations, in particular with the GeoServices API from ArcGIS. This includes common chart types such as bar charts, line charts, scatterplots, as well as custom graphics designed with Vega grammar. Built on D3.js - Cedar is extensible and interactive.

Cedar is open-source under the Apache license. Visit the Esri Github repository to learn more and contribute.

https://esri.github.io/cedar/

## D3

D3.js is a JavaScript library for manipulating documents based on data. D3 helps you bring data to life using HTML, SVG, and CSS. D3’s emphasis on web standards gives you the full capabilities of modern browsers without tying yourself to a proprietary framework, combining powerful visualization components and a data-driven approach to DOM manipulation.

D3 allows you to bind arbitrary data to a Document Object Model (DOM), and then apply data-driven transformations to the document. For example, you can use D3 to generate an HTML table from an array of numbers. Or, use the same data to create an interactive SVG bar chart with smooth transitions and interaction.

D3 is not a monolithic framework that seeks to provide every conceivable feature. Instead, D3 solves the crux of the problem: efficient manipulation of documents based on data. This avoids proprietary representation and affords extraordinary flexibility, exposing the full capabilities of web standards such as HTML, SVG, and CSS. With minimal overhead, D3 is extremely fast, supporting large datasets and dynamic behaviors for interaction and animation. D3’s functional style allows code reuse through a diverse collection of official and community-developed modules.

https://d3js.org/

## Local Servers
To explore this in a local copy, a local server will need to be set up. It is your choice what to use but Python/Flask or NodeJS both work as nothing in here is particularly demanding.
live-server
