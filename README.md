# Impact of Covid-19 on Clark County, Nevada

In this project we will explore the progression of the pandemic in Clark County, Nevada and also derive insights about the pandemic could have specifically impacted the toursim industry within this county (through the lens of publicly available Airbnb data).

## File Structure
```
.
├── README.md
├── License
├── data
│   ├── AirbnbCleanData
│   ├── AirbnbRawData
│   └── CovidRawData
│   │   └── covidcases
│   │   └── maskdata
├── conclusions_screenshots
│   ├── AvailabilityMap.png
│   ├── CovidProgressionTimeseries.png
│   ├── NeighborhoodsMap.png
│   ├── PriceAvailabilityTimeseries.png
│   ├── PriceMap.png
├── src
│   ├── A4 notebook.ipynb
│   ├── ExploratoryDataAnalysis.twb
│   ├── HypothesisTest.ipynb
│   └── TableauPrepCleaningSteps.hyper
└── submissions
    ├── A4.pdf
    ├── A5.pdf
    ├── A6.pdf
    └── A7.pdf
```

## License

The Johns Hopkins data is available under a creative [commons license](https://creativecommons.org/licenses/by/4.0/).

The New York Times mask compliance data is available under a [permissive license](https://github.com/nytimes/covid-19-data/blob/master/LICENSE) with proper attribution.

Inside Airbnb [data policies](http://insideairbnb.com/data-policies.html).

The CDC mask mandate data citation:
CDC, COVID-19 Community Intervention & Critical Populations Task Force, Monitoring & Evaluation Team, Mitigation Policy Analysis Unit, the CDC, Center for State, Tribal, Local, and Territorial Support, Public Health Law Program, and Max Gakh, Assistant Professor, School of Public Health, University of Nevada, Las Vegas, “U.S. State and Territorial Orders Requiring Masks in Public,” (August 15, 2021).

## Datasets
Inside Airbnb data: The data is a collection of Airbnb data that is publicly available on its website, across multiple cities. The data is aimed at providing a 360-degree insight into Airbnb’s presence in a city. [Dataset URL](http://insideairbnb.com/get-the-data.html).

The [RAW_us_confirmed_cases.csv file](https://www.kaggle.com/antgoldbloom/covid19-data-from-john-hopkins-university?select=RAW_us_confirmed_cases.csv) from the Kaggle repository of John Hopkins University COVID-19 data. This is where I got information about confirmed Covid-19 case counts.

The [CDC dataset](https://data.cdc.gov/Policy-Surveillance/U-S-State-and-Territorial-Public-Mask-Mandates-Fro/62d6-pm5i) of masking mandates by county. Here I got information about the dates during which a mask mandate was enforced in Clark county.

The New York Times [mask compliance survey data](https://github.com/nytimes/covid-19-data/tree/master/mask-use). This dataset provided information about mask mandate compliance probabilities.
    
## Conclusions
This research project helped us understand how the pandemic’s confirmed case counts progressed in Clark County, Nevada and how the mask mandates that were enforced, potentially helped in keeping the case counts lower. We also learned that most of the Airbnb listing in this county are unsurprisingly concentrated in the areas near Las Vegas. Visually we can see that the listings with a higher price point (closer to $500 per day) are also more concentrated around Las Vegas. We see that the median availability of these listings was at a low in December 2020 and then they increased in Q1 of 2021 before dropping again towards the end of the same quarter when concerns about the Delta variant and case counts increased. The prices and the availability of the listings then significantly increased starting in July 2021, which indicated a comfort of the Airbnb owners to host new guests and the increased willingness to travel of the tourists after vaccinations were rolled out throughout the country. This study helps us understand human centered data science as it fundamentally sheds light on questions about human behaviours and livelihoods during the pandemic. It shows us how human emotions of fear and decision making impact economies at a macro level and therefore the income of the people in that region.
