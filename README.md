# CNN-Weapon-Detection
DRIVE LINK FOR DATASET -> https://drive.google.com/drive/folders/1XThtfJHrUAb-PpFkT0mKGo11KMpVot7X?usp=drive_link

In this project, we present a novel object detection and identification framework designed to bolster public safety. Prior to developing our proposed model, we conducted a thorough analysis of existing frameworks, assessing their strengths and weaknesses based on machine learning and deep learning algorithms. Drawing insights from this evaluation, we designed a comprehensive solution combining an unmanned aerial vehicle (UAV) for data collection and a convolutional neural network (CNN) for threat recognition and handheld object identification, such as guns and knives used by criminals.

The CNN model in our proposed framework consists of 16 layers, encompassing input, convolutional, dense, max-pool, and flattened layers with varying dimensions. To train and validate the model, we utilized the Small Objects Handled Similarly to a Weapon (SOHAs) dataset, a benchmarked weapon detection dataset. The SOHAs dataset comprises six classes with a total of 8945 images, divided into 5947 training images, 1699 testing images, and 849 validation images.

Upon successful object identification and classification, distinguishing between criminal and non-criminal individuals, the pertinent data on criminals are forwarded to law enforcement agencies. Meanwhile, non-criminal data are used to further refine and improve the accuracy of the CNN model. Our proposed CNN model achieved outstanding results, surpassing several pre-trained models with an accuracy of 0.8352 and a validation accuracy of 0.7758. Additionally, the model demonstrated minimal loss, registering 0.83 and a validation loss of 0.97.

The implementation of our framework not only reduces the burden on crime-fighting agencies but also enhances the accuracy of crime detection. It ensures fairness in its identification process and operates with low computational costs, setting it apart from similar pre-trained models. By leveraging UAV technology and CNN-based object detection, our proposed framework constitutes a promising approach for augmenting public safety measures.



