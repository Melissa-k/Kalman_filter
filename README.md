# Kalman_filter
## Implementation of Kalman filter in C++ and python. 1D and multidimensional Kalman filter are investigated. 
A vast majority of modern systems are supplied with numerous sensors. These sensors provide estimation of hidden (unknown) variables based on the series of measurements. For example, the GPS receiver provides the location and velocity estimation, where location and velocity are hidden variables and differential time of satellite's signals arrival are the measurements.

Providing accurate and precise estimation of the hidden variables when there is uncertainty is one of the biggest challenges of tracking and control system. In the GPS receiver, the measurements uncertainty depends on many external factors such as thermal noise, atmospheric effects, slight changes in satellite's positions, receiver clock precision and many more. 

Among the significant toolbox of mathematical tools that can be used for stochastic estimation from noisy sensor measurements, one of the most well-known and often-used algorithms is the Kalman filter.  The  Kalman  filter  is  named  after Rudolph E. Kalman, who in 1960 published his famous paper describing a recursive solution to the discrete-data linear filtering problem [1].

The  Kalman  filter is essentially a set of mathematical equations that implement a predictor-corrector type estimator that  is optimal in the sense that it minimizes the estimated error covariance when some presumed conditions are met. Simply put, The Kalman Filter produces estimates of hidden variables based on inaccurate and uncertain measurements. As well, the Kalman Filter provides a prediction of the future system state, based on the past estimations. 

Since it is the time of its introduction, the Kalman filter has been the subject of extensive research and application, particularly in the  area  of  autonomous or assisted navigation. This is likely due in large part to advances in digital computing that made the use of  the filter practical, but also to the relative simplicity and robust nature of the filter itself. A complete tutorial about Kalman filtering is given in [2].

## I.1 Mathematical Formulation of Kalman Filter

## References
[1] R.  E.  Kalman.  1960.  “A  New  Approach  to  Linear  Filtering  and  Prediction Problems,” Transaction of the SME-Journal of Basic Engineering, pp. 35-45 (March 1960).

[2] G.  Welch  and  G.  Bishop.  1995.  “An  Introduction to  the  Kalman  Filter” University of North Carolina, Department of Computer Science, TR 95-041. 

[3] https://arxiv.org/ftp/arxiv/papers/1204/1204.0375.pdf

[4] https://www.kalmanfilter.net/default.aspx
