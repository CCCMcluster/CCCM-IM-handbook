# Communication
Introduction....
1. **Define your goal:** Why are you communicating your analysis?
    - give insight
    - inform on the topic
    - engage people in taking action
2. **Identify your target audience:** To whom you are delivering your communication?
    - cluster partners
    - affected population
    - HCT
    - donors
    - host government
3. **Choose the right communication media:** How do yoyu reach your audience?
    - reports
    - profiles
    - interactive exploratory dasboards
    - infographic
    - video
    - social media 
    - events
4. **Work on your message:** What do you want to communicate? 
    - background
    - supporting details
    - results/conclusions
    - bottom line
    - so what

<!--- Nancy Baron's Escape from the Ivory Tower --->
```{tip}
- Tell a story
- Choose hooks for your audience
- Say it visually
- Be transparent
```


## How to talk about numbers
...
## Data Visualization
...
### Visual Design Principles
...
### Choosing the right charts
When visualising your data, the choice of chart depends on the quantity and type of data you want to respresent; the relationships in that data, and ultimately, whether or not the graph clearly communicates your message.[^footnote1]

The following is pseudo-decision tree, to support choosing the most appropriate chart type depending on your data and it relationships.

#### Deviation
Emphasise variations (+/-) from a fixed reference point. Typically the reference point is zero but it can also be a target or a long-term average. Can also be used to show sentiment (positive/neutral/negative).

**Examples:** Showing the number of people entering or exiting a site over a period of time. Showing satisfaction with a component in a training. Demographics pyramid in a site, showing popuation breakdown by age and gender.

![Diverging bar](/part1/images/deviation1.png)  
**Diverging bar:** A simple standard bar chart that can handle both negative and positive magnitude values.

![Diverging stacked bar](/part1/images/deviation2.png)  
**Diverging bar:** Perfect for presenting survey results which involve sentiment (eg disagree/neutral/agree).

![Spine](/part1/images/deviation3.png)  
**Spine:** Splits a single value into two contrasting components (eg male/female).

![Surplus/deficit filled line](/part1/images/deviation4.png)  
**Surplus/deficit filled line:** The shaded area of these charts allows a balance to be shown – either against a
baseline or between two series.

#### Corellation
Show the relationship between two or more variables. Be mindful that, unless you tell them otherwise, many readers
will assume the relationships you show them to be causal (i.e. one causes the other).

**Examples:** Showing the relationships between areas of origin and current location of displacement.

![Scatterplot](/part1/images/corellation1.png)  
**Scatterplot:** The standard way to show the relationship between two continuous variables, each of which has its own axis.

![Column + line timeline](/part1/images/corellation2.png)  
**Column + line timeline:** A good way of showing the relationship between an amount (columns) and a rate (line).

![Connected scatterplot](/part1/images/corellation2.png)  
**Connected scatterplot:** Usually used to show how the relationship between 2 variables has changed over time.

![Bubble](/part1/images/corellation4.png)  
**Bubble:** Like a scatterplot, but adds additional detail by sizing the circles according to a third variable.

![XY heatmap](/part1/images/corellation5.png)  
**XY heatmap:** A good way of showing the patterns between 2 categories of data, less effective at showing fine differences in amounts.

#### Ranking
Use where an item’s position in an ordered list is more important than its absolute or relative value. Don’t be afraid to highlight the points of interest.

**Examples:** Comparing indicaotrs of need. Comparing displacement population figures across sites or districts.


### Use of Colour
...

[^footnote1]: Adapted from the FTs [Visual Vocabulary](http://ft-interactive.github.io/visual-vocabulary/). A similar graphics decision tree, based on the type and number of variables, is available at [Data-to-Viz.com](https://www.data-to-viz.com/#area)


