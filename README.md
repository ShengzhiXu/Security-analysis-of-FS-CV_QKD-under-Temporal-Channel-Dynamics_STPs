Title: State Transition Probability (STP) Matrices for Turbulent FSO Channels

Description:
This dataset contains state transition probability (STP) matrices used in the analysis of time-varying free-space optical (FSO) channels under atmospheric turbulence. The matrices are constructed based on the methodology described in the main manuscript.

Each CSV file represents a discrete-time Markov chain model of the channel.

File List:

1. STP_matrix_strong_AO.csv
   STP matrix for strong turbulence conditions with adaptive optics (AO) compensation.

2. STP_matrix_strong_BL.csv
   STP matrix for strong turbulence conditions without adaptive optics (baseline case).

3. STP_matrix_weak_AO.csv
   STP matrix for weak turbulence conditions with adaptive optics (AO) compensation.

4. STP_matrix_weak_BL.csv
   STP matrix for weak turbulence conditions without adaptive optics (baseline case).

Data Format:

* Each file is in CSV format.
* Rows represent the current state.
* Columns represent the transition probabilities.
* Each row is normalized such that the sum of probabilities equals 1.

Notes:

* The number of states (K) and the state partitioning method are defined in the main manuscript.
* Channel parameters, including turbulence strength and system settings, are provided in the manuscript.
* AO denotes adaptive optics compensation, while BL denotes the baseline case without AO.

Usage:
These matrices can be directly used to simulate temporal evolution of the channel via a finite-state Markov chain, or to compute performance metrics such as time-dependent transmittance statistics and secret key rate (SKR).

Contact:
For questions regarding the dataset, please refer to the corresponding author of the manuscript.
