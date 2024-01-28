| [Home](https://ncbartel.github.io/Portfolio/) | [Visualizing Debt](visualizing-government-debt) | [Critique by Design](critique-by-design) | [Final Project I](final-project-part-one) | [Final Project II](final-project-part-two) | [Final Project III](final-project-part-three) |
# OECD Government Debt Bar Chart 
<iframe src="https://data.oecd.org/chart/7kl9" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/7kl9" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2022</a></iframe>
Source: [OECD, 2023](https://data.oecd.org/gga/general-government-debt.htm)

# OECD Government Heat Map Table 
<div class='tableauPlaceholder' id='viz1706465583004' style='position: relative'>
<noscript><a href='#'><img alt='OECD Government Debt Table ' src='https:&#47;&#47;public.tableau.com&#47;
static&#47;images&#47;
OE&#47;OECDGovernmentDebt&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript>
<object class='tableauViz'  style='display:none;'>
<param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> 

<param name='embed_code_version' value='3' />

<param name='site_root' value='' />
<param name='name' value='OECDGovernmentDebt&#47;Sheet1' />

<param name='tabs' value='no' />
<param name='toolbar' value='yes' />

<param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;OE&#47;OECDGovernmentDebt&#47;Sheet1&#47;1.png' /> 
<param name='animate_transition' value='yes' />
<param name='display_static_image' value='yes' />

<param name='display_spinner' value='yes' />

<param name='display_overlay' value='yes' />
<param name='display_count' value='yes' />

<param name='language' value='en-US' />
<param name='filter' value='publish=yes' />
</object></div>                
<script type='text/javascript'>
    var divElement = document.getElementById('viz1706465583004');                    
    var vizElement = divElement.getElementsByTagName('object')[0];
    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
    var scriptElement = document.createElement('script');                    
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
    vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

Source: [OECD, 2023](https://data.oecd.org/gga/general-government-debt.htm)

<div class='tableauPlaceholder' id='viz1706476263186' style='position: relative'><noscript><a href='#'><img alt='OECD Debt by Country Over Time ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;OE&#47;OECDGovernmentDebt&#47;Sheet2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'>
<param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> 
<param name='embed_code_version' value='3' /> 
<param name='path' value='views&#47;OECDGovernmentDebt&#47;Sheet2?:language=en-US&amp;:embed=true&amp;publish=yes' /> 
<param name='toolbar' value='yes' />
<param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;OE&#47;OECDGovernmentDebt&#47;Sheet2&#47;1.png' /> 
<param name='animate_transition' value='yes' />
<param name='display_static_image' value='yes' />
<param name='display_spinner' value='yes' />
<param name='display_overlay' value='yes' />
<param name='display_count' value='yes' />
<param name='language' value='en-US' />
<param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>
var divElement = document.getElementById('viz1706476263186');
var vizElement = divElement.getElementsByTagName('object')[0];                    
vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
var scriptElement = document.createElement('script');                    
scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

Source: [OECD, 2023](https://data.oecd.org/gga/general-government-debt.htm)

When I was considering my options for the visualization, I wanted to display how it varies by country and using a map to do it with a heat map seemed like the most appropriate way to quickly view it. I added a time filter onto it to allow viewers to see how the percentage of debt to GDP changes over time. I chose a blue to red scale with blue being lower percentage reflecting a better debt to GDP ratio and red being a higher percentage reflecting a worse debt to GDP ratio. I chose red as it was an alert color for danger as having a high debt to GDP ratio would suggest. I opted to change the background map color to black to make the colors pop more and make null values not be attracting attention of the viewer. 

Additionally, I wanted to add an animated timeline to the map to show the year-to-year differences without needing to click through each year. I also opted to change the Debt to GDP to a dimension value instead of a sum or a minimum value since it was not accurately representing the value for that year. To help better reflect the year, I added the values on top of the respective country to show the smaller differences as well more easily.

Using this visualization, I found that the data reflected economic changes such as the economic crash in Japan that they were recovering from the 1990s until the early 2000s that impacted their debt to GDP ratio. Another interesting aspect visible by this is the impact of joining the EU for Greece and eventual collapse of their markets. With being able to search and select specific countries, it is possible to see how one, a few, or many countries/regions change over time.

---

# Summary of Different Visualizations:

Of the three visualizations, I believe that my least favorite was the bar chart from the OECD. This mainly was due to that it did not show the historical trends of the data and was in a grayscale with the only accented bar being the OECD global average. While looking at markets, it is helpful to be able to see both the historical and global trends of an economy which the bar chart is unable to represent that the heat map and the animated global map are both able to. 

The heat map was better than the bar chart since it added both historical and global elements that could be seen in one place. However, a critique on this was that, as the heat map in class showed, it was too busy with data. The color scheme was effective from blue being positive and orange being an alert color. However, I did not like the gray value in between the two which made places such as Japan or Greece essentially disappear in the wave of blue and orange. 

I chose an actual global map since the ISO county codes on the heat map take a bit to analyze for the viewer and do not show regional trends as easily as a map. I also chose an animated timeseries so the viewer could physically see how a country changed over time. A downside however to this feature is that is that you have to click through each year to see the data where the table can view it all at once. 