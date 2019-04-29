# EKF
Learning EKF filters

This repo includes code that I am using to understand the differnet kind of Kahlman filters. Regular Kahlman filters for linear systems, Extended Kahlman filter for nonlinear systems, and Error Kahlman filters.


## Resources
- http://web.mit.edu/kirtley/kirtley/binlustuff/literature/control/Kalman%20filter.pdf
- http://biorobotics.ri.cmu.edu/papers/sbp_papers/integrated3/kleeman_kalman_basics.pdf High level slides with formatting errors

## Basic Kahlman Filter
The system consists of a state vector X, that is not directly observable. Observations are done using sensors whose values depend on X in a linear way, so the values of the observations Y can be described as Y = AX + n. The Y and X vectors can have different sizes. A is a rectangular matrix. AX is matric multiple, and n is gaussian noise vector (same size as Y), with a different mean and variance for each entry.

