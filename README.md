# Machine Vision - Coursework 

This repository presents the submitted work for the COMP0137 courseworks 1 and 2 (UCL 2024/2025).

---

## Coursework 1

### Coursework Overview:

This lab explores fitting simple parametric models to visual data. The goal of part A is to fit one Gaussian model to the data for skin and another Gaussian to non-skin pixels, and use this to find the posterior probability that each pixel in an image is skin. The aim of part B is to fit a mixture of Gaussians model to one dimensional data. The aim of part C is to fit a mixture of Gaussians model to the RGB data. The aim of Part D is to apply this to real data.

**Overall Grade:** 98.00 / 100.00

### Detailed Commentary

| Item | Feedback                                                                         |
| ---- | -------------------------------------------------------------------------------- |
| 1A   | Good, however, you are expected to explain why the guitar is classified as skin. |
| 1B   | Good, the analysis is solid.                                                     |
| 1C   | Good!                                                                            |
| 2B   | Good! The code is well-written, and the explanation is clear and thorough.       |
| 2C–F | Good! Nice implementation of the AUC, and excellent explanations throughout.     |

---

## Coursework 2

### Coursework Overview:

This lab explores condensation (particle filters), factored sampling, calculating the homography that best maps two sets of points to one another (and applying this to panoramas), as well as camera projections. 

**Overall Grade:** 93.00 / 100.00

### Detailed Commentary

| Part | Feedback                                                                                                                     |
| ---- | ---------------------------------------------------------------------------------------------------------------------------- |
| A    | Good but you are expected to show empirically that the homography matrix can exactly map any 4 points to any other 4 points. |
| D    | Good overall – but for cube explanations, you missed mentioning issues related to lens distortion.                           |
| E–F  | Overall good!                                                                                                                |
| G    | Results look good. For explanation, you are expected to analyze more in depth.                                               |
| H    | Good! Two proposed actions seem to be quite reasonable!                                                                      |

 

 ## Repository structure: 
```
├── instructions/    
│   ├── cw-1/
│   │   ├── MachineVision_HW1.pdf
│   │   ├── apples.zip
│   │   └── testApples.zip
│   ├── cw-2/
│   │   ├── COMP 0137 Machine Vision HW2.pdf
│   │   ├── student-version/
│   │   │   ├── HW2_Practical7c.ipynb
│   │   │   ├── HW2_TrackingAndHomographies.ipynb
│   │   │   ├── Pattern01.zip
│   │   │   ├── ll.mat
│   │   │   ├── lr.mat
│   │   │   ├── ul.mat
│   │   │   └── ur.mat
├──machine-vision-cw-1/
│   ├── apples/
│   │   ├── ApplesAndPears_by_srqpix_ClydeRobinson.jpg
│   │   ├── ApplesAndPears_by_srqpix_ClydeRobinson.png
│   │   ├── Apples_by_kightp_Pat_Knight_flickr.jpg
│   │   ├── Apples_by_kightp_Pat_Knight_flickr.png
│   │   ├── Attributions.txt
│   │   ├── bobbing-for-apples.jpg
│   │   └── bobbing-for-apples.png
│   ├── my_apple_images/
│   │   ├── apple_1.jpg
│   │   ├── apple_1.png
│   │   ├── apple_2.jpg
│   │   ├── apple_2.png
│   │   ├── apple_3.jpg
│   │   └── apple_3.png
│   ├── testApples/
│   │   ├── Apples_by_MSR_MikeRyan_flickr.jpg
│   │   ├── Attributions.txt
│   │   ├── Bbr98ad4z0A-ctgXo3gdwu8-original.jpg
│   │   ├── Bbr98ad4z0A-ctgXo3gdwu8-original.png
│   │   └── audioworm-QKUJj2wmxul-original.jpg
│   ├── FaceData.mat
│   ├── MoGCribSheet.pdf
│   ├── RGBSkinNonSkin.mat
│   ├── bob_GroundTruth_small.mat
│   ├── bob_small.jpeg
│   ├── practicalMixGaussA.ipynb
│   ├── practicalMixGaussB.ipynb
│   ├── practicalMixGaussC.ipynb
│   └── practicalMixGauss_Apples.ipynb
├── machine-vision-cw-2/    
│   ├── HW2_Practical7c.ipynb
│   ├── HW2_TrackingAndHomographies.ipynb
│   ├── labA.ipynb
│   ├── labB.ipynb
│   ├── practical1A.ipynb
│   ├── practical1B.ipynb
│   ├── practical2A.ipynb
│   └── practical2B.ipynb       
└── README.md                      
```

