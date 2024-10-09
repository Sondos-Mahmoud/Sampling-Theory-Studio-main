# Sampling_Theory Studio

## Overview
Sampling_Theory Studio is a desktop application developed using PyQt5 Designer and Python. This application allows users to work with signals, perform sampling, and recover the original signal using different frequencies.

## Team Information
Sampling_Theory Studio is a desktop application developed by Team 4, consisting of the following members:
- Sondos Mahmoud
- Fatma Ehab
- Mai Mohamed
- Noura Osama

## Features

1. **Signal Loading and Visualization**: Users can load a mid-length signal with approximately 1000 points. The application provides a graph to visualize the loaded signal.
![337760068-a276d6b3-e061-4580-ad3c-06cb34f8e73b](https://github.com/user-attachments/assets/128ee3f0-31ea-4312-a328-3667c036a9f5)

2. **Sampling**: The loaded signal can be sampled using different frequencies. Users can choose the sampling frequency, which is displayed either as the actual frequency or the normalized one based on the state of the "Actual" checkbox.
![image](https://github.com/user-attachments/assets/fa0362d6-5a9d-4a87-bf40-7ec03af1723b)

3. **Signal Recovery**: After sampling, the application utilizes the sampled points to recover the original signal. A graph is provided to display the reconstructed signal.

4. **Difference Visualization**: Users can compare the original signal with the reconstructed one using a third graph, which shows the difference between the two signals.
![image](https://github.com/user-attachments/assets/b57a5cc3-a2b5-4160-8efc-0702eb339820)

5. **Signal Mixer/Composer**: The loaded signal can be sourced from a file or created in the application's signal mixer/composer. In the mixer, users can add multiple sinusoidal signals of different frequencies and magnitudes. Components can also be removed while preparing the mixed signal.

6. **Noise Addition**: Users have the option to add noise to the loaded signal. The noise level can be controlled using a custom Signal-to-Noise Ratio (SNR). The application demonstrates the dependency of the noise effect on the signal frequency.
![image](https://github.com/user-attachments/assets/b26f7995-ec0a-4b0b-a3f8-9459ca0df50a)

7. **Real-time Processing**: Sampling and recovery are performed in real-time, instantly reflecting any changes made by the user.
![image](https://github.com/user-attachments/assets/42105cda-3c96-4e47-90b5-5aebe02f8a44)

8. **Resizable UI**: The application's UI is designed to be easily resizable, ensuring a smooth user experience.


## Usage

Upon launching Sampling_Theory Studio, you will be presented with a user-friendly interface that allows you to interact with the various features of the application. Load your signal, adjust the sampling frequency, add/remove components in the signal mixer, and explore the visualizations of the original signal, reconstructed signal, and difference between them.

