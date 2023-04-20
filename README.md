# Knee Joint Space Segmentation using U-Net

## Problem Statement: 
Knee Osteoarthritis (OA) is one of the most chronic joint diseases worldwide, where early detection of knee OA has traditionally focused on the analysis of knee cartilage degeneration and joint structures. While X-ray and MRI images are the most common imaging modality to assess knee cartilage, interpretation of the images is still highly subjective. From the computational perspective, we all know that deep learning computer vision methods have already demonstrated very successful applications in a variety of medical image analysis tasks, including object detection, image registration, segmentation, and classification. This project tends to use a deep neural network model, called U-Net to tackle the problem of knee joint space segmentation in plain radiographs. 

![Original X-ray](https://github.com/aptafti/few_shot_image_segmentation/blob/main/9974855L.png)
![Knee joint space segmentation](https://github.com/aptafti/few_shot_image_segmentation/blob/main/9974855Ls.png)


## Dataset:
This GitHub repository includes four different folders, as follows:
1) <strong>Train_X:</strong> original x-ray images 
2) <strong>Train_Y:</strong> ground truth/gold standard knee joint segmentation masks made manually by domain experts 
3) <strong>Test_X:</strong> You will be randomly selecting five images from Train_X and put them here in this folder.  
4) <strong>Test_Y:</strong> empty at the moment. Once you build the segmentation model, then you please use the model to automatically segment all five images available at the <strong>Test_X</strong> folder, and put the predictive masks here in this folder. 

## Computational Tasks:
You please try the following and see what you can make:
1) Use all images available at Train_X (original images) and Train_Y (segmentation masks) to build a model, named modelKneeJointSpaceSegmentation. 
2) Randomly select five images from the dataset and put them at Test_X
2) Apply the model (modelKneeJointSpaceSegmentation) on five random images available at Test_X. 
3) Save the predictive masks at Test_Y. Save the model here too. 
4) Use IoU (Intersection over Union) to see how much the results (predictive masks) are close to the masks manually provided at Train_Y.

## Due:
Wednesday, September 28, 2022, 11:59 pm EDT. 

## Contacts:
If you have any questions, please feel free to contact tafti.ahmad@pitt.edu or yanshan.wang@pitt.edu

## Reference: 
[1] Ronneberger O, Fischer P, Brox T. [U-net: Convolutional networks for biomedical image segmentation](https://link.springer.com/chapter/10.1007/978-3-319-24574-4_28). In International Conference on Medical image computing and computer-assisted intervention 2015 Oct 5 (pp. 234-241). Springer, Cham.
