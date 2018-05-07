# Topic-Model-and-Clustering

### Overview

Text is the necessary format that carry a lot of info. In this project, we are going to focus on the text documents, and implement clustering model to goup the unlabeled documents as well as identify the topics based on the documents we collected.

### Dataset

In our dataset, we had 100 movies with titles, wikis, reviews info collected from an online post.

### Content

Part 1: Load Data

Part 2: Tokenizing and Stemming

Part 3: TF-IDF

Part 4: K-means clustering

Part 5: Topic Modeling - Latent Dirichlet Allocation

### Result

##### K-MEANS Cluster

Based on the sample output, we could see that the movies are clustered together based on the TF-IDF matrix.
At the same time, we could see how many movies are clustered in the same group, and their average rank for each cluster.

<div>

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>rank</th>
      <th>title</th>
      <th>cluster</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>1</th>
      <td>0</td>
      <td>The Godfather</td>
      <td>1</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1</td>
      <td>The Shawshank Redemption</td>
      <td>1</td>
    </tr>
    <tr>
      <th>1</th>
      <td>2</td>
      <td>Schindler's List</td>
      <td>1</td>
    </tr>
    <tr>
      <th>2</th>
      <td>3</td>
      <td>Raging Bull</td>
      <td>2</td>
    </tr>
    <tr>
      <th>1</th>
      <td>4</td>
      <td>Casablanca</td>
      <td>1</td>
    </tr>
    <tr>
      <th>3</th>
      <td>5</td>
      <td>One Flew Over the Cuckoo's Nest</td>
      <td>3</td>
    </tr>
    <tr>
      <th>1</th>
      <td>6</td>
      <td>Gone with the Wind</td>
      <td>1</td>
    </tr>
    <tr>
      <th>4</th>
      <td>7</td>
      <td>Citizen Kane</td>
      <td>4</td>
    </tr>
    <tr>
      <th>1</th>
      <td>8</td>
      <td>The Wizard of Oz</td>
      <td>1</td>
    </tr>
    <tr>
      <th>4</th>
      <td>9</td>
      <td>Titanic</td>
      <td>4</td>
    </tr>
  </tbody>
</table>
</div>


Number of films included in each cluster:


<div>

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>cluster</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>2</th>
      <td>38</td>
    </tr>
    <tr>
      <th>1</th>
      <td>25</td>
    </tr>
    <tr>
      <th>4</th>
      <td>19</td>
    </tr>
    <tr>
      <th>0</th>
      <td>11</td>
    </tr>
    <tr>
      <th>3</th>
      <td>7</td>
    </tr>
  </tbody>
</table>
</div>

 Average rank (1 to 100) per cluster:

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>rank</th>
    </tr>
    <tr>
      <th>cluster</th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>47.636364</td>
    </tr>
    <tr>
      <th>1</th>
      <td>42.960000</td>
    </tr>
    <tr>
      <th>2</th>
      <td>52.342105</td>
    </tr>
    <tr>
      <th>3</th>
      <td>59.428571</td>
    </tr>
    <tr>
      <th>4</th>
      <td>49.842105</td>
    </tr>
  </tbody>
</table>








