---
title: Progress Measurement for Canada’s Sustainable Development Goals
language: en
permalink: /methodology/
layout: page
---

## Introduction   
The [2030 Agenda for Sustainable Development](https://www.un.org/sustainabledevelopment/development-agenda/), adopted by all United Nations Member States in 2015, provides a blueprint for improving the economy, society, and the environment in a sustainable manner. At its heart, the 17 Sustainable Development Goals (SDGs) are a universal call to action to end poverty, protect the planet, and ensure that all people globally can enjoy peace and prosperity.  

The goals are underpinned by a framework of global indicators that allow Canada and other countries to monitor and report on progress. They cover a broad range of social, environmental, and economic issues with a focus on the most vulnerable and a commitment to “leave no one behind”. To complement the global goals, countries are encouraged to develop a national implementation plan that focuses on country-developed indicators to address specific national contexts and priorities to achieve the SDGs.  

To support Canada’s domestic implementation of the SDGs that the Government of Canada has committed to, a [national strategy](https://www.canada.ca/en/employment-social-development/programs/agenda-2030/moving-forward.html) has been established. In addition, the development of a Canadian-specific indicator framework was an opportunity to elaborate on the UN goals with a set of indicators that align more closely with Canada’s domestic priorities related to sustainable development.  
  


## Measuring Progress   
Measuring and monitoring progress with reliable information is key to understanding how Canada advances toward the achievement of the SDGs.  

Closely monitoring the progress of each indicator not only illustrates where Canada is making progress or areas where progress is not being made and Canada can focus its efforts, but also communicates how Canada is doing in an open and transparent manner. A robust measure of progress quantifies an indicator’s progress towards reaching the target in a scientific manner and can used as a tool to better understand success of policies and actions taken to achieve those targets. It can also act as a clear signal to decision-makers to re-adjust or develop effective evidence-based policies to help ensure Canada achieves its targets.  
 



## Methodology Adopted   
The Canadian Indicator Framework (CIF) lays the foundation for Canada to measure and report its progress on the 17 SDGs within the Canadian context. The CIF focuses on Canadian priorities for sustainable development and can be considered a complement to the Global Indicator Framework. In the CIF the 17 Sustainable Development Goals are complemented by 33 ambitions and 86 indicators that are Canadian specific. However, unlike the Global Indicator Framework where every indicator has a target, less than half of the indicators in the CIF currently have a defined target, either quantitative (e.g., target 11.5 *By 2030, 22% of commuters adopt shared or active transportation*) or aspirational (e.g., target 5.2 *Greater representation of women in leadership roles*).  

To complement the CIF, Statistics Canada has developed a robust and simple method of measuring progress which can be reported using visualizations that allow data users to easily see areas of progress or weakness. Even in the absence of specific quantitative targets, an estimate of progress can inform whether undesired trends are being observed by reporting progress deterioration. In essence, this measure of progress provides a simplified illustration of Canada’s progress toward achieving the SDGs, assuming that the current trends are maintained.  



### Requirements   
Statistics Canada identified essential requirements for the adopted methodology. The guiding principle for the methodology was the necessity of a consistent and easily interpretable measure that could reach a broad audience while maintaining scientific integrity.  

More specifically, the methodology must:  

1. Allow for different data periodicity and timeliness: Data series available in Canada have various collection calendars and reference periods. Some are collected every year while others every few years. Furthermore, the time required between the collection of data and release of official statistics varies greatly between programs.  
2. Provide a calculation for measuring progress in the absence of a quantitative target: To gain a greater understanding of policy impacts and progress towards the achievements of the SDGs, it is crucial to be able to assess progress in the absence of a specific numerical target.  
3. Allow for the calculation of an aggregate measure, whether at the target, ambition, or goal level: When used appropriately, a composite measure of progress is valuable to leaders and policymakers to help steer policy and actions towards making progress to achieve the SDGs.  

  
The adopted methodology cannot rely on:  

1. The need to create a target when there is none. As a statistical agency, we remain politically neutral. Therefore, it is outside the scope of our mandate to assign targets. Thus, the methodology must be valid even in the absence of a target.  
2. Indicator-specific thresholds for progress categories: It was assessed that using different criteria for each indicator would put too much emphasis on the method rather than the message and overall progress. Therefore, the methodology developed uses a straightforward and consistent method across all indicators.  
3.	The existence of extended time-series: Many issues covered in the SDGs haven’t been measured for an extended period. Opting for a methodology that is robust despite a shorter time-series allows for a considerable increase in the number of indicators for which progress can be calculated.  
4.	Modelling: Similar to item 3, modelling usually requires a longer time-series which will reduce the number of indicators eligible for calculation of the progress measure.  


### Methodology   
The progress measure consists of a measure of observed growth compared to an evaluation of the proximity to achieving the target under current conditions. In situations where no quantitative target is provided, the time series is evaluated on the apparent trend of the data.  
  
Keeping in mind the limited number of data points in each time series and a desire to keep the methodology simple and transparent, the optimal methodology for measuring progress closely mirrors the progress methodology used by Eurostat[^1].  

Progress is measured using the growth over the observed period and is calculated by a compound annual growth rate,  

![](https://raw.githubusercontent.com/sdg-data-canada-odd-donnees/cif-cic_dev/develop/assets/img/methodology/cagr_observed.PNG)  

where  
*CAGR*<sub>o</sub> is the observed compound annual growth rate between *t<sub>0</sub>* and *t<sub>i</sub>*     
*y<sub>ti</sub>* is the value of the indicator at time *t<sub>i</sub>*    
*t<sub>i</sub>* is the most recent year where data is available, and    
*t<sub>0</sub>* is the base year, 2015, unless otherwise specified.    

<br><br> 

#### Indicators with quantitative targets  
In the case where a quantitative target for the indicator is provided, the observed *CAGR<sub>o</sub>* is compared to the theoretical *CAGR<sub>r</sub>*, which represents the growth required to achieve the target, by calculating the ratio (*R<sub>o/r</sub>*) as follows:   

![Growth ratio](https://raw.githubusercontent.com/sdg-data-canada-odd-donnees/cif-cic_dev/develop/assets/img/methodology/ratio.PNG)  

where   

![Theoretical cumulative annual growth rate](https://raw.githubusercontent.com/sdg-data-canada-odd-donnees/cif-cic_dev/develop/assets/img/methodology/cagr_theoretical.PNG)   

*x<sub>tT</sub>* is the target value of the indicator in the target year, *t<sub>T</sub>*.   

The result is compared against a set of thresholds[^2] and assigned a progress category, described below:   
  
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-fymr{border-color:inherit;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-0pky{border-color:inherit;text-align:left;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-fymr">Ratio of observed over required growth rate</th>
    <th class="tg-fymr">Category</th>
    <th class="tg-fymr">Symbol</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0pky">Target is achieved</td>
    <td class="tg-0pky">Target achieved</td>
    <td class="tg-0pky"><img src="https://github.com/sdg-data-canada-odd-donnees/cif-cic_dev/blob/develop/assets/img/progress/target-achieved-gauge.png?raw=true" width="150" height="150"></td>
  </tr>
  <tr>
    <td class="tg-0pky">R<sub>o/r</sub> ≥ 95%</td>
    <td class="tg-0pky">On track</td>
    <td class="tg-0pky"><img src="https://github.com/sdg-data-canada-odd-donnees/cif-cic_dev/blob/develop/assets/img/progress/green-gauge.png?raw=true" alt="Guage icon with four equally sized colour segments (from left to right): red, orange, yellow, green. A black needle points at the middle of the green segment." width="150" height="150"></td>
  </tr>
  <tr>
    <td class="tg-0pky">60% ≤ R<sub>o/r</sub> &lt; 95%</td>
    <td class="tg-0pky">Progress made but acceleration needed</td>
    <td class="tg-0pky"><img src="https://github.com/sdg-data-canada-odd-donnees/cif-cic_dev/blob/develop/assets/img/progress/yellow-gauge.png?raw=true" alt="Guage icon with four equally sized colour segments (from left to right): red, orange, yellow, green. A black needle points at the middle of the yellow segment." width="150" height="150"></td>
  </tr>
  <tr>
    <td class="tg-0pky">0% ≤ R<sub>o/r</sub> &lt; 60%</td>
    <td class="tg-0pky">Limited progress</td>
    <td class="tg-0pky"><img src="https://github.com/sdg-data-canada-odd-donnees/cif-cic_dev/blob/develop/assets/img/progress/orange-gauge.png?raw=true" alt="Guage icon with four equally sized colour segments (from left to right): red, orange, yellow, green. A black needle points at the middle of the orange segment." width="150" height="150"></td>
  </tr>
  <tr>
    <td class="tg-0pky">R<sub>o/r</sub> &lt; 0%</td>
    <td class="tg-0pky">Deterioration</td>
    <td class="tg-0pky"><img src="https://github.com/sdg-data-canada-odd-donnees/cif-cic_dev/blob/develop/assets/img/progress/red-gauge.png?raw=true" alt="Guage icon with four equally sized colour segments (from left to right): red, orange, yellow, green. A black needle points at the middle of the red segment." width="150" height="150"></td>
  </tr>
</tbody>
</table>

<br><br>  
  
  
#### Indicators without quantitative targets  
In the case where no quantitative target for a given indicator has been provided, *CAGR<sub>o</sub>* is compared to a pre-determined fixed growth rate and the thresholds have been fixed at 0%, 0.5% and 1.5%.  
  

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-fymr{border-color:inherit;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-0pky{border-color:inherit;text-align:left;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-fymr">Ratio of observed over required growth rate</th>
    <th class="tg-fymr">Category</th>
    <th class="tg-fymr">Symbol</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0pky">CAGR<sub>o</sub> ≥ 1.5%</td>
    <td class="tg-0pky">On track</td>
    <td class="tg-0pky"><img src="https://github.com/sdg-data-canada-odd-donnees/cif-cic_dev/blob/develop/assets/img/progress/green-gauge.png?raw=true" alt="Guage icon with four equally sized colour segments (from left to right): red, orange, yellow, green. A black needle points at the middle of the green segment." width="150" height="150"></td>
  </tr>
  <tr>
    <td class="tg-0pky">0.5% ≤ CAGR<sub>o</sub> &lt; 1.5%</td>
    <td class="tg-0pky">Progress made but acceleration needed</td>
    <td class="tg-0pky"><img src="https://github.com/sdg-data-canada-odd-donnees/cif-cic_dev/blob/develop/assets/img/progress/yellow-gauge.png?raw=true" alt="Guage icon with four equally sized colour segments (from left to right): red, orange, yellow, green. A black needle points at the middle of the yellow segment." width="150" height="150"></td>
  </tr>
  <tr>
    <td class="tg-0pky">0% ≤ CAGR<sub>o</sub> &lt; 0.5%</td>
    <td class="tg-0pky">Limited progress</td>
    <td class="tg-0pky"><img src="https://github.com/sdg-data-canada-odd-donnees/cif-cic_dev/blob/develop/assets/img/progress/orange-gauge.png?raw=true" alt="Guage icon with four equally sized colour segments (from left to right): red, orange, yellow, green. A black needle points at the middle of the orange segment." width="150" height="150"></td>
  </tr>
  <tr>
    <td class="tg-0pky">CAGR<sub>o</sub> &lt; 0%</td>
    <td class="tg-0pky">Deterioration</td>
    <td class="tg-0pky"><img src="https://github.com/sdg-data-canada-odd-donnees/cif-cic_dev/blob/develop/assets/img/progress/red-gauge.png?raw=true" alt="Guage icon with four equally sized colour segments (from left to right): red, orange, yellow, green. A black needle points at the middle of the red segment." width="150" height="150"></td>
  </tr>
</tbody>
</table>
  
<br><br>   

### Aggregation at the Goal Level  
To determine an aggregate level of progress (for example overall progress at the goal level, or if there is more than one indicator for a target or ambition), the methodology developed by Eurostat is once again the preferred methodology.  The progress measure for each indicator is converted into a score, and then averaged at the aggregated level. Each indicator within a goal (or target or ambition) are equi-weighted. The score, both at the indicator and goal/ambition/target level, varies between -5 and 5[^3].   
  
<br>  
  
#### Aggregation for indicators without quantitative targets     
The scoring function for indicators without a quantitative target is a linear transformation of the CAGR thresholds described above. The cut-off points for a score of ±5 are set to ±2%, as illustrated in Figure 1 below.   

![Scoring function for indicators without a quantitative target](https://raw.githubusercontent.com/sdg-data-canada-odd-donnees/cif-cic_dev/develop/assets/img/methodology/scoring_non_quantitative.png)   

<br>  
  
  
#### Aggregation for indicators with quantitative targets     
The scoring function for indicators with a quantitative target reflects the thresholds used to categorize the indicators and uses cut-off values of 130% for a score of +5 and -60% for a score of -5. This is illustrated in Figure 2 below.   

![Scoring function for indicators with a quantitative target](https://raw.githubusercontent.com/sdg-data-canada-odd-donnees/cif-cic_dev/develop/assets/img/methodology/scoring_quantitative.png)   

### Considerations and Exceptions    
Due to the nature of the data, a series of considerations and exceptions have been defined:  


1. Should there be no data in 2015, the first available year following 2015 will be used.[^4]    
   a. For indicators with a reference period across two years, for example a reference period of April 1, 2015- March 31, 2016:  
      i. The first year is used as the reference period (e.g., if the reference period is 2015-16, then 2015 is used).     
   b. Even when the target results from a policy that was implemented after 2015, the base year for calculating the progress measure will be 2015 when data exists. This aligns with Statistics Canada quality dimensions coherence and comparability.  
2. Similar to (1), should the target year be March 20xx, then 20xx-1 will be used as the target year in the calculation since it is the last complete year of data. For example, the year 2022 will be used in the calculation of the progress for an indicator with a target of March 2023.  
3. If the target value is zero, it will be replaced by 0.001 in the calculation of the progress measure.  
4. In the absence of a specified target date, it is assumed that 2030 is the target period.   
5. Should the target year be in the past, the following will be done:  
   a. Calculate using the methodology with target until the target year (*y*).  
   b. Continue calculating using the methodology with target, keeping the now obsolete target value and year.   
   c. Include a note to users explaining how to interpret the information.  
   d. Should a new target value and year be introduced, start using the new values in the calculation, and recalculate from *y+1*.  
   e. Include a note to users explaining the change.  
6. A minimum of two years of data is required to calculate the progress measure.  
7. To calculate the summary measure for a target, ambition or goal, a minimum of 60% of indicators for which it is possible to calculate a progress measure is needed.  
8. The progress estimates oversimplify reality. Users should use the progress measure in addition to specific indicator values and other relevant information.  
9. The impact of policies takes time to be reflected in the data; the longer the time series, the better the methodology will be to measure progress.  
10. The progress measure for indicators that start above the target at their base year for which progress then declines will be automatically overridden to “Deterioration”[^5].  
11. Binary indicators will be assigned one of these 2 categories:  
   a. “Target achieved” if “yes”.   
   b. “Target not achieved” if “no”.  
12. For indicators with two targets, for example CIF target 3.8 - By 2025, 95% coverage of all childhood vaccines and 90% coverage of all adolescent vaccines, the result that is the farthest from its target is used as progress measure.  
13. Specific exception: CIF indicator 5.4.1 - Proportion of time spent on unpaid domestic and care work is reporting the proportion of day spent on unpaid domestic and care work, by sex. To be able to calculate the progress toward the target Equal sharing of parenting roles and family responsibilities, the indicator will be modified prior to calculation. A ratio of the proportion of time for women to that for men will be used, with a desired target of 1.   


 
## Future Work   

Statistics Canada’s SDG team is working with the Open SDG community to integrate the indicator-level progress measurement into the back end of the Open SDG platform. It will be represented by a label and an icon describing the most recently calculated progress for each indicator. Once implemented, the functionality will be available for all Open SDG users. Due to the complexity of the indicator frameworks, the functionality will only include indicators that report an aggregate value at first – indicators composed solely of sub-components, such as CIF indicator 3.9.1 - *Incidence of selected diseases*, will require manual calculation and manual input of the progress labels to be displayed on the Open SDG data hub. The Statistics Canada team will continue improving the automatic calculation, as well as developing the aggregate measurement to be integrated into the platform.   


## Metadata   

##### Canadian Indicator Framework  

| Indicator number | Indicator name                                                                                                                                                                | Desired direction |
|------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------|
| 1.1.1            | Poverty rate, as measured by Canada’s official poverty line                                                                                                                   | Decrease          |
| 1.2.1            | Prevalence of asset resilience                                                                                                                                                | Increase          |
| 1.3.1            | Debt to disposable income ratio                                                                                                                                               | Decrease          |
| 1.4.1            | Median household after-tax income                                                                                                                                             | Increase          |
| 2.1.1            | Prevalence of food insecurity                                                                                                                                                 | Decrease          |
| 2.2.1            | Index of Agri-Environmental Sustainability                                                                                                                                    | Increase          |
| 3.1.1            | Percentage of Canadians who report eating fruits and vegetables 5 or more times per day                                                                                       | Increase          |
| 3.2.1            | Percentage of youth (aged 12 to 17) who have used an e-cigarette in the past 30 days                                                                                          | Decrease          |
| 3.3.1            | Proportion of the population living with obesity                                                                                                                              | Decrease          |
| 3.4.1            | Alcohol per capita consumption (aged 15 years and older) within a calendar year in litres of pure alcohol                                                                     | Decrease          |
| 3.5.1            | Proportion of Canadians meeting the 2020 Canadian physical activity guidelines                                                                                                | Increase          |
| 3.6.1            | Percentage of Canadians who are satisfied or very satisfied with their life                                                                                                   | Increase          |
| 3.7.1            | Percentage of Canadians who perceived their overall health as very good to excellent                                                                                          | Increase          |
| 3.8.1            | Percentage of Canadians who perceived their mental health as very good to excellent                                                                                           | Increase          |
| 3.9.1            | Vaccination rates for selected diseases                                                                                                                                       | Increase          |
| 3.10.1           | Incidence of selected diseases                                                                                                                                                | Decrease          |
| 3.11.1           | Mortality rate for selected causes of death                                                                                                                                   | Decrease          |
| 3.12.1           | Tuberculosis incidence per 100,000 population in Inuit Nunangat                                                                                                               | Decrease          |
| 3.13.1           | Rate of apparent opioid toxicity deaths per 100,000 population                                                                                                                | Decrease          |
| 3.14.1           | Percentage of Canadians (aged 18+) who currently smoke cigarettes                                                                                                             | Decrease          |
| 3.15.1           | Proportion of persons with unmet health care needs                                                                                                                            | Decrease          |
| 4.1.1            | High school completion rate                                                                                                                                                   | Increase          |
| 4.2.1            | Post-secondary education attainment rate                                                                                                                                      | Increase          |
| 4.3.1            | Proportion of children aged 0 to 5 years who use any forms of early learning and child care services                                                                          | Increase          |
| 5.1.1            | Proportion of the population who self-reported being sexually assaulted in the last 12 months                                                                                 | Decrease          |
| 5.2.1            | Proportion of women and girls aged 15 years and older subjected to physical, sexual or psychological violence by a current or former intimate partner in the last 12 months   | Decrease          |
| 5.3.1            | Proportion of leadership roles held by women                                                                                                                                  | Increase          |
| 5.4.1            | Proportion of time spent on unpaid domestic and care work                                                                                                                     | Decrease          |
| 5.5.1            | Median hourly gender wage ratio                                                                                                                                               | Increase          |
| 6.1.1            | Number of long-term drinking water advisories on public systems on reserves                                                                                                   | Decrease          |
| 6.2.1            | Percentage of municipalities across Canada with sustained drinking water advisories                                                                                           | Decrease          |
| 6.3.1            | Water use growth rate                                                                                                                                                         | Decrease          |
| 6.4.1            | Water quality in Canadian rivers                                                                                                                                              | Increase          |
| 6.5.1            | Percentage of wastewater systems on reserves where effluent quality standards are achieved                                                                                    | Increase          |
| 6.6.1            | Percentage of wastewater systems in Canada where effluent quality standards are achieved                                                                                      | Increase          |
| 7.1.1            | Total annual energy savings resulting from adoption of energy efficiency codes, standards and practices                                                                       | Increase          |
| 7.2.1            | Proportion of electricity generated from renewable and other non-greenhouse gas emitting sources                                                                              | Increase          |
| 7.3.1            | Total energy consumption per capita                                                                                                                                           | Decrease          |
| 8.1.1            | Unemployment rate                                                                                                                                                             | Decrease          |
| 8.2.1            | Employment rate                                                                                                                                                               | Increase          |
| 8.3.1            | Proportion of youth not in education, employment or training                                                                                                                  | Decrease          |
| 8.4.1            | Rate of involuntary part-time work                                                                                                                                            | Decrease          |
| 8.5.1            | Gross domestic product per capita                                                                                                                                             | Increase          |
| 8.6.1            | Jobs in the clean technology products sector                                                                                                                                  | Increase          |
| 9.1.1            | Proportion of enterprises that introduced innovations with environmental benefits                                                                                             | Increase          |
| 9.2.1            | Gross domestic expenditure on research and development intensity                                                                                                              | Increase          |
| 9.3.1            | Proportion of households that have access to broadband Internet service at speeds of 50/10 Mbps                                                                               | Increase          |
| 9.4.1            | Proportion of Canadians that have access to the latest generally deployed mobile wireless technology                                                                          | Increase          |
| 9.5.1            | Greenhouse gas emissions per dollar of value-added from the production of infrastructure assets                                                                               | Decrease          |
| 9.6.1            | Number of publicly available electric vehicle charging and alternative fuelling stations in Canada                                                                            | Increase          |
| 9.7.1            | Remaining useful service life ratio of infrastructure assets                                                                                                                  | Increase          |
| 10.1.1           | Gini Coefficient                                                                                                                                                              | Decrease          |
| 10.2.1           | Proportion of the population reporting discrimination or unfair treatment                                                                                                     | Decrease          |
| 11.1.1        | (a) Number of shelter users experiencing chronic homelessness; and (b) percentage change in the number of shelter users experiencing chronic homelessness from the 2016 baseline | Decrease          |
| 11.2.1           | Proportion of households in core housing need                                                                                                                                 | Decrease          |
| 11.3.1           | Percentage of the population living in areas where air pollutant concentrations are less than or equal to the 2020 Canadian Ambient Air Quality Standards                     | Increase          |
| 11.4.1           | Percentage of the population living within 500 metres of a public transport stop                                                                                              | Increase          |
| 11.5.1           | Proportion of commuters using sustainable transportation                                                                                                                      | Increase          |
| 11.6.1           | Total waste disposal per capita                                                                                                                                               | Decrease          |
| 11.7.1           | Proportion of the population aged 12 and over who reported their sense of belonging to their local community as being very strong or somewhat strong                          | Increase          |
| 12.1.1           | Proportion of new light duty vehicle registrations that are zero-emission vehicles                                                                                            | Increase          |
| 12.2.1           | Proportion of businesses that adopted selected environmental protection activities and management practices                                                                   | Increase          |
| 12.3.1           | Total waste diversion per capita                                                                                                                                              | Increase          |
| 12.4.1           | Proportion of discarded plastic leaked permanently into the environment                                                                                                       | Decrease          |
| 13.1.1           | Greenhouse gas emissions                                                                                                                                                      | Decrease          |
| 13.2.1           | Deaths due to exposure to excessive natural heat                                                                                                                              | Decrease          |
| 13.3.1           | Proportion of municipal organizations who factored climate change adaptation into their decision-making process                                                               | Increase          |
| 13.4.1           | Flood protection infrastructure spending                                                                                                                                      | Increase          |
| 14.1.1           | Proportion of marine and coastal areas conserved                                                                                                                              | Increase          |
| 14.2.1           | Proportion of key fish stocks in the Cautious and Healthy zones                                                                                                               | Increase          |
| 15.1.1           | Proportion of native wild species ranked secure or apparently secure according to the national extinction risk level                                                          | Increase          |
| 15.2.1           | Proportion of species at risk showing progress towards their population and distribution objectives                                                                           | Increase          |
| 15.3.1           | Canadian species index                                                                                                                                                        | Increase          |
| 15.4.1           | Proportion of Canada's land and inland waters conserved                                                                                                                       | Increase          |
| 15.5.1           | Proportion of the sustainable wood supply harvested                                                                                                                           | Decrease          |
| 15.6.1           | Forest area as a proportion of total land area                                                                                                                                | No change         |
| 16.1.1           | Proportion of Canadians who reported feeling safe walking alone in their neighborhood after dark                                                                              | Increase          |
| 16.2.1           | Incidence of selected types of crime                                                                                                                                          | Decrease          |
| 16.3.1           | Incidence of cyber-crime                                                                                                                                                      | Decrease          |
| 16.4.1           | Civil Court case completion time                                                                                                                                              | Decrease          |
| 16.5.1           | Criminal Court case completion time                                                                                                                                           | Decrease          |
| 16.6.1           | Incarceration rate                                                                                                                                                            | Decrease          |
| 16.7.1           | Proportion of the population with high levels of confidence in selected institutions                                                                                          | Increase          |
| 17.1.1           | Statistical Performance Indicators                                                                                                                                            | Increase          |
| 17.2.1           | Total official support for sustainable development                                                                                                                            | Increase          |
| 17.3.1           | Exports of environmental and clean technology goods and services to developing countries                                                                                      | Increase          |


## References   

Destatis. *Indicator status summary*.  

Eurostat (2021). *Sustainable development in the European Union - Monitoring report on progress towards the SDGs in an EU context*.  

Eurostat (2014). *Getting messages across using indicators - A handbook based on experiences from assessing Sustainable Development Indicators*.  

Gennari, P. and D’Orazio, M. (2020). *Statistical approach for assessing progress toward the SDG targets*. Statistical Journal of the IAOS, 36, 1129–1142  

OECD (2019). *Measuring Distance to the SDG Targets - An Assessment of Where OECD Countries Stand*.      

UN DESA (2020). *Sustainable Development Goals Progress Chart 2020 - Technical Note*.    

Bidarbakht Nia, A. (2017). *A weighted extrapolation method for measuring the SDGs progress*. UNESCAP SD Working paper series, 04, March 2017  

Bidarbakht Nia, A. (2017). *Tracking progress towards the SDGs: measuring the otherwise ambiguous progress*. UNESCAP SD Working paper series, 05, May 2017   

UNESCAP (2020). *Progress Assessment Methodology*.    

Sachs, J., Kroll, C., Lafortune, G., Fuller, G., Woelm, F. (2021). *The Decade of Action for the Sustainable Development Goals: Sustainable Development Report 2021*. Cambridge: Cambridge University Press.   

## Notes  

[^1]: For a detailed description of the methodology, please refer to Eurostat (2021).  
[^2]: All thresholds are standards in the international communities. After assessment, it was found that they are also applicable in the Canadian context.   
[^3]: For a detailed description of the methodology, please refer to Eurostat (2021), Annex III.  
[^4]: In very few cases where the periodicity of the data is over 4 years or more, a base period of 2014 has been used.  
[^5]: This is a necessary measure to counteract a drawback of the formula: In situation where the target was achieved during the base period but deteriorated afterwards, the formula calculates significant progress as the indicator decreases (or increases) more ‘than it should’ to meet the target. Take for example target 3.13 *By 2035, less than 5% of Canadians (aged 15+) are cigarette smokers.* Suppose that in 2015, 3% of Canadians aged 15+ are cigarette smokers, and that in 2020 this percentage raises to 10%. The formula will calculate the growth required to go from 3% to 5% (instead of the one from 10% to 5%) and will conclude that great progress has been made since the new value not only reached 5% but progressed further ahead to 10%.  
