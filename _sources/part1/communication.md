# Communication
Introduction....

## How to write about numbers
When preparing to write up an analysis, it is important to first consider the following:  
**Determine your objectives.** Is the intention to inform or update a group on recent activities? Is it to provide insight on a particular topic? Is it to change peoples understanding or decisions on an particular operational issue? Is it to engage with people to gather feedback or to take action?  
**Identify your target audience.** What group or groups are you targeting with the above objectives? You will need to tailor the language(non technical experts may not be familiar with technical language), length (shorter messages may be more suitable for general public consumption) and style (different audiences have different lenses in which they will consume and interpret your message).

There are seven basic principles about writing about numbers: [^footnote5]  
1. **Establish the context for your facts.**  

2. **Pick simple, plausible examples.**  

3. **Select the right tools and media  for the job.** The three basic tools for presenting quantitative information: prose, tables and charts. Choosing the most appropriate tool (or mix of them) and understanding their strengths and weaknesses, is important. Equally important is to use the most appropriate mix of media. Eg. Reports, interactive dashboards, infographics, video, social media, events.  

4. **Defining your terms (and be careful with jargon).** Unnecessary use of of acronyms and jargon will likely exclude parts of your audience or cause misunderstanding due to unshared understanding of concepts. If acronyms must be used, it is good practice to show them alongside their long form at the point where they first appear.  

5. **Reporting and interpreting.**  

6. **Specify direction and magnitude of an association.**  

7. **Summarize patterns.**

```{tip}
- Tell a story
- Choose hooks for your audience
- Say it visually
- Be transparent with the limitations of your analysis
```

## Data Visualization
...

### Choosing the right charts
When visualising your data, the choice of chart depends on the quantity and type of data you want to represent; the relationships in that data, and ultimately, whether or not the graph clearly communicates your message.[^footnote1]

The following is pseudo-decision tree, to support choosing the most appropriate chart type depending on your data and it relationships.

#### Deviation
Emphasize variations (+/-) from a fixed reference point. Typically the reference point is zero but it can also be a target or a long-term average. Can also be used to show sentiment (positive/neutral/negative).

**Examples:** Showing the number of people entering or exiting a site over a period of time. Showing satisfaction with a component in a training. Demographics pyramid in a site, showing population breakdown by age and gender.

```{dropdown} Deviation chart examples
![Diverging bar](/part1/images/deviation1.png)  
**Diverging bar:** A simple standard bar chart that can handle both negative and positive magnitude values.

![Diverging stacked bar](/part1/images/deviation2.png)  
**Diverging bar:** Perfect for presenting survey results which involve sentiment (eg disagree/neutral/agree).

![Spine](/part1/images/deviation3.png)  
**Spine:** Splits a single value into two contrasting components (eg male/female).

![Surplus/deficit filled line](/part1/images/deviation4.png)  
**Surplus/deficit filled line:** The shaded area of these charts allows a balance to be shown – either against a
baseline or between two series.
```
#### Correlation
Show the relationship between two or more variables. Be mindful that, unless you tell them otherwise, many readers
will assume the relationships you show them to be causal (i.e. one causes the other).

**Examples:** Showing the relationships between areas of origin and current location of displacement.

```{dropdown} Correlation chart examples

![Scatterplot](/part1/images/corellation1.png)  
**Scatterplot:** The standard way to show the relationship between two continuous variables, each of which has its own axis.

![Column + line timeline](/part1/images/corellation2.png)  
**Column + line timeline:** A good way of showing the relationship between an amount (columns) and a rate (line).

![Connected scatterplot](/part1/images/corellation3.png)  
**Connected scatterplot:** Usually used to show how the relationship between 2 variables has changed over time.

![Bubble](/part1/images/corellation4.png)  
**Bubble:** Like a scatterplot, but adds additional detail by sizing the circles according to a third variable.

![XY heatmap](/part1/images/corellation5.png)  
**XY heatmap:** A good way of showing the patterns between 2 categories of data, less effective at showing fine differences in amounts.
```

#### Ranking
Use where an item’s position in an ordered list is more important than its absolute or relative value. Don’t be afraid to highlight the points of interest.

