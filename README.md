# distance-estimation-from-2D-outdoor-images-using-commodity-hardware
MSc. Thesis Informatics TUM 

This repository contains the constructed dataset and the predicted depth map outputs that are used in this master thesis.

## Abstract
Safety in construction sites is vital because the industry is prone to accidents and dangerous situations. With the improving and expanding technology, computer vision can be used to ensure safety and reduce the accident rate.  As a contribution to an environmental health and safety project, a depth estimation framework is created to estimate distances and detect potential dangerous situations in construction sites. This thesis has two main deliverables: a uniquely created dataset and a framework for distance estimation.
Unlike other approaches in related work, depth estimation with 2D images is advanced with a newly created dataset and commodity hardware.
The created dataset is made up of two different settings: the experimental and the real-life setting. In the experimental setting, a set of different weather and surface conditions are analyzed. The weather conditions include sunny, shady, and cloudy and the surface conditions consist of grass, concrete, and interlocking pavement stone. These conditions are tested on six different monocular depth estimation methods, namely Monodepth, Monodepth2, Eigen's model, Densedepth, FCRN and Semodepth.
These methods are analyzed against certain criteria such as robustness, sensitivity and time complexity and evaluated with different metrics, which is condensed into a generic framework. Further, with the predicted depth maps, functions are extracted to calculate back the depth values to distance.
The real-life setting consists of images taken in a real construction site environment. Functions extracted in the experimental setting are applied in this setting to investigate whether the distances between the relative objects and the people in the scene can be extracted correctly. 
The dataset and extracted depth maps of each model is publicly available
