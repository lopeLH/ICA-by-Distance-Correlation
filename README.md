# ICA by Distance Correlation
Blind Source Separation of two people talking at the same time with two simulated mics.

Intuitivelly, ICA finds the projection directions that minimize the statistical dependence of the resulting features. To ilustrate this, in this example we generate random projection directions and measure the statistical dependence of the resulting features with the distance correlation function (https://en.wikipedia.org/wiki/Distance_correlation).

The figure below shows ICA's projection directions (blue), the best randomly found directions so far (red) and the current directions being evaluated (orange), along with their corresponding distance correlations. This shows that ICA is indeed fact minimizing the statistical dependence of the resulting componnents.

  <img src="https://github.com/lopeLH/BlindSourceSeparation/blob/master/movie.gif?raw=true" width=650></img>

![alt text](https://github.com/lopeLH/BlindSourceSeparation/blob/master/movie.gif?raw=true)
