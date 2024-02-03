# Socio-economic-Factors-for-Geographic-Clustering
## Identifying the various clusters of countries that are more similar to each other than others, in terms of certain socio-economic factors.

#### We decide the number of clusters using a concept called Dendrogram which is a tree-like diagram that records the sequences of merges or splits.
<ul>
<li>Single Linkage Dendrogram</li></ul>

<img width="684" alt="image" src="https://github.com/shivam937/Socio-economic-Factors-for-Geographic-Clustering/assets/78429225/fcdeef60-5859-45d3-8d52-02cec2654088">

<ul>
<li>Average Linkage Dendrogram</li></ul>

<img width="684" alt="image" src="https://github.com/shivam937/Socio-economic-Factors-for-Geographic-Clustering/assets/78429225/e024a538-0571-45f2-8efb-bc6ba657f874">

<ul>
<li>Complete Linkage Dendrogram</li></ul>

<img width="681" alt="image" src="https://github.com/shivam937/Socio-economic-Factors-for-Geographic-Clustering/assets/78429225/29cac2ac-7704-40cb-b100-b8ffa06bc8b5">
<hr>

<ul>
 <li>We can see that the <i><b>complete linkage</b></i> gives better separated clusters. A cluster is considered better separated if the vertical distance connecting those clusters is higher.
  <li>Now, we can set a threshold distance and draw a horizontal line. The number of clusters will be the number of vertical lines which are being intersected by the line drawn using the threshold.
<li>The branches of this dendrogram are cut at a level where there is a lot of ‘space’ to cut them, that is where the jump in levels of two consecutive nodes is large
<li>Here, we can choose to cut it at ~10 since the space between the two nodes is largest.
<li>Now, dividing the cluster into 4 groups:</li></ul>

<img width="696" alt="image" src="https://github.com/shivam937/Socio-economic-Factors-for-Geographic-Clustering/assets/78429225/10d685a2-16bd-4ecf-9d6a-fee58df73ec2">


<ul>
  <li>Cluster analysis is an unsupervised technique that tries to identify subgroups among the observations that, with respect to certain characteristics, are similar to each other.</li>
  <li>All clustering techniques aim to group observations into subgroups/clusters so that:</li>
<ul>
  <li>Each cluster contains observations that are similar to each other. </li>
  <li>The cluster should be homogeneous with respect to certain clustering features.</li>
<li>The observations of one cluster are different from observations of other clusters. </li>
 <li>Each cluster is different from other groups with respect to the same characteristics.</li>
</ul>
</ul>



### 📖 Description
<hr>
<ul>
<li> This implementation is based on <b>Clustering Model</b>
<li> In this project we have used <b> Country Dataset</b> and <b>Hierarchical Clustering Algorithm</li>
</ul>


### ⌛ Dataset
<hr>
<ul>
<li> Download the dataset from given link
<li> https://drive.google.com/file/d/1_rcHoRSpwXxYw86KGf_hreHeu15eXgKh/view?usp=sharing
 </li>
</ul>

<b> Dataset info:</b>
<ul>
<li>country: Name of the country
<li>child_mort: Death of children under 5 years of age per 1000 live births
<li>exports - Exports in % of the GDP per capita
<li>health - The total spend on health given as % of GDP
<li>imports - The value of imports given as % of GDP per capita
<li>income - The net income per person
<li>inflation - Inflation rate %
<li>life_expec - Average life expectancy in years
<li>total_fer - The fertility rate - Average children per woman in the country
<li>gdpp - GDP per capita
</ul>


### 📋 Requirement
<hr>
<ul>
<li>Python 3.5</li>
<li>Jupiter Notebook</li>
<li>Pandas Library</li>
<li>Seaborn Library to visualize data</li>
<li>Sklearn Library</li>
</ul>


### 🧑‍💻 Contributor
<hr>
<b>Shivam Singh</b>
<ul>
<li> [💼 Linkedin] (https://www.linkedin.com/feed/)</li>
</ul>


<b>Thank You</b>

