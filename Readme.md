**Abstract**

Damage in yield due to crop diseases is a great concern to the farmers and India being an
agriculture-based country, a large portion of the country’s GDP also depends on it. Loss
of yield due to undetected or untimely dispersion of pesticides affects the overall crop
production. In this project, a method to identify the type of disease present in a crop
based on leaf images using machine learning is proposed. First, the leaves are individually
detected in real-time from the field using Single Shot Detector (SSD). To classify the type
of disease present in the crop, a Convolutional neural networks architecture is proposed
which is trained on the PlantVillage dataset and the proposed hybrid network is deployed
on the embedded platforms namely NVIDIA Jetson TX1 and NVIDIA Jetson Nano,
for real-time detection and identification. The disease classification accuracy achieved is
around 96.88%. Moreover, the proposed Classification model’s accuracy is compared with
the AlexNet model’s accuracy. As a result, the proposed classification model accuracy is
higher than AlexNet CNNs model accuracy, which is 95.53%. Furthermore, the proposed
plant disease detection system also tested at a tomato farm. This in-field real-time testing
shows that the proposed model is robust and gives efficient results in real-time testing.

This project aims to aid the farmers by embedding the machine learning model for
detection and classification in a handheld device that would inform the farmers about
the disease type on time, thereby providing them sufficient help to take precautions and
countermeasures for its removal.
