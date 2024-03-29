<div id="top"></div>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Stargazers][stars-shield]][stars-url]


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <!-- <a href="https://github.com/github_username/repo_name">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a> -->

<h2 align="center">Saudi Used Cars ML Project</h3>

  <p align="center">
    This project is aimed to predict the price of a used car in Saudi Arabia.
    <br />
    The data set is Saudi Used Cars Dataset, and the target is the price.
    <br />
    <a href="https://github.com/AlfaisalGassim/saudi_used_cars_ml"><strong>Explore the docs »</strong></a>
    <br />
    <br />
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li><a href="#data-dictionary">Data Dictionary</a></li>
    <li><a href="#exploratory-data-analysis">Exploratory Data Analysis (EDA)</a></li>
      <ul>
        <li><a href="#issues">Issues</a></li>
      </ul>
    <li><a href="#data-cleaning">Data Cleaning</a></li>
      <ul>
        <li><a href="#datatypes">DataTypes</a></li>
        <li><a href="#quick-observations">Quick Observations</a></li>
      </ul>
    <li><a href="#machine-learning">Machine Learning</a></li>
    <li><a href="#contributors">Contributors</a></li>
    <li><a href="#references">References</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

<!-- [![Product Name Screen Shot][product-screenshot]](https://example.com) -->


The dataset contains records of used cars collected from **syarah.com**. Each row represents a used car with a link to its webpage. Other information regarding each car is the brand name, model, manufacturing year, origin, the color of the car, options, capacity of the engine, type of fuel, transmission type, the mileage that the car covered, region price, and negotiable.

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

* [Python](https://www.python.org/)
* [Jupyter Notebook](https://jupyter.org/)


<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Data Dictionary

- **Make:** Car company'name
- **Type:** Car type
- **Year:** Production year
- **Origin:** If  it from Saudi Arabia or Gulf countries or other
- **Color:** Car color
- **Options:** Full, Semi Full, Standard
- **Engine_Size**
- **Fule_Type:** Gas, Diesel, Hybrid
- **Gear_Type:** Automatic, Manual
- **Mileage:** the distance travel
- **Region:** the region of the car
- **Price:** price of the car
- **Negotiable:** (True/False) if the price is negotiable





<p align="right">(<a href="#top">back to top</a>)</p>




## Exploratory Data Analysis

### DataTypes
Data columns (total 14 columns):
| #  |   Column    | Non-Null Count | Dtype   |
| -- |  --------   |    --------    |-------- |
| 0  | Unnamed: 0  | 6428 non-null  | int64   |
| 1  | Make        | 6428 non-null  | object  |
| 2  | Type        | 6428 non-null  | object  |
| 3  | Year        | 6428 non-null  | int64   |
| 4  | Origin      | 6428 non-null  | object  |
| 5  | Color       | 6428 non-null  | object  |
| 6  | Options     | 6428 non-null  | object  |
| 7  | Engine_Size | 6428 non-null  | float64 |
| 8  | Fuel_Type   | 6428 non-null  | object  |
| 9  | Gear_Type   | 6428 non-null  | object  |
| 10 | Mileage     | 6428 non-null  | int64   | 
| 11 | Region      | 6428 non-null  | object  |
| 12 | Price       | 6428 non-null  | int64   |
| 13 | Negotiable  | 6428 non-null  | bool    |

 6428 entries
 
 ### Quick Observations
 
- The year of the used cars in our dataset are from 1964 until 2022, Wheras 75% of the cars were from 2018 and older.  
- The engine size ranging between 1-litre and 9-litre.
- The Mileage is started from 100 to 20000000.
- The price ranging from 0 to 1150000. 
 

<p align="right">(<a href="#top">back to top</a>)</p>




## Data Cleaning 

### Issues:
- Drop [Unnamed: 0] column  
- Drop all the observations in [Price] column with the values (0 and 1)
- Handle the outliers in the Mileage column

<p align="right">(<a href="#top">back to top</a>)</p>




## Machine Learning
For the machine learning we've created three models:
- Linear Regression model
- Decision Tree model
- K-Nearest Neighbors model

<p align="right">(<a href="#top">back to top</a>)</p>



## Contributors

* [Alfasial Alqahtani](https://github.com/AlfaisalGassim)
* [Fatema Buhuligah](https://github.com/Ifatema)
* [Sarah Alharbi](https://github.com/SarahAA1)
* [Saleh Alabbas](https://github.com/Saleh-Alabbas)

<p align="right">(<a href="#top">back to top</a>)</p>




## References 

* [GitHub README Template](https://github.com/othneildrew/Best-README-Template)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/AlfaisalGassim/saudi_used_cars_ml.svg?style=for-the-badge
[contributors-url]: https://github.com/AlfaisalGassim/saudi_used_cars_ml/graphs/contributors
[stars-shield]: https://img.shields.io/github/stars/AlfaisalGassim/saudi_used_cars_ml.svg?style=for-the-badge
[stars-url]: https://github.com/AlfaisalGassim/saudi_used_cars_ml/stargazers
