# TEST PROJECT


<table class="tg">
<thead>
  <tr>
    <th class="tg-0lax">
      <p align="center">
        <img src="https://github.com/picotank/testproject/blob/main/optical_flow.gif" width="420px">
      </p>
      Event Data Optical Flow Estimation
    </th>
    <th class="tg-0lax">
      <p align="center">
        <img src="https://github.com/picotank/testproject/blob/main/outdoor1_trajectory.png" width="420px">
      </p>
      Odometry Estimation
    </th>
  </tr>
</thead>
</table>

## Result
<p align="center">
  <img src="https://github.com/picotank/testproject/blob/main/rpe1.png" width="420px">
  <img src="https://github.com/picotank/testproject/blob/main/rpe2.png" width="420px">
</p>
* The evaluation is done under our evaluation scripts.
<table class="tg">
<thead>
  <tr>
    <th class="tg-0pky">Dataset</th>
    <th class="tg-0pky">Sequence</th>
    <th class="tg-0pky">RPE (median)</th>
    <th class="tg-0pky">RPE (mean)</th>
    <th class="tg-0pky">% Outlier (&gt;0.5)</th>
    <th class="tg-0pky">% Outlier (&gt;1.0)</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0pky">MVSEC</td>
    <td class="tg-0pky">Indoor_flying1</td>
    <td class="tg-0pky">0.3856</td>
    <td class="tg-0pky">0.5213</td>
    <td class="tg-0pky">38.63</td>
    <td class="tg-0pky">15.00</td>
  </tr>
  <tr>
    <td class="tg-0pky"></td>
    <td class="tg-0pky">Indoor_flying2</td>
    <td class="tg-0pky">0.3820</td>
    <td class="tg-0pky">0.5333</td>
    <td class="tg-0pky">39.79</td>
    <td class="tg-0pky">15.56</td>
  </tr>
  <tr>
    <td class="tg-0pky"></td>
    <td class="tg-0pky">Indoor_flying3</td>
    <td class="tg-0pky">0.4045</td>
    <td class="tg-0pky">0.5684</td>
    <td class="tg-0pky">39.36</td>
    <td class="tg-0pky">20.47</td>
  </tr>
  <tr>
    <td class="tg-0pky"></td>
    <td class="tg-0pky">Indoor_flying4</td>
    <td class="tg-0pky">0.5217</td>
    <td class="tg-0pky">0.5919</td>
    <td class="tg-0pky">52.41</td>
    <td class="tg-0pky">17.74</td>
  </tr>
  <tr>
    <td class="tg-0pky"></td>
    <td class="tg-0pky">Outdoor_day1</td>
    <td class="tg-0pky">0.1039</td>
    <td class="tg-0pky">0.1363</td>
    <td class="tg-0pky">1.44</td>
    <td class="tg-0pky">1.44</td>
  </tr>
  <tr>
    <td class="tg-0pky"></td>
    <td class="tg-0pky">Outdoor_day2**</td>
    <td class="tg-0pky">0.1301</td>
    <td class="tg-0pky">0.3527</td>
    <td class="tg-0pky">21.78</td>
    <td class="tg-0pky">16.83</td>
  </tr>
  <tr>
    <td class="tg-0pky"></td>
    <td class="tg-0pky">Outdoor_night</td>
    <td class="tg-0pky">0.1270</td>
    <td class="tg-0pky">0.2725</td>
    <td class="tg-0pky">15.88</td>
    <td class="tg-0pky">10.90</td>
  </tr>
  <tr>
    <td class="tg-0pky">IRJJ</td>
    <td class="tg-0pky">Poster_translation</td>
    <td class="tg-0pky">0.2678</td>
    <td class="tg-0pky">0.6211</td>
    <td class="tg-0pky">41.12</td>
    <td class="tg-0pky">34.67</td>
  </tr>
</tbody>
</table>