**Examples:** Comparing indicators of need. Comparing displacement population figures across sites or districts.
```{dropdown} Ranking chart examples
![Ordered bar](/part1/images/ranking1.png)  
**Histogram:** Standard bar charts display the ranks of values much more easily when sorted into order..

![Ordered column](/part1/images/ranking2.png)  
**Ordered column:** Same as above but more suited to categories of dates or with short labels.

![Ordered proportional symbol](/part1/images/ranking3.png)  
**Ordered proportional symbol:** Use when there are big variations between values and/or seeing tne differences
between data is not so important..

![Slope](/part1/images/ranking4.png)  
**Slope:** Perfect for showing how ranks have changed over time or vary betweencategories.

![Lollipop](/part1/images/ranking5.png)  
**Lollipop:** Lollipops draw more attention to the data value than standard bar/column and can also show rank and
value ef effectively.

![Bump](/part1/images/ranking6.png)  
**Bump:** Effective for showing changing rankings across multiple dates. For large datasets,consider grouping lines
using colour.
```
#### Distribution
Show values in a dataset and how often they occur. The shape (or ‘skew’) of a distribution can be a memorable way of highlighting the lack of uniformity or equality in the data.

**Examples:**  
```{dropdown} Distribution chart examples
![Histogram](/part1/images/distribution1.png)  
**Histogram:** The standard way to show a statistical distribution - keep the gaps between columns small to highlight the ‘shape’ of the data.

![Dot plot](/part1/images/distribution2.png)  
**Dot plot:** A simple way of showing the change or range (min/max) of data across multiple categories.

![Box plot](/part1/images/distribution3.png)  
**Box plot:** Summarise multiple distributions by showing the median (centre) and range of the data.

![Population pyramid](/part1/images/distribution4.png)  
**Population pyramid:** A standard way for showing the age and sex breakdown of a population distribution;
effectively, back to back histograms.

![Beeswarm](/part1/images/distribution5.png)  
**Beeswarm:** Use to emphasise individual points in a distribution. Points can be sized to an additional variable.
Best with medium sized datasets.
```

#### Change over time
Give emphasis to changing trends. These can be short (intra-day) movements or extended series traversing decades or centuries: Choosing the correct time period is important to provide suitable context for the reader.  

**Examples:**  
```{dropdown} Change over time chart examples
![Line](/part1/images/changeovertime1.png)  
**Line:** The standard way to show a changing time series. If data are irregular, consider markers to represent
data points.

![Column](/part1/images/changeovertime2.png)  
**Column:** Columns work well for showing change over time - but usually best with only one series of data at a time.
```

#### Magnitude
Show size comparisons. These can be relative (just being able to see larger/bigger) or absolute (need to see fine differences). Usually these show a ‘counted’ number (for example, barrels, dollars or people) rather than a calculated rate or per cent.  

**Examples:**  
```{dropdown} Magnitude chart examples
```

#### Part-to-whole
Show how a single entity can be broken down into its component elements. If the reader’s interest is solely in the size of the components, consider a magnitude-type chart instead.

**Examples:**  
```{dropdown} Part-to-whole chart examples
```

#### Spatial
Aside from locator maps only used when precise locations or geographical patterns in data are more important to the reader than anything else.

**Examples:**
```{dropdown} Spatial chart examples
```

#### Flow
Show the reader volumes or intensity of movement between two or more states or conditions. These might be logical sequences or geographical locations.

**Examples:**  
```{dropdown} Flow chart examples
```

### Visual Design Principles
Developed by German psychologists, the Gestalt laws describe how we interpret the complex world around us. They explain why a series of flashing lights appear to be moving. And why we read a sentence like this, *notli ket his ort hat*. Understanding these "laws" can be useful in making sure your message is being conveyed effectively.

#### Law of Similarity.
...
#### Law of Pragnanz
...
#### Law of Proximity
...
#### Law of Continuity
...
#### Law of Closure
...
#### Law of Common Region
...


### Use of Colour
When choosing colours in your charts its important to understand possible local significance that may be associated to a specific colour. For instance, in one country a colour may signify good luck, whereas in a different country, the same colour could be associated with a non-state armed group.[^footnote4]

