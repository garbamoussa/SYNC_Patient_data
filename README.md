
<h1 align=center>Synthetic Data Generation via Gaussian Copula : SYNC Patient data</h1>


<h2 align=center>Synthetic Data Generation via Gaussian Copula : SYNC Patient data :</h2>

<h3>Author: </h3>

GARBA Moussa, PhD<br>


<h2>Research Question</h2>

### Objective:


#  healthcare data - Project

- Problem: 1. Assuming we are given only these summary values, how do we reconstruct/trace back the data for each patient, on each one of the variables "trt" "age" "bmi" "gender" "response", particularly if we are additionally informed that some patients have missing values in one or more of those variables?.

- Problem 2. How do we measure the accuracy between the reconstructed data and the original data?. In this case, we have access to the original individual data, so if we have the methodology to measure the difference between the reconstructed and the original data, we can do so and then try it with other simulated data to see how robust our approach is.


# Synthetic Data Generation via Gaussian Copula : SYNC 
- The central idea of SYNC is to fit Gaussian copula models to each of the low- resolution datasets in order to correctly capture dependencies and marginal distributions, and then sample from the fitted models to obtain the desired high-resolution subsets.

- Synthetic data is a data object that is artificially created rather than collected from actual events. It is widely used in applications like harmonizing multiple data sources or augmenting existing data. 

- Downscaling :  efficiently produce high quality data, generate high-resolution data (e.g., individual level records) from multiple low-resolution sources (e.g., averages of many individual records).

- Practitioners often find individual level data far more appealing, as aggregated data lack information such as variances and distributions of variables. 

- Downscaled synthetic data to be useful :  it needs to be *fair* and *consistent*.

- Fair : simulated data should mimic realistic distributions and correlations of the true population as closely as possible. 

- Consistent : downscaled samples, the results need to be consistent with the original data. 


SYNC (Synthetic Data Generation via Gaussian Copula) to simulate microdata by sampling features in batches. The concept is motivated by [Copula-based approach to synthetic population generation] and [Dependence-preserving approach to synthesizing household characteristics]. 


The rationale behind SYNC  is that features can be segmented into dis- tinct batches based on their correlations, which reduces the high dimensional problem into several sub-problems in lower dimensions.

Feature dependency in high dimensions is hard to evaluate via common methods due to its complexity and computation requirements, and as such, Gaussian copula, a family of multivariate distributions that is capable of capturing dependencies among random variables, becomes an ideal candidate for the application.

## Datasets


## Methodology 



