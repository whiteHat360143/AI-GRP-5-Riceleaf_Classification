Project Title: Classifying Rice Varieties in Bangladesh using Custom CNN and ML Classifiers

Group 5:
Mohammad Ashiquzzaman Hadi
2021-3-60-143
Sahla Fabia Safa
2021-2-60-061
Shaiful Islam
2022-1-60-120
Umme Habiba Rupu
2022-1-60-334

Description of the problem and Dataset:
This paper presents a method for classifying rice varieties in Bangladesh using a custom Convolutional Neural Network (CNN) and several machine learning classifiers. The proposed model
is trained and tested on a dataset of rice grain images to evaluate accuracy, precision, recall, and F1-score. The identification of rice varieties is critical for agricultural research,
quality control, and market standardization. This study proposes a robust methodology for classifying 38 distinct rice varieties from the Bangladesh Institute of Nuclear Agriculture (BINA) and the International Rice Research Institute (IRRI) using low-resolution images captured by high-power digital microscope cameras. A comprehensive dataset comprising 19,000 original and 76,000 augmented images was utilized to train and evaluate multiple convolutional neural network (CNN) architectures, including a custom CNN, ConvNeXt Tiny, ResNet50, and MobileNetV3,integrated with a Convolutional Block Attention Module (CBAM) for enhanced feature extraction. Data preprocessing techniques, such as resizing, noise reduction, normalization, and augmentation, were applied to ensure robust model performance. The processed features were fed into various classifiers, including Support Vector Machine (SVM), K-Nearest Neighbors (KNN), Random Forest (RF), and XGBoost, to achieve high classification accuracy. The models were trained with optimized parameters, including the AdamW optimizer, a learning rate of 1e-4, and cosine annealing scheduling, achieving stable convergence over 80 epochs. The proposed pipeline demonstrates strong generalization and robustness, offering a scalable solution for rice variety classification in agricultural applications. The results indicate that the custom CNN achieves superior classification performance compared to traditional ML classifiers.

This study works with a publicly available dataset which were utilized to train and evaluate the classifiers. This dataset contains a carefully collected set of low-resolution images of
38 well-known rice varieties from BINA and IRRI. It helps in identifying the unique features of these rice types for accurate classification. The dataset includes images of 38 different
types of rice, specifically: BD33, BD30, BD39, BD56, BD93, BD91, BD49, BD51, BD52, BD76, BD95, BD57, BD87,BD70, BD85, BD72, BD79, BD75, Binadhan7, Binadhan8, Binadhan10, Binadhan11, Binadhan12, Binadhan14, Binadhan16, Binadhan17, Binadhan19, Binadhan20, Binadhan21, Binadhan23, Binadhan24, Binadhan25, Binadhan26, BR22, BR23, BRRI67, BRRI74, and BRRI102. There are 19,000 original JPG images and 76,000 augmented images in total. Images were taken using high-power 1600x and 1000x digital microscope cameras between January 15 and February 28,
2024. The dataset is divided into two main parts: Original images and Augmented images. Each part has 38 folders, one for each rice variety.

We have used kaggle online platform to run and prepare our model. Hardware specs (Cloud)
CPU: x86_64
Total RAM (GB): 31.35
GPU: Tesla P100-PCIE-16GB

We have designed Custom CNN and used augmented data images for our model. We have also performed generalization process and obtained a better result as well.

This study introduced a deep learning framework for classifying 38 rice varieties from BINA and IRRI using lowresolution microscopic images. With careful preprocessing, advanced CNN models, and attention mechanisms, the approach achieved high accuracy and robustness. The use of CNN feature extractors combined with traditional machine learning classifiers also showed that hybrid methods can, in some cases, surpass standard end-to-end networks. The findings highlight that rice variety identification can be reliably automated, reducing the limitations of manual methods while supporting breeding programs, quality control, and large-scale monitoring. Future research may extend this work to field-levelimages, optimize models for mobile deployment, and exploretransformer-based networks. Overall, the framework offers ascalable and efficient solution that contributes to precision agriculture and food security.








