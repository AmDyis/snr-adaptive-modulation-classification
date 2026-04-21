# Adaptive Radio Signal Recognition

This repository contains materials for a thesis project on radio signal modulation recognition using machine learning methods.

The project focuses on adaptive modulation recognition based on signal-to-noise ratio (SNR). Several neural network architectures were studied and compared, including CNN, LNN, ResNet, and Transformer. Based on the experimental results, a combined adaptive approach was proposed, where the model used for classification depends on the estimated SNR of the input signal.

## Repository contents

This repository includes:

- the thesis document
- the presentation related to the thesis
- trained neural network models
- Jupyter notebooks with saved experimental results
- selected figures and visual materials

## Project overview

The work investigates automatic recognition of radio signal modulation types using the RadioML 2018 dataset. The study includes:

- analysis of classical and neural network approaches to radio signal recognition
- comparison of CNN, LSTM, ResNet, and Transformer models
- development of a combined adaptive classification approach
- development of a neural network model for preliminary SNR estimation
- evaluation of the final adaptive recognition system

## Main idea

The proposed system first estimates the SNR of the input radio signal and then selects the most suitable neural network model for modulation classification. This allows the system to use different architectures depending on signal quality and improves the overall recognition performance compared to a single-model approach.

## Models included

- CNN
- LSTM
- ResNet
- Transformer
- SNR estimation CNN
- combined adaptive model

## Repository structure

- `docs/` — document of "ВКР"
- `experiment/` — experiment of research
- `notebook/` — Jupyter notebooks with results and experiments

## Trained models

Some trained model files may be provided separately because of GitHub file size limits. If necessary, they can be attached through Releases or external storage.

## Repository notes

This repository is intended as a thesis and research materials repository. It includes trained models and experimental notebooks, but it is not necessarily a fully reproducible end-to-end training environment for all experiments.

## Dataset

The experiments are based on the RadioML 2018 dataset.

## Keywords

radio signal recognition, modulation classification, machine learning, neural networks, SNR estimation, CNN, LSTM, ResNet, Transformer, RadioML 2018
