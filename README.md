ABSTRACT: Arrhythmia identification from electrocardiograms through deep learning is a proven method for diagnosis. However, there is an imbalance of arrhythmia samples in existing databases, which can result in less accurate classification of more uncommon but still dangerous arrhythmias—which can go misdiagnosed, and result in a greater risk for stroke, cardiac arrest, and death. Convolutional neural network (CNN) arrhythmia classification via ECG datasets augmented through generative adversarial networks (GAN) can offer more accurate and effective diagnostic procedures. Our study aimed to create and evaluate the effectiveness of a one-dimensional CNN (1D-CNN) that automatically detects and identifies heart rhythms (sinus rhythm, sinus bradycardia, atrial fibrillation, sinus tachycardia, atrial flutter, sinus irregularity, supraventricular fibrillation, and atrial tachycardia) from short-term ECG recordings out of a dataset including over 10,000 real ECG samples and TimeGAN-synthesized data. ECG data underwent preprocessing and segmentation, and was split into training and testing sets conducted with 5-fold cross-validation with an 80/20 split. The 1D-CNN 8-layer model was developed and evaluated with several performance metrics, and resulted in inconsistent accuracies (95.576% for sinus bradycardia, but 5.514% for sinus irregularity). The TimeGAN was evaluated based on a visualization, which revealed completely unrealistic generated data. However, with further modifications and improvement, synthesized data could potentially be utilized to resolve the class imbalance issue, thus improving the performance of the CNN. Overall, the findings of this study, in tandem with previous research, could work to advance diagnostic procedures of arrhythmias through the use of GANs and CNNs for ECG analysis.
