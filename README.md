<!DOCTYPE html>
<html xmlns="http://www.w3.org/1999/xhtml">
<head>

<meta charset="utf-8">
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<meta name="generator" content="pandoc" />



<title>Coronavirus</title>

<meta property="og:title" content="Coronavirus" />

<meta name='viewport' content='width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no' />

<link rel="icon" href="data:image/x-icon;" type="image/x-icon">


<script type="text/javascript">
window.FlexDashboardComponents = [];
</script>

<script id="flexdashboard-navbar" type="application/json">
[{"icon":"fa-share-alt","items":[{"title":"Twitter","icon":"fa-twitter"},{"title":"Facebook","icon":"fa-facebook"},{"title":"Google+","icon":"fa-google-plus"},{"title":"LinkedIn","icon":"fa-linkedin"},{"title":"Pinterest","icon":"fa-pinterest"}]}]
</script>
<script src="site_libs/jquery-1.12.4/jquery.min.js"></script>
<meta name="viewport" content="width=device-width, initial-scale=1" />
<link href="site_libs/bootstrap-3.3.5/css/cosmo.min.css" rel="stylesheet" />
<script src="site_libs/bootstrap-3.3.5/js/bootstrap.min.js"></script>
<script src="site_libs/bootstrap-3.3.5/shim/html5shiv.min.js"></script>
<script src="site_libs/bootstrap-3.3.5/shim/respond.min.js"></script>
<script src="site_libs/stickytableheaders-0.1.19/jquery.stickytableheaders.min.js"></script>
<link href="site_libs/font-awesome-5.1.0/css/all.css" rel="stylesheet" />
<link href="site_libs/font-awesome-5.1.0/css/v4-shims.css" rel="stylesheet" />
<script src="site_libs/htmlwidgets-1.5.1/htmlwidgets.js"></script>
<script src="site_libs/plotly-binding-4.9.2.1/plotly.js"></script>
<script src="site_libs/typedarray-0.1/typedarray.min.js"></script>
<link href="site_libs/crosstalk-1.1.0.1/css/crosstalk.css" rel="stylesheet" />
<script src="site_libs/crosstalk-1.1.0.1/js/crosstalk.min.js"></script>
<link href="site_libs/plotly-htmlwidgets-css-1.52.2/plotly-htmlwidgets.css" rel="stylesheet" />
<script src="site_libs/plotly-main-1.52.2/plotly-latest.min.js"></script>
<link href="site_libs/datatables-css-0.0.0/datatables-crosstalk.css" rel="stylesheet" />
<script src="site_libs/datatables-binding-0.13/datatables.js"></script>
<link href="site_libs/dt-core-1.10.20/css/jquery.dataTables.min.css" rel="stylesheet" />
<link href="site_libs/dt-core-1.10.20/css/jquery.dataTables.extra.css" rel="stylesheet" />
<script src="site_libs/dt-core-1.10.20/js/jquery.dataTables.min.js"></script>
<script src="site_libs/proj4js-2.3.15/proj4.js"></script>
<link href="site_libs/highcharts-7.0.1/css/motion.css" rel="stylesheet" />
<link href="site_libs/highcharts-7.0.1/css/htmlwdgtgrid.css" rel="stylesheet" />
<script src="site_libs/highcharts-7.0.1/highcharts.js"></script>
<script src="site_libs/highcharts-7.0.1/highcharts-3d.js"></script>
<script src="site_libs/highcharts-7.0.1/highcharts-more.js"></script>
<script src="site_libs/highcharts-7.0.1/modules/stock.js"></script>
<script src="site_libs/highcharts-7.0.1/modules/map.js"></script>
<script src="site_libs/highcharts-7.0.1/modules/annotations.js"></script>
<script src="site_libs/highcharts-7.0.1/modules/boost.js"></script>
<script src="site_libs/highcharts-7.0.1/modules/data.js"></script>
<script src="site_libs/highcharts-7.0.1/modules/drag-panes.js"></script>
<script src="site_libs/highcharts-7.0.1/modules/drilldown.js"></script>
<script src="site_libs/highcharts-7.0.1/modules/item-series.js"></script>
<script src="site_libs/highcharts-7.0.1/modules/offline-exporting.js"></script>
<script src="site_libs/highcharts-7.0.1/modules/overlapping-datalabels.js"></script>
<script src="site_libs/highcharts-7.0.1/modules/exporting.js"></script>
<script src="site_libs/highcharts-7.0.1/modules/export-data.js"></script>
<script src="site_libs/highcharts-7.0.1/modules/funnel.js"></script>
<script src="site_libs/highcharts-7.0.1/modules/heatmap.js"></script>
<script src="site_libs/highcharts-7.0.1/modules/treemap.js"></script>
<script src="site_libs/highcharts-7.0.1/modules/sankey.js"></script>
<script src="site_libs/highcharts-7.0.1/modules/solid-gauge.js"></script>
<script src="site_libs/highcharts-7.0.1/modules/streamgraph.js"></script>
<script src="site_libs/highcharts-7.0.1/modules/sunburst.js"></script>
<script src="site_libs/highcharts-7.0.1/modules/vector.js"></script>
<script src="site_libs/highcharts-7.0.1/modules/wordcloud.js"></script>
<script src="site_libs/highcharts-7.0.1/modules/xrange.js"></script>
<script src="site_libs/highcharts-7.0.1/modules/tilemap.js"></script>
<script src="site_libs/highcharts-7.0.1/modules/venn.js"></script>
<script src="site_libs/highcharts-7.0.1/modules/gantt.js"></script>
<script src="site_libs/highcharts-7.0.1/modules/timeline.js"></script>
<script src="site_libs/highcharts-7.0.1/modules/parallel-coordinates.js"></script>
<script src="site_libs/highcharts-7.0.1/plugins/grouped-categories.js"></script>
<script src="site_libs/highcharts-7.0.1/plugins/motion.js"></script>
<script src="site_libs/highcharts-7.0.1/plugins/multicolor_series.js"></script>
<script src="site_libs/highcharts-7.0.1/custom/reset.js"></script>
<script src="site_libs/highcharts-7.0.1/custom/symbols-extra.js"></script>
<script src="site_libs/highcharts-7.0.1/custom/text-symbols.js"></script>
<script src="site_libs/highchart-binding-0.7.0/highchart.js"></script>
<style type="text/css">

/*
 Dashboard CSS from Keen IO Dashboards
 (https://github.com/keen/dashboards)
*/

body {
  background: #f2f2f2;
  padding: 60px 0 0 8px; /* padding-top overridden by theme */
}

body hr {
  border-color: #d7d7d7;
  margin: 10px 0;
}

.navbar-inverse .navbar-nav > li > a,
.navbar .navbar-brand {
  text-decoration: none;
}

.navbar-logo {
  margin-top: 1px;
}

.navbar-logo img {
  margin-right: 12px;
}

.navbar-author {
  margin-left: 10px;
  font-size: 15px;
}

.navbar .dropdown-menu .fa {
  min-width: 20px;
}

.navbar .dropdown-menu {
  min-width: 150px;
  max-height: 500px;
  overflow: auto;
}

.chart-wrapper,
.nav-tabs-custom,
.sbframe-commentary
{
  background: #fff;
  border: 1px solid #e2e2e2;
  border-radius: 3px;
  margin-bottom: 8px;
  margin-right: 8px;
}

.chart-title {
  border-bottom: 1px solid #d7d7d7;
  color: #666;
  font-size: 14px;
  font-weight: 300;
  padding: 7px 10px 4px;
}

.chart-wrapper .chart-title:empty {
  display: none;
}

.chart-wrapper .chart-stage {
  overflow: hidden;
  padding: 5px 10px;
  position: relative;
}

.chart-wrapper .chart-notes {
  background: #fbfbfb;
  border-top: 1px solid #e2e2e2;
  color: #808080;
  font-size: 12px;
  padding: 8px 10px 5px;
}

/*
 CSS for handling flexbox layout
*/

#dashboard-container {
  visibility: hidden;
}

.tab-content>.dashboard-page-wrapper.active {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
}

.dashboard-page-wrapper {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
      -ms-flex-direction: column;
          flex-direction: column;
}

.dashboard-row-orientation {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
      -ms-flex-direction: column;
          flex-direction: column;
}

.dashboard-row {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: horizontal;
  -webkit-box-direction: normal;
  -webkit-flex-direction: row;
      -ms-flex-direction: row;
          flex-direction: row;
}

.dashboard-row-flex {
  -webkit-box-flex: 1;
  -webkit-flex: 1;
      -ms-flex: 1;
          flex: 1;
}

.dashboard-column-orientation {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: horizontal;
  -webkit-box-direction: normal;
  -webkit-flex-direction: row;
      -ms-flex-direction: row;
          flex-direction: row;
}

.dashboard-column {
  -webkit-box-flex: 1;
  -webkit-flex: 1;
      -ms-flex: 1;
          flex: 1;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
      -ms-flex-direction: column;
          flex-direction: column;
}

.chart-wrapper-flex {
  -webkit-box-flex: 1;
  -webkit-flex: 1;
      -ms-flex: 1;
          flex: 1;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
      -ms-flex-direction: column;
          flex-direction: column;
}

.chart-stage-flex {
  -webkit-box-flex: 1;
  -webkit-flex: 1;
      -ms-flex: 1;
          flex: 1;
  position: relative;
}

.chart-shim {
  position: absolute;
  left: 8px; top: 8px; right: 8px; bottom: 8px;
}

.no-padding .chart-shim {
  left: 0; top: 0; right: 0; bottom: 0;
}

.flowing-content-shim {
  overflow: auto;
  left: 0; top: 0; right: 0; bottom: 0;
  padding-left: 8px;
  padding-right: 8px;
}

.flowing-content-container {
  padding-top: 8px;
  padding-bottom: 8px;
}

.chart-stage .table-bordered {
  border: none;
}

.chart-stage .table-bordered > tbody > tr > th,
.chart-stage .table-bordered > tfoot > tr > th,
.chart-stage .table-bordered > tbody > tr > td,
.chart-stage .table-bordered > tfoot > tr > td {
  border: none;
}

.chart-stage .table-bordered > tbody > tr > td {
  border-top: 1px solid #dddddd;
}

.chart-stage .table-bordered > thead > tr > th {
  border: none;
  border-bottom: 2px solid #dddddd;
}

.bootstrap-table table>thead {
  background-color: #fff;
}

.bootstrap-table table.data,
.bootstrap-table table.shiny-table {
  width: inherit !important;
}

.bootstrap-table table.data>tbody>tr>th,
.bootstrap-table table.shiny-table>tbody>tr>th {
  border-top: none;
  border-bottom: 2px solid #dddddd;
  padding: 5px;
}

.bootstrap-table .data td[align=right] {
  font-family: inherit;
}

.chart-wrapper form {
  padding-left: 5px;
  padding-right: 5px;
}

.shiny-input-container label {
  font-weight: normal;
}

.chart-stage .html-widget {
  width: 100% !important;
  height: 100% !important;
}

.chart-stage .html-widget-static-bound {
  width: 100% !important;
  height: 100% !important;
}

.chart-stage .shiny-bound-output {
  width: 100% !important;
  height: 100% !important;
}

/* Omit display of empty paragraphs */

.chart-shim>p:empty {
  display: none;
}

.chart-stage>p:empty {
  display: none;
}

/* Omit display of special knitr options div*/

.chart-stage .knitr-options {
  display: none;
}

/* Automatically resizing images */

.image-container {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  margin: 0;
}

.image-container img {
  opacity: 0;
  overflow: hidden;
}

/* Value box */

.value-box {
  border-radius: 2px;
  position: relative;
  display: block;
  margin-right: 8px;
  margin-bottom: 8px;
  box-shadow: 0 1px 1px rgba(0, 0, 0, 0.1);
}

.value-box > .inner {
  padding: 10px;
  padding-left: 20px;
  padding-right: 20px;
}

.value-box .value {
  font-size: 38px;
  font-weight: bold;
  margin: 0 0 3px 0;
  white-space: nowrap;
  padding: 0;
}

.value-box .caption {
  font-size: 15px;
}
.value-box .caption > small {
  display: block;
  font-size: 13px;
  margin-top: 5px;
}

.value-box .icon i {
  position: absolute;
  top: 15px;
  right: 15px;
  font-size: 80px;
  color: rgba(0, 0, 0, 0.15);
}

.linked-value:hover {
  cursor: pointer;
}

.value-box.linked-value:hover {
  box-shadow: 0 2px 2px rgba(0, 0, 0, 0.3);
}

/* STORYBOARD */

.storyboard-nav button {
  background: transparent;
  border: 0;
  opacity: .3;
  outline: none;
  padding: 0;
}

.storyboard-nav button:hover,
.storyboard-nav button:hover {
  opacity: .5;
}

.storyboard-nav button:disabled,
.storyboard-nav button:disabled {
  opacity: .1;
}

.storyboard-nav .sbnext,
.storyboard-nav .sbprev {
  float: left;
  width: 2%;
  height: 120px;
  font-size: 50px;
}

