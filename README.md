#  ![image](https://volcano.si.edu/includes/images/volcano_icon_24.png) Data_Analysis_with_Volcano_Data

<p dir="auto">
<a href="https://www.python.org" rel="nofollow"><img src="https://camo.githubusercontent.com/c676b5f90a1650624a0a9832d7954edda1db39ad3347d90c8c51e88ff2f92252/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f507974686f6e2d4646443433423f7374796c653d666f722d7468652d6261646765266c6f676f3d707974686f6e266c6f676f436f6c6f723d6461726b677265656e" alt="" data-canonical-src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&amp;logo=python&amp;logoColor=darkgreen" style="max-width: 100%;">
 </a> <a href="https://numpy.org" rel="nofollow"><img src="https://camo.githubusercontent.com/e4f918596bfc1a8746d3bf5426a212500a5b36b1e5c63869cbe65b071dcdb48a/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4e756d70792d3737374242343f7374796c653d666f722d7468652d6261646765266c6f676f3d6e756d7079266c6f676f436f6c6f723d7768697465" alt="" data-canonical-src="https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&amp;logo=numpy&amp;logoColor=white" style="max-width: 100%;"></a> <a href="https://pandas.pydata.org" rel="nofollow"><img src="https://camo.githubusercontent.com/5e18e9b742657f6921829e31b6ee09d5d345633d8680cf1881f637d8e7bc44f1/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f50616e6461732d3243324437323f7374796c653d666f722d7468652d6261646765266c6f676f3d70616e646173266c6f676f436f6c6f723d7768697465" alt="" data-canonical-src="https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&amp;logo=pandas&amp;logoColor=white" style="max-width: 100%;"></a><a href="https://matplotlib.org" rel="nofollow"><img src="https://camo.githubusercontent.com/b8f888055ab43caf0282c9c13b362891a9c8999c718c0ff304f293a31e6e5989/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6d6174706c6f746c69622d3131353537633f267374796c653d666f722d7468652d6261646765266c6f676f3d707974686f6e266c6f676f436f6c6f723d7768697465" alt="" data-canonical-src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&amp;logo=matplotlib&amp;logoColor=white" style="max-width: 100%;"></a>  
<a href="https://colab.research.google.com" rel="nofollow"><img src="https://camo.githubusercontent.com/ce254316621ae7180772f1e8355fd15d6258eda95d51897e76068d11e6fa7987/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f436f6c61622d4639414230303f7374796c653d666f722d7468652d6261646765266c6f676f3d676f6f676c65636f6c616226636f6c6f723d353235323532" alt="" data-canonical-src="https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&amp;logo=googlecolab&amp;color=525252" style="max-width: 100%;"></a>
<a href="https://seaborn.pydata.org" rel="nofollow"><img src="https://camo.githubusercontent.com/101be66de91539d76350fbbe304a613f954c675849f6325d1cce7eddf6b1f12d/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f507974686f6e2d736561626f726e2d626c75652e7376673f7374796c653d666c6174266c6f676f3d707974686f6e266c6f676f436f6c6f723d7768697465" alt="" data-canonical-src="https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&amp;logo=seaborn&amp;color=525252" style="max-width: 100%;"></a></p>


