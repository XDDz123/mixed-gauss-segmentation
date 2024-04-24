# Gaussian Mixture Model Image Segmentation
This project utilizes mixed gaussians to compute the probability of whether a pixel belongs to the desired object (i.e. distribution).
### Training Data
![image](https://github.com/XDDz123/mixed-gauss-segmentation/assets/20507222/26dda26e-321f-45c0-8446-b1bb8c3290ab)
As shown in the image above, the model takes images and correspondings masks as inputs. In this case, apples are masked out for training a model which can detect apples within pictures.
### Tuning
![image](https://github.com/XDDz123/mixed-gauss-segmentation/assets/20507222/ce99b21e-14b6-440f-8249-4308aca9da3d)
Optimal thresholds are found by locating the trade-off point on ROC curves.
### Sample Results
![image](https://github.com/XDDz123/mixed-gauss-segmentation/assets/20507222/6277707b-c9a7-469b-903f-1cbecc576f15)
![image](https://github.com/XDDz123/mixed-gauss-segmentation/assets/20507222/c51e4c6c-367c-49c7-9c54-3cb97142532d)

