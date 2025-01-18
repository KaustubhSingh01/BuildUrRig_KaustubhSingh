# BuildUrRig_KaustubhSingh

This project majorly focuses on using machine learning in a way which could be helpful in 
building systems as per as their requirement, people who are confused about their PC builds 
and configuration, and want’s a rough but sturdy and data-packed idea of it’s relative 
performance, now di erent systems could be build for di erent purposes. 
There are people who want a server level workstation for their use and then there are folks 
who just want to grind in some good FPS, and yes it’s the gamer’s section, and in the PC 
building community the major portions are held by this category only, hence my project 
mainly focuses in the gamer’s build performance prediction.



This model is based on the concept of the effect of hardware specifications on the performance, and for this project I've taken 2 reasonable components in account, which are:

CPU:No_of_cores, No_of_threads, CPUfrequency, CpuTDP, Cpu_TURBO_CLOCK

GPU:GpuBandwidth, GpuBaseClock,GpuBoostClock, GpuMemorySize

And used NeuralNetworks for the classified FPS prediction(One of whose example is provided in the main FPS_Prediction_Combined.ipynb file itself)



# How to test the model:
After forking all of the directory in this repo, just run the FPS_Prediction_Combined.ipynb to train the models,
keeping in mind that all the datasets are in same directory,
Now feed in the data with proper order as a numpy array(like {FeatureArr} in the code itself) as per as the hardware specification, and you'll get the predictions.  