# A New ConvMixer-based Approach for Diagnosis of Fault Bearing using Signal Spectrum
## Abstract
It has been reported that nearly 40% of electrical machine failures are caused by bearing problems. That is why identifying bearing failure is crucial. Deep learning for diagnosing bearing faults has been widely used, like WDCNN, Conv-mixer, and Siamese models. However, good diagnosis takes a significant quantity of training data. In order to overcome this, we propose a new approach that can dramatically improve training performance with a small data set. In particular, we propose to integrate the ConvMixer models to the backbone of Siamese network, and use the few-short learning for more accurate classification even with limited training data. Various experimental results with raw signal inputs and signal spectrum inputs are conducted, and compared with those from traditional models using the same data set provided by Case Western Reserve University (CWRU).
## Our contributions

![image](https://github.com/VuManhHung307201/bearing_faults_diagnosis/assets/106971509/b64b8ed4-70b1-4672-b51c-ae8f7eda059e)


Motivated from opportunities and challenges of fault bearing analysis, and inspired by advances of deep learning techniques, in this research, we propose
a new approach for the diagnosis of fault bearing even in the case of limited training data. In particular, based on the Siamese backbone, we propose to
integrate the Convmixer architecture to create a new model, namely Siamese-based Conv-Mixer, combining Siamese and Conv-Mixer, in which, twins network
Conv-Mixer includes Deptwise-Pointwise combined with Batch Normalization. Besides, we also propose using the few-short learning prediction method. The proposed model has been validated on the public Case Western Reserve University (CWRU) database. Quantitative assessments in comparison with other approaches and the ablation study have shown that the performance on a limited
data set improves greatly when the proposed model is used in conjunction with the few-shot learning prediction approach. For instance, the proposed model
achieves an accuracy of 95.48% with just 90 training samples, while all models A New ConvMixer-based Approach for Diagnosis of Fault Bearing 3 from earlier research achieve an accuracy of less than 92%. The proposed model has also been tested with having a spectrogram transform on the input and no spectrogram transform on the input on many instances of varying training samples
## Result
![image](https://github.com/VuManhHung307201/bearing_faults_diagnosis/assets/106971509/4c903c3e-f952-4b76-ade5-46f7bbe7821a)

  With just 77.39% accuracy with WDCNN and 80% accuracy using the Conv-Mixer model, traditional deep learning types for a small dataset produce unsatisfactory results.
While the proposed scheme can achieve an accuracy of up to 95.48% with just 90 training samples. The presented method likewise performs well, responding with 99.84% accuracy when there are 19800 training samples. The suggested approach provides efficient results in both small and big data sets, in addition to providing superior outcomes for small data sets. 
![image](https://github.com/VuManhHung307201/bearing_faults_diagnosis/assets/106971509/3c771828-ec32-4016-92d6-7c27dd1e2725)

  To further evaluate the performance of the proposed approach , we compare
the results of our model with those by other methods reported in recent works in
Table 2. The proposed model has a 99.84% efficiency compared to several other
rolling bearing defect diagnostic methods. The Multi-scale CNN and Long Short-
term Memory (LSTM) in [28] model has a 98.46% efficiency, LAFD-Net in [29]
give 99.03% and the Symmetrized Dot Pattern (SDP) + Squeeze-and-Excitation
enabled Convolutional Neural Network (SE-CNN) model mentioned in the [30]
article has a 99.75% efficiency. As can be observed, our model performs well both
with small amounts of data and with big amounts of data. The suggested model
also offers excellent efficiency.
# Citation
