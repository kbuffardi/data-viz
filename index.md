[comment]: # (Compile this presentation with the command below)
[comment]: # (mdslides index.md && mv index/index.html .)
[comment]: # (THEME = night)
[comment]: # (CODE_THEME = base16/zenburn)
[comment]: # (The list of themes is at https://revealjs.com/themes/)
[comment]: # (The list of code themes is at https://highlightjs.org/)
[comment]: # (Pass optional settings to reveal.js:)
[comment]: # (controls: true)
[comment]: # (keyboard: true)
[comment]: # (progress: true)
[comment]: # (width: "1024")
[comment]: # (markdown: { smartypants: true })
[comment]: # (hash: false)
[comment]: # (respondToHashChanges: false)
[comment]: # (Other settings are documented at https://revealjs.com/config/)

### Data Visualization Workshop
----------

Dr. Kevin Buffardi, Professor, Chico State

<small>See this presentation at [learnbyfailure.com/data-viz/](https://learnbyfailure.com/data-viz/) and its source on [GitHub](https://github.com/kbuffardi/data-viz/).</small>

<img src="qr-data-viz.png" alt="QR code for this presentation" width="30%">
</img>

<small>[Back to LearnByFailure](https://learnbyfailure.com/research/)
</small>

[comment]: # (!!!)

#### Goals 

- Communicate meaning of data
  - Relationships
  - Comparisons
  - Distributions
  - Composition
- Interact and explore data

[comment]: # (!!!)

#### Modes of Visualization

- What is necessary?
  - **Tables** enable lookup of specific values
  - **Charts** provide nuance 
    - simplify multivariate visualization
  - **Interactive visualizations** provide custom control

[comment]: # (!!!)

#### Get to Know Your Data

- How many variables?
- Categorical
  - Qualitative data
  - Clusters
- Ordinal
  - Ordered, but not on numerical scale
    - "Strongly Disagree" to "Strongly Agree" Likert-type
- Numeric
  - Continuous
  - Discrete

[comment]: # (!!!)

#### Choosing the Right Chart

<a href="https://extremepresentation.typepad.com/files/choosing-a-good-chart-09.pdf" target="_blank">
<img src="extreme-presentation-chart.jpg" alt="Decision tree for choosing the right chart, via Abela">
</img>
</a>

[comment]: # (!!!)

#### Choosing the Right Colors

  - **Sequential** - vary only lightness/opacity
    - **Continuous** - continuous scale
    - **Discrete** - ordinal, discrete, or "buckets"

<a href="https://www.atlassian.com/data/charts/how-to-choose-colors-data-visualization" target="_blank">
  <img src="https://wac-cdn.atlassian.com/dam/jcr:f2340687-9e19-4859-9c2c-87465f001678/continuous-vs-discrete-choropleth.png?cdnVersion=2635" alt="Comparing continuous color scale vs. buckets">
  </img>
</a>

[comment]: # (|||)

#### Choosing the Right Colors

  - **Divergent** - vary between hues to signify magnitude and category

<a href="https://www.flerlagetwins.com/2019/04/predominance-maps.html" target="_blank">
  <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgnOr7w8BsVOBvofx12YOM3k0p0emSW5Z_hNNECGFH0lNbgqZ8vkQ3mYB7nhxslpw01c5oamv8LsrBaqUGE83AVXQOhrbTkGW5lSVKgkGYRtsHWrO3jgFfwxnUyMRsQLbV0L9UaqpMTsRKM/s1600/Heading.png" alt="Diverging scale illustrating voting preference by county in USA">
  </img>
</a>

[comment]: # (|||)

#### Choosing the Right Colors

  - **Categorical** - categorize by hue

<a href="https://analysisfunction.civilservice.gov.uk/policy-store/data-visualisation-colours-in-charts/" target="_blank">
  <img src="https://analysisfunction.civilservice.gov.uk/wp-content/uploads/2022/03/Clustered-bar-chart-new-order.svg" alt="Categorical scales for comparing fruit sales between multiple shops">
  </img>
</a>

[comment]: # (!!!)

#### Viz Sins

Common bad practices ("Viz Sins") 

  - Misrepresent data
  - Difficult to interpret

[comment]: # (|||)

#### Viz Sins: Colors

- Color scale does not match data type
  - Too close to differentiate
  - Ignoring Color Blindness
    - [Simulate Color Blindness](https://www.color-blindness.com/coblis-color-blindness-simulator/)
- Antidotes
  - [Color blind safe palettes](https://davidmathlogic.com/colorblind)
  - Redundant encoding data (shapes/patterns/size/etc.)

[comment]: # (|||)

#### Viz Sins: Axes

- Axes
  - Label scale and units
  - Avoid misleading "broken axis"
  - Unnecessary dimensions
- Linear vs Logarithmic scale

[comment]: # (|||)

#### Viz Sins: Where People Live

- Graphing by location
  - Population density is a dominant factor
  - [Reddit People Live in Cities](https://www.reddit.com/r/PeopleLiveInCities/)

[comment]: # (|||)

#### Viz Sins: Over-sliced Pie

- Pie charts with too many slices

<a href="https://www.atlassian.com/data/charts/how-to-choose-colors-data-visualization" target="_blank">
  <img src="https://wac-cdn.atlassian.com/dam/jcr:60eecca0-6c0b-406e-b491-be1c88fc619c/pie-chart-grouping-slices.png?cdnVersion=2635" alt="Contrasting pie chart with 12 slices versus one with 6">
  </img>
</a>

[comment]: # (!!!)

#### Interactive Visualizations

- Interaction gives control over visualization
- [Shneiderman's Information Seeking Mantra](https://www.cs.umd.edu/~ben/papers/Shneiderman1996eyes.pdf)
  - Overview first
  - Zoom and filter
  - Details on demand

[comment]: # (!!!)

#### Tools

- Charts
  - R [ggplot](https://ggplot2.tidyverse.org/)
  - Python [plotly](https://plotly.com/python/)
- Interactive visualizations
  - Shiny for [R](https://shiny.posit.co/py/docs/comp-r-shiny.html) or [Python](https://shiny.posit.co/py/)
  - [Tableau](https://www.tableau.com/)

[comment]: # (!!!)

#### Data Visualization Workshop

<small>This presentation is accessible at [learnbyfailure.com/data-viz/](https://learnbyfailure.com/data-viz/) and its source is available on [GitHub](https://github.com/kbuffardi/data-viz/).</small>

<img src="qr-data-viz.png" alt="QR code for this presentation" width="30%">
</img>

<small>[Back to LearnByFailure](https://learnbyfailure.com/research/)
</small>
