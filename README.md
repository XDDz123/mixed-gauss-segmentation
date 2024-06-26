# Gaussian Mixture Model Image Segmentation </br>
This project implemented mixed gaussians (GMM) from scratch to compute the probability of whether a pixel belongs to the desired object. </br> </br>
The optimization contains two steps which are repeated until convergence:
* Expectation step: compute the posterior probability given the current model to determine which data point belongs to which gaussian.
* Maximization Step: update the gaussian distributions' properties to maximize the probability of generating data points belonging them.

This process is known as the [Expectation Maximization algorithm](https://en.wikipedia.org/wiki/Expectation%E2%80%93maximization_algorithm).
### Training Data
![image](https://github.com/XDDz123/mixed-gauss-segmentation/assets/20507222/e8cc0a0e-b645-4b10-bf03-9e9b31ff18e3) </br>
As shown in the image above, the model takes images and correspondings masks as inputs. </br>
In this case, apples are masked out for training a model which can detect apples within pictures.
### Tuning
<img src="https://github.com/XDDz123/mixed-gauss-segmentation/assets/20507222/ce99b21e-14b6-440f-8249-4308aca9da3d" width="400" height="320"> </br>
Optimal thresholds are found by locating the trade-off point on ROC curves.
### Sample Results
#### Test Data
![image](https://github.com/XDDz123/mixed-gauss-segmentation/assets/20507222/26dda26e-321f-45c0-8446-b1bb8c3290ab) </br>
#### Heat Map
![image](https://github.com/XDDz123/mixed-gauss-segmentation/assets/20507222/6277707b-c9a7-469b-903f-1cbecc576f15) </br>
#### Binary Mask
![image](https://github.com/XDDz123/mixed-gauss-segmentation/assets/20507222/ede11973-0ca5-420b-a6cb-66f215c54771)

