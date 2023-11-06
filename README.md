# Electricity Consumption Forecasting Using Arima, UCM, Machine Learning (Random Forest and k-NN), and Deep Learning (GRU Recurrent Neural Network) Models

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
[![Report][report-shield]][report-url]
[![Slides][slides-shield]][slides-url]

## Table of contents

* [Abstract](#Abstract)
* [Report (ITA)](https://www.mdpi.com/2304-6740/11/11/421) and [Slides (EN)](https://github.com/giocoal/cluster-analysis-on-computational-chemistry-simulations-water-adsorption-on-atmosperic-particulate/blob/main/thesis%20manuscript%20and%20presentation%20slides/Thesis.pdf)
* [Status](#status)
* [Contact](#contact)
* [License](#license)
* [Contributing](#contributing)
* [Contributors](#contributors)

## Abstract

The forecasting of time series of electricity consumption plays an important role in efficient resource management and strategic planning in the energy sector. In this project, we analyse a univariate, homogeneous, high-frequency time series of electricity consumption measured every 10 minutes from 01/01/2017 to 30/11/2017, comparing statistical (ARIMA and UCM), Machine Learning (Random Forest and k-NN) and Deep Learning (GRU Recurrent Neural Network) approaches to model the time series and forecast consumption for the month of December 2017. The best performing of the models in each family, trained on data sampled between 01/01/2017 to 31/10/2017 (or a portion thereof) and validated on November 2017 data, resulted in the following error measures: $MAE_{ARIMA}=1010.08$, $MAE_{UCM}=1183.40$ and $MAE_{ML}= 1184.07$, leading the ARIMA approach to be the most accurate in forecasting among those tested.

<p align="center">
<img src="images/Validation.png" width="100%" />
<em>Forecasts for the validation set (November 2017) made with the best models for each class.</em>
</p>

## Status

 Project is: ![##c5f015](https://via.placeholder.com/15/c5f015/000000?text=+)  _Done_

## Contact

Feel free to contact me!
- [Google Scholar](https://scholar.google.com/citations?user=XwyRP1wAAAAJ&hl=en&oi=sra)
- [Linkedin](https://www.linkedin.com/in/giorgio-carbone-63154219b/)
- [Github](https://github.com/giocoal)

## License
* >You can check out the full license [here](https://github.com/giocoal/analysis-and-forecasting-tetouan-city-power-consumption-ARIMA-UCM-GRU/blob/main/README.md)

This project is licensed under the terms of the **MIT** license.

## Contributing

1. Fork it (<https://github.com/giocoal/analysis-and-forecasting-tetouan-city-power-consumption-ARIMA-UCM-GRU.git>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

# Contributors

* [Giorgio Carbone](https://github.com/giocoal) 

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/giocoal/analysis-and-forecasting-tetouan-city-power-consumption-ARIMA-UCM-GRU.svg?style=for-the-badge
[contributors-url]: https://github.com/giocoal/analysis-and-forecasting-tetouan-city-power-consumption-ARIMA-UCM-GRU/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/giocoal/analysis-and-forecasting-tetouan-city-power-consumption-ARIMA-UCM-GRU.svg?style=for-the-badge
[forks-url]: https://github.com/giocoal/analysis-and-forecasting-tetouan-city-power-consumption-ARIMA-UCM-GRU/network/members
[stars-shield]: https://img.shields.io/github/stars/giocoal/analysis-and-forecasting-tetouan-city-power-consumption-ARIMA-UCM-GRU.svg?style=for-the-badge
[stars-url]: https://github.com/giocoal/analysis-and-forecasting-tetouan-city-power-consumption-ARIMA-UCM-GRU/stargazers
[issues-shield]: https://img.shields.io/github/issues/giocoal/analysis-and-forecasting-tetouan-city-power-consumption-ARIMA-UCM-GRU.svg?style=for-the-badge
[issues-url]: https://github.com/giocoal/analysis-and-forecasting-tetouan-city-power-consumption-ARIMA-UCM-GRU/issues
[license-shield]: https://img.shields.io/github/license/giocoal/analysis-and-forecasting-tetouan-city-power-consumption-ARIMA-UCM-GRU.svg?style=for-the-badge
[license-url]: https://github.com/giocoal/analysis-and-forecasting-tetouan-city-power-consumption-ARIMA-UCM-GRU/blob/master/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/giorgio-carbone-63154219b/
[report-shield]: https://img.shields.io/badge/Read%20Report%20-grey?style=for-the-badge
[report-url]: https://github.com/giocoal/analysis-and-forecasting-tetouan-city-power-consumption-ARIMA-UCM-GRU/blob/main/report/Project_Report.pdf
[slides-shield]: https://img.shields.io/badge/Read%20Slides%20-grey?style=for-the-badge
[slides-url]: https://www.slideshare.net/Giorgio469575/electricity-consumption-forecasting-using-arima-ucm-machine-learning-and-deep-learning-models
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com