# Lossless Compression of JPEG images using Machine Learning
This [paper](https://ieeexplore.ieee.org/document/10581343) presents an innovative approach to the lossless compression of JPEG (Joint Photographic Experts Group) images, comparing the strengths of **Convolutional Neural Networks (CNNs)**, **Recurrent Neural Networks (RNNs)**, and **Generative Adversarial Networks (GANs)** to discover the optimal compression methods. Our model delves into the usage of **CNNs to get good at extracting spatial features**, **RNNs to handle sequential data and find temporal redundancies**, and **GANs to improve the decompression process** so that the reconstructed images are very accurate.

Through comprehensive testing, our GAN-based approach significantly outperforms existing lossless compression techniques by achieving **higher compression ratios while maintaining impeccable image quality**. The usage of these advanced neural network models not only sets a new benchmark in JPEG image compression but also highlights the potential for deep learning architectures to **revolutionize multimedia storage and transmission technologies**. This study focuses on the JPEG format but has implications for a wider range of image processing tasks. It shows that GANs are good at getting rid of decompression artifacts and making the best use of space for multimedia storage. This could lead to big improvements in digital media tasks where image integrity is very important.

# 💡 Introduction
In the digital age, images are omnipresent and form the backbone of various applications across numerous industries, including healthcare, media, surveillance, and more. JPEG, as one of the **most prevalent image formats, balances quality and compression efficiency, making it a universal choice for storing and transmitting digital images**. However, with the ever-increasing volume of digital imagery and the demand for high-quality images, traditional JPEG compression methods are facing limitations, especially in applications where **loss of data cannot be tolerated**. The advent of deep learning offers new avenues to enhance lossless compression techniques, potentially overcoming the constraints of existing methods.

While JPEG provides mechanisms for both lossy and lossless compression, the latter is less explored, particularly in the context of leveraging advanced neural network architectures. **The primary challenge in lossless JPEG image compression lies in achieving higher compression ratios without sacrificing any of the original data**. Conventional algorithms struggle with the complexity and diversity of image data, often leading to inefficient compression or the loss of critical information. This research aims to investigate whether CNNs, RNNs, and GANs can address these challenges by exploiting their capabilities for feature extraction, sequential data processing, and data generation, respectively.

The study focuses on the following objectives: <br/>
✅ To develop a novel framework comparing CNNs, RNNs, and GANs for the lossless compression of JPEG images, aiming to surpass the efficiency of traditional compression methods. <br/>
✅ To evaluate the effectiveness of this approach in maintaining the integrity and quality of images post-compression and decompression. <br/>
✅ To explore the potential of deep learning models in automating and optimizing the compression process, making it more adaptable to various types of image data. <br/>

This research is poised to make significant contributions to the field of digital image processing by introducing a cutting-edge approach to lossless JPEG image compression. By harnessing the power of GAN, it seeks to set new standards for compression efficiency, image quality, and processing speed. The findings could have wide-ranging implications for industries relying on digital imaging, enhancing the storage, transmission, and accessibility of high-fidelity images.

# 🚙 Functionalities
1️⃣ **CNN**: <br/>
· **Feature Extraction**: CNNs excel at automatically detecting and **extracting complex features and patterns** within images, such as edges, textures, and shapes. This is achieved through convolutional layers that **apply filters** to the input image, capturing spatial hierarchies. <br/>
· **Redundancy Reduction**: By identifying these features, CNNs can help **encode image data more efficiently, reducing redundancy without losing critical information**. This is particularly useful in lossless compression, where the goal is to minimize file size without data loss. <br/><br/>
2️⃣ **RNN**: <br/>
· **Sequential Data Processing**: RNNs are designed to handle sequential data, making them ideal for **analyzing the spatial relationships and dependencies within an image**. Unlike CNNs, which process the image in one pass, RNNs can process data in a sequence, capturing temporal and spatial patterns across the image. <br/>
· **Enhanced Encoding**: This ability allows for more sophisticated encoding strategies that consider the entire context of the image, leading to more efficient compression. RNNs can **effectively model the sequential nature of image data, further reducing the size of the compressed file while maintaining the integrity of the original image.** <br/><br/>
3️⃣ **GAN**: <br/>
· **Image Reconstruction**: During the decompression phase, GANs can play a crucial role in **reconstructing the compressed image back to its original state**. The generative model learns to produce images that are **indistinguishable from the original images, ensuring high fidelity.** <br/>
· **Artifact Reduction**: One of the challenges in lossless compression is the potential introduction of artifacts during decompression. GANs can be trained to **minimize these artifacts, ensuring that the decompressed image retains the quality and details of the original.** <br/>

This holistic approach aims to set new benchmarks in the field of lossless image compression, making it possible to store and transmit JPEG images more efficiently without compromising on quality.

# 🏛️ Architectural Diagrams
**CNN Architecture** <br/>
![image](https://github.com/user-attachments/assets/37b764cd-2bf2-451e-a26d-76ac164da53e) <br/>
**RNN Architecture** <br/>
![image](https://github.com/user-attachments/assets/5d70f025-cf83-40f5-918d-98da0687d6a0) <br/>
**GAN Architecture** <br/>
![image](https://github.com/user-attachments/assets/6b077aed-cf6e-4f85-8656-a78e150cd9ca) <br/>
**GAN Structure Overview** <br/>
![image](https://github.com/user-attachments/assets/eaddda8b-a1dc-4c8f-8595-b95446cd3322) <br/>

# 📊 Dataset
The [CIFAR-10 dataset](https://www.cs.toronto.edu/~kriz/cifar.html#:~:text=CIFAR%2D10%20python%20version) is a widely used benchmark in the fields of machine learning and computer vision for evaluating the performance of image recognition algorithms. Comprising 60,000 32x32 color images, the dataset is divided into 50,000 training images and 10,000 testing images. These images are evenly distributed across 10 different classes, which include airplanes, cars, birds, cats, deer, dogs, frogs, horses, ships, and trucks, with each class containing 6,000 images.

# 📈 Results and Discussion
In this project, we adopted a GAN for image compression and also incorporated advanced deep learning techniques like separable convolutions, enhancing efficiency and performance. Our framework outperformed the baseline and other deep learning models in terms of SSIM and PSNR metrics, demonstrating superior image quality with reduced training time. This efficiency comes from smart changes like skipping connections and improving convolutions. This shows that our GAN-based model is flexible and good at image compression tasks. <br/>

This approach demonstrates improvements in training efficiency and processing time. This project also highlights the potential of GANs in enhancing image compression methodologies, offering a promising direction for future research and application in real-world scenarios. In-depth results are availablle in our paper, so please do visit the link.



























