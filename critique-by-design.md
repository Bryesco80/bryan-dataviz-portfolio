| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Are The OECD's Biggest Drinking Countries Cutting Back?
_Thought Process:_ 

I experimented with different visualization formats in Tableau, including tables and bar charts, to see which one would work best for my redesign. After trying different formats, I decided to use line charts because I thought they would be a good way to show how alcohol consumption changed over time. I wanted to compare alcohol consumption over a ten-year period to see which countries experienced an increase or decrease.

My first design included data from 2013 to 2023, but I noticed that the dataset contained over 50 countries. I thought including all of them would make the visualization too crowded and difficult to understand. Because of this, I decided to narrow it down to eight countries with high alcohol consumption levels.

For my second design, I decided to only show the consumption levels for 2013 and 2023 instead of including every year in between. I also added labels to show the exact values for each country. I thought this made it easier to see how much alcohol consumption had changed over the ten-year period.

For my final redesign, I kept the same format as my second sketch but made a few changes to make the visualization easier to understand. I added two different colors to show which countries experienced an increase or decrease in alcohol consumption. I also changed the order of the countries and updated the title and subtitle to better explain what the data was showing.

Something I found interesting was that alcohol consumption did not decrease in every country. Lithuania experienced a decrease from 14.5 to 11.0 litres per capita, while Latvia increased from 10.4 to 11.7 litres per capita. I thought this was interesting because it showed that the countries did not all follow the same trend.

I think my final redesign makes it easier to compare alcohol consumption between 2013 and 2023. By focusing on eight countries instead of showing all 50 or more, I was able to make the visualization less crowded. Using different colors also made it easier to identify which countries increased or decreased their alcohol consumption without having to compare every value individually.

## Step one: the visualization

Link: https://makeovermonday.vercel.app/dataset/2023w27
Data Source: https://www.oecd.org/en/data/indicators/alcohol-consumption.html

## Step two: the critique
_Question: Describe your overall observations about the data visualization here.  What stood out to you?  What did you find worked really well?  What didn't work well?_

_Answer: My overall observation for the data visualization was that it wasn't good. I had trouble understanding what the data visualization was trying to communicate. The title and the data visual contradict itself. The title of "Alcohol Consumption in OECD Countries" prompted me to think the data would show a comparison between OECD Countries. The dataviz showed a lot of lines, to represent OECD countries, but it left off the countries names and were colored grey. It also highlighted New Zealand, by highlighting its respective line with the color red, but I had no idea why it was highlighted compared to the other countries. I liked the title, y-axis (Alcohol Consumption measurement), and x-axis (Year). They're easy to understand and intuitive. It would help to have the type of measurement used on the y-axis for clarity._

_Question: Who is the primary audience for this tool?  Do you think this visualization is effective for reaching that audience?  Why or why not?_

_Answer: The primary audience for this tool is policy makers and public health officials in OECD countries. I do not think that the visualization is effective for reaching that audience because it doesn't include the names of countries in the data, except New Zealand. It would be hard to distinguish individual OECD countries in the data._

_Question: Based on your critique, what do you think you'll try to focus on in your redesign?   Any ideas or inspiration for how you can make a better data visualization?  What are you excited to try next?_

_Answer: Based on my critique, I will try to focus on communicating the data in a simpler way. My plan is to try to understand why New Zealand was highlighted in the data. If I can find why, I'll try to communicate that, so the reader can understand what the original data was trying to convey. I'd change the title and add a subtitle for more context. If I can't find the importance of New Zealand, I will likely change the visual to a horizontal bar chart to compare alcohol consumption in OECD Countries in an easier manner. I'll edit the bar charts to be in descending order. I will also add the names of the countries to each bar, rather than leaving them blank. I will also add the specific measurement used for alcohol consumption to the y-axis. I'm excited to see how the visual will look like after the formatted changes. I'm hoping to make the visualization easier to understand for the reader._

## Step three: Sketch a solution

_First sketch:_
![Original Visualization](Screenshot%202026-11-12%20220630.png)

_Second sketch:_
![Visualization Screenshot](Screenshot%202026-11-12%20221003.png)

## Step four: Test the solution

The feedback I received was positive about the story I was trying to tell with my visualization. Both people liked that I used different colors to show which countries experienced an increase or decrease in alcohol consumption. They thought this made it easier to understand what the data was showing.

One issue that came up was that they had a hard time understanding what the measurements represented. Even though I included liters per capita in the subtitle, it was not clear enough for them. Based on this feedback, I decided to include the measurement next to each value in my final redesign. I also kept the different colors because they both thought it was a good way to show the changes in alcohol consumption.

## Step five: build the solution
![Visualization Screenshot](Screenshot%202026-11-12%20225328.png)
<div class='tableauPlaceholder' id='viz1794537004003' style='position: relative'><noscript><a href='#'><img alt='Are The OECD&#39;s Biggest Drinking Countries Cutting Back?A comparison of alcohol consumpton in the eight highest-consuming OECD countries in 2023, showing how consumption has changed since 2013.  ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ma&#47;MakeOverMonday_17945369387150&#47;AreTheOECDsBiggestDrinkingCountriesCittingBack3&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='MakeOverMonday_17945369387150&#47;AreTheOECDsBiggestDrinkingCountriesCittingBack3' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ma&#47;MakeOverMonday_17945369387150&#47;AreTheOECDsBiggestDrinkingCountriesCittingBack3&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                <script type='text/javascript'>
  var divElement = document.getElementById('viz1794537004003');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

## References
_Makeover Monday. (2023). 2023 Week 27 dataset. https://makeovermonday.vercel.app/dataset/2023w27_
_OECD, Alcohol consumption indicator. https://www.oecd.org/en/data/indicators/alcohol-consumption.html_

## AI acknowledgements
_AI wasn't used to help me complete this assignment_

