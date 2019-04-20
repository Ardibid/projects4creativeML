#### General List
A short review of the papers/projects/repos that can be helpful in creative ML

## Intro:
For the final projects, I am aiming for two main categories: </br>
   1. Camera Pose Estimation from a Single RGB Image  </br>
   2. Human Pose Estimation from a Single RGB Image  </br>


In each category, I introduce multiple cases that can be used as a part of the proposed framework. </br>

The rest of this post will include: </br>
   1. [Camera Pose Estimation](/README.md#Camera-Pose-Estimation)  </br>
   2. [Question Samples](/README.md#question-samples)  </br>

---
[Code]( )/[Data]( )/[Paper]( )/[Demo]( )/[Video]( )

## Projects List:

### Camera Pose Estimation:
   1. PoseNet: A Convolutional Network for Real-Time 6-DOF Camera Relocalization [1]
   They present a robust and real-time monocular six degree of freedom relocalization system. Our system trains a convolutional neural network to regress the 6-DOF camera pose from a single RGB image in an end-to-end manner with no need of additional engineering or graph optimisation. The algorithm can operate indoors and outdoors in real time, taking 5ms per frame to compute. It obtains approximately 2m and 3 degrees accuracy for large scale outdoor scenes and 0.5m and 5 degrees accuracy indoors. This is achieved using an efficient 23-layer deep convnet, demonstrating that convnets can be used to solve complicated out of image plane regression problems. This was made possible by leveraging transfer learning from large scale classification data. We show that the PoseNet localizes from high level features and is robust to difficult lighting, motion blur and different camera intrinsic where point based SIFT registration fails. Furthermore, we show how the pose feature that is produced generalizes to other scenes allowing us to regress pose with only a few dozen training examples. </br>
   
   [Code](https://github.com/alexgkendall/caffe-posenet)/[Trained Model] (http://mi.eng.cam.ac.uk/~agk34/resources/PoseNet.zip) / Data (not available)/[Paper](https://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Kendall_PoseNet_A_Convolutional_ICCV_2015_paper.pdf)/[Demo](http://mi.eng.cam.ac.uk/projects/relocalisation/)


### Body Pose Estimation:
   1. VNect:Real-time 3D Human Pose Estimation with a Single RGB Camera [[1]] <br>
      They present the first real-time method to capture the full global 3D skeletal pose of a human in a stable, temporally consistent manner using a single RGB camera.</br>
      Code (available upon request)/[Data](http://gvv.mpi-inf.mpg.de/3dhp-dataset/)/[Paper](http://gvv.mpi-inf.mpg.de/projects/VNect/content/VNect_SIGGRAPH2017.pdf)/[Video](https://youtu.be/7B7-IzqL9UI)


[1]: /papers/
[2]: /papers/VNect-%20Real-time%203D%20Human%20Pose%20Estimation%20with%20a%20Single%20RGB%20Camera.pdf
