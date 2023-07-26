
# Adapting NeRF for Low-Latency Reconstruction in VR Teleoperation



<img src="armcam.gif" alt="Alt Text" width="300" height="200">  <img src="walle.gif" alt="Alt Text" width="300" height="200"> 

<img src="santa.gif" alt="Alt Text" width="300" height="200"> <img src="bunnies.gif" alt="Alt Text" width="300" height="200"> 

In order to optimize virtual reality (VR) for teleoperation, 360-degree scene reconstruction is necessary for complex navigation and depth estimation. Previous point-cloud based methods create latency between user and robot head movements that cause confusion and nausea. NeRF methods provide SotA novel-view synthesis, but also suffer due to high latency. We develop a novel pipeline based on an Efficient-NeRF(ENeRF)-backbone to generate free-viewpoint scenes. We adapt a PyTorch implementation of ENeRF, and achieve a 60 degree field-of-view. Future work involves stitching together separate views for an instantaneous, 360-degree reconstruction, as well as adapting the network for Unity to allow for real-world usage through the Spot interface.
                                                                                                                                  
**Source views and novel-view results:**

<img src="-0.67.jpg" alt="Alt Text" width="300" height="200">  <img src="0.67.jpg" alt="Alt Text" width="300" height="200"> <img src="armcam.gif" alt="Alt Text" width="300" height="200"> 

<img src="demo_wall3_src2.png" alt="Alt Text" width="300" height="200">  <img src="demo_walle_src1.png" alt="Alt Text" width="300" height="200">     <img src="walle.gif" alt="Alt Text" width="300" height="200">

<img src="santa1.png" alt="Alt Text" width="300" height="200">  <img src="santa2.png" alt="Alt Text" width="300" height="200"> <img src="santa.gif" alt="Alt Text" width="300" height="200"> 

<img src="bunnies1.png" alt="Alt Text" width="300" height="200">  <img src="bunnies2.png" alt="Alt Text" width="300" height="200"> <img src="bunnies.gif" alt="Alt Text" width="300" height="200"> 

<img src="guitar1.png" alt="Alt Text" width="300" height="200">  <img src="guitar2.png" alt="Alt Text" width="300" height="200"> <img src="guitar.gif" alt="Alt Text" width="300" height="200"> 
