---
title: "Efficient and secure content-based image retrieval with deep neural networks in the mobile cloud computing"
collection: publications
permalink: /publication/2024-02-17-paper-title-number-4
excerpt: 'Smart devices offer a variety of more convenient forms to help us record our lives and generate a large amount of data in this process. Limited by the local storage capacity, many users outsource their image data directly to the cloud server. However, images stored in plaintext on the cloud server are very insecure, resulting in image privacy information can be easily leaked. Therefore, users will encrypt the images and outsource them to the cloud server, but the encrypted images cannot be retrieved. Therefore, we proposed a secure and efficient ciphertext image retrieval scheme based on image content retrieval (CBIR) and approximate homomorphic encryption (HE). First, we used approximate homomorphic encryption to encrypt images after resizing and uploaded the ciphertext images to the cloud for feature extraction of ciphertext. At the same time, the large images (size, dimension, and resolution) would generate data inflation after using homomorphic encryption. Therefore, the original images are encrypted using the chaotic image encryption scheme to reduce ciphertext size and computation costs. Second, we proposed two deepening network depth optimization strategies that address the problem of insufficient neural network depth. Finally, reducing the dimensionality of the ciphertext feature vector using locally sensitive hashing (LSH) can accelerate the retrieval of ciphertext images. Compared with other literature, our ciphertext image retrieval scheme can significantly reduce the rounds of user-server communication.
'
date: 2023-04-03
venue: 'Computers & Security'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S0167404823000731'
citation: 'Yu Wang, Liquan Chen, Ge Wu, Kunliang Yu, Tianyu Lu,
Efficient and secure content-based image retrieval with deep neural networks in the mobile cloud computing,
Computers & Security,
Volume 128,
2023,
103163,
ISSN 0167-4048,
https://doi.org/10.1016/j.cose.2023.103163.
'
---

To protect privacy, many users opt to encrypt images prior to outsourcing them to cloud service platforms (CSPs). However, this encryption process results in the loss of image features and subsequent inability to retrieve them. We propose an image encryption and retrieval algorithm, which ensures that privacy is not leaked in both the upload and retrieval stages. First, overcoming the insufficient security and degradation in chaotic systems, we introduce the time-varying functions, and unscented Kalman filter to improve the non-adjacent coupled map lattice complexity and security. Secondly, considering the encryption efficiency, we compress the plaintext image to reduce the time of the encryption phase and improve the overall encryption speed. Finally, we use the locally sensitive hash (LSH) for feature vector dimensionality reduction to improve the retrieval efficiency and perform a secondary LSH on the reduced feature vector to form a new hash-key retrieval structure in the generate index phase, which improves the retrieval efficiency. The experimental results prove that our proposed encryption algorithm can meet the image encryption algorithms high retrieval accuracy and multi-user without revealing privacy.