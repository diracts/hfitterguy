# hfitterguy
How long is the next video going to be?

## The Plan
1) Scrape hbomberguy's youtube video metadata (upload date, view count, video length, etc.)
2) Plot the time series of interesting variables (view count, video length, etc.)
3) Try fitting with multiple reasonable functional forms (exponential, 1st-4th order polynomials, sigmoid, log, linear, etc.)
4) Analyze success of fit
5) Estimate uncertainty
6) Find most likely time of next upload (this will be more fitting)
7) Apply most likely time of next upload to video length projection
8) Fold all uncertainties into final video length guess

## Dependencies
 - Pandas
 - Numpy
 - Matplotlib
 - Seaborn
