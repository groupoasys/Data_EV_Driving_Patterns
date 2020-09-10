# Data of Driving Patterns for Electric Vehicles (EVs) 🚗

## Goals 🏆

The aim of this repository is to provide the details of the EV driving patterns data set used in papers [[1]](https://arxiv.org/abs/1908.00787) and [[2]](https://arxiv.org/abs/2002.07021). This article have been developed by some members of the [OASYS group](https://sites.google.com/view/groupoasys/home) thanks to the funding of the project [Flexanalytics (https://groupoasysflexanalytics.readthedocs.io/en/latest/). We suggest you to visit the related links to know more our research 😉

## Contents 🎪

This repository includes the data about the driving patterns of an EV-fleet for one year. This data set is synthetically derived the availability profiles and energy required for transportation of EVs from the data collected by the [National Household Travel Survey](https://nhts.ornl.gov/). This EV-fleet is made up of 1000 EVs. Each data file is explained below: 

- Availability: The availability profiles show in which time periods the EV is available (the value is 1), to charge or discharge, and unavailable (the value is 0). The following files of availability can be downloaded:

    * [Data_a_24_1000](https://drive.google.com/file/d/1ZLeopKk0zuBNjB3ujzY-_40QiXz4DdRS/view?usp=sharing): The time period is 1 hour.
    
    * [Data_a_48_1000](https://drive.google.com/file/d/10uMwUzHm2YRvnNHqr7O7Q2Sk3_N4hlgm/view?usp=sharing): The time period is 30 minutes.
    
    * [Data_a_96_1000](https://drive.google.com/file/d/18yZ81ROMQDjKkjd8qmMyzdU70nYbM62B/view?usp=sharing): The time period is 15 minutes.
    
- EV demand: This data includes the distance travelled per EV each day. This data is found in the following file:

    * [Data_d](https://drive.google.com/file/d/1947OwAF6g8_j_ZhyDTn1Cmh50ALTYnuI/view?usp=sharing).

## References 📚
[1] Á. Porras, R. Fernández-Blanco, J. M. Morales and S. Pineda, "Day-ahead Operation of an Aggregator of Electric Vehicles via Optimization under Uncertainty," 2019 International Conference on Smart Energy Systems and Technologies (SEST), Porto, Portugal, 2019, pp. 1-6, doi: 10.1109/SEST.2019.8848991.

[2] Á. Porras, R. Fernández-Blanco, J. M. Morales and S. Pineda, "An Efficient Robust Approach to the Day-ahead Operation of an Aggregator of Electric Vehicles," in IEEE Transactions on Smart Grid, doi: 10.1109/TSG.2020.3004268.

 ## Contributors 🌬☀
 
 * [OASYS group](http://oasys.uma.es) -  groupoasys@gmail.com

 ## License 📝
 
    Copyright 2019 Optimization and Analytics for Sustainable energY Systems (OASYS)

    Licensed under the GNU General Public License, Version 3 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.gnu.org/licenses/gpl-3.0.en.html

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
