This repo contains notebooks, raw results, and associated pubs_adj data for a follow-up to Zhang et al.'s 2023 Scientific Productivity as a Random Walk. 

There are ten models:

Naïve-GRW-Y, yearwise naïve fitted lognormal geometric random walk

Naïve-GRW-S, stagewise naïve fitted lognormal geometric random walk

AR(1)-GRW-Y, yearwise first-order autoregressive fitted lognormal geometric random walk

AR(1)-GRW-S, stagewise first-order autoregressive fitted lognormal geometric random walk

Hurdle-AR(1)-GRW-Y, yearwise first-order autoregressive fitted lognormal geometric random walk with a binary nil/not-nil Markov hurdle

Hurdle-AR(1)-GRW-P, first-order autoregressive fitted lognormal geometric random walk with a productivity-dependent binary nil/not-nil hurdle

Hurdle-AR(1)-GRW-PG-ZD, first-order autoregressive fitted lognormal geometric random walk with a productivity-dependent binary nil/not-nil hurdle, gamma-distributed restart productivity, and zero-duration-dependent restart dynamics

Hurdle-TGRW-PG-ZD, directly truncated fitted lognormal geometric random walk with a productivity-dependent binary nil/not-nil hurdle, gamma-distributed restart productivity, and zero-duration-dependent restart dynamics

Hurdle-AR(1)-PG-ZR-PAD, first-order autoregressive fitted lognormal geometric random walk with a probability-dependent binary nil/not-nil hurdle, gamma-distribution restart productivity, and zero-duration-dependent/activity-dependent restart dynamics

Hurdle-AR(1)-PG-ZR-PAD, first-order autoregressive fitted lognormal geometric random walk with a productivity-dependent binary nil/not-nil hurdle, gamma-distributed restart productivity, zero-duration/activity-dependent restart dynamics, and a scholat effect drawn from a normally distribution with 0-mean and centered-average-time-adjusted variance.

Notebooks for all eight are included, as well as supplemental notebooks for Markov analysis of empirical data

