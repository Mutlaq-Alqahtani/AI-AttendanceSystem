# AI-AttendanceSystem
Traditional methods of monitoring attendance for employees and students have become increasingly ineffective. The advent of artificial intelligence, particularly facial recognition technology, has revolutionized attendance tracking. Individuals often forget to carry their smart cards, leading to inefficiencies and inaccuracies. Facial recognition addresses this issue by allowing attendance registration with a simple face scan, streamlining the process and enhancing accuracy.

# Model Evaluations
In this section, I evaluate the performance of various backbone architectures integrated into my Siamese Network facial recognition model. These architectures are crucial for extracting essential features from images and enabling the algorithm to distinguish between different faces.

I am assessing four distinct backbone architectures:

ResNet-18
ResNet-34
VGG11
VGG13
Each architecture varies in complexity and its ability to capture subtle details within images. My goal is to determine which backbone architecture best suits my facial recognition task, focusing on accuracy, adaptability to different conditions, and computational efficiency.

The choice of backbone is critical as it influences the model’s ability to accurately recognize faces. More complex architectures like ResNet-50 and ResNet-101 offer higher accuracy for intricate facial features but require more computational resources. Conversely, simpler architectures such as ResNet-18 and VGG11 may be less precise in capturing fine details but are more efficient.

To evaluate these architectures, I use the Contrastive Loss function, an integral part of training my Siamese Network for facial recognition. This function emphasizes penalizing errors on pairs of images of different individuals more heavily than errors on pairs of the same individual, thereby guiding the model to focus on distinguishing features.

My evaluation indicates that the VGG13 architecture performs best for this task, exhibiting the lowest epoch loss, which is a key indicator of model performance.
