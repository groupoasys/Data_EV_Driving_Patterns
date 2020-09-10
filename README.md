# Data of Driving Patterns for Electric Vehicles (EVs) 🚗

## Goals 🏆

The aim of this repository is to provide the details of the EV driving patterns data set used in papers [[1]](https://arxiv.org/abs/1908.00787) and [[2]](https://arxiv.org/abs/2002.07021). This article have been developed by some members of the [OASYS group](https://sites.google.com/view/groupoasys/home) thanks to the funding of the project [Flexanalytics](https://groupoasysflexanalytics.readthedocs.io/en/latest/). We suggest you to visit the related links to know more our research 😉

## Contents 🎪

This repository includes the data about the driving patterns of an EV-fleet for one year. This data set contains the availability profiles and the energy required for transportation of EVs, which are synthetically derived from the data collected by the [National Household Travel Survey](https://nhts.ornl.gov/). This EV-fleet is made up of 1000 EVs. Each data file is explained below: 

- Availability: The availability profiles show in which time periods the EV is available (the value is 1), to charge or discharge, and unavailable (the value is 0). The following files of availability can be downloaded:

    * [Data_a_24_1000](https://drive.google.com/file/d/1ZLeopKk0zuBNjB3ujzY-_40QiXz4DdRS/view?usp=sharing): The time period is 1 hour.
    
    * [Data_a_48_1000](https://drive.google.com/file/d/10uMwUzHm2YRvnNHqr7O7Q2Sk3_N4hlgm/view?usp=sharing): The time period is 30 minutes.
    
    * [Data_a_96_1000](https://drive.google.com/file/d/18yZ81ROMQDjKkjd8qmMyzdU70nYbM62B/view?usp=sharing): The time period is 15 minutes.
    
- EV demand: This data includes the distance travelled per EV each day. This data is found in the following file:

    * [Data_d](https://drive.google.com/file/d/11DZ53OqEmPUVkLn6OY6DgNc-9-JS7Zay/view?usp=sharing).

## References 📚
[1] Á. P. Cabrera, R. Fernández-Blanco, J. M. Morales and S. Pineda, "Day-ahead Operation of an Aggregator of Electric Vehicles via Optimization under Uncertainty," 2019 International Conference on Smart Energy Systems and Technologies (SEST), Porto, Portugal, 2019, pp. 1-6, doi: 10.1109/SEST.2019.8848991.

[2] Á. Porras, R. Fernández-Blanco, J. M. Morales and S. Pineda, "An Efficient Robust Approach to the Day-ahead Operation of an Aggregator of Electric Vehicles," in IEEE Transactions on Smart Grid, doi: 10.1109/TSG.2020.3004268.

[3] OASYS, Data EV Driving Patterns, Github repository (https://github.com/groupoasys/Data_EV_Driving_Patterns) , 2020

## How to cite the repository and the paper? 📝

If you want to cite the papers [[1]](https://ieeexplore.ieee.org/abstract/document/8848991) and [[2]](https://ieeexplore.ieee.org/document/9122589), or this repo, [[3]](https://github.com/groupoasys/Data_DrivingPatterns_EVs), please use the following bib entries:

* Article 1:
```
@INPROCEEDINGS{8848991,
  author={Á. P. {Cabrera} and R. {Fernández-Blanco} and J. M. {Morales} and S. {Pineda}},
  booktitle={2019 International Conference on Smart Energy Systems and Technologies (SEST)}, 
  title={Day-ahead Operation of an Aggregator of Electric Vehicles via Optimization under Uncertainty}, 
  year={2019},
  volume={},
  number={},
  pages={1-6},}
```
* Article 2:
```
@ARTICLE{9122589,
  author={Á. {Porras} and R. {Fernández-Blanco} and J. M. {Morales} and S. {Pineda}},
  journal={IEEE Transactions on Smart Grid}, 
  title={An Efficient Robust Approach to the Day-ahead Operation of an Aggregator of Electric Vehicles}, 
  year={2020},
  volume={},
  number={},
  pages={1-1},}
```
* Repository:
```
@article{EVDrivingPatterns_2020,
author = {OASYS},
journal = {GitHub repository (https://github.com/groupoasys/Data{\_}EV{\_}Driving{\_}Patterns)},
title = {{Data EV Driving Patterns}},
url = {https://github.com/groupoasys/Data{\_}EV{\_}Driving{\_}Patterns},
year = {2020}
}
```
## Do you want to contribute? 🕵🏾‍♂️
 
 Please, do it 😏 Any feedback is welcome 🤗 so feel free to ask or comment anything you want via a Pull Request in this repo.
 If you need extra help, you can ask Álvaro Porras (alvaroporras19@gmail.com).

 ## Contributors 🌬☀
 
 * [OASYS group](http://oasys.uma.es) -  groupoasys@gmail.com
 
 ## Developed by 👨🏾‍💻
 * [Álvaro Porras](https://www.researchgate.net/profile/Alvaro_Porras_Cabrera2) - alvaroporras19@gmail.com

 ## License 📝
 
    Copyright 2020 Optimization and Analytics for Sustainable energY Systems (OASYS)

    Licensed under the GNU General Public License, Version 3 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.gnu.org/licenses/gpl-3.0.en.html

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
