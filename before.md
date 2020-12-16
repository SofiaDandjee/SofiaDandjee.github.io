---
layout: default
title: Food for thought
---

<div id = menu align="center">
  <h1> ON THE MENU </h1>
  <li> What is the average diet of a Londoner? </li>
  <li> What constitues a healthy diet? </li>
  <li> How much does each area spend on food expenditure? </li>
  <li> How does the food diet relate on the area's wealth? </li>
</div>

Keeping a good and balanced diet is fundamental to having a healthy life as it helps avoiding food-related illnesses such as diabetes, obesity and cardiovascular diseases. However, the price of the food products influences greatly the decisions of individuals in purchasing them or not. There is a strong belief amongst consumers that more expensive products are healthier than cheaper ones, even this is not always true. Thus, we ask ourselves: do people have an equal chance in maintaining a nutritious diet and thus a healthy life?


### What is the average diet of a Londoner?

{% include piecharts.html %}

### What constitutes a healthy diet?

{% include correlations.html %}

<div align="center"> {% include barplots_score1.html %} </div>

<div align="center"> {% include barplots_score2.html %} </div>

<div align="center"> {% include scatter2D.html %} </div>


### What is the proportion of food related expenditure in each borough? How does it relate to its economic situation?

<iframe frameborder="1" class="juxtapose" width="350" height="400" marginwidth="500" align="center" src="https://cdn.knightlab.com/libs/juxtapose/latest/embed/index.html?uid=539588b2-3f8c-11eb-83c8-ebb5d6f907df"></iframe>

### How does a healthy diet relates to the borough's economic situation? Is this connection area-dependent?

{% include economicindicators_map.html %}

{% include scatter3d_plot.html %}

The detailed analysis of the project can be found <a href = "https://nbviewer.jupyter.org/github/SofiaDandjee/food_for_thought/blob/main/project.ipynb"> here </a>.
