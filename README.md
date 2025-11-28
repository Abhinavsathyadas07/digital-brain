# Digital Brain: Neural Prosthetic Simulator

This project models a Brain-Computer Interface (BCI) system designed to restore memory in patients with Alzheimer's Disease. The digital brain acts as an artificial substitute for damaged hippocampal regions, collecting and processing electrical signals from the nervous system to facilitate memory recall.

## Project Modules

- **Electrode Array Simulator:** Models electrode placement and neural signal acquisition from the hippocampus (CA1/CA3).
- **Neural Signal Processor:** Decodes and predicts spatiotemporal neural firing patterns using ML-based computational models.
- **Stimulation Control:** Simulates closed-loop stimulation protocols to restore damaged neural connections.
- **Dashboard Interface:** Visualizes neural activity, device status, and stimulation patterns.

## Architecture Overview

1. Input: Simulated nervous system electrical impulses and hippocampal activity
2. Signal Processing: Filtering, segmentation, and feature extraction using real-time algorithms
3. Machine Learning Model: Decoding, predicting, and generating hippocampal signals for memory restoration
4. Output: Controlled stimulation signals to substitute impaired regions
5. Monitoring: Web-based dashboard for device analytics and user feedback

## Technology Stack
- Embedded simulation (C++/Python)
- Data pipelines & ML models (Python, TensorFlow/PyTorch)
- Web dashboard (Streamlit/React)
- Cloud processing integration (AWS, scalable ML inference)

## Research References
- [Brain Computer Interface memory restoration](https://www.frontiersin.org/journals/neuroscience/articles/10.3389/fnins.2020.00692/full)
- [Neural Prosthetics for Memory Recall](https://neurosciencenews.com/neuroprosthetics-memory-25610/)
- [Memory Prosthesis Science](https://www.technologyreview.com/2022/09/06/1059032/memory-prosthesis-damaged-brains/)
- [Recent FDA trial for BCI](https://www.statnews.com/2025/11/20/fda-approves-paradromics-bci-trial-for-speech-restoration/)

## Contributor
Abhinav Sathyadas (Warsaw, Poland)