.storyboard-nav .sbprev {
  text-align: left;
  width: 2%;
}

.storyboard-nav .sbnext {
  float: right;
  text-align: right;
  margin-right: 8px;
}

.storyboard-nav .sbframelist {
  margin: 0 auto;
  width: 94%;
  height: 120px;
  overflow: hidden;
  text-shadow: none;
  margin-bottom: 8px;
}

.storyboard-nav .sbframelist ul {
  list-style: none;
  margin: 0;
  padding: 0;
  height: 100%;
}

.storyboard-nav .sbframelist ul li {
  float: left;
  width: 270px;
  height: 100%;
  padding: 10px 10px 10px 10px;
  margin-right: 8px;
  background: #fff;
  border: 1px solid #e2e2e2;
  border-radius: 3px;
  color: #3a3c47;
  text-align: left;
  font-size: 14px;
  cursor: pointer;
}

.storyboard-nav .sbframelist ul li:last-child {
  margin-right: 0px;
}

.storyboard-nav .sbframelist ul li.active {
  color: #fff;
  background: #B8B8B8;
}

.sbframe-commentary {
  width: 300px;
  background: #fbfbfb;
  font-size: 14px;
}

.sbframe-commentary ul {
  padding-left: 22px;
}

.sbframe.active {
  display: flex;
}

.sbframe:not(.active) {
  display: none;
}

/* NAV TABS */

.nav-tabs-custom > .nav-tabs {
  margin: 0;
  border-bottom: 1px solid #d7d7d7;
  color: #666;
  font-size: 14px;
  font-weight: 300;
  border-top-right-radius: 3px;
  border-top-left-radius: 3px;
}
.nav-tabs-custom > .nav-tabs > li {
  border-top: 3px solid transparent;
  margin-bottom: -1px;
  margin-right: 5px;
}
.nav-tabs-custom > .nav-tabs > li > a,
.nav-tabs-custom > .nav-tabs > li > a:active {
  color: #666;
  font-weight: 300;
  font-size: 14px;
  border-radius: 0;
  padding: 3px 10px 5px;
  text-transform: none;
}

.nav-tabs-custom > .nav-tabs > li:not(.active) > a {
  border-bottom-color: transparent;
}

.nav-tabs-custom > .nav-tabs > li > a.text-muted {
  color: #999;
}
.nav-tabs-custom > .nav-tabs > li > a,
.nav-tabs-custom > .nav-tabs > li > a:hover {
  background: transparent;
  margin: 0;
}
.nav-tabs-custom > .nav-tabs > li > a:hover {
  color: #999;
}
.nav-tabs-custom > .nav-tabs > li:not(.active) > a:hover,
.nav-tabs-custom > .nav-tabs > li:not(.active) > a:focus,
.nav-tabs-custom > .nav-tabs > li:not(.active) > a:active {
  border-color: transparent;
}
.nav-tabs-custom > .nav-tabs > li.active {
  border-top-color: #3c8dbc;
}
.nav-tabs-custom > .nav-tabs > li.active > a,
.nav-tabs-custom > .nav-tabs > li.active:hover > a {
  background-color: #fff;
  color: #666;
}
.nav-tabs-custom > .nav-tabs > li.active > a {
  border-top-color: transparent;
  border-left-color: #d7d7d7;
  border-right-color: #d7d7d7;
}
.nav-tabs-custom > .nav-tabs > li:first-of-type {
  margin-left: 0;
}
.nav-tabs-custom > .nav-tabs > li:first-of-type.active > a {
  border-left-color: transparent;
}
.nav-tabs-custom > .nav-tabs.pull-right {
  float: none !important;
}
.nav-tabs-custom > .nav-tabs.pull-right > li {
  float: right;
}
.nav-tabs-custom > .nav-tabs.pull-right > li:first-of-type {
  margin-right: 0;
}
.nav-tabs-custom > .nav-tabs.pull-right > li:first-of-type > a {
  border-left-width: 1px;
}
.nav-tabs-custom > .nav-tabs.pull-right > li:first-of-type.active > a {
  border-left-color: #d7d7d7;
  border-right-color: transparent;
}
.nav-tabs-custom > .nav-tabs > li.header {
  line-height: 35px;
  padding: 0 10px;
  font-size: 20px;
  color: #666;
}
.nav-tabs-custom > .nav-tabs > li.header > .fa,
.nav-tabs-custom > .nav-tabs > li.header > .glyphicon,
.nav-tabs-custom > .nav-tabs > li.header > .ion {
  margin-right: 5px;
}
.nav-tabs-custom > .tab-content {
  background: #fff;
  padding: 0;
  border-bottom-right-radius: 3px;
  border-bottom-left-radius: 3px;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
}

.nav-tabs-custom > .tab-content > .chart-wrapper {
  background: #fff;
  border: none;
  margin: 0;
}


.nav-tabs-custom > .tab-content > .active {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
}

.nav-tabs-custom .dropdown.open > a:active,
.nav-tabs-custom .dropdown.open > a:focus {
  background: transparent;
  color: #999;
}


@media (max-width: 767px) {
  .value-box {
    text-align: center;
    margin-right: 8px;
  }
  .value-box .icon {
    display: none;
  }
}

/* Fixed position sidebar */

.section.sidebar {
  position: fixed;
  top: 51px; /* overridden by theme */
  left: 0;
  bottom: 0;
  border-right: 1px solid #e2e2e2;
  background-color: white; /* overridden by theme */
  padding-left: 10px;
  padding-right: 10px;
  visibility: hidden;
  overflow: auto;
}

.section.sidebar form p:first-child {
  margin-top: 10px;
}

/* Embedded source code */

#flexdashboard-source-code {
  display: none;
}

.featherlight-content #flexdashboard-source-code {
  display: inline-block;
}

.featherlight-content {
  width: 80%;
  max-width: 800px;
  padding: 0 !important;
  border-bottom: none !important;
}

.featherlight:last-of-type {
  background: rgba(0, 0, 0, 0.7);
}

.featherlight-inner {
  width: 100%;
}

.featherlight-content pre {
  margin: 0;
  border: 0;
  background: #fff;
  font-size: 12px;
}

.unselectable {
  -ms-user-select: none;
  -webkit-user-select: none;
  -khtml-user-select: none;
  -moz-user-select: -moz-none;
  -o-user-select: none;
  user-select: none;
}

#flexdashboard-source-code code {
  -ms-user-select: text;
  -webkit-user-select: text;
  -khtml-user-select: text;
  -moz-user-select: text;
  -o-user-select: text;
  user-select: text;
}

/* DataTables Tweaks */

.dataTables_filter input[type="search"] {
  -webkit-appearance: searchfield;
  outline: none;
}

.dataTables_wrapper.no-footer
.dataTables_info {
  padding-top: 0;
}


table.dataTable thead th {
  border-bottom: 1px solid #d7d7d7;
}

.dataTables_wrapper.no-footer .dataTables_scrollBody {
  border-bottom: 1px solid #d7d7d7;
}

/* Mobile phone only CSS */

.desktop-layout div.section.mobile {
  display: none;
}

.mobile-layout div.section.no-mobile {
  display: none;
}

.mobile-figure {
  display: none;
}



body {
  padding-top: 60px;
}

.section.sidebar {
  top: 51px;
  background-color: rgba(39, 128, 227, 0.1);
}

.value-box {
  color: #f9f9f9;
}

.bg-primary {
  background-color: rgba(39, 128, 227, 0.7);
}

.storyboard-nav .sbframelist ul li.active {
  background-color: rgba(39, 128, 227, 0.7);
}

.nav-tabs-custom > .nav-tabs > li.active {
  border-top-color: rgba(39, 128, 227, 0.7);
}

.bg-info {
  background-color: rgba(153, 84, 187, 0.7);
}

.bg-warning {
  background-color: rgba(255, 117, 24, 0.7);
}

.bg-danger {
  background-color: rgba(255, 0, 57, 0.7);
}

.bg-success {
  background-color: rgba(63, 182, 24, 0.7);
}

.chart-title {
  font-weight: 500;
}

.nav-tabs-custom > .nav-tabs > li > a,
.nav-tabs-custom > .nav-tabs > li > a:active {
  font-weight: 500;
}

@media only screen and (min-width: 768px) {
html, body {
  height: 100%;
}

#dashboard-container {
  height: 100%;
}
}
</style>



</head>

<body>

<div class="navbar navbar-inverse navbar-fixed-top" role="navigation">
<div class="container-fluid">
<div class="navbar-header">

<button id="navbar-button" type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar">
<span class="icon-bar"></span>
<span class="icon-bar"></span>
<span class="icon-bar"></span>
</button>

<span class="navbar-logo pull-left">
  
</span>
<span class="navbar-brand">
  Coronavirus
  <span class="navbar-author">
        </span>
</span>

</div>
<div id="navbar" class="navbar-collapse collapse">
<ul class="nav navbar-nav navbar-left">
</ul>
<ul class="nav navbar-nav navbar-right">
</ul>
</div><!--/.nav-collapse-->
</div><!--/.container-->
</div><!--/.navbar-->

<script type="text/javascript">


