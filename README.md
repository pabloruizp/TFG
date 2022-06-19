# Small Vessel Detection in Seaborne Environments using Deep Learning Techniques
**Author** - Pablo Ruiz Ponce

**Supervisor** - José García Rodríguez

**Abstract -** 
Each day hundreds of people risk their lives on different seas and oceans all around the globe in order to run away from wars, poverty and other miseries. In this thesis, we propose the use of deep learning based object detectors to autonomously locate small vessels in changing seaborne environments for search and rescue operations using aerial images. After extensive research on actual approaches and available datasets, using the YOLOX architecture we have achieved high accuracy and real-time inference on the SeaDronesSee dataset. In order to face the high imbalance present in the dataset, the variations of the dataset and a weighted loss have been proposed and implemented. Additionally, the proposed method has been tested on unseen images from similar datasets achieving promising results and proving the robustness of the solution.

[**Thesis**](tfg.pdf)

[**Slides**](https://docs.google.com/presentation/d/1YW_sweCJLjFlOXR9ppB9-jQ3vayrGyaJ62e-P-crUMc/edit?usp=sharing) - Slides used for the defense of the thesis

**Docker** - Custom Docker image for training the proposed architecture using CUDA 11

**Datasets** - Modified annotation files for the different SeaDronesSee datasets versions

[**YOLOX**](https://github.com/pabloruizp/YOLOX) - Modified YOLOX architecture used for this thesis
