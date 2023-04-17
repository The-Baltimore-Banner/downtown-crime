- [Overview](#overview)
- [Methodology](#method)
- [Limitations](#limitations)
- [License](#license)


## Overview


Many visitors and residents say concerns about safety and crime in general deter them from lingering downtown, even as other city neighborhoods on the east and west sides are far more violent.
After a drop during the pandemic, rates of most crimes downtown have rebounded and remain high compared to nearby neighborhoods that make up the central part of the city, including Fells Point and the Inner Harbor, the Banner analysis found.


Thefts per capita in the Inner Harbor — which includes Harbor East — were slightly higher than in downtown in 2022, but violent crime is much more prevalent downtown. The number of aggravated assaults per 1,000 residents is nearly four times higher than in other nearby neighborhoods in the city’s core. Shooting and homicide rates match those in the historically most violent police districts, and downtown suffers from some of the highest rates of robbery in the city.






Read the story: [Beat down by crime, disinvestment and a pandemic, can downtown Baltimore recover?](www.thebaltimorebanner.com//).


Where to get the data you need:


Put CSV in the data folder:
[Baltimore Police Part 1 Crimes Database](https://data.baltimorecity.gov/datasets/part-1-crime-data-/explore)


Put neighborhoods in data folder:
[Baltimore Neighborhoods](https://data.baltimorecity.gov/datasets/neighborhood-1/explore?location=39.284818%2C-76.620500%2C11.86)
[Baltimore Police Districts](https://data.baltimorecity.gov/datasets/956e52eb7abb4787abd7386e8efd600b_0/about)

Put police districts in data folder:
[Baltimore Police Districts](https://data.baltimorecity.gov/maps/956e52eb7abb4787abd7386e8efd600b/about)


<a id="method"></a>


## Methodology
### How we analyzed BPD violent crime data


This analysis of Baltimore Police Part 1 Crime Data relies on neighborhood classifications and city police districts from the city of Baltimore as well as the greater downtown definition set by the Downtown Merchants Association. A computer-readable version of this map did not exist prior to this analysis. The Banner created this by setting coordinates to plot the definitions of geography where merchants can join the downtown association. This can be confusing because there are two neighborhoods called downtown.


While reviewing this analysis, it is important to focus on the difference between the number of crimes and the number of victims. The data includes one row for every victim of a Part 1 crime. To get distinct crimes, we grouped them by time and location. In some cases, a shooting event led to multiple victims, some who were homicide victims and others who were shooting victims. Our analysis counts this as one shooting crime, but multiple shooting victims.


<a id="limitations"></a>


## Limitations
### Missing entries and errors we overcame to tell this story


There are known errors in the public Part 1 Crimes Database. The database is also frequently changing. Crimes that were once classified as homicides are often reclassified, making it difficult to recreate mid-year BPD reports at the end of the year. A slight variation is to be expected.


Not every year in the database is reliable. In response to previous questions from The Banner, BPD admitted that shooting data before 2014 should not be relied on. They have never said why. Further analysis has led The Banner to question data in 2014 as well, leaving only the last seven years for analysis.


This analysis relies on a geographic join between latitudes and longitudes for crimes and maps that say where police districts, neighborhoods and greater downtown are. Some crimes say they are in a police district but their plot on a map would not have matched that neighborhood. Examples are included in the code. When analyzing city-designated districts and neighborhoods, we relied on the classifications included in the data. When analyzing the greater downtown area, we could only rely on the geographic join. The crime rates there may be higher.


This analysis used different populations for each year, relying on 5-year ACS estimates between 2015 and 2021. For 2022, we used 2021 data since 2022 is not a year available. ACS 5-year estimates do not match the 2020 Decennial Census. To avoid a spike in population, we used the ACS for 2020.


<a id="license"></a>


## License


Copyright 2023, The Venetoulis Institute for Local Journalism


Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:


1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.


2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.


3. Neither the name of the copyright holder nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.


THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