## Introduction
#### From wikipedia:
A volcano is a rupture in the crust of a planetary-mass object, such as Earth, that allows hot lava, volcanic ash, and gases to escape from a magma chamber below the surface.
A volcano is a rupture in the crust of a planetary-mass object, such as Earth, that allows hot lava, volcanic ash, and gases to escape from a magma chamber below the surface.
![image](https://scitechdaily.com/images/Mount-Redoubt-Eruption-scaled.jpg)
## Challenge
There are five sources of data for analizing the impact of the volcano eruptions, which county is more prone to this disaster and how to take measures to prevent it.The data has to be combined together to get broad insights for informed decision making.

The data is orginally from <a href="https://volcano.si.edu/" rel="nofollow">The Smithsonian Institution</a>

## Exploratory Data Analysis
Therefore, with the help of data  analysis and visualization, we can find trend about countries with most volcano occurences and look for measures to migitate against such disaster for future purposes. 


## Conclusions and Recommendations
In the volcano data (volcano.csv), 44.6% of all volcanic eruption occurences actually happened,other category includes volcanic eruption uncertain or there is unrest.
United states with the highest number of volcanic eruption since year dated 1883 should be paid attention to. Particular places such as Oregon and California which have the highest occurence in the country should be given attention. Stratovolcano volcano type has the highest occurence from the year stated

## Data Dictionary
# Volcano.csv
<table>
<thead>
<tr>
<th align="left">variable</th>
<th align="left">class</th>
<th align="left">description</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">volcano_number</td>
<td align="left">double</td>
<td align="left">Volcano unique ID</td>
</tr>
<tr>
<td align="left">volcano_name</td>
<td align="left">character</td>
<td align="left">Volcano name</td>
</tr>
<tr>
<td align="left">primary_volcano_type</td>
<td align="left">character</td>
<td align="left">Volcano type (see wikipedia above for full details)</td>
</tr>
<tr>
<td align="left">last_eruption_year</td>
<td align="left">character</td>
<td align="left">Last year erupted</td>
</tr>
<tr>
<td align="left">country</td>
<td align="left">character</td>
<td align="left">Country</td>
</tr>
<tr>
<td align="left">region</td>
<td align="left">character</td>
<td align="left">Region</td>
</tr>
<tr>
<td align="left">subregion</td>
<td align="left">character</td>
<td align="left">Sub region</td>
</tr>
<tr>
<td align="left">latitude</td>
<td align="left">double</td>
<td align="left">Latitude</td>
</tr>
<tr>
<td align="left">longitude</td>
<td align="left">double</td>
<td align="left">Longitude</td>
</tr>
<tr>
<td align="left">elevation</td>
<td align="left">double</td>
<td align="left">Elevation</td>
</tr>
<tr>
<td align="left">tectonic_settings</td>
<td align="left">character</td>
<td align="left">Plate tectonic settings (subduction, intraplate, rift zone) + crust</td>
</tr>
<tr>
<td align="left">evidence_category</td>
<td align="left">character</td>
<td align="left">Type of evidence</td>
</tr>
<tr>
<td align="left">major_rock_1</td>
<td align="left">character</td>
<td align="left">Major rock type</td>
</tr>
<tr>
<td align="left">major_rock_2</td>
<td align="left">character</td>
<td align="left">Major rock type</td>
</tr>
<tr>
<td align="left">major_rock_3</td>
<td align="left">character</td>
<td align="left">Major rock type</td>
</tr>
<tr>
<td align="left">major_rock_4</td>
<td align="left">character</td>
<td align="left">Major rock type</td>
</tr>
<tr>
<td align="left">major_rock_5</td>
<td align="left">character</td>
<td align="left">Major rock type</td>
</tr>
<tr>
<td align="left">minor_rock_1</td>
<td align="left">character</td>
<td align="left">Minor rock type</td>
</tr>
<tr>
<td align="left">minor_rock_2</td>
<td align="left">character</td>
<td align="left">Major rock type</td>
</tr>
<tr>
<td align="left">minor_rock_3</td>
<td align="left">character</td>
<td align="left">Minor rock type</td>
</tr>
<tr>
<td align="left">minor_rock_4</td>
<td align="left">character</td>
<td align="left">Minor rock type</td>
</tr>
<tr>
<td align="left">minor_rock_5</td>
<td align="left">character</td>
<td align="left">Minor rock type</td>
</tr>
<tr>
<td align="left">population_within_5_km</td>
<td align="left">double</td>
<td align="left">Total population within 5 km of volcano</td>
</tr>
<tr>
<td align="left">population_within_10_km</td>
<td align="left">double</td>
<td align="left">Total population within 10 km of volcano</td>
</tr>
<tr>
<td align="left">population_within_30_km</td>
<td align="left">double</td>
<td align="left">Total population within 30 km of volcano</td>
</tr>
<tr>
<td align="left">population_within_100_km</td>
<td align="left">double</td>
<td align="left">Total population within 100 km of volcano</td>
</tr>
</tbody>
</table>


## eruption.csv
<table>
<thead>
<tr>
<th align="left">variable</th>
<th align="left">class</th>
<th align="left">description</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">volcano_number</td>
<td align="left">double</td>
<td align="left">Volcano unique ID</td>
</tr>
<tr>
<td align="left">volcano_name</td>
<td align="left">character</td>
<td align="left">Volcano name</td>
</tr>
<tr>
<td align="left">eruption_number</td>
<td align="left">double</td>
<td align="left">Eruption number</td>
</tr>
<tr>
<td align="left">eruption_category</td>
<td align="left">character</td>
<td align="left">Type of eruption</td>
</tr>
<tr>
<td align="left">area_of_activity</td>
<td align="left">character</td>
<td align="left">Area of activity</td>
</tr>
<tr>
<td align="left">vei</td>
<td align="left">double</td>
<td align="left">Volcano Explosivity Index (0-8) see wikipedia above</td>
</tr>
<tr>
<td align="left">start_year</td>
<td align="left">double</td>
<td align="left">Start year</td>
</tr>
<tr>
<td align="left">start_month</td>
<td align="left">double</td>
<td align="left">Start month</td>
</tr>
<tr>
<td align="left">start_day</td>
<td align="left">double</td>
<td align="left">Start day</td>
</tr>
<tr>
<td align="left">evidence_method_dating</td>
<td align="left">character</td>
<td align="left">Evidence for dating volcano eruption</td>
</tr>
<tr>
<td align="left">end_year</td>
<td align="left">double</td>
<td align="left">End year</td>
</tr>
<tr>
<td align="left">end_month</td>
<td align="left">double</td>
<td align="left">End Month</td>
</tr>
<tr>
<td align="left">end_day</td>
<td align="left">double</td>
<td align="left">End day</td>
</tr>
<tr>
<td align="left">latitude</td>
<td align="left">double</td>
<td align="left">Latitude</td>
</tr>
<tr>
<td align="left">longitude</td>
<td align="left">double</td>
<td align="left">Longitude</td>
</tr>
</tbody>
</table>


## events.csv
<table>
<thead>
<tr>
<th align="left">variable</th>
<th align="left">class</th>
<th align="left">description</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">volcano_number</td>
<td align="left">double</td>
<td align="left">Volcano Unique ID</td>
</tr>
<tr>
<td align="left">volcano_name</td>
<td align="left">character</td>
<td align="left">Volcano name</td>
</tr>
<tr>
<td align="left">eruption_number</td>
<td align="left">double</td>
<td align="left">Eruption number</td>
</tr>
<tr>
<td align="left">eruption_start_year</td>
<td align="left">double</td>
<td align="left">Eruption start year</td>
</tr>
<tr>
<td align="left">event_number</td>
<td align="left">double</td>
<td align="left">Event number</td>
</tr>
<tr>
<td align="left">event_type</td>
<td align="left">character</td>
<td align="left">Event type</td>
</tr>
<tr>
<td align="left">event_remarks</td>
<td align="left">character</td>
<td align="left">Event remarks</td>
</tr>
<tr>
<td align="left">event_date_year</td>
<td align="left">double</td>
<td align="left">Event year</td>
</tr>
<tr>
<td align="left">event_date_month</td>
<td align="left">double</td>
<td align="left">Event month</td>
</tr>
<tr>
<td align="left">event_date_day</td>
<td align="left">double</td>
<td align="left">Event day</td>
</tr>
</tbody>
</table>


## tree_rings.csv
<table>
<thead>
<tr>
<th align="left">variable</th>
<th align="left">class</th>
<th align="left">description</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">year</td>
<td align="left">integer</td>
<td align="left">Year of observation CE</td>
</tr>
<tr>
<td align="left">n_tree</td>
<td align="left">double</td>
<td align="left">Tree ring z-scores relative to year = 1000-1099 (a <a href="https://en.wikipedia.org/wiki/Standard_score" rel="nofollow">z-score</a> is a measure of variability from the mean - either positive or negative)</td>
</tr>
<tr>
<td align="left">europe_temp_index</td>
<td align="left">double</td>
<td align="left">Pages 2K Temperature for Europe in Celsius relative to 1961 to 1990</td>
</tr>
</tbody>
</table>


## sulfur.csv
<table>
<thead>
<tr>
<th align="left">variable</th>
<th align="left">class</th>
<th align="left">description</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">year</td>
<td align="left">double</td>
<td align="left">Year w/ decimal CE</td>
</tr>
<tr>
<td align="left">neem</td>
<td align="left">double</td>
<td align="left">Sulfur detected in ng/g from NEEM - ice cores from Greenland, data collected from melting ice cores, data range was 500 to 705 CE</td>
</tr>
<tr>
<td align="left">wdc</td>
<td align="left">double</td>
<td align="left">Sulfur detected in ng/g from WDC - ice cores from Antartica, data collected from melting ice cores, data range was 500 to 705 CE</td>
</tr>
</tbody>
</table>
