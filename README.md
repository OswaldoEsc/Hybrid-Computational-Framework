# Hybrid Computational Framework for Fault Detection in Coil Winding Manufacturing Process Using Knowledge Distillation - Repository

Welcome to the Electric Motor Manufacturing Fault Detection Repository! This project aims to minimize wasted time and costs associated with detecting faults in the manufacturing of electric motors by modeling process interdependencies and identifying faults early in the process.

## Overview
Manufacturing electric motors is a complex process involving deformable materials like copper wire. Detecting faults at the end-of-line tests can result in wasted time and costs due to rework or scrappage. This project proposes a computational framework to model process interdependencies in a complex electric motor manufacturing process involving copper wire as a deformable material.

A Discrete Event Simulation (DES) model was developed to capture process interdependencies and their influence on the generation of faults in a linear coil winding process. The model simulates the behavior of the copper wire in every turn during the coil-winding process and captures electrical and geometrical faults in the wound coil as soon as they appear. The accuracy and reliability of the model were validated with a series of experiments conducted using a lab-based linear coil-winding machine setup and expert feedback from the electrical machine manufacturing industry.

The conventional End of the Line (EoL) tests are insufficient in detecting faults during process resulting in increased manufacturing costs and lead times. The proposed methodology utilises a Knowledge Distillation (KD) approach to address the challenges associated with the technique and optimise the student model's performance by employing architecture search and data augmentation. Multiple SML algorithms were evaluated to determine their effectiveness in predicting faults during manufacturing. The Random Forest algorithm demonstrated superior performance due to its ability to handle complex data and identify the impact of interdependencies of process parameters on the final product quality. The method was validated by conducting physical experiments on a linear coil-winding machine, and the results indicated that the Random Forest algorithm has the potential to decrease simulation time from 2 minutes to less than a second. The proposed methodology has the potential to reduce manufacturing time, enhance stator quality, and ultimately improve their reliability and safety.

## Repository Contents
This repository contains the following resources:

+ **Data:** The raw data, processed data, and experimental results used for the development and validation of the DES model.

+ **Charts:** Visualizations showcasing the relationship between input parameters and the occurrence of faults, as well as hotspot regions in the final wound coil.

+ **Documentation:** Detailed documentation explaining the methodology, implementation, and usage of the computational framework and DES model.

+ **Documentation:** To better understand the DES model in action, a video demonstration is provided.

## Future Work
Potential future work includes integrating the model with live shop floor data to project the state of the coil and determine if or where defects are likely to occur. This real-time fault detection could significantly improve manufacturing efficiency and reduce waste in the electric motor industry.

We encourage contributions and feedback from researchers and industry professionals. Feel free to explore the resources provided in this repository and reach out with any questions, suggestions, or improvements.
