<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
<!--
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
-->


<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://cityroute.ml">
    <img src="https://agrand.ie/wp-content/uploads/2016/11/Events_animated_v1.gif" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">CityRoute Data Analytics</h3>

  <!--
  <p align="center">
    An awesome README template to jumpstart your projects!
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template">View Demo</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Report Bug</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Request Feature</a>
  </p>
  -->
</p>



<!-- TABLE OF CONTENTS --><!--
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>
-->


<!-- ABOUT THE PROJECT -->
## About The Project

This repository contains the data analytics portion of the [CityRoute Web Application](https://cityroute.ml/#/). 
The specifications of this project called for us to analyse historic Dublin Bus data and weather data in order to create dynamic travel time estimates.
Based on our analysis we were required to develop a system which when presented with any bus route, departure time, the day of the week and current weather conditions produces an accurate estimate of travel time for the complete route and sections of the route.

The main technology used for the data analysis was [Jupyter notebooks](https://jupyter.org/index.html) along with various python libraries. 


<!-- THE REPOSITORY -->
## The Repository

This section provides an overview of the repository.

* [Dublin_Bus_GTFS](Dublin_Bus_GTFS) : here you will find a notebook that was used to compare the [GTFS](https://transitfeeds.com/p/transport-for-ireland/782) bus stop data over the years from 2018 to 2021.
* [Modelling](Modelling) : contains a notebook for each modelling approach taken.
* [Preparation](Preparation) : contains the notebooks used to clean and prepare the Dublin Bus data and [Open Weather Maps](https://openweathermap.org/history) historic weather data.
* [Understanding](Understanding) : contains each team members notebooks used to gain an understanding of the Dublin Bus data.
* [data](data) : contains various json files created.
* [review_analysis](review_analysis) : contains a notebook used to analyse Google Play Store app reviews.
* [route-46a](route-46a) : contains the notebook used to test modelling approaches on the subset of data describing route 46A.

The following folders contain the trained predictive models stored in pickle files:

* [route_models](route_models)
* [stop_models](stop_models)
* [stop_models_outbound](stop_models_outbound)
* [stop_pair_models_inbound](stop_pair_models_inbound)
* [stop_pair_models_outbound](stop_pair_models_outbound)

The following are additional notebooks:

* [Routes-and-Stops.ipynb](Routes-and-Stops.ipynb) : was used to create the various json files found in [data](data).
* [Sample-Prediction.ipynb](Sample-Prediction.ipynb) : was used to make sample predictions with the Route model.


<!-- THE PROJECT -->
## The Project

Project Link: [https://github.com/CityRoute/Web-App-CityRoute](https://github.com/CityRoute/Web-App-CityRoute)
