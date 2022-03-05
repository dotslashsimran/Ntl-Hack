<div align="center">
  <a href="https://github.com/github_username/repo_name">
    <img src="assets/images/ML-Arts.png" alt="Logo">
  </a>
 </div>

## About The Project
There were two main objectives of our project: 
- A minecraft skin generator model using CycleGANs (in progress)
- Combining art with videos using Neural Style Transfer

## How It Works?
For minecraft skin generator model, CycleGAN image translation technique is used. Tensorflow framework is employed for custom features and better prototyping. We've used OpenCV for image processing. Upscaling and downscaling of images has been done using its built-in functions. 

In Neural style transfer model, We used Style Transfer on each frame of the desired video, and added features of the paintings the user provided. With the help of TensorFlow Hub, we picked out the perfect model for NST. We then concatenated each frame of the Image array at 30fps, to create a perfectly smooth video.

## Future Prospects
- Our aim is to add a 3D visualizer to the wesbite so as to employ 3D renditions of 2D skins.

- Adding a multitude of art styles as the model becomes more efficient. 

- We also plan to deploy the application on Cloud GPUs and TPUs to reduce the conversion times. Furthermore, we plan to integrate a user friendly UI with the application. Drag and drop, see your cinema evolve.

### Contributors
[![](https://github.com/demie20.png?size=50)](https://github.com/demie20)
[![](https://github.com/aman190202.png?size=50)](https://github.com/aman190202)
[![](https://github.com/dotslashsimran.png?size=50)](https://github.com/dotslashsimran)
