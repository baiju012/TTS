# TTS Model Benchmarking (Tacotron2 vs FastSpeech2)

## 1. Project Overview
This project benchmarks two popular text-to-speech (TTS) models, **Tacotron2** and **FastSpeech2**, for inference time and model size. The task involves synthesizing speech from a given text input using pre-trained models from the ESPnet model zoo.

## 2. Prerequisites
- Python 3.x
- Google Colab or a similar environment
- Install required packages using the following commands:
  ```bash
  pip install transformers espnet_model_zoo torch


## 3. Model Descriptions
Tacotron2: A sequence-to-sequence model for TTS that generates mel spectrograms from text.
FastSpeech2: A non-autoregressive TTS model known for faster inference while maintaining high-quality output.

## 4. Steps to Run the Benchmark
Clone/download this repository to your local system.
Install necessary libraries using the given command.
Load pre-trained models using the ESPnet model zoo.
Run the provided Python script to benchmark Tacotron2 and FastSpeech2.

## 5. Input Text
A simple English sentence: "The quick brown fox jumps over the lazy dog."
The script tokenizes this input text for use with both models.

## 6. Benchmarking Metrics
Inference Time: Measures the time taken by each model to generate output from the input text.
Model Size: Calculates the size of each model in MB (megabytes).

## 7. Expected Output
Inference time (seconds) for both models.
The size of each model in MB.

## 8. Dependencies
Transformers: For loading the tokenizer and managing text inputs.
ESPnet Model Zoo: For downloading and using pre-trained TTS models.
Torch: For running inference on the models.
