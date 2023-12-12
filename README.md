<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exploratory Data Analysis and Clustering of Music Dataset</title>
</head>
<body>

<h1>Exploratory Data Analysis and Clustering of Music Dataset</h1>

<h2>Data Cleaning and Exploration</h2>
<p>We conducted an exploratory analysis of the dataset, addressing missing values and removing unnecessary columns. The popularity distribution of songs revealed an average around 35, with most songs clustering around 0, suggesting low popularity or default values for unrated songs.</p>

<h2>Correlation Analysis</h2>
<p>A heatmap based on the correlation matrix showed significant correlations, such as 0.76 between loudness and energy, -0.73 between acousticness and energy, a moderate relationship of 0.48 between danceability and valence, -0.59 between acousticness and loudness, and a moderate correlation of 0.31 between explicit and speechiness. Only 8.6% of songs were identified as explicit.</p>

<h2>Feature Distributions</h2>
<p>Variables like danceability exhibited a normal distribution, indicating a mix of danceable and less energetic songs. The majority of songs had high energy values, while speechiness generally showed low values. Acousticness displayed more songs with lower values.</p>

<h2>Genre and Popularity</h2>
<p>A diverse range of genres was present, with the top 5 genres by average popularity being pop-film (59.28), k-pop (56.90), chill (53.65), sad (52.38), and grunge (49.59). Pop-film and k-pop stood out with consistently high-quality songs.</p>

<h2>Duration, Artists, and Tonality</h2>
<p>The average song duration was around 3 minutes, with exceptions. The artists with the highest popularity included Sam Smith with Kim Petras, Bizarrap with Quevedo, and Manuel Turizo. Most songs were in major tonality (72,681), while the rest were in minor tonality.</p>

<h2>Time Signature</h2>
<p>The majority of songs were in 4/4 time (101,842), followed by 3/4 time (9,195).</p>

<h2>Clustering Analysis</h2>
<p>Using clustering, two clusters provided the best results. We experimented with various clustering methods, first using danceability and energy, and then applying PCA. The results included a Silhouette Score of 0.3168, a Davies-Bouldin Index of 1.24, a Calinski-Harabasz Index of 46,119.85, and an Inertia of 405,819.16.</p>

<h2>Cluster Summaries</h2>
<p><strong>Cluster 1:</strong></p>
<ul>
  <li>High Energy</li>
  <li>High Danceability</li>
  <li>High Speechiness</li>
  <li>Low Acousticness</li>
  <li>High Valence</li>
</ul>
<p><strong>Cluster 2:</strong></p>
<ul>
  <li>Low Energy</li>
  <li>Low Danceability</li>
  <li>Low Speechiness</li>
  <li>High Acousticness</li>
  <li>Low Valence</li>
</ul>

<h2>Top Songs by Cluster</h2>
<p><strong>Cluster 1:</strong></p>
<p>"Unholy (feat. Kim Petras)" by Sam Smith;Kim Petras (Popularity: 100)</p>
<p><strong>Cluster 2:</strong></p>
<p>"Glimpse of Us" by Joji (Popularity: 94)</p>

<h2>Conclusion</h2>
<p>In conclusion, this comprehensive analysis of the music dataset has provided valuable insights into the diverse world of music. From understanding the distribution of popularity to exploring intricate correlations between musical features, this exploration unveils the complexity of factors influencing a song's reception.</p>

<p>The clustering analysis successfully categorized songs into distinct clusters based on key features, shedding light on the inherent patterns within the dataset. These clusters, characterized by their energy, danceability, and acoustic qualities, offer a nuanced perspective on the diverse musical landscape.</p>

<p>Whether you're a music enthusiast, data scientist, or industry professional, this exploration aims to spark curiosity and contribute to a deeper understanding of the multifaceted nature of music. As the dataset evolves and more insights emerge, this analysis serves as a foundation for further exploration and discovery in the realm of music data analytics.</p>

<p>Thank you for joining us on this journey through the melodies and patterns of the dataset. May the insights gained inspire further exploration and appreciation of the rich tapestry that is music.</p>

<p>Feel the rhythm, embrace the data, and let the melodies guide your curiosity!</p>

</body>
</html>
