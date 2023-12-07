# Oil Palm Knocking Sound Classification using CNN
Hi there. This is my first repository. any recommendation is allowed! 
The goal of this project is to integrate a local wisdom technique to classify infected oil palm trees from healthy trees into computer using Convolution Neural Netwok (CNN).
## Data
All input data (2075 files) is greyscale MFCC picture transformed from 24 kHz knocking sounds which was collected by hand with Apple airpod pro as the recording device. Here's the classes of this dataset

1. Healthy (Recorded from any spot on healthy oil palm trees)
![healthy_spectrumplot](https://github.com/augsornthip03/SoundRecognitionOilpalm/assets/132915443/ba934d7b-ce24-430c-989a-456883e4aaa4)
2. Infected (Recorded from infected area on an infected tree)
![infected_spectrumplot](https://github.com/augsornthip03/SoundRecognitionOilpalm/assets/132915443/343b9843-be83-4c1a-af68-e216ea8a0889)
3. Boundary (Recorded from The boundary beside the infected area)
![boundary_spectrumplot](https://github.com/augsornthip03/SoundRecognitionOilpalm/assets/132915443/cd50f309-bf62-4878-b69d-f91b9c8c5759)

The figures above showing the differences in term of signal characteristic. Before passing it to CNN, it had been transformed into MFCC spectrogram
![fig6](https://github.com/augsornthip03/SoundRecognitionOilpalm/assets/132915443/c8c60681-396c-46ed-9e70-74b5376fb519)
