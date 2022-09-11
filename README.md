# ECG Signals

## what is ECG?
An electrocardiogram (ECG) is a simple test that can be used to check your heart's rhythm and electrical activity.

## How can we record ECG signal?
Electrical signals are produced by contractions in the heart walls which drive electrical currents and create different potentials throughout the body. By placing electrodes on the skin.

## How can we use ECG signal?
There are a lot of medical infotmation that we can understand from ECG signal and beside them there is a fact that ECG signal is unique for every person so we can use to identify people.

**for more information you can check Introduction to ECG signal processing slide at this repository.**

## resources and papers

1_Real time :

a) usually doesn't have preprocessing section 

Papers :

1) https://iopscience.iop.org/article/10.1088/1742-6596/931/1/012004
2) https://biomedical-engineering-online.biomedcentral.com/articles/10.1186/1475-925X-13-160 
3) https://www.mdpi.com/1424-8220/21/1/202

codes :
1) https://github.com/c-labpl/qrs_detector
2) https://how2electronics.com/ecg-monitoring-with-ad8232-ecg-sensor-arduino/



2_Not real time :

Parts :
1) preprocessing (denoising and Baseline wander) 
2) Peak detection (QRS)
3) Feature extraction
4) Feature Selection
5) Normalization
6) Neural Network



Papers :

1) https://www.sciencedirect.com/science/article/abs/pii/S0263224113002133
2) http://diec.unizar.es/~laguna/personal/publicaciones/libroWiley.pdf


codes :
1) https://github.com/c-labpl/qrs_detector
2) https://github.com/topics/ecg-filtering


###### valid resources(papers with code)

[MIT_BIH database](https://physionet.org/content/mitdb/1.0.0/) is a valid reource of ECG signals with papers and codes about ECG signal processing that we currently are working on reproducing their work.

[Papers and codes](https://paperswithcode.com/dataset/mit-bih-arrhythmia-database)

