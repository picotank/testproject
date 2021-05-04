# Test Project


## Abstract
We developed an interest point detector to detect interest point location for **event camera images**. The idea was adapted from the literature *"SuperPoint: Self-Supervised Interest Point Detection and Description."* Daniel DeTone, Tomasz Malisiewicz, Andrew Rabinovich. ArXiv 2018. [1]

Our algorithm mainly consists of two parts:
We first train our detector network with synthetic event data. We then iteratively use the trained detector network to label interest points of a real-world dataset and train the network with the labeled dataset.


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
