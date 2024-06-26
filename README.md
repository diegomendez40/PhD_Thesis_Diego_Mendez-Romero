# PhD Thesis on Neural-Kalman Schemes

Neural-Kalman Schemes -- a new AI scheme enhancing wireless communications!

These novel Neural-Kalman Schemes can revolutionize abrupt change detection.

Not just in wireless communications, but also e.g. **in finance** (see Chapter 9 for financial applications!). *You can detect any new global trends earlier* -- close to immediately -- with these techniques and [I intend to prove it](https://github.com/diegomendez40/GlobalAbruptChangeDetection).

## Getting Started

For an explanation of Neural-Kalman schemes, see the main pdf, `PhD_Thesis_Diego_Méndez_Romero_v1.pdf`, and the accompanying viva slides, `Neural-Kalman Schemes for Channel Tracking and Learning_v0.074.pptx`, or watch `Video explanation for NNFK (IEEE presentation).mp4`.

## Repository Structure

This repository will include the original and expanded versions of code and publications related to the development of Neural-Kalman schemes for channel tracking and learning, as proposed in Diego Méndez Romero's 2023 PhD Thesis.

### Neural-Kalman Schemes for Non-Stationary Channel Tracking and Learning

"Neural-Kalman Schemes for Non-Stationary Channel Tracking and Learning" - A dissertation submitted by Diego Méndez Romero in partial fulfillment of the requirements for the degree of Doctor of Philosophy in Multimedia and Communications, Universidad Carlos III de Madrid - Advisor/Tutor: M. Julia Fernández-Getino García - Leganés, February 2023

This dissertation is contained in the main pdf, `PhD_Thesis_Diego_Méndez_Romero_v1.pdf`, and summarized in the accompanying viva slides, `Neural-Kalman Schemes for Channel Tracking and Learning_v0.074.pptx`.

### Paper 01 - SMAP

Méndez-Romero, D. and Fernández-Getino García, M. J. (2018). Simpler Multipath Detection for Vehicular OFDM Channel Tracking. IEEE Transactions on Vehicular Technology,
67(11):10752-10759. DOI: 10.1109/TVT.2018.2868445

**Results**: A computationally inexpensive, threshold-based abrupt-change detector called Simplified Maximum A Posteriori (SMAP) is presented. Simulations show this estimator greatly reduces channel tracking error in the target SNR range at a very small computational cost, thus outperforming previously known systems.

### Paper 02 - Vehicular Kalman trackers

Méndez-Romero, D. and Fernández-Getino García, M. J. (2020). Death/Birth and SNR Detection for Vehicular Kalman Channel Trackers. In 2020 IEEE 20th Mediterranean Electrotechnical Conference (MELECON) [16-18 June 2020], pages 104-108, Palermo, Italy. IEEE. DOI: 10.1109/MELECON48756.2020.9140497

**Results**: This paper considers combined death/birth and SNR detection when SNR is dynamical and may drift. Simulation results compared different schemes combining SNR detection and SMAP and suggest that SMAP, while being robust to SNR drift, benefits from an accurate SNR detection.

### Paper 03 - Neural-Network-Switched Kalman Filters

Méndez-Romero, D., Fernández-Getino Garcia, M. J., Tonello, A. M., and Dobre, O. A. (2020). Neural-Network-Switched Kalman Filters as Novel Trackers for Multipath Channels. In 2020 IEEE International Conference on Communications Workshops (ICC Workshops) [7-11 June 2020], pages 1-5, Dublin, Ireland. IEEE.
DOI: 10.1109/ICCWorkshops49005.2020.9145198

**Results**: Neural-Network-Switched Kalman Filters (NNKFs) are proposed as novel trackers for multipath channels. The core idea is similar to the SMAP switch in Paper 01, but now the tap birth/death detection will be performed via an artificial neuronal network (NNs).

The proposed Neural-Kalman scheme is robust to wide variations in the probabilities of tap birth and death. Such robustness suggests a single, low-complexity NNKF could be reusable over different tap indices and communication environments.

## Visual Summary

My research, visually summarized in a single image:

![Why Neural-Network-switched Kalman filters are better](assets/Infograf%C3%ADa%20NNKF.jpg)

