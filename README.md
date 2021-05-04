# Test Project


## Abstract
We developed an interest point detector to detect interest point location from **event camera data**. This idea was adapted from the literature *"SuperPoint: Self-Supervised Interest Point Detection and Description."*[1]

Our algorithm mainly consists of two parts:
We first train our detector network with synthetic event data. We then iteratively use the trained detector network to label interest points of a real-world dataset and train the network with the labeled dataset.

<p align="center">
  <img src="https://raw.githubusercontent.com/picotank/testproject/main/header_office.png" width="900px">
</p>

## Requirements
The environment is run in python 3.6, Pytorch 1.5.0.


## Results

<table style="width:100%">
<thead>
  <tr>
    <th><h3>Dataset</h3></th>
    <th><h3>Intensity Image</h3></th>
    <th><h3>&nbsp;&nbsp;Event Data&nbsp;&nbsp;</h3></th>
    <th><h3>&nbsp;&nbsp;&nbsp;&nbsp;Heamap&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</h3></th>
    <th><h3>Interest Points</h3></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>boxes_6dof</td>
    <td colspan="4"><img src="https://github.com/picotank/testproject/blob/main/box_final.gif" width="960px"></td>
  </tr>
  <tr>
    <td>dynamic_6dof</td>
    <td colspan="4"><img src="https://github.com/picotank/testproject/blob/main/office_1_final.gif" width="960px"></td>
  </tr>
  <tr>
    <td>office_spiral</td>
    <td colspan="4"><img src="https://github.com/picotank/testproject/blob/main/office_2_final.gif" width="960px"></td>
  </tr>
  <tr>
    <td>urban</td>
    <td colspan="4"><img src="https://github.com/picotank/testproject/blob/main/urban_final.gif" width="960px"></td>
  </tr>
</tbody>
</table>

## Reference
[1] DeTone, D., Malisiewicz, T., & Rabinovich, A. (2018). SuperPoint: Self-Supervised Interest Point Detection and Description. 2018 IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops (CVPRW), 337-33712.

[2] Zhu, A.Z., Thakur, D., Özaslan, T., Pfrommer, B., Kumar, V., & Daniilidis, K. (2018). The Multivehicle Stereo Event Camera Dataset: An Event Camera Dataset for 3D Perception. IEEE Robotics and Automation Letters, 3, 2032-2039.

[3] Mueggler, E., Rebecq, H., Gallego, G., Delbrück, T., & Scaramuzza, D. (2017). The event-camera dataset and simulator: Event-based data for pose estimation, visual odometry, and SLAM. The International Journal of Robotics Research, 36, 142 - 149.



