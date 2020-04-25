# kickstarter-analysis
Performing analysis on Kickstarter data to uncover trends

### Challenge

#### Outcomes Based on Goal
<img src="Outcomes Based On Goal.png"/>
<p>The plot shows a chart with the following three overlaid lines:</br>
<ul>
    <li>a blue line for the success rate vs. campaign goals of the kickstarter campaigns in the <i>Plays</i> subcategory</li>
    <li>an orange line for the failure rate vs. campaign goals of the kickstarter campaigns in the <i>Plays</i> subcategory</li>
    <li>a grey line for the cancellation rate vs. campaign goals of the kickstarter campaigns in the <i>Plays</i> subcategory</li>
</ul>

#### Outcomes Based on Launch Date
<img src="Outcomes Based on Launch Date.png"/>
<p>The plot shows a chart with the following three overlaid lines:</br>
<ul>
    <li>a gray line for the number of successes vs. launch date (month) of the kickstarter campaigns</li>
    <li>an orange line for the number of failures vs. launch date (month) of the kickstarter campaigns</li>
    <li>a grey line for the number of cancellations vs. launch date (month) of the kickstarter campaigns</li>
</ul>

### Observations

#### Outcomes Based on Goal

<p>The following observations can be made from the visualisation about the campaigns in the <i>Plays</i> category:
<ul>
    <li>The most successful campaigns fall into two distinct goal ranges: &lt;$1,000 up to $5,000, and $35,000 to $44,999</li>
    <li>The least successful campaigns fall into two distinct goal ranges: $25,000 to $34,999, and &ge;$45,000</li>
    <li>There a no plays campaigns that have been canceled</li>
</ul>

#### Outcomes Based on Launch Date

<p>The following observations can be made from the visualization:
<ul>
    <li>Most successful campaigns are launched in May, followed closely by June and July</li>
    <li>Most failed campaigns are also launched in May and October</li>
    <li>Campaign cancellation does not appear to be affected by launch date</li>
</ul>

### Inferrence
<p>A hypothesis that can be inferred from this visualisation is that, for a play campaign to be successful, it has to have a small goal which can be achieved with a small number of financiers or a medium sized goal which, with a reasonable amount of effort.</p>

### Further Investigation
<p>What still needs investigation is the success rate when the campaign goal and launch date are both taken into account and presented on a single graph. That plot would give a much better insight into finding the optimum combination of attributes that would result in the largest amount of donations.</p>

### Limitations and Suggestions for More Tables and Graphs
<p>The data does not specify the resources, human and otherwise, that were allotted to the campaigns. Including that information in the table could provide further insight into the amount of resources that need to be allotted in relation to the goal of the campaign.</p>
