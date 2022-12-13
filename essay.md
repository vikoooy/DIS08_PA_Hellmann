# Essay

## Short Introduction

I started this assignment by defining a topic I want to work on. There were several to choose: Veganism/Sustainability, Racism or Feminism were my favorite topics. I wanted to work on something meaningful to me. Personally, I always try to make a change in my behaviour to be as welcoming and respectful to other people. To ensure this it is important to know the structural problems in our society. This is what I wanted to perform my task on: learning a bit more on structural problems. 

## Description of my datasets

I looked for possible datasets and problems in every of these three main topics. I had an option for everything but finally I choose to work on feminism. 

The first dataset I found describes the proportion of women and men in the first leadership position across all states. I found this quite interesting but unfortunately this dataset hasn’t enough interesting information for me. So I digged a bit further and found two additional datasets with new information: one describes the proportion of women and men in the second leadership position and one shows the unadjusted gender pay gap. Because all of this information seemed interesting to combine, I choose those datasets for my assignment. 

### First dataset: proportion of women and men in the first leadership position across all states

This dataset is originally provided by the BMFSFJ, the “*Bundesministerium für Familie, Senioren, Frauen und Jugend*”, which translates to “*Federal Ministry for Family Affairs, Senior Citizens, Women and Youth*”. I found this dataset on govdata ([https://www.govdata.de/web/guest/suchen/-/details/oberste-fuhrungspositionen-in-der-privatwirtschaft-nach-geschlecht-und-landern](https://www.govdata.de/web/guest/suchen/-/details/oberste-fuhrungspositionen-in-der-privatwirtschaft-nach-geschlecht-und-landern)) but you can find the original source of the dataset here: [https://www.daten.bmfsfj.de/daten/daten/anteil-von-frauen-und-maennern-in-fuehrungspositionen-in-der-privatwirtschaft-oberste-ebene-131638](https://www.daten.bmfsfj.de/daten/daten/anteil-von-frauen-und-maennern-in-fuehrungspositionen-in-der-privatwirtschaft-oberste-ebene-131638) [downloaded at: 12/04/2022, 1:49 pm]

The BMFSFJ describes the variable first leadership position as following: 

- First leadership position are defined as: Management, the boards of directors, (store and operations) management and owners

The other variables of this dataset are: 

- State ID: the state ID is working like a key in this dataset. It’s in integer specific for the state. The data type is an integer. The chosen IDs are the following:
    
    
    | 08 | Baden-Württemberg |
    | --- | --- |
    | 09 | Bayern |
    | 11 | Berlin |
    | 12 | Brandenburg |
    | 04 | Bremen |
    | 06 | Hessen |
    | 13 | Mecklenburg-Vorpommern |
    | 03 | Niedersachsen |
    | 05 | Nordrhein-Westfalen |
    | 07 | Rheinland-Pfalz |
    | 10 | Saarland |
    | 14 | Sachsen |
    | 15 | Sachsen-Anhalt |
    | 01 / 02 | Schleswig-Holstein / Hamburg 1) |
    | 16 | Thüringen |
- State name: this columns provides the name of the states as you can see above. Additionally to those states there’s a row without a state ID which is called ‘Germany’, as this row contains the summed up data over all states per year. As you can see, the data for ‘Schleswig-Holstein’ and ‘Hamburg’ are accumulated. The data type is a string.
- Year: this column contains the following years: 2020, 2018, 2016, 2014, 2012 and 2008. The data type is an integer.
- Total number of workers in this position: this column contains information on how many workers are working in the first leadership position, so women and men are summed up. The data type is an integer.
- Total number of women in this position: this column contains the number of how many women are working in the first leadership position. The data type is an integer.
- Number of women in this position in percentage: this column takes the total number of women working in this position and calculates a percentage from the number of overall workers in this position. The data type is an integer.
- Total number of men in this position: the same as in the column ‘Total number of women in this position’ but only for men. The data type is an integer.
- Number of men in this position in percentage: also the same as in the column ‘TNumber of women in this position in percentage’ but only for men. The data type is an integer.

Furthermore the BMFSFJ provides following information on the dataset: 

- The data is collected by survey and workers are allowed to choose their position on their own
- Only companies with at least one employee subject to social insurance are included in the survey
- The private sector is delimited by legal form and industry
- Public corporations and so on are excluded, as are non-profit organizations, public administration, and agricultural and forestry operations

The collection period ranges from 2008 - 2020 but not every year in between is included as specified above. I wasn’t able to find out why there’s this bigger gap between 2008 and 2012, but data for 2010 is missing. 

As mentioned above I wanted to work on some feminist topic. This dataset is interesting for me because I knew there’s a gap in the number of women and men working in leadership positions but I didn’t know how much of a gap there is. I wanted to learn more about this topic. Knowledge in feminism and the structural problems in our society can be helpful to collect arguments and to raise awareness in discussions if necessary. It might also be helpful for me because at some time in the future I want to found a company on my own. To prevent my own company following existing structures it’s important to know that they exist. 

### Second dataset: proportion of women and men in the second leadership position across all states

This dataset is also provided from the BMFSFJ. I also found this one on govdata first ([https://www.govdata.de/web/guest/suchen/-/details/zweite-ebene-der-fuhrungspositionen-in-der-privatwirtschaft-nach-geschlecht-und-landern](https://www.govdata.de/web/guest/suchen/-/details/zweite-ebene-der-fuhrungspositionen-in-der-privatwirtschaft-nach-geschlecht-und-landern) ) and the original source can be found here: [https://www.daten.bmfsfj.de/daten/daten/anteil-von-frauen-und-maennern-in-fuehrungspositionen-in-der-privatwirtschaft-zweite-ebene-131652](https://www.daten.bmfsfj.de/daten/daten/anteil-von-frauen-und-maennern-in-fuehrungspositionen-in-der-privatwirtschaft-zweite-ebene-131652). [downloaded at: 12/04/2022, 2:15 pm]

This dataset is very similar to the first one, so I won’t describe the variables as detailed to prevent repeating myself and just copy-pasting the information from above. 

The BMFSFJ describes the second leadership position as following: 

- The second management level is the level directly below the "top management level”. They are referring to the first dataset I chose.

The other variables are the following: 

- State ID
- State name
- Year
- Total number of workers in this position
- Total number of women in this position
- Number of women in this position in percentage
- Total number of men in this position
- Number of men in this position in percentage

These columns contain the same information and data types, so the description from above are suitable for the columns in this dataset as well. 

Also the collection period is the same as in the first dataset. 

This dataset is interesting for me because I was curious on how the gap from the first leadership position might change in a position under this level. It helps on getting to know the structural problems in companies better as the gap doesn’t start at top level management but before. To ensure prevention structural changes need to happen before they exist so it’s important to know at which position problems occur. To get a better feeling for this I mostly used this dataset to compare the different numbers of women and men in this position per state and per year and mostly compared the numbers in percentage. 

### Third dataset: unadjusted gender pay gap

This dataset is also provided from the BMFSFJ. I also found this one on govdata first ([https://www.govdata.de/web/guest/suchen/-/details/verdienstunterschiede-von-frauen-und-mannern-nach-landern](https://www.govdata.de/web/guest/suchen/-/details/verdienstunterschiede-von-frauen-und-mannern-nach-landern)) and the original source can be found here: [https://www.daten.bmfsfj.de/daten/daten/verdienstunterschiede-von-frauen-und-maennern-unbereinigter-gender-pay-gap-nach-laendern-132012](https://www.daten.bmfsfj.de/daten/daten/verdienstunterschiede-von-frauen-und-maennern-unbereinigter-gender-pay-gap-nach-laendern-132012). [downloaded at: 12/04/2022, 2:38 pm]

The BMFSFJ states that the calculation is based on the definition of the gender pay gap from the european union as following: “The calculation includes dependent employment relationships of all economic sections and establishment sizes, with the exception of the economic sections "Agriculture, forestry, fishing", "Public administration, defense, social security", "Private households with domestic staff" and "Extra-territorial organizations and corporations" as well as establishments with fewer than ten employees.” [C].

This dataset contains the following variables: 

- State ID: the State ID is also working like a key in this dataset. The IDs are defined the same as in the other two datasets. Data type is an integer.
- State name: this column contains the names of the states plus an additional row ‘Germany’ for the summed up data over all states. Important to know is that in this dataset the data for ‘Schleswig-Holstein’ and ‘Hamburg’ are not accumulated. The data type is a string.
- Year: this column contains the following years: 2021, 2020, 2019, 2018, 2017, 2016, 2015, 2014, 2010, 2007. This data type is an integer.
- Pay Gap in Percentage: this column contains the unadjusted gender pay gap in percentage per state and year. This data type is an integer.

The column year contains some missing data for some years in between the existing ones but I also wasn’t able to find out why this is. 

As described above, this dataset contains information on the gender pay gap. This is a phenomenon which describes that women and men working in the same positions are getting different salaries; women usually earn less than men. It is calculated as the difference between the average gross hourly earnings of men and women in relation to the gross hourly earnings of men [A]. There is a difference between the adjusted and the unadjusted gender pay gap: 

“The adjusted gender pay gap is calculated on the basis of the Structure of Earnings Surveys (SES), which are published every four years. It calculates the part of the pay gap that is attributable to structural differences between women and men. These include, for example, differences in the scope of employment, professional experience or level of education. It thus shows the difference in earnings between women and men who have comparable qualifications, employment histories and occupations. 

The unadjusted gender pay gap, on the other hand, generally measures the average earnings of all employees. It therefore does not take into account any wage-determining factors and is generally around three times as large as the adjusted value.” [A]. 

There’s a big discussion on which gender pay gap needs to be looked at, the adjusted or the unadjusted. 

As you can see in the definition above, the adjusted gender pay gap takes account of wage-determining factors such as parental leave or qualification. The unadjusted gender pay gap on the other hand doesn’t have a look at these factors, which is why it’s often criticised due to overestimating actual earnings gap and inaccurately. Personally, I think it’s important to have a look at both but to keep in mind that the factors considered in the adjusted gender pay gap are also due to structural changes, e.g. women leaving more often for parental leave than men and therefore don’t have the same chances on an equal pay as this leave isn’t necessary the preferred choice of women [B].

I would’ve preferred to take both pay gaps into my comparison, but on the three platforms provided for a dataset to choose I could only find the unadjusted gender pay gap so I will be working with this one. 

The collection period ranges from 2007 to 2021.

I combined the gender pay gap per state and year with the information on the number of women and men working in leadership positions per state and year because I thought it’s interesting to have another measurement. This way I was able to have a look at how structural problems may change over the course of years and how it differs in states. 

### Conceptualisation of my application

As described above I wanted to have a look at how the different positions and how the gender pay gap changes over time and how it differs in states. My steps are documented and explained in the code in detail but I want to give a brief summary on my steps and thoughts here.

To start with my task, I first needed to perform some data cleaning. By reading in the xlsx files the first few rows doesn’t contain useful information as they are more like filler rows in the original file, so I needed to delete them. After deleting them, I needed to define a useful header row. 

After doing this, I recognised the different years included in the datasets. Because I wanted to compare the data per year I needed to adjust the data. To do so I looked which years are included in every dataset, which are: 2020, 2018, 2016 and 2014, so I dropped the other years. 

The next thing I realised was the accumulated data from ‘Schleswig-Holstein’ and ‘Hamburg’ in the two datasets containing information on the leading positions. For a proper comparison I needed to accumulate those data in the gender pay gap dataset. To do so, I extracted the rows for the states, summed up the numbers, dropped the original rows and included the new rows to the original dataset. I also needed to rename the values in the rows so the naming and the state ID would match the other datasets. 

After that I started my analysis. I was curious on the data so I started some explorative-data-analysis-like process. To do so, I wanted to join the datasets and found the .merge() function. After some reading I recognised that this function works similar to a join in sql. Due to the lecture in databases I’m currently taking I felt comfortable doing this and was curious how this looks like in Python. I like how easy to use this is if you have at least one column you could use as a key. Fortunately my datasets contain the state ID which is a perfect fit for the merge to work. After trying this merge only by state ID I recognised some strange merging, which is due to the different years the datasets contain the state IDs four times. To perform a clear merge I chose to also use the year as a key, and after finding that out the merge worked perfectly fine with my data. 

After merging the datasets with the first and second leading positions I added two columns to the merged dataset: I calculated the difference between women and men in these two positions to compare these. I recognised that some of these values are >0, which is when more women than men are working in these positions (e.g. in Mecklenburg-Vorpommern in 2020). I didn’t find a good solution for this outlier so I left it as that. 

I ended my analysis by looking at different numbers, which I will present here: 

- the highest gender pay gap was in Baden-Württemberg in 2014 with 27 % (the newest average gender pay gap is from 2021 at 18 % [D])
    - I first used the dataset with the accumulated data, but due to the accumulation of course the accumulated data showed the highest gender pay gap. Because this isn’t reality I performed this task on the original dataset.
- the lowest gender pay gap was in Sachsen-Anhalt in 2016 with 4 %
- the highest gap in first and leadership positions was in Bayern in 2016 with 63.4 % for the highest position and 32.8 % in the second highest position. It’s interesting that these two values happen to be in the same row.

After analysing, I started with some visualisations of the gender pay gap over years and the percentages of women and men working in positions over years. 

My last step was to include some ipywidgets to get an interactive analysis. My idea was to include filters on years and states. I read through their documentation but wasn’t able to implement these on my own, so I read through a tutorial [E] and followed it. I marked this code as copied just to make sure, but I tried following in implementing the steps on my own instead of copy-pasting to properly learn this because I think this widgets might be valuable for me for future tasks. Now you can filter the datasets by year, then by state and in a third implementation by both. To use these filters you need to run the display(output) lines first as documented in the code. 



[A]: [https://de.statista.com/statistik/daten/studie/1220561/umfrage/bereinigter-gender-pay-gap-in-deutschland/#:~:text=Unterschied zwischen bereinigtem und unbereinigtem GPG&text=Somit zeigt er den Verdienstunterschied,den Durchschnittsverdienst aller Arbeitnehmer%3Ainnen](https://de.statista.com/statistik/daten/studie/1220561/umfrage/bereinigter-gender-pay-gap-in-deutschland/#:~:text=Unterschied%20zwischen%20bereinigtem%20und%20unbereinigtem%20GPG&text=Somit%20zeigt%20er%20den%20Verdienstunterschied,den%20Durchschnittsverdienst%20aller%20Arbeitnehmer%3Ainnen), 12/13/2022, 1:10 pm 

[B]: [https://www.bpb.de/themen/arbeit/arbeitsmarktpolitik/318555/geschlechterungleichheiten-gender-pay-gap/#:~:text=Der unbereinigte Gender Pay Gap,um so Verzerrungen zu minimieren](https://www.bpb.de/themen/arbeit/arbeitsmarktpolitik/318555/geschlechterungleichheiten-gender-pay-gap/#:~:text=Der%20unbereinigte%20Gender%20Pay%20Gap,um%20so%20Verzerrungen%20zu%20minimieren). 12/13/2022, 1:22 pm

[C]: [https://www.daten.bmfsfj.de/daten/daten/verdienstunterschiede-von-frauen-und-maennern-unbereinigter-gender-pay-gap-nach-laendern-132012](https://www.daten.bmfsfj.de/daten/daten/verdienstunterschiede-von-frauen-und-maennern-unbereinigter-gender-pay-gap-nach-laendern-132012) 12/13/2022, 1:26 pm

[D]: [https://www.destatis.de/EN/Press/2022/03/PE22_088_621.html#:~:text=Press release No.&text=WIESBADEN – Women in Germany earned,compared with the previous year](https://www.destatis.de/EN/Press/2022/03/PE22_088_621.html#:~:text=Press%20release%20No.&text=WIESBADEN%20%E2%80%93%20Women%20in%20Germany%20earned,compared%20with%20the%20previous%20year). 13/12/2022, 2:09 pm

[E]: [https://towardsdatascience.com/bring-your-jupyter-notebook-to-life-with-interactive-widgets-bc12e03f0916](https://towardsdatascience.com/bring-your-jupyter-notebook-to-life-with-interactive-widgets-bc12e03f0916) 12/07/2022, 2:23 pm

Other sources I used during the coding journey: 

[https://stackoverflow.com/questions/17071871/how-do-i-select-rows-from-a-dataframe-based-on-column-values](https://stackoverflow.com/questions/17071871/how-do-i-select-rows-from-a-dataframe-based-on-column-values)  

[https://www.askpython.com/python-modules/pandas/update-the-value-of-a-row-dataframe](https://www.askpython.com/python-modules/pandas/update-the-value-of-a-row-dataframe). 

[https://stackoverflow.com/questions/11346283/renaming-column-names-in-pandas](https://stackoverflow.com/questions/11346283/renaming-column-names-in-pandas) 

[https://stackoverflow.com/questions/43136137/drop-a-specific-row-in-pandas](https://stackoverflow.com/questions/43136137/drop-a-specific-row-in-pandas) 

[https://www.askpython.com/python-modules/pandas/update-the-value-of-a-row-dataframe](https://www.askpython.com/python-modules/pandas/update-the-value-of-a-row-dataframe) 

[https://www.geeksforgeeks.org/how-to-add-one-row-in-an-existing-pandas-dataframe/](https://www.geeksforgeeks.org/how-to-add-one-row-in-an-existing-pandas-dataframe/) 

[https://stackoverflow.com/questions/34227038/python-pandas-merge-keyerror](https://stackoverflow.com/questions/34227038/python-pandas-merge-keyerror) 

[https://www.geeksforgeeks.org/how-to-add-column-from-another-dataframe-in-pandas/](https://www.geeksforgeeks.org/how-to-add-column-from-another-dataframe-in-pandas/) 

[https://jupyter-tutorial.readthedocs.io/de/latest/workspace/pandas/combining-merging.html](https://jupyter-tutorial.readthedocs.io/de/latest/workspace/pandas/combining-merging.html) 

[https://stackoverflow.com/questions/41815079/pandas-merge-join-two-data-frames-on-multiple-columns](https://stackoverflow.com/questions/41815079/pandas-merge-join-two-data-frames-on-multiple-columns) 

[https://de.acervolima.com/loschen-sie-zeilen-aus-dem-datenrahmen-basierend-auf-einer-bestimmten-bedingung-die-auf-eine-spalte-angewendet-wird/](https://de.acervolima.com/loschen-sie-zeilen-aus-dem-datenrahmen-basierend-auf-einer-bestimmten-bedingung-die-auf-eine-spalte-angewendet-wird/) 

[https://ciksiti.com/de/chapters/11540-divide-two-columns-pandas](https://ciksiti.com/de/chapters/11540-divide-two-columns-pandas) 

[https://www.geeksforgeeks.org/how-to-drop-one-or-multiple-columns-in-pandas-dataframe/](https://www.geeksforgeeks.org/how-to-drop-one-or-multiple-columns-in-pandas-dataframe/) 

[https://de.acervolima.com/so-loschen-sie-eine-oder-mehrere-spalten-in-pandas-dataframe/](https://de.acervolima.com/so-loschen-sie-eine-oder-mehrere-spalten-in-pandas-dataframe/) 

[https://www.geeksforgeeks.org/display-the-pandas-dataframe-in-table-style/](https://www.geeksforgeeks.org/display-the-pandas-dataframe-in-table-style/) 

[https://www.codegrepper.com/tpc/delete+header+row+from+dataframe+python](https://www.codegrepper.com/tpc/delete+header+row+from+dataframe+python) 

[https://statologie.de/nan-zeilen-loeschen-pandas/](https://statologie.de/nan-zeilen-loeschen-pandas/) 

[https://databasecamp.de/python/pandas-grundlagen-2](https://databasecamp.de/python/pandas-grundlagen-2) 

[https://statologie.de/excel-dateien-pandas/](https://statologie.de/excel-dateien-pandas/) 

[https://ipywidgets.readthedocs.io/en/stable/](https://ipywidgets.readthedocs.io/en/stable/)

[https://jakevdp.github.io/PythonDataScienceHandbook/03.07-merge-and-join.html](https://jakevdp.github.io/PythonDataScienceHandbook/03.07-merge-and-join.html)