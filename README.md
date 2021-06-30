<h2 align="center">
  <a href="https://smart-maas.eu/en/"><img src="https://github.com/SmartMaaS-Services/Transaction-Context-Manager/blob/main/docs/images/Header.jpeg" alt="Smart MaaS" width="500"></a>
  <br>
      SMART MOBILITY SERVICE PLATFORM
  <br>
  <a href="https://smart-maas.eu/en/"><img src="https://github.com/SmartMaaS-Services/Transaction-Context-Manager/blob/main/docs/images/Logos-Smart-MaaS.png" alt="Smart MaaS" width="250"></a>
  <br>
</h2>

<p align="center">
  <a href="mailto:info@smart-maas.eu">Contact</a> •
  <a href="https://smart-maas.eu/en/">Project Page</a>
</p>


***

<h1 align="center">
  <a>
    Data-Source Plugin for Grafana
  </a>
</h1>

***


This demo plugin illustrates how to access the Fiware COMET component in order to send data queries, receive the response data, transform it into Grafana Response Format and return it to Grafana to visualize them. It uses the Grafana time-series format to process data with only temporal meta-data and the Grafana tabular format to visualize location meta-data on a world map.
In order to use other output data formats, e.g. for non-standard Grafana panels, the data output part of ```datasource.js``` can be adapted to meet the respective needs.
