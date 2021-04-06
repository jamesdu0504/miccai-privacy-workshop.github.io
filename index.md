# MICCAI 2021 PPML Workshop and Tutorial

Despite substantial advances in the field of machine learning for medical imaging, clinical translation of AI techniques is still constrained by the lack of sufficiently large, representative and unbiased datasets. The primary cause of this challenge can be identified as the strict regulation of confidential patient data, alongside ethical and moral considerations of the medical profession. 
Secure and privacy-preserving Artificial Intelligence can offer regulation-compliant solutions, enabling the simultaneous utilisation and protection of sensitive datasets. So far, only federated learning has seen widespread attention in the field. However, federated learning on its own is an insufficient measure of privacy protection, as witnessed by a mounting body of literature on successful privacy attacks leading to partial or catastrophic loss of privacy.
Four main techniques offering provable guarantees of privacy and confidentiality are currently under active investigation for utilisation with machine learning techniques: Differential Privacy, Homomorphic Encryption, Secure Multi-Party Computation and utilisation of Trusted Execution Environments. 
The proposed tutorial, complementing workshop on the same subject, will introduce participants to these computational techniques of privacy-preserving machine learning by providing hands-on guidance to train a deep neural network on medical imaging data using federated learning with differential privacy and secure multi-party computation, as well as performing end-to-end encrypted inference on medical imaging data. Furthermore, a hands-on instruction session will be offered showcasing zero-knowledge data science on remote data using tensor manipulation and data science tools. The tutorial is organised collaboratively between TU Munich, Imperial College London and OpenMined and will feature the open source PriMIA and deepee libraries for Python.

## Participant Information

The tutorial will consist of two parts. It will provide the MICCAI community the opportunity to learn the theory and applications of the main computational privacy techniques: Differential Privacy, Homomorphic Encryption and Secure Multi-Party Computation. Specifically, these techniques will be applied directly to the training of neural networks for medical imaging analysis on the Paediatric Pneumonia Chest Dataset as well as the Medical Decathlon Liver Segmentation Dataset, showcasing classification and segmentation tasks common in medical imaging analysis. 
Furthermore, participants will learn the underpinnings of two open-source libraries specifically designed for remote manipulation of unseen data for tasks such as exploratory data analysis and for differentially private deep learning on medical images (deepee/PriMIA).
Participants are encouraged to take part in the workshop on privacy-preserving medical imaging analysis which has also been proposed. In cases where this is not possible, they are encouraged to visit https://courses.openmined.org and https://www.udacity.com/course/secure-and-private-ai--ud185 to learn the basics of privacy-preserving machine learning using free courses offered by OpenMined.
The concrete outline of topics that will be covered is as follows:
- PriMIA: Setup and introduction to the system model. Setting up Data Owner Worker Nodes and Central Servers. 
- PriMIA: Introduction to federated learning with PriMIA. Application of Differential Privacy, secure aggregation and encrypted inference from the trained model
- PriMIA: Deep-dive into differentially private gradient descent and secure multi-party computation
- PriMIA: Worked examples using MNIST, the chest x-ray dataset, and the medical segmentation decathlon dataset
- deepee: Introduction to differential privacy in the context of deep learning
- deepee: Discussion on the importance of privacy hyper-parameters 
- deepee: Practical application of differential privacy to liver segmentation models

The tutorial will be framed by short-form lectures introducing the pertinent topics.
We believe the exposure towards these techniques to be of great interest and importance to the MICCAI community. As medical artificial intelligence applications mature towards clinical application, the design of trustworthy AI systems is becoming more important. 

## Schedule

| Time | Event |
| --- | --- |
| 08:00 - 08:30 | Theoretical aspects of federated learning |
| 08:30 - 10:00 | Live coding: federated learning example using [PriMIA](https://github.com/gkaissis/PriMIA) |
| 10:00 - 10:15 | Break |
| 10:15 - 11:00 | Short intro to differential privacy |
| 11:00 - 12:00 | Live coding: Privacy-preserving deep learning using [deepee](https://github.com/gkaissis/deepee) |

## Organisers
- Georgios Kaissis, Technical University of Munich and Imperial College London
- Daniel Rueckert, Technical University of Munich and Imperial College London
- Alexander Ziller, Technical University of Munich
- Dmitrii Usynin, Technical University of Munich and Imperial College London
