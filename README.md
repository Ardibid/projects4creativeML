---


---

<p>A short review of the papers/projects/repos that can be helpful in creative ML</p>
<h2 id="intro">Intro:</h2>
<p>For the final projects, I am aiming for two main categories: </p>
<ol>
<li><a href="/README.md#Camera-Pose-Estimation">Camera Pose Estimation from a Single or Series of RGB Image</a></li>
<li>[Human Pose Estimation from a Single or Series of RGB Image](/README.md#Human-User Pose-Estimation)</li>
<li><a href="/README.md#Robotic-Motion">Robotic motion</a></li>
<li><a href="/README.md#Painting">Painting</a></li>
</ol>
<p>In each category, I introduce multiple cases that can be used as a part of the proposed framework. </p>
<hr>
<p>For each paper, these items are checked:<br>
<a href="">Code</a>/<a href="">Data</a>/<a href="">Paper</a>/<a href="">Demo</a>/<a href="">Video</a></p>
<h1 id="short-list">Short List:</h1>
<h3 id="camera-pose-estimation">Camera Pose Estimation:</h3>
<ol>
<li>
<p><strong>PoseNet</strong>: A Convolutional Network for Real-Time 6-DOF Camera Relocalization [<a href="/assets/papers/PoseNet-%20A%20Convolutional%20Network%20for%20Real-Time%206-DOF%20Camera%20Relocalization.pdf">1</a>]<br>
<a href="https://github.com/alexgkendall/caffe-posenet">Code</a> <a href="https://github.com/kentsommer/tensorflow-posenet">TF implementation</a>/<a href="http://mi.eng.cam.ac.uk/~agk34/resources/PoseNet.zip">Trained Model</a> / Data (not available)/ <a href="https://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Kendall_PoseNet_A_Convolutional_ICCV_2015_paper.pdf">Paper</a>/<a href="http://mi.eng.cam.ac.uk/projects/relocalisation/">Demo</a><br></p>
</li>
<li>
<p>Image-based localization using LSTMs for structured feature correlation [<a href="/assets/papers/Adversarial%20PoseNet-%20A%20Structure-aware%20Convolutional%20Network%20for%20Human%20Pose%20Estimation.pdf">2</a>]<br>
<a href="https://github.com/NavVisResearch/NavVis-Indoor-Dataset/">Data</a>/<a href="http://openaccess.thecvf.com/content_ICCV_2017/papers/Walch_Image-Based_Localization_Using_ICCV_2017_paper.pdf">Paper</a>/Code not available <br></p>
</li>
<li>
<p>Relative Camera Pose Estimation Using Convolutional Neural Networks [<a href="/assets/papers/Relative%20Camera%20Pose%20Estimation%20Using%20Convolutional%20Neural%20Networks.pdf">3</a>]<br>
<a href="https://github.com/AaltoVision/relativeCameraPose">Code by imelekhov (Torch)</a> / No Data /<a href="https://link.springer.com/content/pdf/10.1007%2F978-3-319-70353-4_57.pdf">Paper</a>/ No Demo / No Video <br></p>
</li>
<li>
<p><strong>RelocNet</strong>: Continuous Metric Learning Relocalisation using Neural Nets<br>
<a href="http://openaccess.thecvf.com/content_ECCV_2018/papers/Vassileios_Balntas_RelocNet_Continous_Metric_ECCV_2018_paper.pdf">Paper</a>/ <a href="http://relocnet.avlcode.org/dataset.html">Data</a> / <a href="http://relocnet.avlcode.org/docs/Balntas_2018_ECCV_presentation.pdf">Presnetation</a>/<a href="http://relocnet.avlcode.org/">Website</a></p>
</li>
<li>
<p>Camera Relocalization by Computing Pairwise Relative Poses Using Convolutional Neural Network<br>
<a href="http://openaccess.thecvf.com/content_ICCV_2017_workshops/papers/w17/Laskar_Camera_Relocalization_by_ICCV_2017_paper.pdf">Paper</a> / <a href="https://github.com/AaltoVision/camera-relocalisation">Code by imelekhov (Torch, MATLAB)</a>/Dataset available (~30 Gig)</p>
</li>
<li>
<p>Video-rate Localization in Multiple Maps for Wearable Augmented Reality </p>
</li>
<li>
<p><strong>VidLoc</strong>: A Deep Spatio-Temporal Model for 6-DoF Video-Clip Relocalization<br>
<a href="http://openaccess.thecvf.com/content_cvpr_2017/papers/Clark_VidLoc_A_Deep_CVPR_2017_paper.pdf">Paper</a> / <a href="https://github.com/futurely/deep-camera-relocalization">Code with trained model</a></p>
</li>
</ol>
<hr>
<h3 id="human-user-pose-estimation">Human User Pose Estimation</h3>
<ol>
<li><strong>VNect</strong>:Real-time 3D Human Pose Estimation with a Single RGB Camera <a href="/assets/papers/VNect-%20Real-time%203D%20Human%20Pose%20Estimation%20with%20a%20Single%20RGB%20Camera.pdf">12</a><br>
Code (available upon request)/<a href="http://gvv.mpi-inf.mpg.de/3dhp-dataset/">Data</a>/<a href="http://gvv.mpi-inf.mpg.de/projects/VNect/content/VNect_SIGGRAPH2017.pdf">Paper</a>/<a href="https://youtu.be/7B7-IzqL9UI">Video</a></li>
<li><strong>Adversarial PoseNet</strong>: A Structure-aware Convolutional Network for Human Pose Estimation<br>
No Code / No Data /<a href="http://openaccess.thecvf.com/content_ICCV_2017/papers/Chen_Adversarial_PoseNet_A_ICCV_2017_paper.pdf">Paper</a>/ No Demo / No Video</li>
<li>Adversarial Joint Image and Pose Distribution Learning for Camera Pose Regression and Refinement<br>
No Code / No Data /<a href="https://arxiv.org/pdf/1903.06646.pdf">Paper</a>/ No Demo / No Video </li>
<li>3D Human Pose Estimation in the Wild by Adversarial Learning<br>
<a href="http://openaccess.thecvf.com/content_cvpr_2018/papers/Yang_3D_Human_Pose_CVPR_2018_paper.pdf">Paper</a>/ <a href="https://github.com/xingyizhou/pose-hg-3d">Code (Torch)</a></li>
<li><strong>OpenPose</strong></li>
</ol>
<h1 id="long-list">Long List</h1>
<h2 id="camera-pose-estimation-1">Camera Pose Estimation:</h2>
<ol start="0">
<li>
<p>Understanding the Limitations of CNN-based Absolute Camera Pose Regression [<a href="/assets/papers/">0</a>]<br>
Torsten Sattler, Qunjie Zhou, Marc Pollefeys, Laura Leal-Taixe´<br>
A comprehensive review of the concepts in Absolute Camera Pose (ACP) and Relative Camera Pose (RCP).<br>
<a href="https://arxiv.org/pdf/1903.07504.pdf">Paper</a></p>
</li>
<li>
<p><strong>PoseNet</strong>: A Convolutional Network for Real-Time 6-DOF Camera Relocalization [<a href="/assets/papers/PoseNet-%20A%20Convolutional%20Network%20for%20Real-Time%206-DOF%20Camera%20Relocalization.pdf">1</a>]<br>
They present a robust and real-time monocular six degree of freedom relocalization system. Our system trains a convolutional neural network to regress the 6-DOF camera pose from a single RGB image in an end-to-end manner with no need of additional engineering or graph optimisation. The algorithm can operate indoors and outdoors in real time, taking 5ms per frame to compute. It obtains approximately 2m and 3 degrees accuracy for large scale outdoor scenes and 0.5m and 5 degrees accuracy indoors. This is achieved using an efficient 23-layer deep convnet, demonstrating that convnets can be used to solve complicated out of image plane regression problems. This was made possible by leveraging transfer learning from large scale classification data. We show that the PoseNet localizes from high level features and is robust to difficult lighting, motion blur and different camera intrinsic where point based SIFT registration fails. Furthermore, we show how the pose feature that is produced generalizes to other scenes allowing us to regress pose with only a few dozen training examples.<br>
<a href="https://github.com/alexgkendall/caffe-posenet">Code</a> <a href="https://github.com/kentsommer/tensorflow-posenet">TF implementation</a>/<a href="http://mi.eng.cam.ac.uk/~agk34/resources/PoseNet.zip">Trained Model</a> / Data (not available)/ <a href="https://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Kendall_PoseNet_A_Convolutional_ICCV_2015_paper.pdf">Paper</a>/<a href="http://mi.eng.cam.ac.uk/projects/relocalisation/">Demo</a><br><br>
<img src="https://github.com/Ardibid/projects4creativeML/blob/master/assets/Images/PoseNet.png?raw=true" width="500"></p>
</li>
<li>
<p>Image-based localization using LSTMs for structured feature correlation [<a href="/assets/papers/Adversarial%20PoseNet-%20A%20Structure-aware%20Convolutional%20Network%20for%20Human%20Pose%20Estimation.pdf">2</a>]<br>
In this work wstrikethrough texte propose a new CNN+LSTM architecture for camera pose regression for indoor and outdoor scenes. CNNs allow us to learn suitable feature representations for localization that are robust against motion blur and illumination changes. We make use of LSTM units on the CNN output, which play the role of a structured dimensionality reduction on the feature vector, leading to drastic improvements in localization performance. We provide extensive quantitative comparison of CNN-based and SIFT-based localization methods, showing the weaknesses and strengths of each. Furthermore, we present a new large-scale indoor dataset with accurate ground truth from a laser scanner. Experimental results on both indoor and outdoor public datasets show our method outperforms existing deep architectures, and can localize images in hard conditions, e.g., in the presence of mostly textureless surfaces, where classic SIFT-based methods fail. <br>
<a href="https://github.com/NavVisResearch/NavVis-Indoor-Dataset/">Data</a>/<a href="http://openaccess.thecvf.com/content_ICCV_2017/papers/Walch_Image-Based_Localization_Using_ICCV_2017_paper.pdf">Paper</a>/Code not available <br><br>
<img src="https://github.com/Ardibid/projects4creativeML/blob/master/assets/Images/Pose%20LSTM.png?raw=true" width="500"></p>
</li>
<li>
<p>Relative Camera Pose Estimation Using Convolutional Neural Networks <a href="/assets/papers/Relative%20Camera%20Pose%20Estimation%20Using%20Convolutional%20Neural%20Networks.pdf">3</a><br>
This paper presents a convolutional neural network based approach for estimating the relative pose between two cameras. The proposed network takes RGB images from both cameras as input and directly produces the relative rotation and translation as output. The system is trained in an end-to-end manner utilising transfer learning from a large scale classification dataset. The introduced approach is compared with widely used local feature based methods (SURF, ORB) and the results indicate a clear improvement over the baseline. In addition, a variant of the proposed architecture containing a spatial pyramid pooling (SPP) layer is evaluated and shown to further improve the performance.<br>
<a href="https://github.com/AaltoVision/relativeCameraPose">Code by imelekhov (Torch)</a> / No Data /<a href="https://link.springer.com/content/pdf/10.1007%2F978-3-319-70353-4_57.pdf">Paper</a>/ No Demo / No Video <br><br>
<img src="https://github.com/Ardibid/projects4creativeML/blob/master/assets/Images/Relative%20Camera%20Pose%20Estimation.png?raw=true" width="500"></p>
</li>
<li>
<p><strong>RelocNet</strong>: Continuous Metric Learning Relocalisation using Neural Nets<br>
They propose a method of learning suitable convolutional representations for camera pose retrieval based on nearest neighbour matching and continuous metric learning-based feature descriptors. It compares pair of images from the camera.<br>
It require parameters forom the  camera that being used.<br>
<a href="http://openaccess.thecvf.com/content_ECCV_2018/papers/Vassileios_Balntas_RelocNet_Continous_Metric_ECCV_2018_paper.pdf">Paper</a>/ <a href="http://relocnet.avlcode.org/dataset.html">Data</a> / <a href="http://relocnet.avlcode.org/docs/Balntas_2018_ECCV_presentation.pdf">Presnetation</a>/<a href="http://relocnet.avlcode.org/">Website</a> <br><br>
<img src="https://github.com/Ardibid/projects4creativeML/blob/master/assets/Images/relocnet.jpg?raw=true" width="500"></p>
</li>
<li>
<p>Camera Relocalization by Computing Pairwise Relative Poses Using Convolutional Neural Network <br>
Our approach localizes a given query image by using a convolutional neural network (CNN) for first retrieving similar database images and then predicting the relative pose between the query and the database images, whose poses are known.<br>
<a href="http://openaccess.thecvf.com/content_ICCV_2017_workshops/papers/w17/Laskar_Camera_Relocalization_by_ICCV_2017_paper.pdf">Paper</a> / <a href="https://github.com/AaltoVision/camera-relocalisation">Code by imelekhov (Torch, MATLAB)</a>/Dataset available (~30 Gig)</p>
</li>
<li>
<p>Video-rate Localization in Multiple Maps for Wearable Augmented Reality </p>
</li>
<li>
<p><strong>VidLoc</strong>: A Deep Spatio-Temporal Model for 6-DoF Video-Clip Relocalization<br>
In this paper we propose a recurrent model for performing 6-DoF localization of video-clips. We find that, even by considering only short sequences (20 frames), the pose estimates are  A Deep Spatio-Temporal Model for 6-DoF Video-Clip Relocalizationsmoothed and the localization error can be drastically reduced.<br>
<a href="http://openaccess.thecvf.com/content_cvpr_2017/papers/Clark_VidLoc_A_Deep_CVPR_2017_paper.pdf">Paper</a> / <a href="https://github.com/futurely/deep-camera-relocalization">Code with trained model</a>/</p>
</li>
</ol>
<h2 id="body-pose-estimation">Body Pose Estimation:</h2>
<p>This <a href="https://github.com/horefice/Human-Pose-Estimation-from-RGB">page</a> collected a good library of related projects/papers.</p>
<ol>
<li><strong>VNect</strong>:Real-time 3D Human Pose Estimation with a Single RGB Camera <a href="/assets/papers/VNect-%20Real-time%203D%20Human%20Pose%20Estimation%20with%20a%20Single%20RGB%20Camera.pdf">12</a> <br><br>
They present the first real-time method to capture the full global 3D skeletal pose of a human in a stable, temporally consistent manner using a single RGB camera.<br>
Code (available upon request)/<a href="http://gvv.mpi-inf.mpg.de/3dhp-dataset/">Data</a>/<a href="http://gvv.mpi-inf.mpg.de/projects/VNect/content/VNect_SIGGRAPH2017.pdf">Paper</a>/<a href="https://youtu.be/7B7-IzqL9UI">Video</a> <img src="/assets/Images/VNect.png" width="600"></li>
<li><strong>Adversarial PoseNet</strong>: A Structure-aware Convolutional Network for Human Pose Estimation<br>
No Code / No Data /<a href="http://openaccess.thecvf.com/content_ICCV_2017/papers/Chen_Adversarial_PoseNet_A_ICCV_2017_paper.pdf">Paper</a>/ No Demo / No Video <img src="/assets/Images/AdversarialPoseNet.png" width="600"></li>
<li><strong>Adversarial Joint Image and Pose Distribution Learning for Camera Pose Regression and Refinement</strong><br>
No Code / No Data /<a href="https://arxiv.org/pdf/1903.06646.pdf">Paper</a>/ No Demo / No Video <img src="/assets/Images/AdversarialJointImagePose.png" width="600"></li>
<li>3D Human Pose Estimation in the Wild by Adversarial Learning <br>
In this paper, we propose an adversarial learning framework, which distills the 3D human pose structures<br>
learned from the fully annotated dataset to in-the-wild images with only 2D pose annotations.<br>
<a href="http://openaccess.thecvf.com/content_cvpr_2018/papers/Yang_3D_Human_Pose_CVPR_2018_paper.pdf">Paper</a>/ <a href="https://github.com/xingyizhou/pose-hg-3d">Code (Torch)</a></li>
<li><strong>OpenPose</strong>:</li>
</ol>

