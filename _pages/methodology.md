---
title: Progress Measurement for Canada’s Sustainable Development Goals
language: en
permalink: /methodology/
layout: page
toc: true
---

# Progress Measurement for Canada’s Sustainable Development Goals   


## Introduction  
The [2030 Agenda for Sustainable Development](https://www.un.org/sustainabledevelopment/development-agenda/), adopted by all United Nations Member States in 2015, provides a blueprint for improving the economy, society, and the environment in a sustainable manner. At its heart, the 17 Sustainable Development Goals (SDGs) are a universal call to action to end poverty, protect the planet, and ensure that all people globally can enjoy peace and prosperity.  

The goals are underpinned by a framework of global indicators that allow Canada and other countries to monitor and report on progress. They cover a broad range of social, environmental, and economic issues with a focus on the most vulnerable and a commitment to “leave no one behind”. To complement the global goals, countries are encouraged to develop a national implementation plan that focuses on country-developed indicators to address specific national contexts and priorities to achieve the SDGs.  

To support Canada’s domestic implementation of the SDGs that the Government of Canada has committed to, a national strategy has been established. The development of a Canadian specific indicator framework was an opportunity to elaborate on the UN’s goal with a set of indicators that align more closely with Canada’s domestic priorities related to sustainable development.  

## Measuring Progress   
Measuring and monitoring progress with reliable information is key to understanding how Canada advances toward the achievement of the SDGs.  

Closely monitoring the progress of each indicator not only teaches us about Canada’s strengths and weaknesses, but also communicates a clear message to Canadians in an open and transparent manner. A robust measure of progress quantifies an indicator’s progress towards reaching the target in a scientific manner and can be indicative of the success of policies and actions taken to achieve those targets. It can also act as a clear signal to decision-makers to influence, readjust, or develop effective evidence-based policies in areas of focus to ensure Canada achieves its targets.  


## Methodology Adopted  
The Canadian Indicator Framework (CIF) lays the foundation for Canada to measure and report its progress on the 17 SDGs within the Canadian context; it will benefit from a robust methodology that will scientifically measure the overall progress accomplished based on existing data and provide an estimate of the amount of work still required to achieve each target and goal. Thus, Statistics Canada developed a robust and simple method of measuring progress, which will be reported using visualizations so that areas of success or weakness can be quickly and easily identified. Even in the absence of specific quantitative targets, an estimate of progress can inform whether undesired trends are being observed by reporting progress deterioration. In essence, this method of progress measurement will provide a simplified illustration of Canada’s progress toward achieving the SDGs, assuming that the current trends are maintained.  

### Requirements  
After a thorough review of existing methodologies to measure progress for the SDGs, Statistics Canada identified essential requirements for the adopted methodology, as well as eliminated undesirable features.  

The adopted methodology must:  
1. allow for different data periodicity and timeliness;  
2. provide a calculation for measuring progress in the absence of a specific numerical target;  
3. allow for the calculation of an aggregate measure.  

The adopted methodology cannot rely on:
1. the creation of targets (statistical, champion area/best performers, expert judgment);  
2. indicator-specific thresholds for progress categories;  
3. modelling;   
4. the existence of long time-series.  

### Methodology
The progress measure consists of a measure of observed growth compared to an evaluation of the proximity to achieving the target under current conditions. In situations where no quantitative target is provided, the time series is evaluated on the apparent trend of the data.  

Keeping in mind the limited number of data points in each time series and a desire to keep the methodology simple and transparent, the optimal candidate for measuring Canadian progress on the SDGs closely follows Eurostat’s methodology[^1].  

The growth over the observed period is calculated by a compound annual growth rate,  


(**INSERT IMAGE HERE**)  

where  
*CAGR*<sub>o</sub> is the observed compound annual growth rate between *t<sub>0</sub>* and *t<sub>i</sub>*     
*y<sub>ti</sub>* is the value of the indicator at time *t<sub>i</sub>*    
*t<sub>i</sub>* is the current year, i.e. the most recent year where data is available, and  
*t<sub>0</sub>* is the base year, 2015.  

#### Indicators with quantitative targets  
In the case where a quantitative target is provided, the observed *CAGR<sub>o</sub>* is compared to a theoretical *CAGR<sub>r</sub>*, which represent the growth required to achieve the target, by calculating the ratio (*R<sub>o/r</sub>*) as follows:  

(**INSERT IMAGE HERE**)  

where   

(**INSERT IMAGE HERE**)  

*x<sub>tT</sub>* is the target value of the indicator in the target year, *t<sub>T</sub>*.  
The result is compared against a set of thresholds[^2] and assigned a progress category, described below:   

| Ratio of observed over required growth rate | Category             |
|---------------------------------------------|----------------------|
| *R<sub>o/r</sub>* ≥ 95%                     | Substantial progress |
| 60% ≤ *R<sub>o/r</sub>* < 95%               | Moderate progress    |
| 0% ≤ *R<sub>o/r</sub>* < 60%                | Negligible progress  |
| *R<sub>o/r</sub>* < 0%                      | Deterioration        |

#### Indicators without quantitative targets  
In the case where no quantitative targets have been provided, *CAGR<sub>o</sub>* is compared to a pre-determined fixed growth rate. That threshold has been fixed at 1%.  

| Observed growth rate          | Category                  |
|-------------------------------|---------------------------|
| *CAGR<sub>o</sub>* > 1%       | Substantial progress      |
| 0% < *CAGR<sub>o</sub>* ≤ 1%  | Moderate progress         |
| -1% < *CAGR<sub>o</sub>* ≤ 0% | Moderate deterioration    |
| *CAGR<sub>o</sub>* ≤ -1%      | Significant deterioration |

### Aggregation at the Goal Level  
For summarizing progress measurement, the methodology developed by Eurostat is once again the preferred methodology. To calculate the measure of progress at the aggregated level (target, ambition or goal), the current measurement for each indicator is converted into a score, and then averaged at the aggregated level. Each indicator within a goal (or target) are equi-weighted. The score, both at the indicator and goal/target level, varies between -5 and 5[^3].  

#### Indicators without quantitative targets   
The scoring function for indicators without a quantitative target is a linear transformation of the CAGR thresholds described above. The cut-off points for a score of ±5 are set to ±2%, as illustrated in Figure 1 below.  

(**INSERT IMAGE HERE**)  

#### Indicators with quantitative targets  
The scoring function for indicators with a quantitative target reflects the thresholds used to categorize the indicators and uses cut-off values of 130% for a score of +5 and -60% for a score of -5. They are illustrated in Figure 2 below.  

(**INSERT IMAGE HERE**)  

### Considerations and Exceptions
Due to the nature of the data, a series of considerations and exceptions have been defined:  


1. Should there be no data in 2015, the first available year following 2015 will be used. Other exceptions regarding the first period of data availability will be treated and documented as they occur.  
   a. Indicators with two years as the reference period:  
      i. The first year will be used as the reference period, as they often refer to fiscal year (since most indicators are policy based). The first year is the last complete year.   
      ii.	Will be used if one of the years is 2015. For example, CIF indicator 3.2.1 starts in 2014-2015. For the purpose of the calculation, 2014 is used.  
   b. Even when the target results from a policy that was implemented after 2015, the base year for calculating the progress measure will be 2015 when data exists. This aligns with Statistics Canada quality dimensions coherence and comparability.  
2. Similar to (1), should the target year be March 20xx, then 20xx-1 will be used as the target year in the calculation as it is the last full year.  
3. If the target value is zero, it will be replaced by 0.001 in the calculation of the progress measure.  
4. In the absence of a specified target date, it is assumed that 2030 is the target period.  
5. Should the target year be in the past, the following will be done:  
   a. Calculate using the methodology with target until the target year (y);  
   b.	Continue calculating using the methodology with target, keeping the now obsolete target value and year;  
   c. Include a note explaining how to interpret the information.  
   d. Should a new target value and year be introduced, start using the new values in the calculation, and recalculate from *y+1* where applicable;  
   e. Include a note to users to explain the change.  
6. A minimum of 2 years of data is required to calculate the progress measure.  
7. In order to calculate the summary measure for a target/goal, a minimum of 60% of indicators for which it is possible to calculate a progress measure are needed.  
8. The progress estimates oversimplify the reality and should be interpreted with additional information or caution.  
9. The impact of policies takes time to be reflected in the data; the longer the time series, the better the progress measure will be.  
10. Indicators that start above the target at their base year for which progress then declines will be automatically overridden to “Deterioration”[^4].  
11. Binary indicators will be assigned one of the4se 2 categories:  
    a. "Target achieved" if "yes";  
    b. "Target not achieved" if "no".  
12. Specific exception: Indicator 5.3.1 Proportion of time spent on unpaid domestic and care work will be modify prior to calculation. A ratio of women/men will be used, with a desired target of 1.  


 
## Future Work  

In the short term, future work in this area includes the integration of the indicator-level progress measurement into the back-end of the Open SDG platform to be widely available for all Open SDG users. In the longer term, the aggregate measurement is also planned to be integrated into the platform.  

Furthermore, a revision of the base year in the methodology will be performed in 2024, coinciding with the CIF strategic review, to assess the replacement of the measure with long-term and short-term measures.  


## Metadata   

##### Canadian Indicator Framework  

| Indicator number | Indicator name                                                                                                                                                                | Desired direction |
|------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------|
| 1.1.1            | Poverty rate, as measured by Canada’s official poverty line                                                                                                                   | Decrease          |
| 1.2.1            | Prevalence of asset resilience                                                                                                                                                | Increase          |
| 2.1.1            | Prevalence of food insecurity                                                                                                                                                 | Decrease          |
| 2.2.1            | Index of Agri-Environmental Sustainability                                                                                                                                    | Increase          |
| 3.1.1            | Percentage of Canadians who report eating fruits and vegetables 5 or more times per day                                                                                       | Increase          |
| 3.2.1            | Prevalence of vaping among youth                                                                                                                                              | Decrease          |
| 3.3.1            | Percentage of the population that is overweight or obese                                                                                                                      | Decrease          |
| 3.4.1            | Prevalence of harmful alcohol use                                                                                                                                             | Decrease          |
| 3.5.1            | Percentage of Canadians who are satisfied or very satisfied with their life                                                                                                   | Increase          |
| 3.6.1            | Percentage of Canadians who perceived their overall health and social well-being as very good to excellent                                                                    | Increase          |
| 3.7.1            | Percentage of Canadians who perceived their mental health as very good to excellent                                                                                           | Increase          |
| 3.8.1            | Vaccination rates for selected diseases                                                                                                                                       | Increase          |
| 3.9.1            | Incidence of selected diseases                                                                                                                                                | Decrease          |
| 3.10.1           | Mortality rate for selected causes of death                                                                                                                                   | Decrease          |
| 3.11.1           | Tuberculosis incidence per 100,000 population in Inuit Nunangat                                                                                                               | Decrease          |
| 3.12.1           | Incidence of opioid and stimulant overdose related harms                                                                                                                      | Decrease          |
| 3.13.1           | Prevalence of cigarette smoking                                                                                                                                               | Decrease          |
| 4.1.1            | High school completion rate                                                                                                                                                   | Increase          |
| 4.2.1            | Post-secondary education attainment rate                                                                                                                                      | Increase          |
| 5.1.1            | Proportion of the population who self-reported being sexually assaulted in the last 12 months                                                                                 | Decrease          |
| 5.1.2            | Proportion of women and girls aged 15 years and older subjected to physical, sexual or psychological violence by a current or former intimate partner in the last 12 months   | Decrease          |
| 5.2.1            | Proportion of leadership roles held by women                                                                                                                                  | Increase          |
| 5.3.1            | Proportion of time spent on unpaid domestic and care work                                                                                                                     | Decrease          |
| 6.1.1            | Number of long-term drinking water advisories on public systems on reserves                                                                                                   | Decrease          |
| 6.2.1            | Percentage of municipalities across Canada with sustained drinking water advisories                                                                                           | Decrease          |
| 6.3.1            | Water use growth rate                                                                                                                                                         | Decrease          |
| 6.4.1            | Water quality in Canadian rivers                                                                                                                                              | Increase          |
| 7.1.1            | Annual energy savings resulting from adoption of energy efficiency codes, standards and practices                                                                             | Increase          |
| 7.2.1            | Total energy consumption per capita                                                                                                                                           | Decrease          |
| 7.3.1            | Proportion of electricity generated from renewable and non-greenhouse gas emitting sources                                                                                    | Increase          |
| 8.1.1            | Unemployment rate                                                                                                                                                             | Decrease          |
| 8.2.1            | Proportion of employees earning less than 66% of the median hourly wage for permanent full-time employees                                                                     | Decrease          |
| 8.3.1            | Proportion of youth not in education, employment or training                                                                                                                  | Decrease          |
| 8.4.1            | Rate of involuntary part-time work                                                                                                                                            | Decrease          |
| 8.5.1            | Gross domestic product per capita                                                                                                                                             | Increase          |
| 8.6.1            | Proportion of jobs in the environmental and clean technology products sector                                                                                                  | Increase          |
| 9.1.1            | Proportion of innovation in environment-related technology                                                                                                                    | Increase          |
| 9.2.1            | Gross domestic expenditure on research and development intensity                                                                                                              | Increase          |
| 9.3.1            | Proportion of households that have access to broadband Internet service at speeds of 50/10 Mbps                                                                               | Increase          |
| 9.4.1            | Proportion of Canadians that have access to the latest generally deployed mobile wireless technology                                                                          | Increase          |
| 9.5.1            | Greenhouse gas emissions per dollar of value-added from the production of infrastructure assets                                                                               | Decrease          |
| 9.6.1            | Number of low carbon recharging and refueling stations under development and completed along major highways, and in rural and urban areas across Canada                       | Increase          |
| 9.7.1            | Number of low carbon recharging and refueling stations under development and completed in public places, on-street, at apartment buildings, retail outlets, and the workplace | Increase          |
| 10.1.1           | Gini Coefficient                                                                                                                                                              | Decrease          |
| 10.2.1           | Proportion of the population reporting discrimination or unfair treatment                                                                                                     | Decrease          |
| 10.3.1           | Median hourly wage ratio                                                                                                                                                      | Increase          |
| 10.4.1           | Median household after-tax income                                                                                                                                             | Increase          |
| 11.1.1           | Growth rate of people experiencing chronic homelessness                                                                                                                       | Decrease          |
| 11.2.1           | Proportion of households in core housing need                                                                                                                                 | Decrease          |
| 11.3.1           | Percentage of the population living in areas where air pollutants concentrations are less or equal to the 2020 Canadian Ambient Air Quality Standards                         | Increase          |
| 11.4.1           | Percentage of the population living within 500 meters of a public transport stop                                                                                              | Increase          |
| 11.5.1           | Percentage of the population using shared or active transportation for commuting                                                                                              | Increase          |
| 11.6.1           | Total waste disposal per capita                                                                                                                                               | Decrease          |
| 11.7.1           | Percentage of the population aged 12 and over who reported their sense of belonging to their local community as being very strong or somewhat strong                          | Increase          |
| 12.1.1           | Proportion of new light duty vehicle registrations that are zero-emission vehicles                                                                                            | Increase          |
| 12.2.1           | Proportion of businesses that adopted selected environmental protection activities and management practices                                                                   | Increase          |
| 12.3.1           | Total waste diversion per capita                                                                                                                                              | Increase          |
| 13.1.1           | Greenhouse gas emissions                                                                                                                                                      | Decrease          |
| 13.2.1           | Frequency of selected natural disasters                                                                                                                                       | Decrease          |
| 13.3.1           | Proportion of municipal organization who factored climate change adaptation into their decision-making process                                                                | Increase          |
| 14.1.1           | Proportion of marine and coastal areas conserved                                                                                                                              | Increase          |
| 14.2.1           | Proportion of fish stocks that are sustainably harvested                                                                                                                      | Increase          |
| 15.1.1           | Proportion of native wild species ranked secure or apparently secure according to the national extinction risk level                                                          | Increase          |
| 15.2.1           | Proportion of species at risk showing progress towards their population and distribution objectives                                                                           | Increase          |
| 15.3.1           | Proportion of terrestrial (land and freshwater) areas conserved                                                                                                               | Increase          |
| 15.4.1           | Proportion of the forest area under an independently verified forest management certification scheme                                                                          | Increase          |
| 15.5.1           | Forest area as a proportion of total land area                                                                                                                                | No change         |
| 16.1.1           | Proportion of Canadians who reported feeling safe walking alone in their neighborhood after dark                                                                              | Increase          |
| 16.2.1           | Crime severity index                                                                                                                                                          | Decrease          |
| 16.3.1           | Incidence of selected types of crime                                                                                                                                          | Decrease          |
| 16.4.1           | Incidence of cybercrime                                                                                                                                                       | Decrease          |
| 16.5.1           | Criminal Court case completion time                                                                                                                                           | Decrease          |
| 16.6.1           | Incarceration rate                                                                                                                                                            | Decrease          |
| 16.7.1           | Proportion of the population with high levels of confidence in selected institutions                                                                                          | Increase          |
| 17.1.1           | Number of open datasets published by the Government of Canada                                                                                                                 | Increase          |
| 17.2.1           | Total official support for sustainable development                                                                                                                            | Increase          |


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
[^4]: This is a necessary measure to counteract a drawback of the formula: In situation where the target was achieved during the base period but deteriorated afterwards, the formula calculates significant progress as the indicator decreases (or increases) more ‘than it should’ to meet the target.  
