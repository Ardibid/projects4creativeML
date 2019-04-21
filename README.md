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
   1. **PoseNet**: A Convolutional Network for Real-Time 6-DOF Camera Relocalization [1]
   They present a robust and real-time monocular six degree of freedom relocalization system. Our system trains a convolutional neural network to regress the 6-DOF camera pose from a single RGB image in an end-to-end manner with no need of additional engineering or graph optimisation. The algorithm can operate indoors and outdoors in real time, taking 5ms per frame to compute. It obtains approximately 2m and 3 degrees accuracy for large scale outdoor scenes and 0.5m and 5 degrees accuracy indoors. This is achieved using an efficient 23-layer deep convnet, demonstrating that convnets can be used to solve complicated out of image plane regression problems. This was made possible by leveraging transfer learning from large scale classification data. We show that the PoseNet localizes from high level features and is robust to difficult lighting, motion blur and different camera intrinsic where point based SIFT registration fails. Furthermore, we show how the pose feature that is produced generalizes to other scenes allowing us to regress pose with only a few dozen training examples. </br>
   
   [Code](https://github.com/alexgkendall/caffe-posenet)/[Trained Model](http://mi.eng.cam.ac.uk/~agk34/resources/PoseNet.zip)/ Data (not available)/[Paper](https://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Kendall_PoseNet_A_Convolutional_ICCV_2015_paper.pdf)/[Demo](http://mi.eng.cam.ac.uk/projects/relocalisation/)
   ![PoseNet](/assets/Images/PoseNet.png "PoseNet")
   2. Image-based localization using LSTMs for structured feature correlation [2]
   In this work we propose a new CNN+LSTM architecture for camera pose regression for indoor and outdoor scenes. CNNs allow us to learn suitable feature representations for localization that are robust against motion blur and illumination changes. We make use of LSTM units on the CNN output, which play the role of a structured dimensionality reduction on the feature vector, leading to drastic improvements in localization performance. We provide extensive quantitative comparison of CNN-based and SIFT-based localization methods, showing the weaknesses and strengths of each. Furthermore, we present a new large-scale indoor dataset with accurate ground truth from a laser scanner. Experimental results on both indoor and outdoor public datasets show our method outperforms existing deep architectures, and can localize images in hard conditions, e.g., in the presence of mostly textureless surfaces, where classic SIFT-based methods fail.
   [Data](https://github.com/NavVisResearch/NavVis-Indoor-Dataset/)/[Paper](http://openaccess.thecvf.com/content_ICCV_2017/papers/Walch_Image-Based_Localization_Using_ICCV_2017_paper.pdf)/Code not available
   ![LSTM](/assets/Images/Pose%20LSTM.png "PoseNet")
   

### Body Pose Estimation:
   1. **VNect**:Real-time 3D Human Pose Estimation with a Single RGB Camera [12] <br>
      They present the first real-time method to capture the full global 3D skeletal pose of a human in a stable, temporally consistent manner using a single RGB camera.</br>
      Code (available upon request)/[Data](http://gvv.mpi-inf.mpg.de/3dhp-dataset/)/[Paper](http://gvv.mpi-inf.mpg.de/projects/VNect/content/VNect_SIGGRAPH2017.pdf)/[Video](https://youtu.be/7B7-IzqL9UI)
      ![VNect](/assets/Images/VNect.png "VNect")
   2. **Adversarial PoseNet**: A Structure-aware Convolutional Network for Human Pose Estimation</br>
   No Code / No Data /[Paper](http://openaccess.thecvf.com/content_ICCV_2017/papers/Chen_Adversarial_PoseNet_A_ICCV_2017_paper.pdf)/ No Demo / No Video
   ![Adversarial PoseNet](/assets/Images/AdversarialPoseNet.png "AdversarialPoseNet")
   3. **Adversarial Joint Image and Pose Distribution Learning for Camera Pose Regression and Refinement**
   No Code / No Data /[Paper](https://arxiv.org/pdf/1903.06646.pdf)/ No Demo / No Video
   ![Adversarial Joint Image and Pose](/assets/Images/AdversarialJointImagePose.png "Adversarial Joint Image and Pose")
   
   

[1]: /assets/papers/PoseNet-%20A%20Convolutional%20Network%20for%20Real-Time%206-DOF%20Camera%20Relocalization.pdf
[2]: /assets/papers/
[3]: /assets/papers/
[12]: /assets/papers/VNect-%20Real-time%203D%20Human%20Pose%20Estimation%20with%20a%20Single%20RGB%20Camera.pdf
