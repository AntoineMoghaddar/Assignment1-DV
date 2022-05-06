# Data Visualizations - Assignment 1

### _The Era of Simulation & Visualization_ :rocket:

`@Author: Antoine A. Moghaddar` <br>
`@version: 1.1 Delta` <br>
`@Date_release: 05-05-2022` <br>

Welcome to the assignment of the Data Visualization 2022 course. The assignment of this year is composed from a
collaboration between the UTwente ESportsLab and the Creative Technology Data Visualization Course. Hence, the theme of
this years assignment is ESports with its focus on racing simulation. With this assignment, you will be participating in
a research currently being conducted by the ESportsLab. The results of your visualisations will be used for
evaluati<br><br>This document will provide you all the necessary information to proceed with this assignment.

[comment]: <> (Let's first start by getting the variables that correlate to your group number.)

[comment]: <> (<br>Please enter your group number --> <input type="number" id="teamid" name="teamid"/> <input type="submit" value="Request Group">)

## The Contents

1. Team
2. Background information
    1. The background of this collaboration
    2. The ESportsLab Research goal
3. The Assignment
    1. The Assignment
    2. The Datasets
    3. The assignment criteria
    4. Deliverables
4. Grading & Passing Criteria
5. Potential continuation of the assignment

## Team

| Name | Function | Contact Details |
| ----- | ----- | ----- |
| [Antoine Moghaddar] | Assignment Lead | a.a.moghaddar@student.utwente.nl | 
| [Andreas Kamilaris] | Course Lead | | 
| [Guido Bruinsma] | Spokesperson ESportsLab |  | 
| [Jannick Siderus] | Student Assistant|  | 

## Background Information

[todo] include information on ESports and Research

## The Assignment
For the assignment, several datasets are recorded. These recordings contain laps that have been driven by various drivers from all classifications.
As the level of expertise differs per driver, the datasets vary a lot, making analysis on these datasets more interesting.
The aim of these assignments is to identify differences in driver performance, to pinpoint the elements that require improvement and to obtain insights into specific driver performances.<br>


The assignment is subdivided into 6 sections. The aim for the first section of the assignment is to provide you with a
basic understanding of the composition of the dataset. Here you are asked to perform simple visualizations based on the
variables that you have been provided with. The second part of the assignment is to gain deeper knowledge on the variables, combine and compute variables and to put variables in a time sequence.
Continuing forward, the third assignment is on the comparison of the variables among different drivers over a specified time sequence

> The analysis that we will do in the assignments will be based Circuit Zandvoort. Later, in the last part of this assignment, you will get the opportunity to work with different circuits than Zandvoort.
> Circuit Zandvoort has a total of 3 Segments divided as follows
> ![Circuit Zandvoort](./Assets/zandvoort.png)

### Basic assignment criteria

- For the duration of this entire assignment, you are allowed to work in pairs,
- Every assignment section should be analysed and documented. <br>We want to have a clear reasoning why you chose the visualisation type and what the story is you want to tell with your visualisation,
- All axis should be labelled with a axis-name, a unit and a correct and logical tick,

> - This assignment is an assignment that you may do individually or in pairs. While it is not mandatory to work in pairs, we do urge you to work in pairs as otherwise the assigment might be a bit too much to handle.
> - We want to encourage you to play around with different visualisation types to enhance and brighten up the story you want to convey with your visualizations.

***

### The Assignment Sections

#### Assignment Section 1

> Within this first section, we lay the basic foundation of the assignment. The goal is to get you familiarized with the
> available elements and let you play with simple visualisations. This first assignment is, in its core, equal for all
> students. However, every student duo has received two different variables which should yield different types of
> visualisations. The dataset that can be used for this assignment is [TODO: insert dataset]. <br>Within this assignment, the x-axis is the performance element <br><br>
> Given the variables [V1] and [V2], visualize and analyse the following:<br>
> 1. Plot the two variables independently into two different visualizations.
     >

1. What is your analysis per variable? <br><br>

> 2. Plot the two variables dependently into one visualisation.
     >

1. How do these variables correlate to each other?

***

#### Assignment Section 2

> The second section of the assignment is about digging deeper into the driver performances. This is where we want to see
> the correlations and the key differences between (and within) laps and track segments. You have been provided with various datasets that
> each correlate to one specific driver and his/her performances. We want to display the variables [V1] and [V2] against the
> same variables from a differrent lap and/or segment. For your group, the datasets that you can use is [D1].
> <br>**TODO Check the assignment on correctness**
> 1. Lap Focused analysis
     >

1. Over the duration of a lap, what analysis can you deduce from [V1]? Show this within a visualization and explain what
   the potential causes for this behaviour are.

>     2. Over the duration of a lap, what analysis can you deduce from [V2]? Show this within a visualization and explain what the potential causes for this behaviour are.
>     3. Define the qualitatively "best lap". from this lap, analyse the causes and effects of [V1] and [V2].
>
>
> 2. Segment Focused Analysis
     >

1. Over the duration of a segment, what analysis can you deduce from [V1]? Show this within a visualization and explain
   what the potential causes for this behaviour are.

>     2. Over the duration of a segment, what analysis can you deduce from [V2]? Show this within a visualization and explain what the potential causes for this behaviour are.
>     3. Has the driver performed statistically better or worse compared to the segment averages? analyse the causes and effects of [V1] and [V2].<br>Deduce from this analysis the possible effects that can explain this behaviour

***

##### Assignment Section 3

> Within this assignment we want to obtain a new perspective from comparing multiple drivers to see how drivers behave
> and whether there can be defined a _standardized_ behaviour for certain events during a session. We want to analyse the
> differences among different drivers to gain insights in how one single driver behaves in certain situations and whether this behaviour
> is the most efficient way to behave. From this analysis, we want to set side-to-side a comparison of the behaviour of the second driver.
> For simplicity, we have recorded a set of different datasets containing data from multiple drivers with different skill levels.
> Every dataset contains a set of approximately 18 recorded laps which you may use freely to compare with.
>
> 1. Per lap, find out the effects of [V1] and [V2] of [Driver1] independently and dependently.
     >

1. How do the variables correlate to the final session result/Lap result?

>     2. Perform a brief analysis on the performance of [Driver1].
>     3. Perform step i and ii on [Driver2]
>
>
> 2. Analyse the differences in performance based on [V1] and [V2] from both drivers.
     >

1. What driver did better overall? Why is that?

>     2. Which sectors of both drivers can be used to teach the other to perform better?

***

##### Assignment Section 4

> In this section, we want to exploit the visualisations and analysis that we have made before and produce an insightful
> dashboard for the end-user. The aim of this assignment is to teach you have to tell a story with research that you have
> conducted
>
> 1. Create a set of 5 dashboards in which you summarize the previous three assignments. Each dashboard must have a unique story with a single aim. The visualisations used as the backbone must support your aim.
> 2. Dependent on the tool you are using, make this dashboard interactive in such a way that the end-user can modify the set to obtain more detailed insights.
>

***

##### Assignment Section 5

> This assignment follows up the previous `Assignment Section 4`. However, in this section we will focus on conveying a story from the dashboards.
> Hence, the main focus here is on presenting information, displaying data and providing insights without confusing the user.<br>
> In the previous assignment you had to create dashboards, or topic-focused substories. These substories will now be merged together to create one single story about the performance of the driver.
>
>
> Story requirements are defined as follows:
> - The flow of information must converge, meaning that a good story first provides general information to adjust and narrow down the focus later in the story on one specific topic.
> - Information topics must be consistent.
> - The story must be visually attractive and easily understandable.


***

##### Assignment Section 6

> Within this last assignment section, the opportunity is given to you to experiment with different datasets available.
> The conditions from the datasets of the aforementioned assignments were all equal
>
>
> - Car: Mclaren MP4
> - Circuit: Zandvoort, The Netherlands
> - Weather Conditions: Sunny weather, no wind
> - Environment: No Distractions
>
> For this assignment, we will provide you with a broad set of secondary datasets that each contain different environmental situations
> <br>The datasets that we have prerecorded are:
> - Dataset with drivers experiencing fatigue
> - Dataset from session on different track (Bahrein, Baku)
> - Dataset from session in wet conditions
> - Dataset with different genres of music
>     - [80's Music](https://open.spotify.com/playlist/5nnxLQhACp3U3CjdoEi2Qk?si=7c250b0f5eca4f17)
>     - [Classical Music](https://open.spotify.com/playlist/11KeuUZ95XYUqelml5Ygtf?si=e37cb75005c24bd0)
>     - [Hardstyle](https://open.spotify.com/playlist/0fsJ3E5Fs8X4J5MQ8DmhXa?si=b9386ec46a014554)
>
> Next to these datasets that we have provided, we will set the ESportsLab available for you to record your own dataset containing personalized conditions.<br>
> If you are interested in this, please contact [Antoine Moghaddar] to discuss the possibilities.
>
> With this assignment, we want to challenge you to generate a personalized story based on varying datasets.


***

## Grading & Passing Criteria

The grading criteria is defined as follows

| Section # | Minimal Requirements | # Points to obtain | 
| --------- | :----------- | :--------- |
| Section 1 | 1) Three "logical" data visualisations using two different variables,<br>2) A brief analysis on the output of each visualisation. | 10 Points |
| Section 2 | 1) At least 2 data visualisations on analysis between laps<br>2) At least 2 data visualisations on differences among track sectors<br>3) Textual analysis on differences between laps<br>4) Textual analysis on differences among sectors of one lap | 20 Points |
| Section 3 | 1) At Least Three Visual Analyses on differences between 2 drivers.<br> 2) Textual Analysis on visualisations | 30 Points |
| Section 4 | 1) A set of five dashboards<br>2) Complete visualizations including legends, axis names, axis units,... | 10 Points |
| Section 5 | 1) A story<br>2) Complete visualizations including legends, axis names, axis units,...  | 10 Points |
| Section 6 | 1) At least 4 visualizations on original datasets<br>2) The visualizations do not contain simple bar charts but rather are<br>built from meaningful visualization types  | 20 Points |

# Potential Continuation of the assignment

[//]: # (sources and references - These are not visible)

[Esports]: <https://www.utwente.nl/nieuws/2019/10/251292/esportslab-op-universiteit-twente>

[Andreas Kamilaris]: <>

[Antoine Moghaddar]: <https://www.linkedin.com/in/antoine-moghaddar-b9129180/>

[Guido Bruinsma]: <https://www.linkedin.com/in/guidobruinsma/>

[Jannick Siderus]: <https://www.linkedin.com/in/jannicksiderius/>

[V1]: <>

[V2]: <>

