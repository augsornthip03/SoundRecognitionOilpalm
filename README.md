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

Here's the CNN's architecture i used in this model
![image](https://github.com/augsornthip03/SoundRecognitionOilpalm/assets/132915443/8516ca55-390c-44ff-9b7d-3178db5424d1)

For Performance comparison i use 3 different algorithms (CNN,MLP,SVC) and seperates the experiment into 2 type of model 1st is Binary classification model (which boundary data is excluded) 2nd is multiclassification model (be able to classify all classes)
![image](https://github.com/augsornthip03/SoundRecognitionOilpalm/assets/132915443/2abdf521-3afd-4455-9942-68724abd3489)

The table below shows all evaluation indicators leading to F1-score
![image](https://github.com/augsornthip03/SoundRecognitionOilpalm/assets/132915443/6545313b-80ca-4b9d-9018-57b4909f4f9b)