Where possible, special attention should be taken to ensure that chart remain readable when printed in gray scale and that they are colour blind safe, meaning that the chart should not be confusing for people with red-green colour blindness (an estimated 8% of men and 0.4% of women).

Adding to the previous description of the role of color in perception, the use of colour in scales, particularly maps, typically takes one of the following three forms.[^footnote2]  

1. ![Sequential](/part1/images/sequential-scale.png) **Continuous(sequential) scales** used to show values going from low to high. Eg. population density per district.

2. ![Diverging](/part1/images/diverging-scale.png) **Diverging scales**  which visualize difference from a norm, such as [this example](https://storymaps.arcgis.com/stories/a371cdf9462b4dca9051b9f60a3185bc) showing location in St Vincent that showed both net inward and outward movements of people following the eruption of a volcano.

3. ![Qualitative](/part1/images/qualitative-scale.png)**Categorical(qualitative) scales** used to distinguish different (non numeric) objects eg. a map using different shades for different countries.

Two of the most common ways to respresent colour are RGB and CMYK. RGB, commonly used on websites can be shown as a hex number or RGB number. For printed materials where colour accuracy is important, CYMK is typically used. Not all software supports the CMYK colour space, so if color accuracy is important you may want to use an Adobe tool such as Illustrator or In Design to apply finishing touches to print materials.[^footnote3]

## Presenting
Having a great data collection system, doing great analysis and creating effective visuals don't necessarily lead to informing or changing decision by themselves. An important skill for IMOs that is often overlooked is the importance of verbal communication and presentation skills, be in in an in-person context such as a Cluster meeting or as is becoming more common, web-based calls. These meeting offer an important window of opportunity where, if communicated clearly and in a convincing manner a good analysis can meet it's objectives.

The following video is an example of effective communication, where the speaker shows a clear understanding of his audience(s), succinctly describes the context, the cause, the call for action (giving specific examples) and the urgency and scale.
<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/PQNmfBY9HRo?controls=0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


When presenting slides, consider the following:  
* ***Only one idea per slide*** Having multiple ideas presented will distract your audience and confuse your key message.  
**Explain your point, then show slide.** Your audience can interpret either the visuals on screen or your spoken message. It is very difficult to both at the same time.  

* **Speaker is the star, not the slides.** The slides exist to aide the communication of the speaker, not to distract from it.

* **Never read from the slides.** It portrays a lack of preparedness and dilutes the communication rather than complimenting it.

* **Keep your hands free to move.** Not verbal expression can help the audience relate to the message and can help emphasise key messages.

* **Tell a story to drive home your message** Conveying your message through a narrative is a powerful way to introduce your audience with your key points, for them to engage with the topic and to remember it.

* **Use photos and drawings on slides.** Photos can help bring an emotive human element into otherwise abstract messages. Effective visuals can communicate concepts that would be much harder to explain through written or spoken word alone.

* **Face your audience, not your slides.** You are trying to convince, your audience, not the slides.

* **Avoid complexity.**  Unnecessary complexity is a barrier for comprehension and can cause your audience to disengage with the topic.

* **Rehearse, rehearse, rehearse.**

[^footnote1]: Adapted from the FTs [Visual Vocabulary](http://ft-interactive.github.io/visual-vocabulary/). A similar graphics decision tree, based on the type and number of variables, is available at [Data-to-Viz.com](https://www.data-to-viz.com/#area)

[^footnote2]: [Colorbrewer](https://colorbrewer2.org/) is a good resource for picking color palettes. [Datawrapper](https://blog.datawrapper.de/which-color-scale-to-use-in-data-vis/) have a good blog post describing the use of different colour scales. 

[^footnote3]: For a detailed explanation of RGB and CMYK and how they differ, see [here](https://en.99designs.ch/blog/tips/correct-file-formats-rgb-and-cmyk/)

[^footnote4]: ACAPS have a great guide on the [Use of Colour in Data Display](https://www.acaps.org/use-colour-data-display)

[^footnote5]: Adapted from The Chicago Guide to Writing about Numbers, by Jane E. Miller