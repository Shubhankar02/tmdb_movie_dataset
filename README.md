<h1>Udacity Project: Investigate TMDB movie dataset</h1>
<hr>
<h2>Project Overview</h2>
<hr>
<p>
  This project is a part of Udacity's machine learning nanodegree foundation course. In this project we have to analyze the data set provided by kaggle. You can find more about this dataset <a href="https://www.kaggle.com/tmdb/tmdb-movie-metadata/home">Here.</a></p>
  <p><h3>Requirement:</h3></p>
  <ul>
  <li>Python - version 3x</li>
  <li>Numpy</li>
  <li>Pandas</li>
  <li>Matpotlib.payplot</li>
  </ul>
  <p>You can install Anaconda which comes with all the above packages plus jupyter notebook</p>
  <hr>
  <h3>Following methods are used in data-analysis</h3>
  <ul>
  <li>calculate(column) - This method takes the one argument. It take the column and find the maximum and minimum value and return the whole row associated with that label and concat these two column and return as dataframe.</li>
  <li>avg(column) - This method takes the one argument. It return the average value.</li>
  <li>sep(columns) - This method takes the one argument. It seperate the multiple values of the same column and return the count of individual value</li>
  <li>avg_values(column) - This method takes the one argument. It returns the average number of successful movies</li>
  <li>sep_profit(column) - This method takes the one argument. It is similar to sep(column), the only difference is, it is associated with the successful movies data</li>
  </ul>
  <p><strong>Note: </strong> The successful movies are those movies who made a profit more than the average profit made by all the movies.</p>
  <hr>
  <h3>The Following questions can be asked from the dataset</h3>
  <ul>
    <li>Movies which are highest and lowest in terms of:</li>
        <ul>
            <li>Profit</li>
            <li>Revenue</li>
            <li>Popularity</li>
            <li>Budget</li>
        </ul>
    <li>About movie cast and genres</li>
        <ul>
            <li>Top 5 genres of all the time</li>
            <li>Top 10 genres of all the time</li>
            <li>Top 5 cast of successful movies</li>
            <li>Top 10 genres of successful movies</li>
        </ul>
</ul>
  