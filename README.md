[MedMNIST](https://medmnist.com/) is a large-scale MNIST-like collection of standardized biomedical images, including 12 datasets for 2D and 6 datasets for 3D. All images are pre-processed into 28 x 28 (2D) or 28 x 28 x 28 (3D) with the corresponding classification labels.

### Key Features 
* Diverse: It covers diverse data modalities, dataset scales (from 100 to 100,000), and tasks (binary/multi-class, multi-label, and ordinal regression). It is as diverse as the VDD and MSD to fairly evaluate the generalizable performance of machine learning algorithms in different settings, but both 2D and 3D biomedical images are provided.   
* Standardized: Each sub-dataset is pre-processed into the same format, which requires no background knowledge for users. As an MNIST-like dataset collection to perform classification tasks on small images, it primarily focuses on the machine learning part rather than the end-to-end system. Furthermore, we provide standard train-validation-test splits for all datasets in MedMNIST v2, therefore algorithms could be easily compared.    
* Lightweight: The small size of 28×28 (2D) or 28×28×28 (3D) is friendly to evaluate machine learning algorithms.    
* Educational: As an interdisciplinary research area, biomedical image analysis is difficult to hand on for researchers from other communities, as it requires background knowledge from computer vision, machine learning, biomedical imaging, and clinical science. Our data with the Creative Commons (CC) License is easy to use for educational purposes.    



### Introductory tutorials for MedMNIST datasets:
* [PneumoniaMNIST](./PneumoniaMNIST.ipynb) is based on a prior dataset of 5,856 pediatric chest X-Ray images. The task is binary-class classification of pneumonia against normal.  
* [OrganAMNIST](./OrganAMNIST.ipynb) is based on 3D CT images. Bounding-box annotations of 11 body organs are used to obtain the organ labels. Hounsfield-Unit (HU) of the 3D images are transformed into gray-scale with an abdominal window. 2D images are cropped from the center slices of the 3D bounding boxes in axial views (planes). 
* [OrganCMNIST](./OrganCMNIST.ipynb) is similar to OrganAMNIST but with a coronal view (plane)
* [OrganSMNIST](./OrganSMNIST.ipynb) is similar to OrganAMNIST but with a saggital view (plane)
* [PathMNIST](./PathMNIST.ipynb) is based on the NIH-ChestXray14 dataset, a dataset comprising 112,120 frontal-view X-Ray images of 30,805 unique patients with the text-mined 14 disease labels 
* [BloodMNIST](./BloodMNIST.ipynb) is based on a dataset of individual normal cells, captured from individuals without infection, hematologic or oncologic disease and free of any pharmacologic treatment at the moment of blood collection. It contains a total of 17,092 images and is organized into 8 classes
* [DermaMNIST](./DermaMNIST.ipynb) is based on the HAM10000, a large collection of multi-source dermatoscopic images of common pigmented skin lesions. The dataset consists of 10,015 dermatoscopic images categorized as 7 different diseases