var FlexDashboard = (function () {

  // initialize options
  var _options = {};

  var FlexDashboard = function() {

    // default options
    _options = $.extend(_options, {
      theme: "cosmo",
      fillPage: false,
      orientation: 'columns',
      storyboard: false,
      defaultFigWidth: 576,
      defaultFigHeight: 461,
      defaultFigWidthMobile: 360,
      defaultFigHeightMobile: 461,
      isMobile: false,
      isPortrait: false
    });
  };

  function init(options) {

    // extend default options
    $.extend(true, _options, options);

    // add ids to sections that don't have them (pandoc won't assign ids
    // to e.g. sections with titles consisting of only chinese characters)
    var nextId = 1;
    $('.level1:not([id]),.level2:not([id]),.level3:not([id])').each(function() {
      $(this).attr('id', 'dashboard-' + nextId++);
    });

    // find navbar items
    var navbarItems = $('#flexdashboard-navbar');
    if (navbarItems.length)
      navbarItems = JSON.parse(navbarItems.html());
    addNavbarItems(navbarItems);

    // find the main dashboard container
    var dashboardContainer = $('#dashboard-container');

    // resolve mobile classes
    resolveMobileClasses(dashboardContainer);

    // one time global initialization for components
    componentsInit(dashboardContainer);

    // look for a global sidebar
    var globalSidebar = dashboardContainer.find(".section.level1.sidebar");
    if (globalSidebar.length > 0) {

      // global layout for fullscreen displays
      if (!isMobilePhone()) {

         // hoist it up to the top level
         globalSidebar.insertBefore(dashboardContainer);

         // lay it out (set width/positions)
         layoutSidebar(globalSidebar, dashboardContainer);

      // tuck sidebar into first page for mobile phones
      } else {

        // convert it into a level3 section
        globalSidebar.removeClass('sidebar');
        globalSidebar.removeClass('level1');
        globalSidebar.addClass('level3');
        var h1 = globalSidebar.children('h1');
        var h3 = $('<h3></h3>');
        h3.html(h1.html());
        h3.insertBefore(h1);
        h1.remove();

        // move it into the first page
        var page = dashboardContainer.find('.section.level1').first();
        if (page.length > 0)
          page.prepend(globalSidebar);
      }
    }

    // look for pages to layout
    var pages = $('div.section.level1');
    if (pages.length > 0) {

        // find the navbar and collapse on clicked
        var navbar = $('#navbar');
        navbar.on("click", "a[data-toggle!=dropdown]", null, function () {
           navbar.collapse('hide');
        });

        // envelop the dashboard container in a tab content div
        dashboardContainer.wrapInner('<div class="tab-content"></div>');

        pages.each(function(index) {

          // lay it out
          layoutDashboardPage($(this));

          // add it to the navbar
          addToNavbar($(this), index === 0);

        });

    } else {

      // remove the navbar and navbar button if we don't
      // have any navbuttons
      if (navbarItems.length === 0) {
        $('#navbar').remove();
        $('#navbar-button').remove();
      }

      // add the storyboard class if requested
      if (_options.storyboard)
        dashboardContainer.addClass('storyboard');

      // layout the entire page
      layoutDashboardPage(dashboardContainer);
    }

    // if we are in shiny we need to trigger a window resize event to
    // force correct layout of shiny-bound-output elements
    if (isShinyDoc())
      $(window).trigger('resize');

    // make main components visible
    $('.section.sidebar').css('visibility', 'visible');
    dashboardContainer.css('visibility', 'visible');

    // handle location hash
    handleLocationHash();

    // intialize prism highlighting
    initPrismHighlighting();

    // record mobile and orientation state then register a handler
    // to refresh if it changes
    _options.isMobile = isMobilePhone();
    _options.isPortrait = isPortrait();
    $(window).on('resize', function() {
      if (_options.isMobile !== isMobilePhone() ||
          _options.isPortrait !== isPortrait()) {
        window.location.reload();
      }
    });

    // trigger layoutcomplete event
    dashboardContainer.trigger('flexdashboard:layoutcomplete');
  }

  function resolveMobileClasses(dashboardContainer) {
     // add top level layout class
    dashboardContainer.addClass(isMobilePhone() ? 'mobile-layout' :
                                                  'desktop-layout');

    // look for .mobile sections and add .no-mobile to their peers
    var mobileSections = $('.section.mobile');
    mobileSections.each(function() {
       var id = $(this).attr('id');
       var nomobileId = id.replace(/-\d+$/, '');
       $('#' + nomobileId).addClass('no-mobile');
    });
  }

  function addNavbarItems(navbarItems) {

    var navbarLeft = $('ul.navbar-left');
    var navbarRight = $('ul.navbar-right');

    for (var i = 0; i<navbarItems.length; i++) {

      // get the item
      var item = navbarItems[i];

      // determine the container
      var container = null;
      if (item.align === "left")
        container = navbarLeft;
      else
        container = navbarRight;

      // navbar menu if we have multiple items
      if (item.items) {
        var menu = navbarMenu(null, item.icon, item.title, container);
        for (var j = 0; j<item.items.length; j++) {
          var subItem = item.items[j];
          var li = $('<li></li>');
          li.append(navbarLink(subItem.icon, subItem.title, subItem.href, subItem.target));
          menu.append(li);
        }
      } else {
        var li = $('<li></li>');
        li.append(navbarLink(item.icon, item.title, item.href, item.target));
        container.append(li);
      }
    }
  }

  // create or get a reference to an existing dropdown menu
  function navbarMenu(id, icon, title, container) {
    var existingMenu = [];
    if (id)
      existingMenu = container.children('#' + id);
    if (existingMenu.length > 0) {
      return existingMenu.children('ul');
    } else {
      var li = $('<li></li>');
      if (id)
        li.attr('id', id);
      li.addClass('dropdown');
      // auto add "Share" title on mobile if necessary
      if (!title && icon && (icon === "fa-share-alt") && isMobilePhone())
        title = "Share";
      if (title) {
        title = title + ' <span class="caret"></span>';
      }
      var a = navbarLink(icon, title, "#");
      a.addClass('dropdown-toggle');
      a.attr('data-toggle', 'dropdown');
      a.attr('role', 'button');
      a.attr('aria-expanded', 'false');
      li.append(a);
      var ul = $('<ul class="dropdown-menu"></ul>');
      ul.attr('role', 'menu');
      li.append(ul);
      container.append(li);
      return ul;
    }
  }

  function addToNavbar(page, active) {

    // capture the id and data-icon attribute (if any)
    var id = page.attr('id');
    var icon = page.attr('data-icon');
    var navmenu = page.attr('data-navmenu');

    // get hidden state (transfer this to navbar)
    var hidden = page.hasClass('hidden');
    page.removeClass('hidden');

    // sanitize the id for use with bootstrap tabs
    id = id.replace(/[.\/?&!#<>]/g, '').replace(/\s/g, '_');
    page.attr('id', id);

    // get the wrapper
    var wrapper = page.closest('.dashboard-page-wrapper');

    // move the id to the wrapper
    page.removeAttr('id');
    wrapper.attr('id', id);

    // add the tab-pane class to the wrapper
    wrapper.addClass('tab-pane');
    if (active)
      wrapper.addClass('active');

    // get a reference to the h1, discover it's id and title, then remove it
    var h1 = wrapper.find('h1').first();
    var title = h1.html();
    h1.remove();

    // create a navbar item
    var li = $('<li></li>');
    var a = navbarLink(icon, title, '#' + id);
    a.attr('data-toggle', 'tab');
    li.append(a);

    // add it to the navbar (or navbar menu if specified)
    var container = $('ul.navbar-left');
    if (navmenu) {
      var menuId = navmenu.replace(/\s+/g, '');
      var menu = navbarMenu(menuId, null, navmenu, container);
      menu.append(li);
    } else {
      container.append(li);
    }

    // hide it if requested
    if (hidden)
      li.addClass('hidden');
  }

  function navbarLink(icon, title, href, target) {

    var a = $('<a></a>');
    if (icon) {

      // get the name of the icon set and icon
      var dashPos = icon.indexOf("-");
      var iconSet = icon.substring(0, dashPos);
      var iconName = icon.substring(dashPos + 1);

      // create the icon
      var iconElement = $('<span class="' + iconSet + ' ' + icon + '"></span>');
      if (title)
        iconElement.css('margin-right', '7px');
      a.append(iconElement);
      // if href is null see if we can auto-generate based on icon (e.g. social)
      if (!href)
        maybeGenerateLinkFromIcon(iconName, a);
    }
    if (title)
      a.append(title);

    // add the href.
    if (href) {
      if (href === "source_embed") {
        a.attr('href', '#');
        a.attr('data-featherlight', "#flexdashboard-source-code");
        a.featherlight({
            beforeOpen: function(event){
              $('body').addClass('unselectable');
            },
            afterClose: function(event){
              $('body').removeClass('unselectable');
            }
        });
      } else {
        a.attr('href', href);
      }
    }

    // add the arget
    if (target)
      a.attr('target', target);

    return a;
  }

  // auto generate a link from an icon name (e.g. twitter) when possible
  function maybeGenerateLinkFromIcon(iconName, a) {

     var serviceLinks = {
      "twitter": "https://twitter.com/share?text=" + encodeURIComponent(document.title) + "&url="+encodeURIComponent(location.href),
      "facebook": "https://www.facebook.com/sharer/sharer.php?s=100&p[url]="+encodeURIComponent(location.href),
      "google-plus": "https://plus.google.com/share?url="+encodeURIComponent(location.href),
      "linkedin": "https://www.linkedin.com/shareArticle?mini=true&url="+encodeURIComponent(location.href) + "&title=" + encodeURIComponent(document.title),
      "pinterest": "https://pinterest.com/pin/create/link/?url="+encodeURIComponent(location.href) + "&description=" + encodeURIComponent(document.title)
    };

    var makeSocialLink = function(a, href) {
      a.attr('href', '#');
      a.on('click', function(e) {
        e.preventDefault();
        window.open(href);
      });
    };

    $.each(serviceLinks, function(key, value) {
      if (iconName.indexOf(key) !== -1)
        makeSocialLink(a, value);
    });
  }

  // layout a dashboard page
  function layoutDashboardPage(page) {

    // use a page wrapper so that free form content above the
    // dashboard appears at the top rather than the side (as it
    // would without the wrapper in a column orientation)
    var wrapper = $('<div class="dashboard-page-wrapper"></div>');
    page.wrap(wrapper);

    // if there are no level2 or level3 headers synthesize a level3
    // header to contain the (e.g. frame it, scroll container, etc.)
    var headers = page.find('h2,h3');
    if (headers.length === 0)
      page.wrapInner('<div class="section level3"></div>');

    // hoist up any content before level 2 or level 3 headers
    var children = page.children();
    children.each(function(index) {
      if ($(this).hasClass('level2') || $(this).hasClass('level3'))
        return false;
      $(this).insertBefore(page);
    });

    // determine orientation and fillPage behavior for distinct media
    var orientation, fillPage, storyboard;

    // media: mobile phone
    if (isMobilePhone()) {

      // if there is a sidebar we need to ensure it's content
      // is properly framed as an h3
      var sidebar = page.find('.section.sidebar');
      sidebar.removeClass('sidebar');
      sidebar.wrapInner('<div class="section level3"></div>');
      var h2 = sidebar.find('h2');
      var h3 = $('<h3></h3>');
      h3.html(h2.html());
      h3.insertBefore(h2);
      h2.remove();

      // wipeout h2 elements then enclose them in a single h2
      var level2 = page.find('div.section.level2');
      level2.each(function() {
        level2.children('h2').remove();
        level2.children().unwrap();
      });
      page.wrapInner('<div class="section level2"></div>');

      // substitute mobile images
      if (isPortrait()) {
        var mobileFigures = $('img.mobile-figure');
        mobileFigures.each(function() {
          // get the src (might be base64 encoded)
          var src = $(this).attr('src');

          // find it's peer
          var id = $(this).attr('data-mobile-figure-id');
          var img = $('img[data-figure-id=' + id + "]");
          img.attr('src', src)
             .attr('width', _options.defaultFigWidthMobile)
             .attr('height', _options.defaultFigHeightMobile);
        });
      }

      // hoist storyboard commentary into it's own section
      if (page.hasClass('storyboard')) {
        var commentaryHR = page.find('div.section.level3 hr');
        commentaryHR.each(function() {
          var commentary = $(this).nextAll().detach();
          var commentarySection = $('<div class="section level3"></div>');
          commentarySection.append(commentary);
          commentarySection.insertAfter($(this).closest('div.section.level3'));
          $(this).remove();
        });
      }

      // force a non full screen layout by columns
      orientation = _options.orientation = 'columns';
      fillPage = _options.fillPage = false;
      storyboard = _options.storyboard = false;

    // media: desktop
    } else {

      // determine orientation
      orientation = page.attr('data-orientation');
      if (orientation !== 'rows' && orientation != 'columns')
        orientation = _options.orientation;

      // determine storyboard mode
      storyboard = page.hasClass('storyboard');

      // fillPage based on options (force for storyboard)
      fillPage = _options.fillPage || storyboard;

      // handle sidebar
      var sidebar = page.find('.section.level2.sidebar');
      if (sidebar.length > 0)
        layoutSidebar(sidebar, page);
    }

    // give it and it's parent divs height: 100% if we are in fillPage mode
    if (fillPage) {
      page.addClass('vertical-layout-fill');
      page.css('height', '100%');
      page.parents('div').css('height', '100%');
    } else {
      page.addClass('vertical-layout-scroll');
    }

    // perform the layout
    if (storyboard)
      layoutPageAsStoryboard(page);
    else if (orientation === 'rows')
      layoutPageByRows(page, fillPage);
    else if (orientation === 'columns')
      layoutPageByColumns(page, fillPage);
  }

  function layoutSidebar(sidebar, content) {

    // get it out of the header hierarchy
    sidebar = sidebar.first();
    if (sidebar.hasClass('level1')) {
      sidebar.removeClass('level1');
      sidebar.children('h1').remove();
    } else if (sidebar.hasClass('level2')) {
      sidebar.removeClass('level2');
      sidebar.children('h2').remove();
    }

    // determine width
    var sidebarWidth = isTablet() ? 220 : 250;
    var dataWidth = parseInt(sidebar.attr('data-width'));
    if (dataWidth)
      sidebarWidth = dataWidth;

    // set the width and shift the page right to accomodate the sidebar
    sidebar.css('width', sidebarWidth + 'px');
    content.css('padding-left', sidebarWidth + 'px');

    // wrap it's contents in a form
    sidebar.wrapInner($('<form></form>'));
  }

  function layoutPageAsStoryboard(page) {

    // create storyboard navigation
    var nav = $('<div class="storyboard-nav"></div>');

    // add navigation buttons
    var prev = $('<button class="sbprev"><i class="fa fa-angle-left"></i></button>');
    nav.append(prev);
    var next= $('<button class="sbnext"><i class="fa fa-angle-right"></i></button>');
    nav.append(next);

    // add navigation frame
    var frameList = $('<div class="sbframelist"></div>');
    nav.append(frameList);
    var ul = $('<ul></ul>');
    frameList.append(ul);

     // find all the level3 sections (those are the storyboard frames)
    var frames = page.find('div.section.level3');
    frames.each(function() {

      // mark it
      $(this).addClass('sbframe');

      // divide it into chart content and (optional) commentary
      $(this).addClass('dashboard-column-orientation');

      // stuff the chart into it's own div w/ flex
      $(this).wrapInner('<div class="sbframe-component"></div>');
      setFlex($(this), 1);
      var frame = $(this).children('.sbframe-component');

      // extract the title from the h3
      var li = $('<li></li>');
      var h3 = frame.children('h3');
      li.html(h3.html());
      h3.remove();
      ul.append(li);

      // extract commentary
      var hr = frame.children('hr');
      if (hr.length) {
        var commentary = hr.nextAll().detach();
        hr.remove();
        var commentaryFrame = $('<div class="sbframe-commentary"></div>');
        commentaryFrame.addClass('flowing-content-shim');
        commentaryFrame.addClass('flowing-content-container');
        commentaryFrame.append(commentary);
        $(this).append(commentaryFrame);

        // look for a data-commentary-width attribute
        var commentaryWidth = $(this).attr('data-commentary-width');
        if (commentaryWidth)
          commentaryFrame.css('width', commentaryWidth + 'px');
      }

      // layout the chart (force flex)
      var result = layoutChart(frame, true);

      // ice the notes if there are none
      if (!result.notes)
        frame.find('.chart-notes').remove();

      // set flex on chart
      setFlex(frame, 1);
    });

    // create a div to hold all the frames
    var frameContent = $('<div class="sbframe-content"></div>');
    frameContent.addClass('dashboard-row-orientation');
    frameContent.append(frames.detach());

    // row orientation to stack nav and frame content
    page.addClass('dashboard-row-orientation');
    page.append(nav);
    page.append(frameContent);
    setFlex(frameContent, 1);

    // initialize sly
    var sly = new Sly(frameList, {
    		horizontal: true,
    		itemNav: 'basic',
    		smart: true,
    		activateOn: 'click',
    		startAt: 0,
    		scrollBy: 1,
    		activatePageOn: 'click',
    		speed: 200,
    		moveBy: 600,
    		dragHandle: true,
    		dynamicHandle: true,
    		clickBar: true,
    		keyboardNavBy: 'items',
    		next: next,
    		prev: prev
    	}).init();

    // make first frame active
    frames.removeClass('active');
    frames.first().addClass('active');

    // subscribe to frame changed events
    sly.on('active', function (eventName, itemIndex) {
      frames.removeClass('active');
      frames.eq(itemIndex).addClass('active')
                          .trigger('shown');
    });
  }

  function layoutPageByRows(page, fillPage) {

    // row orientation
    page.addClass('dashboard-row-orientation');

    // find all the level2 sections (those are the rows)
    var rows = page.find('div.section.level2');

    // if there are no level2 sections then treat the
    // entire page as if it's a level 2 section
    if (rows.length === 0) {
      page.wrapInner('<div class="section level2"></div>');
      rows = page.find('div.section.level2');
    }

    rows.each(function () {

      // flags
      var haveNotes = false;
      var haveFlexHeight = true;

      // remove the h2
      $(this).children('h2').remove();

      // check for a tabset
      var isTabset = $(this).hasClass('tabset');
      if (isTabset)
        layoutTabset($(this));

      // give it row layout semantics if it's not a tabset
      if (!isTabset)
        $(this).addClass('dashboard-row');

      // find all of the level 3 subheads
      var columns = $(this).find('div.section.level3');

      // determine figureSizes sizes
      var figureSizes = chartFigureSizes(columns);

      // fixup the columns
      columns.each(function(index) {

        // layout the chart (force flex if we are in a tabset)
        var result = layoutChart($(this), isTabset);

        // update flexHeight state
        if (!result.flex)
          haveFlexHeight = false;

        // update state
        if (result.notes)
          haveNotes = true;

        // set the column flex based on the figure width
        // (value boxes will just get the default figure width)
        var chartWidth = figureSizes[index].width;
        setFlex($(this), chartWidth + ' ' + chartWidth + ' 0px');

      });

      // remove empty chart note divs
      if (isTabset)
        $(this).find('.chart-notes').filter(function() {
            return $(this).html() === "&nbsp;";
        }).remove();
      if (!haveNotes)
        $(this).find('.chart-notes').remove();

       // make it a flexbox row
      if (haveFlexHeight)
        $(this).addClass('dashboard-row-flex');

      // now we can set the height on all the wrappers (based on maximum
      // figure height + room for title and notes, or data-height on the
      // container if specified). However, don't do this if there is
      // no flex on any of the constituent columns
      var flexHeight = null;
      var dataHeight = parseInt($(this).attr('data-height'));
      if (dataHeight)
        flexHeight = adjustedHeight(dataHeight, columns.first());
      else if (haveFlexHeight)
        flexHeight = maxChartHeight(figureSizes, columns);
      if (flexHeight) {
        if (fillPage)
          setFlex($(this), flexHeight + ' ' + flexHeight + ' 0px');
        else {
          $(this).css('height', flexHeight + 'px');
          setFlex($(this), '0 0 ' + flexHeight + 'px');
        }
      }

    });
  }

  function layoutPageByColumns(page, fillPage) {

    // column orientation
    page.addClass('dashboard-column-orientation');

    // find all the level2 sections (those are the columns)
    var columns = page.find('div.section.level2');

    // if there are no level2 sections then treat the
    // entire page as if it's a level 2 section
    if (columns.length === 0) {
      page.wrapInner('<div class="section level2"></div>');
      columns = page.find('div.section.level2');
    }

    // layout each column
    columns.each(function (index) {

      // remove the h2
      $(this).children('h2').remove();

      // make it a flexbox column
      $(this).addClass('dashboard-column');

      // check for a tabset
      var isTabset = $(this).hasClass('tabset');
      if (isTabset)
        layoutTabset($(this));

      // find all the h3 elements
      var rows = $(this).find('div.section.level3');

      // get the figure sizes for the rows
      var figureSizes = chartFigureSizes(rows);

      // column flex is the max row width (or data-width if specified)
      var flexWidth;
      var dataWidth = parseInt($(this).attr('data-width'));
      if (dataWidth)
        flexWidth = dataWidth;
      else
        flexWidth = maxChartWidth(figureSizes);
      setFlex($(this), flexWidth + ' ' + flexWidth + ' 0px');

      // layout each chart
      rows.each(function(index) {

        // perform the layout
        var result = layoutChart($(this), false);

        // ice the notes if there are none
        if (!result.notes)
          $(this).find('.chart-notes').remove();

        // set flex height based on figHeight, then adjust
        if (result.flex) {
          var chartHeight = figureSizes[index].height;
          chartHeight = adjustedHeight(chartHeight, $(this));
          if (fillPage)
            setFlex($(this), chartHeight + ' ' + chartHeight + ' 0px');
          else {
            $(this).css('height', chartHeight + 'px');
            setFlex($(this), chartHeight + ' ' + chartHeight + ' ' + chartHeight + 'px');
          }
        }
      });
    });
  }

  function chartFigureSizes(charts) {

    // sizes
    var figureSizes = new Array(charts.length);

    // check each chart
    charts.each(function(index) {

      // start with default
      figureSizes[index] = {
        width: _options.defaultFigWidth,
        height: _options.defaultFigHeight
      };

      // look for data-height or data-width then knit options
      var dataWidth = parseInt($(this).attr('data-width'));
      var dataHeight = parseInt($(this).attr('data-height'));
      var knitrOptions = $(this).find('.knitr-options:first');
      var knitrWidth, knitrHeight;
      if (knitrOptions) {
        knitrWidth = parseInt(knitrOptions.attr('data-fig-width'));
        knitrHeight =  parseInt(knitrOptions.attr('data-fig-height'));
      }

      // width
      if (dataWidth)
        figureSizes[index].width = dataWidth;
      else if (knitrWidth)
        figureSizes[index].width = knitrWidth;

      // height
      if (dataHeight)
        figureSizes[index].height = dataHeight;
      else if (knitrHeight)
        figureSizes[index].height = knitrHeight;
    });

    // return sizes
    return figureSizes;
  }

  function maxChartHeight(figureSizes, charts) {

    // first compute the maximum height
    var maxHeight = _options.defaultFigHeight;
    for (var i = 0; i<figureSizes.length; i++)
      if (figureSizes[i].height > maxHeight)
        maxHeight = figureSizes[i].height;

    // now add offests for chart title and chart notes
    if (charts.length)
      maxHeight = adjustedHeight(maxHeight, charts.first());

    return maxHeight;
  }

  function adjustedHeight(height, chart) {
    if (chart.length > 0) {
      var chartTitle = chart.find('.chart-title');
      if (chartTitle.length)
        height += chartTitle.first().outerHeight();
      var chartNotes = chart.find('.chart-notes');
      if (chartNotes.length)
        height += chartNotes.first().outerHeight();
    }
    return height;
  }

  function maxChartWidth(figureSizes) {
    var maxWidth = _options.defaultFigWidth;
    for (var i = 0; i<figureSizes.length; i++)
      if (figureSizes[i].width > maxWidth)
        maxWidth = figureSizes[i].width;
    return maxWidth;
  }

  // layout a chart
  function layoutChart(chart, forceFlex) {

    // state to return
    var result = {
      notes: false,
      flex: false
    };

    // extract the title
    var title = extractTitle(chart);

    // find components that apply to this container
    var components = componentsFind(chart);

    // if it's a custom component then call it and return
    var customComponents = componentsCustom(components);
    if (customComponents.length) {
      componentsLayout(customComponents, title, chart);
      result.notes = false;
      result.flex = forceFlex || componentsFlex(customComponents);
      return result;
    }

    // put all the content in a chart wrapper div
    chart.addClass('chart-wrapper');
    chart.wrapInner('<div class="chart-stage"></div>');
    var chartContent = chart.children('.chart-stage');

    // flex the content if appropriate
    result.flex = forceFlex || componentsFlex(components);
    if (result.flex) {
      // add flex classes
      chart.addClass('chart-wrapper-flex');
      chartContent.addClass('chart-stage-flex');

      // additional shim to break out of flexbox sizing
      chartContent.wrapInner('<div class="chart-shim"></div>');
      chartContent = chartContent.children('.chart-shim');
    }

    // set custom data-padding attribute
    var pad = chart.attr('data-padding');
    if (pad) {
      if (pad === "0")
        chart.addClass('no-padding');
      else {
        pad = pad + 'px';
        chartContent.css('left', pad)
                    .css('top', pad)
                    .css('right', pad)
                    .css('bottom', pad)
      }
    }

    // call compoents
    componentsLayout(components, title, chartContent);

    // also activate components on shiny output
    findShinyOutput(chartContent).on('shiny:value',
      function(event) {
        var element = $(event.target);
        setTimeout(function() {

          // see if we opted out of flex based on our output (for shiny
          // we can't tell what type of output we have until after the
          // value is bound)
          var components = componentsFind(element);
          var flex = forceFlex || componentsFlex(components);
          if (!flex) {
            chart.css('height', "");
            setFlex(chart, "");
            chart.removeClass('chart-wrapper-flex');
            chartContent.removeClass('chart-stage-flex');
            chartContent.children().unwrap();
          }

          // perform layout
          componentsLayout(components, title, element.parent());
        }, 10);
      });

    // add the title
    var chartTitle = $('<div class="chart-title"></div>');
    chartTitle.html(title);
    chart.prepend(chartTitle);

    // add the notes section
    var chartNotes = $('<div class="chart-notes"></div>');
    chartNotes.html('&nbsp;');
    chart.append(chartNotes);

    // attempt to extract notes if we have a component
    if (components.length)
      result.notes = extractChartNotes(chartContent, chartNotes);

    // return result
    return result;
  }

  // build a tabset from a section div with the .tabset class
  function layoutTabset(tabset) {

    // check for fade option
    var fade = tabset.hasClass("tabset-fade");
    var navClass = "nav-tabs";

    // determine the heading level of the tabset and tabs
    var match = tabset.attr('class').match(/level(\d) /);
    if (match === null)
      return;
    var tabsetLevel = Number(match[1]);
    var tabLevel = tabsetLevel + 1;

    // find all subheadings immediately below
    var tabs = tabset.find("div.section.level" + tabLevel);
    if (!tabs.length)
      return;

    // create tablist and tab-content elements
    var tabList = $('<ul class="nav ' + navClass + '" role="tablist"></ul>');
    $(tabs[0]).before(tabList);
    var tabContent = $('<div class="tab-content"></div>');
    $(tabs[0]).before(tabContent);

    // build the tabset
    tabs.each(function(i) {

      // get the tab div
      var tab = $(tabs[i]);

      // get the id then sanitize it for use with bootstrap tabs
      var id = tab.attr('id');

      // sanitize the id for use with bootstrap tabs
      id = id.replace(/[.\/?&!#<>]/g, '').replace(/\s/g, '_');
      tab.attr('id', id);

      // get the heading element within it and grab it's text
      var heading = tab.find('h' + tabLevel + ':first');
      var headingText = heading.html();

      // build and append the tab list item
      var a = $('<a role="tab" data-toggle="tab">' + headingText + '</a>');
      a.attr('href', '#' + id);
      a.attr('aria-controls', id);
      var li = $('<li role="presentation"></li>');
      li.append(a);
      if (i === 0)
        li.attr('class', 'active');
      tabList.append(li);

      // set it's attributes
      tab.attr('role', 'tabpanel');
      tab.addClass('tab-pane');
      tab.addClass('tabbed-pane');
      tab.addClass('no-title');
      if (fade)
        tab.addClass('fade');
      if (i === 0) {
        tab.addClass('active');
        if (fade)
          tab.addClass('in');
      }

      // move it into the tab content div
      tab.detach().appendTo(tabContent);
    });

    // add nav-tabs-custom
    tabset.addClass('nav-tabs-custom');

    // internal layout is dashboard-column with tab-content flexing
    tabset.addClass('dashboard-column');
    setFlex(tabContent, 1);
  }

  // one time global initialization for components
  function componentsInit(dashboardContainer) {
    for (var i=0; i<window.FlexDashboardComponents.length; i++) {
      var component = window.FlexDashboardComponents[i];
      if (component.init)
        component.init(dashboardContainer);
    }
  }

  // find components that apply within a container
  function componentsFind(container) {

    // look for components
    var components = [];
    for (var i=0; i<window.FlexDashboardComponents.length; i++) {
      var component = window.FlexDashboardComponents[i];
      if (component.find(container).length)
        components.push(component);
    }

    // if there were none then use a special flowing content component
    // that just adds a scrollbar in fillPage mode
    if (components.length == 0) {
      components.push({
        find: function(container) {
          return container;
        },

        flex: function(fillPage) {
          return fillPage;
        },

        layout: function(title, container, element, fillPage) {
          if (fillPage) {
            container.addClass('flowing-content-shim');
            container.addClass('flowing-content-container');
          }
        }
      });
    }

    return components;
  }

  // if there is a custom component then pick it out
  function componentsCustom(components) {
    var customComponent = [];
    for (var i=0; i<components.length; i++)
      if (components[i].type === "custom") {
        customComponent.push(components[i]);
        break;
      }
    return customComponent;
  }

  // query all components for flex
  function componentsFlex(components) {

    // no components at all means no flex
    if (components.length === 0)
      return false;

    // otherwise query components (assume true unless we see false)
    var isMobile = isMobilePhone();
    for (var i=0; i<components.length; i++)
      if (components[i].flex && !components[i].flex(_options.fillPage))
        return false;
    return true;
  }

  // layout all components
  function componentsLayout(components, title, container) {
    var isMobile = isMobilePhone();
    for (var i=0; i<components.length; i++) {
      var element = components[i].find(container);
      if (components[i].layout) {
        // call layout (don't call other components if it returns false)
        var result = components[i].layout(title, container, element, _options.fillPage);
        if (result === false)
          return;
      }
    }
  }

  // get a reference to the h3, discover it's inner html, and remove it
  function extractTitle(container) {
    var h3 = container.children('h3').first();
    var title = '';
    if (!container.hasClass('no-title'))
      title = h3.html();
    h3.remove();
    return title;
  }

  // extract chart notes
  function extractChartNotes(chartContent, chartNotes) {
    // look for a terminating blockquote or image caption
    var blockquote = chartContent.children('blockquote:last-child');
    var caption = chartContent.children('div.image-container')
                              .children('p.caption');
    if (blockquote.length) {
      chartNotes.html(blockquote.children('p:first-child').html());
      blockquote.remove();
      return true;
    } else if (caption.length) {
      chartNotes.html(caption.html());
      caption.remove();
      return true;
    } else {
      return false;
    }
  }

  function findShinyOutput(chartContent) {
    return chartContent.find('.shiny-text-output, .shiny-html-output');
  }

  // safely detect rendering on a mobile phone
  function isMobilePhone() {
    try
    {
      return ! window.matchMedia("only screen and (min-width: 768px)").matches;
    }
    catch(e) {
      return false;
    }
  }

  function isFillPage() {
    return _options.fillPage;
  }

  // detect portrait mode
  function isPortrait() {
    return ($(window).width() < $(window).height());
  }

  // safely detect rendering on a tablet
  function isTablet() {
    try
    {
      return window.matchMedia("only screen and (min-width: 769px) and (max-width: 992px)").matches;
    }
    catch(e) {
      return false;
    }
  }

  // test whether this is a shiny doc
  function isShinyDoc() {
    return (typeof(window.Shiny) !== "undefined" && !!window.Shiny.outputBindings);
  }

  // set flex using vendor specific prefixes
  function setFlex(el, flex) {
    el.css('-webkit-box-flex', flex)
      .css('-webkit-flex', flex)
      .css('-ms-flex', flex)
      .css('flex', flex);
  }

  // support bookmarking of pages
  function handleLocationHash() {

    // restore tab/page from bookmark
    var hash = window.location.hash;
    if (hash.length > 0)
      $('ul.nav a[href="' + hash + '"]').tab('show');
    FlexDashboardUtils.manageActiveNavbarMenu();

    // navigate to a tab when the history changes
    window.addEventListener("popstate", function(e) {
      var hash = window.location.hash;
      var activeTab = $('ul.nav a[href="' + hash + '"]');
      if (activeTab.length) {
        activeTab.tab('show');
      } else {
        $('ul.nav a:first').tab('show');
      }
      FlexDashboardUtils.manageActiveNavbarMenu();
    });

    // add a hash to the URL when the user clicks on a tab/page
    $('.navbar-nav a[data-toggle="tab"]').on('click', function(e) {
      var baseUrl = FlexDashboardUtils.urlWithoutHash(window.location.href);
      var hash = FlexDashboardUtils.urlHash($(this).attr('href'));
      var href = baseUrl + hash;
      FlexDashboardUtils.setLocation(href);
    });

    // handle clicks of other links that should activate pages
    var navPages = $('ul.navbar-nav li a[data-toggle=tab]');
    navPages.each(function() {
      var href =  $(this).attr('href');
      var links = $('a[href="' + href + '"][data-toggle!=tab]');
      links.each(function() {
        $(this).on('click', function(e) {
          window.FlexDashboardUtils.showPage(href);
        });
      });
    });
  }

  // tweak Prism highlighting
  function initPrismHighlighting() {

    if (window.Prism) {
      Prism.languages.insertBefore('r', 'comment', {
        'heading': [
          {
            // title 1
        	  // =======

        	  // title 2
        	  // -------
        	  pattern: /\w+.*(?:\r?\n|\r)(?:====+|----+)/,
            alias: 'operator'
          },
          {
            // ### title 3
            pattern: /(^\s*)###[^#].+/m,
            lookbehind: true,
            alias: 'operator'
          }
        ]
      });

      // prism highlight
      Prism.highlightAll();
    }
  }


  // get theme color
  var themeColors = {
    bootstrap: {
      primary: "rgba(51, 122, 183, 0.4)",
      info: "rgb(217, 237, 247)",
      success: "rgb(223, 240, 216)",
      warning: "rgb(252, 248, 227)",
      danger: "rgb(242, 222, 222)"
    },
    cerulean: {
      primary: "rgb(47, 164, 231)",
      info: "rgb(217, 237, 247)",
      success: "rgb(223, 240, 216)",
      warning: "rgb(252, 248, 227)",
      danger: "rgb(242, 222, 222)"
    },
    journal: {
      primary: "rgba(235, 104, 100, 0.70)",
      info: "rgb(217, 237, 247)",
      success: "rgb(223, 240, 216)",
      warning: "rgb(252, 248, 227)",
      danger: "rgb(242, 222, 222)"
    },
    flatly: {
      primary: "rgba(44, 62, 80, 0.70)",
      info: "rgba(52, 152, 219, 0.70)",
      success: "rgba(24, 188, 156, 0.70)",
      warning: "rgba(243, 156, 18, 0.70)",
      danger: "rgba(231, 76, 60, 0.70)"
    },
    readable: {
      primary: "rgba(69, 130, 236, 0.4)",
      info: "rgb(217, 237, 247)",
      success: "rgb(223, 240, 216)",
      warning: "rgb(252, 248, 227)",
      danger: "rgb(242, 222, 222)"
    },
    spacelab: {
      primary: "rgba(68, 110, 155, 0.25)",
      info: "rgb(217, 237, 247)",
      success: "rgb(223, 240, 216)",
      warning: "rgb(252, 248, 227)",
      danger: "rgb(242, 222, 222)"
    },
    united: {
      primary: "rgba(221, 72, 20, 0.30)",
      info: "rgb(217, 237, 247)",
      success: "rgb(223, 240, 216)",
      warning: "rgb(252, 248, 227)",
      danger: "rgb(242, 222, 222)"
    },
    cosmo: {
      primary: "rgba(39, 128, 227, 0.7)",
      info: "rgba(153, 84, 187, 0.7)",
      success: "rgba(63, 182, 24, 0.7)",
      warning: "rgba(255, 117, 24, 0.7)",
      danger: "rgba(255, 0, 57, 0.7)"
    },
    lumen: {
      primary: "rgba(21, 140, 186, 0.70)",
      info: "rgba(117, 202, 235, 0.90)",
      success: "rgba(40, 182, 44, 0.70)",
      warning: "rgba(255, 133, 27, 0.70)",
      danger: "rgba(255, 65, 54, 0.70)"
    },
    paper: {
      primary: "rgba(33, 150, 243, 0.35)",
      info: "rgb(225, 190, 231)",
      success: "rgb(223, 240, 216)",
      warning: "rgb(255, 224, 178)",
      danger: "rgb(249, 189, 187)"
    },
    sandstone: {
      primary: "rgba(50, 93, 136, 0.3)",
      info: "rgb(217, 237, 247)",
      success: "rgb(223, 240, 216)",
      warning: "rgb(252, 248, 227)",
      danger: "rgb(242, 222, 222)"
    },
    simplex: {
      primary: "rgba(217, 35, 15, 0.25)",
      info: "rgb(217, 237, 247)",
      success: "rgb(223, 240, 216)",
      warning: "rgb(252, 248, 227)",
      danger: "rgb(242, 222, 222)"
    },
    yeti: {
      primary: "rgba(0, 140, 186, 0.298039)",
      info: "rgb(217, 237, 247)",
      success: "rgb(223, 240, 216)",
      warning: "rgb(252, 248, 227)",
      danger: "rgb(242, 222, 222)"
    }
  }
  function themeColor(color) {
    return themeColors[_options.theme][color];
  }

  FlexDashboard.prototype = {
    constructor: FlexDashboard,
    init: init,
    isMobilePhone: isMobilePhone,
    isFillPage: isFillPage,
    themeColor: themeColor
  };

  return FlexDashboard;

})();

// utils
window.FlexDashboardUtils = {
  resizableImage: function(img) {
    var src = img.attr('src');
    var url = 'url("' + src + '")';
    img.parent().css('background', url)
                .css('background-size', 'contain')
                .css('background-repeat', 'no-repeat')
                .css('background-position', 'center')
                .addClass('image-container');
  },
  setLocation: function(href) {
    if (history && history.pushState) {
      history.pushState(null, null, href);
    } else {
      window.location.replace(href);
    }
    setTimeout(function() {
        window.scrollTo(0, 0);
    }, 10);
    this.manageActiveNavbarMenu();
  },
  showPage: function(href) {
    $('ul.navbar-nav li a[href="' + href + '"]').tab('show');
    var baseUrl = this.urlWithoutHash(window.location.href);
    var loc = baseUrl + href;
    this.setLocation(loc);
  },
  showLinkedValue: function(href) {
    // check for a page link
    if ($('ul.navbar-nav li a[data-toggle=tab][href="' + href + '"]').length > 0)
      this.showPage(href);
    else
      window.open(href);
  },
  urlWithoutHash: function(url) {
    var hashLoc = url.indexOf('#');
    if (hashLoc != -1)
      return url.substring(0, hashLoc);
    else
      return url;
  },
  urlHash: function(url) {
    var hashLoc = url.indexOf('#');
    if (hashLoc != -1)
      return url.substring(hashLoc);
    else
      return "";
  },
  manageActiveNavbarMenu: function () {
    // remove active from anyone currently active
    $('.navbar ul.nav').find('li').removeClass('active');
    // find the active tab
    var activeTab = $('.dashboard-page-wrapper.tab-pane.active');
    if (activeTab.length > 0) {
      var tabId = activeTab.attr('id');
      if (tabId)
        $(".navbar ul.nav a[href='#" + tabId + "']").parents('li').addClass('active');
    }
  }
};

window.FlexDashboard = new FlexDashboard();

// empty content
window.FlexDashboardComponents.push({
  find: function(container) {
    if (container.find('p').length == 0)
      return container;
    else
      return $();
  }
})

// plot image
window.FlexDashboardComponents.push({

  find: function(container) {
    return container.children('p')
                    .children('img:only-child');
  },

  layout: function(title, container, element, fillPage) {
    FlexDashboardUtils.resizableImage(element);
  }
});

// plot image (figure style)
window.FlexDashboardComponents.push({

  find: function(container) {
    return container.children('div.figure').children('img');
  },

  layout: function(title, container, element, fillPage) {
    FlexDashboardUtils.resizableImage(element);
  }
});

// htmlwidget
window.FlexDashboardComponents.push({

  init: function(dashboardContainer) {
    // trigger "shown" after initial layout to force static htmlwidgets
    // in runtime: shiny to be resized after the dom has been transformed
    dashboardContainer.on('flexdashboard:layoutcomplete', function(event) {
      setTimeout(function() {
        dashboardContainer.trigger('shown');
      }, 200);
    });
  },

  find: function(container) {
    return container.children('div[id^="htmlwidget-"],div.html-widget');
  }
});

// gauge
window.FlexDashboardComponents.push({

  find: function(container) {
    return container.children('div.html-widget.gauge');
  },

  flex: function(fillPage) {
    return false;
  },

  layout: function(title, container, element, fillPage) {


  }

});

// shiny output
window.FlexDashboardComponents.push({
  find: function(container) {
    return container.children('div[class^="shiny-"]');
  }
});

// datatables
window.FlexDashboardComponents.push({
  find: function(container) {
    return container.find('.datatables');
  },
  flex: function(fillPage) {
    return fillPage;
  }
});

// bootstrap table
window.FlexDashboardComponents.push({

  find: function(container) {
    var bsTable = container.find('table.table');
    if (bsTable.length !== 0)
      return bsTable;
    else
      return container.find('tr.header').parent('thead').parent('table');
  },

  flex: function(fillPage) {
    return fillPage;
  },

  layout: function(title, container, element, fillPage) {

    // alias variables
    var bsTable = element;

    // fixup xtable generated tables with a proper thead
    var headerRow = bsTable.find('tbody > tr:first-child > th').parent();
    if (headerRow.length > 0) {
      var thead = $('<thead></thead>');
      bsTable.prepend(thead);
      headerRow.detach().appendTo(thead);
    }

    // improve appearance
    container.addClass('bootstrap-table');

    // for fill page provide scrolling w/ sticky headers
    if (fillPage) {
      // force scrollbar on overflow
      container.addClass('flowing-content-shim');

      // stable table headers when scrolling
      bsTable.stickyTableHeaders({
        scrollableArea: container
      });
    }
  }
});

// embedded shiny app
window.FlexDashboardComponents.push({

  find: function(container) {
    return container.find('iframe.shiny-frame');
  },

  flex: function(fillPage) {
    return fillPage;
  },

  layout: function(title, container, element, fillPage) {
    if (fillPage) {
      element.attr('height', '100%');
    } else {
      // provide default height if necessary
      var height = element.get(0).style.height;
      if (!height)
        height = element.attr('height');
      if (!height)
        element.attr('height', 500);
    }
  }
});

// shiny fillRow or fillCol
window.FlexDashboardComponents.push({

  find: function(container) {
    return container.find('.flexfill-container');
  },

  flex: function(fillPage) {
    return fillPage;
  },

  layout: function(title, container, element, fillPage) {
    if (fillPage)
      element.css('height', '100%');
    else {
      // provide default height if necessary
      var height = element.get(0).style.height;
      if (height === "100%" || height === "auto" || height === "initial" ||
          height === "inherit" || !height) {
        element.css('height', 500);
      }
    }
  }
});

// valueBox
window.FlexDashboardComponents.push({

  type: "custom",

  find: function(container) {
    if (container.find('span.value-output, .shiny-valuebox-output').length)
      return container;
    else
      return $();
  },

  flex: function(fillPage) {
    return false;
  },

  layout: function(title, container, element, fillPage) {

    // alias variables
    var chartTitle = title;
    var valueBox = element;

    // add value-box class to container
    container.addClass('value-box');

    // value paragraph
    var value = $('<p class="value"></p>');

    // if we have shiny-text-output then just move it in
    var valueOutputSpan = [];
    var shinyOutput = valueBox.find('.shiny-valuebox-output').detach();
    if (shinyOutput.length) {
      valueBox.children().remove();
      shinyOutput.html("&mdash;");
      value.append(shinyOutput);
    } else {
      // extract the value (remove leading vector index)
      var chartValue = valueBox.text().trim();
      chartValue = chartValue.replace("[1] ", "");
      valueOutputSpan = valueBox.find('span.value-output').detach();
      valueBox.children().remove();
      value.text(chartValue);
    }

    // caption
    var caption = $('<p class="caption"></p>');
    caption.html(chartTitle);

    // build inner div for value box and add it
    var inner = $('<div class="inner"></div>');
    inner.append(value);
    inner.append(caption);
    valueBox.append(inner);

    // add icon if specified
    var icon = $('<div class="icon"><i></i></div>');
    valueBox.append(icon);
    function setIcon(chartIcon) {
      var iconLib = "";
      var components = chartIcon.split("-");
      if (components.length > 1)
        iconLib = components[0];
      icon.children('i').attr('class', iconLib + ' ' + chartIcon);
    }
    var chartIcon = valueBox.attr('data-icon');
    if (chartIcon)
      setIcon(chartIcon);

    // set color based on data-background if necessary
    var dataBackground = valueBox.attr('data-background');
    if (dataBackground)
      valueBox.css('background-color', bgColor);
    else {
      // default to bg-primary if no other background is specified
      if (!valueBox.hasClass('bg-primary') &&
          !valueBox.hasClass('bg-info') &&
          !valueBox.hasClass('bg-warning') &&
          !valueBox.hasClass('bg-success') &&
          !valueBox.hasClass('bg-danger')) {
        valueBox.addClass('bg-primary');
      }
    }

    // handle data attributes in valueOutputSpan
    function handleValueOutput(valueOutput) {

      // caption
      var dataCaption = valueOutput.attr('data-caption');
      if (dataCaption)
        caption.html(dataCaption);

      // icon
      var dataIcon = valueOutput.attr('data-icon');
      if (dataIcon)
        setIcon(dataIcon);

      // color
      var dataColor = valueOutput.attr('data-color');
      if (dataColor) {
        if (dataColor.indexOf('bg-') === 0) {
          valueBox.css('background-color', '');
          if (!valueBox.hasClass(dataColor)) {
             valueBox.removeClass('bg-primary bg-info bg-warning bg-danger bg-success');
             valueBox.addClass(dataColor);
          }
        } else {
          valueBox.removeClass('bg-primary bg-info bg-warning bg-danger bg-success');
          valueBox.css('background-color', dataColor);
        }
      }

      // url
      var dataHref = valueOutput.attr('data-href');
      if (dataHref) {
        valueBox.addClass('linked-value');
        valueBox.off('click.value-box');
        valueBox.on('click.value-box', function(e) {
          window.FlexDashboardUtils.showLinkedValue(dataHref);
        });
      }
    }

    // check for a valueOutputSpan
    if (valueOutputSpan.length > 0) {
      handleValueOutput(valueOutputSpan);
    }

    // if we have a shinyOutput then bind a listener to handle
    // new valueOutputSpan values
    shinyOutput.on('shiny:value',
      function(event) {
        var element = $(event.target);
        setTimeout(function() {
          var valueOutputSpan = element.find('span.value-output');
          if (valueOutputSpan.length > 0)
            handleValueOutput(valueOutputSpan);
        }, 10);
      }
    );
  }
});


</script>

<div id="dashboard-container">

<div id="india" class="section level1">
<h1>INDIA</h1>
<div id="row" class="section level2">
<h2>Row</h2>
<div id="confirmed" class="section level3 value-box">
<h3>confirmed</h3>
<div class="knitr-options" data-fig-width="576" data-fig-height="460">

</div>
<span class="value-output" data-caption="Total Confirmed Cases" data-icon="fas fa-user-md" data-color="purple">34,863 </span>
</div>
<div id="active" class="section level3 value-box">
<h3>active</h3>
<div class="knitr-options" data-fig-width="576" data-fig-height="460">

</div>
<span class="value-output" data-caption="Active Cases" data-icon="fas fa-ambulance" data-color="#1f77b4">24,647 (70.7%)</span>
</div>
<div id="recovered" class="section level3 value-box">
<h3>recovered</h3>
<div class="knitr-options" data-fig-width="576" data-fig-height="460">

</div>
<span class="value-output" data-caption="Recovered Cases" data-icon="fas fa-heartbeat" data-color="forestgreen">9,059 (36.8%)</span>
</div>
<div id="death" class="section level3 value-box">
<h3>death</h3>
<div class="knitr-options" data-fig-width="576" data-fig-height="460">

</div>
<span class="value-output" data-caption="Death Cases" data-icon="fas fa-heart-broken" data-color="red">1,154 (3.3%)</span>
</div>
<div id="totaltested" class="section level3 value-box">
<h3>TotalTested</h3>
<div class="knitr-options" data-fig-width="576" data-fig-height="460">

</div>
<span class="value-output" data-icon="fas fa-stethoscope">830201</span>
</div>
</div>
<div id="row-1" class="section level2">
<h2>Row</h2>
<div id="cases-distribution-by-state-2020-05-01" class="section level3">
<h3>Cases Distribution by State (2020-05-01)</h3>
<div class="knitr-options" data-fig-width="576" data-fig-height="460">

</div>
<div id="htmlwidget-a18511b6f58edf749b03" style="width:576px;height:460.8px;" class="plotly html-widget"></div>
<script type="application/json" data-for="htmlwidget-a18511b6f58edf749b03">{"x":{"visdat":{"54d11deb6f7a":["function () ","plotlyVisDat"]},"cur_data":"54d11deb6f7a","attrs":{"54d11deb6f7a":{"x":["Maharashtra","Gujarat","Delhi","Madhya Pradesh","Rajasthan","Tamil Nadu","Uttar Pradesh","Andhra Pradesh","Telangana","West Bengal","Jammu and Kashmir","Karnataka","Kerala","Bihar","Punjab","Haryana","Odisha","Jharkhand","Chandigarh","Uttarakhand","Himachal Pradesh","Assam","Chhattisgarh","Andaman and Nicobar Islands","Ladakh","Meghalaya","Puducherry","Goa","Manipur","Tripura","Mizoram","Arunachal Pradesh","Nagaland","Dadra and Nagar Haveli","Daman and Diu","Lakshadweep","Sikkim"],"y":[10498,4395,3515,2625,2582,2323,2211,1403,1038,758,614,565,498,425,480,339,142,110,74,57,40,43,40,33,22,12,8,7,2,2,1,1,0,0,0,0,0],"marker":{"color":"#1f77b4"},"name":"Confirmed","alpha_stroke":1,"sizes":[10,100],"spans":[1,20],"type":"bar"},"54d11deb6f7a.1":{"x":["Maharashtra","Gujarat","Delhi","Madhya Pradesh","Rajasthan","Tamil Nadu","Uttar Pradesh","Andhra Pradesh","Telangana","West Bengal","Jammu and Kashmir","Karnataka","Kerala","Bihar","Punjab","Haryana","Odisha","Jharkhand","Chandigarh","Uttarakhand","Himachal Pradesh","Assam","Chhattisgarh","Andaman and Nicobar Islands","Ladakh","Meghalaya","Puducherry","Goa","Manipur","Tripura","Mizoram","Arunachal Pradesh","Nagaland","Dadra and Nagar Haveli","Daman and Diu","Lakshadweep","Sikkim"],"y":[1773,613,1094,482,893,1258,551,321,442,124,216,229,383,84,104,235,41,19,18,36,28,29,36,16,17,0,5,7,2,2,0,1,0,0,0,0,0],"marker":{"color":"forestgreen"},"name":"Recovered","alpha_stroke":1,"sizes":[10,100],"spans":[1,20],"type":"bar","inherit":true},"54d11deb6f7a.2":{"x":["Maharashtra","Gujarat","Delhi","Madhya Pradesh","Rajasthan","Tamil Nadu","Uttar Pradesh","Andhra Pradesh","Telangana","West Bengal","Jammu and Kashmir","Karnataka","Kerala","Bihar","Punjab","Haryana","Odisha","Jharkhand","Chandigarh","Uttarakhand","Himachal Pradesh","Assam","Chhattisgarh","Andaman and Nicobar Islands","Ladakh","Meghalaya","Puducherry","Goa","Manipur","Tripura","Mizoram","Arunachal Pradesh","Nagaland","Dadra and Nagar Haveli","Daman and Diu","Lakshadweep","Sikkim"],"y":[459,214,59,137,58,27,40,31,28,33,8,22,4,2,20,4,1,3,0,0,2,1,0,0,0,1,0,0,0,0,0,0,0,0,0,0,0],"marker":{"color":"red"},"name":"Death","alpha_stroke":1,"sizes":[10,100],"spans":[1,20],"type":"bar","inherit":true}},"layout":{"margin":{"b":60,"l":60,"t":40,"r":10,"pad":2},"barmode":"stack","yaxis":{"domain":[0,1],"automargin":true,"title":"Total Cases (log scaled)","type":"log","fixedrange":true},"xaxis":{"domain":[0,1],"automargin":true,"title":"","categoryorder":"array","categoryarray":["Maharashtra","Gujarat","Delhi","Madhya Pradesh","Rajasthan","Tamil Nadu","Uttar Pradesh","Andhra Pradesh","Telangana","West Bengal","Jammu and Kashmir","Karnataka","Kerala","Bihar","Punjab","Haryana","Odisha","Jharkhand","Chandigarh","Uttarakhand","Himachal Pradesh","Assam","Chhattisgarh","Andaman and Nicobar Islands","Ladakh","Meghalaya","Puducherry","Goa","Manipur","Tripura","Mizoram","Arunachal Pradesh","Nagaland","Dadra and Nagar Haveli","Daman and Diu","Lakshadweep","Sikkim"],"fixedrange":true,"type":"category"},"hovermode":"compare","showlegend":true},"source":"A","config":{"showSendToCloud":false,"displayModeBar":false},"data":[{"x":["Maharashtra","Gujarat","Delhi","Madhya Pradesh","Rajasthan","Tamil Nadu","Uttar Pradesh","Andhra Pradesh","Telangana","West Bengal","Jammu and Kashmir","Karnataka","Kerala","Bihar","Punjab","Haryana","Odisha","Jharkhand","Chandigarh","Uttarakhand","Himachal Pradesh","Assam","Chhattisgarh","Andaman and Nicobar Islands","Ladakh","Meghalaya","Puducherry","Goa","Manipur","Tripura","Mizoram","Arunachal Pradesh","Nagaland","Dadra and Nagar Haveli","Daman and Diu","Lakshadweep","Sikkim"],"y":[10498,4395,3515,2625,2582,2323,2211,1403,1038,758,614,565,498,425,480,339,142,110,74,57,40,43,40,33,22,12,8,7,2,2,1,1,0,0,0,0,0],"marker":{"color":"#1f77b4","line":{"color":"rgba(31,119,180,1)"}},"name":"Confirmed","type":"bar","error_y":{"color":"rgba(31,119,180,1)"},"error_x":{"color":"rgba(31,119,180,1)"},"xaxis":"x","yaxis":"y","frame":null},{"x":["Maharashtra","Gujarat","Delhi","Madhya Pradesh","Rajasthan","Tamil Nadu","Uttar Pradesh","Andhra Pradesh","Telangana","West Bengal","Jammu and Kashmir","Karnataka","Kerala","Bihar","Punjab","Haryana","Odisha","Jharkhand","Chandigarh","Uttarakhand","Himachal Pradesh","Assam","Chhattisgarh","Andaman and Nicobar Islands","Ladakh","Meghalaya","Puducherry","Goa","Manipur","Tripura","Mizoram","Arunachal Pradesh","Nagaland","Dadra and Nagar Haveli","Daman and Diu","Lakshadweep","Sikkim"],"y":[1773,613,1094,482,893,1258,551,321,442,124,216,229,383,84,104,235,41,19,18,36,28,29,36,16,17,0,5,7,2,2,0,1,0,0,0,0,0],"marker":{"color":"forestgreen","line":{"color":"rgba(255,127,14,1)"}},"name":"Recovered","type":"bar","error_y":{"color":"rgba(255,127,14,1)"},"error_x":{"color":"rgba(255,127,14,1)"},"xaxis":"x","yaxis":"y","frame":null},{"x":["Maharashtra","Gujarat","Delhi","Madhya Pradesh","Rajasthan","Tamil Nadu","Uttar Pradesh","Andhra Pradesh","Telangana","West Bengal","Jammu and Kashmir","Karnataka","Kerala","Bihar","Punjab","Haryana","Odisha","Jharkhand","Chandigarh","Uttarakhand","Himachal Pradesh","Assam","Chhattisgarh","Andaman and Nicobar Islands","Ladakh","Meghalaya","Puducherry","Goa","Manipur","Tripura","Mizoram","Arunachal Pradesh","Nagaland","Dadra and Nagar Haveli","Daman and Diu","Lakshadweep","Sikkim"],"y":[459,214,59,137,58,27,40,31,28,33,8,22,4,2,20,4,1,3,0,0,2,1,0,0,0,1,0,0,0,0,0,0,0,0,0,0,0],"marker":{"color":"red","line":{"color":"rgba(44,160,44,1)"}},"name":"Death","type":"bar","error_y":{"color":"rgba(44,160,44,1)"},"error_x":{"color":"rgba(44,160,44,1)"},"xaxis":"x","yaxis":"y","frame":null}],"highlight":{"on":"plotly_click","persistent":false,"dynamic":false,"selectize":false,"opacityDim":0.2,"selected":{"opacity":1},"debounce":0},"shinyEvents":["plotly_hover","plotly_click","plotly_selected","plotly_relayout","plotly_brushed","plotly_brushing","plotly_clickannotation","plotly_doubleclick","plotly_deselect","plotly_afterplot","plotly_sunburstclick"],"base_url":"https://plot.ly"},"evals":[],"jsHooks":[]}</script>
</div>
</div>
<div id="row-2" class="section level2" data-width="400">
<h2>Row</h2>
<div id="daily-cumulative-cases-by-type" class="section level3">
<h3>Daily Cumulative Cases by Type</h3>
<div class="knitr-options" data-fig-width="576" data-fig-height="460">

</div>
<div id="htmlwidget-0a12143004467efa8d89" style="width:576px;height:460.8px;" class="plotly html-widget"></div>
<script type="application/json" data-for="htmlwidget-0a12143004467efa8d89">{"x":{"visdat":{"54d1601c337b":["function () ","plotlyVisDat"]},"cur_data":"54d1601c337b","attrs":{"54d1601c337b":{"x":{},"y":{},"fillcolor":"#1f77b4","mode":"none","stackgroup":"one","name":"Active","alpha_stroke":1,"sizes":[10,100],"spans":[1,20],"type":"scatter"},"54d1601c337b.1":{"x":{},"y":{},"fillcolor":"forestgreen","mode":"none","stackgroup":"one","name":"Recovered","alpha_stroke":1,"sizes":[10,100],"spans":[1,20],"type":"scatter","inherit":true},"54d1601c337b.2":{"x":{},"y":{},"fillcolor":"red","mode":"none","stackgroup":"one","name":"Death","alpha_stroke":1,"sizes":[10,100],"spans":[1,20],"type":"scatter","inherit":true}},"layout":{"margin":{"b":40,"l":60,"t":25,"r":10},"title":"","yaxis":{"domain":[0,1],"automargin":true,"title":"Cumulative Number of Cases","fixedrange":true},"xaxis":{"domain":[0,1],"automargin":true,"title":"Date","fixedrange":true},"legend":{"x":0.1,"y":0.9},"hovermode":"compare","showlegend":true},"source":"A","config":{"showSendToCloud":false,"displayModeBar":false},"data":[{"x":["2020-01-30","2020-01-31","2020-02-01","2020-02-02","2020-02-03","2020-02-04","2020-02-05","2020-02-06","2020-02-07","2020-02-08","2020-02-09","2020-02-10","2020-02-11","2020-02-12","2020-02-13","2020-02-14","2020-02-15","2020-02-16","2020-02-17","2020-02-18","2020-02-19","2020-02-20","2020-02-21","2020-02-22","2020-02-23","2020-02-24","2020-02-25","2020-02-26","2020-02-27","2020-02-28","2020-02-29","2020-03-01","2020-03-02","2020-03-03","2020-03-04","2020-03-05","2020-03-06","2020-03-07","2020-03-08","2020-03-09","2020-03-10","2020-03-11","2020-03-12","2020-03-13","2020-03-14","2020-03-15","2020-03-16","2020-03-17","2020-03-18","2020-03-19","2020-03-20","2020-03-21","2020-03-22","2020-03-23","2020-03-24","2020-03-25","2020-03-26","2020-03-27","2020-03-28","2020-03-29","2020-03-30","2020-03-31","2020-04-01","2020-04-02","2020-04-03","2020-04-04","2020-04-05","2020-04-06","2020-04-07","2020-04-08","2020-04-09","2020-04-10","2020-04-11","2020-04-12","2020-04-13","2020-04-14","2020-04-15","2020-04-16","2020-04-17","2020-04-18","2020-04-19","2020-04-20","2020-04-21"],"y":[1,1,1,2,3,3,3,3,3,3,3,3,3,3,3,3,3,3,3,3,3,3,3,3,3,3,3,3,3,3,3,3,5,6,28,30,31,34,39,48,63,71,81,91,102,112,126,146,171,198,256,334,403,497,571,657,730,883,1019,1139,1326,1635,2059,2545,3105,3684,4293,4777,5350,5915,6728,7599,8453,9211,10454,11485,12371,13432,14354,15725,17305,17305,17305],"fillcolor":"#1f77b4","mode":"none","stackgroup":"one","name":"Active","type":"scatter","marker":{"color":"rgba(31,119,180,1)","line":{"color":"rgba(31,119,180,1)"}},"error_y":{"color":"rgba(31,119,180,1)"},"error_x":{"color":"rgba(31,119,180,1)"},"line":{"color":"rgba(31,119,180,1)"},"xaxis":"x","yaxis":"y","frame":null},{"x":["2020-01-30","2020-01-31","2020-02-01","2020-02-02","2020-02-03","2020-02-04","2020-02-05","2020-02-06","2020-02-07","2020-02-08","2020-02-09","2020-02-10","2020-02-11","2020-02-12","2020-02-13","2020-02-14","2020-02-15","2020-02-16","2020-02-17","2020-02-18","2020-02-19","2020-02-20","2020-02-21","2020-02-22","2020-02-23","2020-02-24","2020-02-25","2020-02-26","2020-02-27","2020-02-28","2020-02-29","2020-03-01","2020-03-02","2020-03-03","2020-03-04","2020-03-05","2020-03-06","2020-03-07","2020-03-08","2020-03-09","2020-03-10","2020-03-11","2020-03-12","2020-03-13","2020-03-14","2020-03-15","2020-03-16","2020-03-17","2020-03-18","2020-03-19","2020-03-20","2020-03-21","2020-03-22","2020-03-23","2020-03-24","2020-03-25","2020-03-26","2020-03-27","2020-03-28","2020-03-29","2020-03-30","2020-03-31","2020-04-01","2020-04-02","2020-04-03","2020-04-04","2020-04-05","2020-04-06","2020-04-07","2020-04-08","2020-04-09","2020-04-10","2020-04-11","2020-04-12","2020-04-13","2020-04-14","2020-04-15","2020-04-16","2020-04-17","2020-04-18","2020-04-19","2020-04-20","2020-04-21"],"y":[0,0,0,0,0,0,0,0,0,0,0,0,0,0,1,1,1,2,2,2,2,3,3,3,3,3,3,3,3,3,3,3,3,3,3,3,3,3,3,3,4,4,4,10,10,13,14,15,15,20,23,23,23,25,40,43,50,75,85,102,137,150,169,191,230,286,329,394,469,565,635,786,972,1086,1198,1365,1509,1767,2040,2466,2854,2854,2854],"fillcolor":"forestgreen","mode":"none","stackgroup":"one","name":"Recovered","type":"scatter","marker":{"color":"rgba(255,127,14,1)","line":{"color":"rgba(255,127,14,1)"}},"error_y":{"color":"rgba(255,127,14,1)"},"error_x":{"color":"rgba(255,127,14,1)"},"line":{"color":"rgba(255,127,14,1)"},"xaxis":"x","yaxis":"y","frame":null},{"x":["2020-01-30","2020-01-31","2020-02-01","2020-02-02","2020-02-03","2020-02-04","2020-02-05","2020-02-06","2020-02-07","2020-02-08","2020-02-09","2020-02-10","2020-02-11","2020-02-12","2020-02-13","2020-02-14","2020-02-15","2020-02-16","2020-02-17","2020-02-18","2020-02-19","2020-02-20","2020-02-21","2020-02-22","2020-02-23","2020-02-24","2020-02-25","2020-02-26","2020-02-27","2020-02-28","2020-02-29","2020-03-01","2020-03-02","2020-03-03","2020-03-04","2020-03-05","2020-03-06","2020-03-07","2020-03-08","2020-03-09","2020-03-10","2020-03-11","2020-03-12","2020-03-13","2020-03-14","2020-03-15","2020-03-16","2020-03-17","2020-03-18","2020-03-19","2020-03-20","2020-03-21","2020-03-22","2020-03-23","2020-03-24","2020-03-25","2020-03-26","2020-03-27","2020-03-28","2020-03-29","2020-03-30","2020-03-31","2020-04-01","2020-04-02","2020-04-03","2020-04-04","2020-04-05","2020-04-06","2020-04-07","2020-04-08","2020-04-09","2020-04-10","2020-04-11","2020-04-12","2020-04-13","2020-04-14","2020-04-15","2020-04-16","2020-04-17","2020-04-18","2020-04-19","2020-04-20","2020-04-21"],"y":[0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,1,1,2,2,2,3,3,4,4,4,7,9,10,11,16,19,24,27,41,47,53,69,83,96,118,134,161,181,227,249,290,332,359,396,423,449,487,522,560,560,560],"fillcolor":"red","mode":"none","stackgroup":"one","name":"Death","type":"scatter","marker":{"color":"rgba(44,160,44,1)","line":{"color":"rgba(44,160,44,1)"}},"error_y":{"color":"rgba(44,160,44,1)"},"error_x":{"color":"rgba(44,160,44,1)"},"line":{"color":"rgba(44,160,44,1)"},"xaxis":"x","yaxis":"y","frame":null}],"highlight":{"on":"plotly_click","persistent":false,"dynamic":false,"selectize":false,"opacityDim":0.2,"selected":{"opacity":1},"debounce":0},"shinyEvents":["plotly_hover","plotly_click","plotly_selected","plotly_relayout","plotly_brushed","plotly_brushing","plotly_clickannotation","plotly_doubleclick","plotly_deselect","plotly_afterplot","plotly_sunburstclick"],"base_url":"https://plot.ly"},"evals":[],"jsHooks":[]}</script>
</div>
<div id="recovery-and-death-rates-by-state" class="section level3">
<h3>Recovery and Death Rates by State</h3>
<div class="knitr-options" data-fig-width="576" data-fig-height="460">

</div>
<div id="htmlwidget-6eb645e3757e531f0552" style="width:100%;height:auto;" class="datatables html-widget"></div>
<script type="application/json" data-for="htmlwidget-6eb645e3757e531f0552">{"x":{"filter":"none","fillContainer":true,"data":[["1","2","3","4","5","6","7","8","9","10","11","12","13","14","15","16","17","18","19","20","21","22","23","24","25","26","27","28","29","30","31","32","33","34","35","36","37"],["Maharashtra","Gujarat","Delhi","Madhya Pradesh","Rajasthan","Tamil Nadu","Uttar Pradesh","Andhra Pradesh","Telangana","West Bengal","Jammu and Kashmir","Karnataka","Kerala","Bihar","Punjab","Haryana","Odisha","Jharkhand","Chandigarh","Uttarakhand","Himachal Pradesh","Assam","Chhattisgarh","Andaman and Nicobar Islands","Ladakh","Meghalaya","Puducherry","Goa","Manipur","Tripura","Mizoram","Arunachal Pradesh","Nagaland","Dadra and Nagar Haveli","Daman and Diu","Lakshadweep","Sikkim"],[10498,4395,3515,2625,2582,2323,2211,1403,1038,758,614,565,498,425,480,339,142,110,74,57,40,43,40,33,22,12,8,7,2,2,1,1,0,0,0,0,0],[1773,613,1094,482,893,1258,551,321,442,124,216,229,383,84,104,235,41,19,18,36,28,29,36,16,17,0,5,7,2,2,0,1,0,0,0,0,0],[459,214,59,137,58,27,40,31,28,33,8,22,4,2,20,4,1,3,0,0,2,1,0,0,0,1,0,0,0,0,0,0,0,0,0,0,0],[8266,3568,2362,2006,1631,1038,1620,1051,568,601,390,314,111,339,356,100,100,88,56,21,7,13,4,17,5,11,3,0,0,0,1,0,0,0,0,0,0],[0.168889312249952,0.139476678043231,0.311237553342816,0.183619047619048,0.345855925639039,0.541541110632802,0.249208502939846,0.228795438346401,0.425818882466281,0.163588390501319,0.351791530944625,0.405309734513274,0.769076305220884,0.197647058823529,0.216666666666667,0.693215339233038,0.288732394366197,0.172727272727273,0.243243243243243,0.631578947368421,0.7,0.674418604651163,0.9,0.484848484848485,0.772727272727273,0,0.625,1,1,1,0,1,null,null,null,null,null],[0.0437226138312059,0.0486916951080774,0.0167852062588905,0.0521904761904762,0.0224632068164214,0.0116229014205768,0.0180913613749435,0.0220955096222381,0.0269749518304432,0.0435356200527705,0.0130293159609121,0.0389380530973451,0.00803212851405622,0.00470588235294118,0.0416666666666667,0.0117994100294985,0.00704225352112676,0.0272727272727273,0,0,0.05,0.0232558139534884,0,0,0,0.0833333333333333,0,0,0,0,0,0,null,null,null,null,null]],"container":"<table class=\"display fill-container\">\n  <thead>\n    <tr>\n      <th> <\/th>\n      <th>State<\/th>\n      <th>Confirmed<\/th>\n      <th>Recovered<\/th>\n      <th>Deaths<\/th>\n      <th>Active<\/th>\n      <th>recover_rate<\/th>\n      <th>death_rate<\/th>\n    <\/tr>\n  <\/thead>\n<\/table>","options":{"pageLength":37,"dom":"tip","columnDefs":[{"targets":7,"render":"function(data, type, row, meta) { return DTWidget.formatPercentage(data, 2, 3, \",\", \".\"); }"},{"targets":6,"render":"function(data, type, row, meta) { return DTWidget.formatPercentage(data, 2, 3, \",\", \".\"); }"},{"className":"dt-right","targets":[2,3,4,5,6,7]},{"orderable":false,"targets":0}],"order":[],"autoWidth":false,"orderClasses":false,"lengthMenu":[10,25,37,50,100]}},"evals":["options.columnDefs.0.render","options.columnDefs.1.render"],"jsHooks":[]}</script>
</div>
</div>
</div>
<div id="todaycase" class="section level1">
<h1>TodayCase</h1>
<div id="row-3" class="section level2">
<h2>Row</h2>
<div id="todaycase-2020-05-01" class="section level3">
<h3>TodayCase (2020-05-01)</h3>
<div class="knitr-options" data-fig-width="576" data-fig-height="460">

</div>
<span class="value-output" data-icon="fa-pencil">1800</span>
</div>
<div id="todaydeaths2020-05-01" class="section level3">
<h3>TodayDeaths(2020-05-01)</h3>
<div class="knitr-options" data-fig-width="576" data-fig-height="460">

</div>
<span class="value-output" data-icon="fa-comments">75</span>
</div>
<div id="todayrecovered2020-05-01" class="section level3">
<h3>TodayRecovered(2020-05-01)</h3>
<div class="knitr-options" data-fig-width="576" data-fig-height="460">

</div>
<span class="value-output" data-icon="fa-trash" data-color="bg-warning">630</span>
</div>
</div>
<div id="row-4" class="section level2">
<h2>Row</h2>
<div id="todaystatewisecase2020-05-01" class="section level3">
<h3>TodayStateWiseCase(2020-05-01)</h3>
<div class="knitr-options" data-fig-width="576" data-fig-height="460">

</div>
<div id="htmlwidget-9d6b291c8ccf4af044db" style="width:576px;height:460.8px;" class="plotly html-widget"></div>
<script type="application/json" data-for="htmlwidget-9d6b291c8ccf4af044db">{"x":{"visdat":{"54d11879a4e1":["function () ","plotlyVisDat"]},"cur_data":"54d11879a4e1","attrs":{"54d11879a4e1":{"x":["Uttarakhand","Assam"],"y":[2,5],"marker":{"color":"#1f77b4"},"name":"todayComfrm","alpha_stroke":1,"sizes":[10,100],"spans":[1,20],"type":"bar"},"54d11879a4e1.1":{"x":["Uttarakhand","Assam"],"y":[8,0],"marker":{"color":"forestgreen"},"name":"todayrecover","alpha_stroke":1,"sizes":[10,100],"spans":[1,20],"type":"bar","inherit":true},"54d11879a4e1.2":{"x":["Uttarakhand","Assam"],"y":[0,0],"marker":{"color":"red"},"name":"todayDeaths","alpha_stroke":1,"sizes":[10,100],"spans":[1,20],"type":"bar","inherit":true}},"layout":{"margin":{"b":60,"l":60,"t":40,"r":10,"pad":2},"barmode":"stack","yaxis":{"domain":[0,1],"automargin":true,"title":"Total Cases (log scaled)","type":"log","fixedrange":true},"xaxis":{"domain":[0,1],"automargin":true,"title":"","categoryorder":"array","categoryarray":["Uttarakhand","Assam"],"fixedrange":true,"type":"category"},"hovermode":"compare","showlegend":true},"source":"A","config":{"showSendToCloud":false,"displayModeBar":false},"data":[{"x":["Uttarakhand","Assam"],"y":[2,5],"marker":{"color":"#1f77b4","line":{"color":"rgba(31,119,180,1)"}},"name":"todayComfrm","type":"bar","error_y":{"color":"rgba(31,119,180,1)"},"error_x":{"color":"rgba(31,119,180,1)"},"xaxis":"x","yaxis":"y","frame":null},{"x":["Uttarakhand","Assam"],"y":[8,0],"marker":{"color":"forestgreen","line":{"color":"rgba(255,127,14,1)"}},"name":"todayrecover","type":"bar","error_y":{"color":"rgba(255,127,14,1)"},"error_x":{"color":"rgba(255,127,14,1)"},"xaxis":"x","yaxis":"y","frame":null},{"x":["Uttarakhand","Assam"],"y":[0,0],"marker":{"color":"red","line":{"color":"rgba(44,160,44,1)"}},"name":"todayDeaths","type":"bar","error_y":{"color":"rgba(44,160,44,1)"},"error_x":{"color":"rgba(44,160,44,1)"},"xaxis":"x","yaxis":"y","frame":null}],"highlight":{"on":"plotly_click","persistent":false,"dynamic":false,"selectize":false,"opacityDim":0.2,"selected":{"opacity":1},"debounce":0},"shinyEvents":["plotly_hover","plotly_click","plotly_selected","plotly_relayout","plotly_brushed","plotly_brushing","plotly_clickannotation","plotly_doubleclick","plotly_deselect","plotly_afterplot","plotly_sunburstclick"],"base_url":"https://plot.ly"},"evals":[],"jsHooks":[]}</script>
</div>
</div>
</div>
<div id="tested" class="section level1">
<h1>Tested</h1>
<div id="statewisetested-2020-05-01" class="section level3">
<h3>STATEWISETESTED ##(2020-05-01)</h3>
<div class="knitr-options" data-fig-width="576" data-fig-height="460">

</div>
<div id="htmlwidget-ecb64ba30fe7a4d8dd4c" style="width:100%;height:500px;" class="highchart html-widget"></div>
<script type="application/json" data-for="htmlwidget-ecb64ba30fe7a4d8dd4c">{"x":{"hc_opts":{"title":{"text":null},"yAxis":{"title":{"text":null}},"credits":{"enabled":false},"exporting":{"enabled":false},"plotOptions":{"series":{"label":{"enabled":false},"turboThreshold":0},"treemap":{"layoutAlgorithm":"squarified"}},"xAxis":{"categories":["Maharashtra","Tamil Nadu","Rajasthan","Andhra Pradesh","Uttar Pradesh","Gujarat","Karnataka","Madhya Pradesh","Odisha","Haryana","Kerala","Bihar","Punjab","Jammu and Kashmir","West Bengal","Uttarakhand","Himachal Pradesh","Ladakh","Goa","Chandigarh","Arunachal Pradesh","Nagaland"]},"series":[{"data":[135694,119748,103704,94558,78013,64007,60156,41712,31696,28202,25973,22672,21205,19746,16525,6565,6133,2245,2031,1147,694,653],"name":"TotalTested"},{"data":[9915,2323,2584,1403,2211,4395,565,2625,142,339,497,409,480,614,758,57,40,22,7,74,2,0],"name":"TotalPositive"}],"colors":["#440154","#21908C","#FDE725"],"chart":{"type":"column","options3d":{"enabled":true,"beta":15}}},"theme":{"chart":{"backgroundColor":"transparent"}},"conf_opts":{"global":{"Date":null,"VMLRadialGradientURL":"http =//code.highcharts.com/list(version)/gfx/vml-radial-gradient.png","canvasToolsURL":"http =//code.highcharts.com/list(version)/modules/canvas-tools.js","getTimezoneOffset":null,"timezoneOffset":0,"useUTC":true},"lang":{"contextButtonTitle":"Chart context menu","decimalPoint":".","downloadJPEG":"Download JPEG image","downloadPDF":"Download PDF document","downloadPNG":"Download PNG image","downloadSVG":"Download SVG vector image","drillUpText":"Back to {series.name}","invalidDate":null,"loading":"Loading...","months":["January","February","March","April","May","June","July","August","September","October","November","December"],"noData":"No data to display","numericSymbols":["k","M","G","T","P","E"],"printChart":"Print chart","resetZoom":"Reset zoom","resetZoomTitle":"Reset zoom level 1:1","shortMonths":["Jan","Feb","Mar","Apr","May","Jun","Jul","Aug","Sep","Oct","Nov","Dec"],"thousandsSep":" ","weekdays":["Sunday","Monday","Tuesday","Wednesday","Thursday","Friday","Saturday"]}},"type":"chart","fonts":[],"debug":false},"evals":[],"jsHooks":[]}</script>
</div>
</div>
<div id="data" class="section level1">
<h1>Data</h1>
<div id="row-5" class="section level2">
<h2>Row</h2>
</div>
</div>
<div id="about-me" class="section level1">
<h1>About Me</h1>
<p><strong>About Me</strong> Name-Rakesh Kumar(genisights private limited) <a href="mailto:Email-Rakesh.Kumar@aaumanalytics.com" class="email">Email-Rakesh.Kumar@aaumanalytics.com</a> Data Patient Level : Raw Data Partition 1 (Till Apr 19) National Level :Time series, State-wise stats and Test counts State Level : has district-wise info State Level : has district-wise info V2 (minor difference in structure) State Level : Daily changes</p>
<p>How this works This repo is merely a bridge to the main source of Data (Google Sheets) Volunteers collect data from trusted sources and update the sheet This repo periodically fetches relevant data from the Sheet and create/update static json/csv. We use Github Actions to fetch the data periodically and auto-commit.</p>
</div>

</div>

<script>

$(document).ready(function () {

  // add bootstrap table styles to pandoc tables
  $('tr.header').parent('thead').parent('table').addClass('table table-condensed');

  // initialize mathjax
  var script = document.createElement("script");
  script.type = "text/javascript";
  script.src  = "https://mathjax.rstudio.com/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML";
  document.getElementsByTagName("head")[0].appendChild(script);

});
</script>

<script type="text/javascript">
$(document).ready(function () {
  FlexDashboard.init({
    theme: "cosmo",
    fillPage: true,
    orientation: "rows",
    storyboard: false,
    defaultFigWidth: 576,
    defaultFigHeight: 460,
    defaultFigWidthMobile: 360,
    defaultFigHeightMobile: 460
  });
});
</script>

</body>
</html>

