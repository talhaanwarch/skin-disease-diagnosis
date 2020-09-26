# skin_cancer_detection_phone_camera
Diagnosis of Skin cancer using mobile phone camera and deep learning
# TO DO
Check formulas of metrics  
Add balance accuracy  
Add labels to ROC  

# SCENARIOs
SCENARIO I: Imagenet weights  
SCENARIO II: ISIC 2019 weights  
SCENARIO III: Imagenet weights +clinical features  
SCENARIO IV v1: ISIC 2019 weights + clinical features (ML ensemble)  
SCENARIO IV v2: ISIC 2019 weights + clinical features (DL ensemble)  
SCENARIO IV v3: ISIC 2019 weights + clinical features (parallel)  

# Base Paper
**The impact of patient clinical information on automated skin cancer detection**
Baseline with CNN (images): 0.710 F1-score
Baseline with CNN (images) + clinical features: 0.790 F1-score

<a href="https://www.sciencedirect.com/science/article/pii/S0010482519304019?via%3Dihub">Paper link</a>

# RESULT

<table>
<thead>
  <tr>
    <th>SCENARIOS</th>
    <th>Precision</th>
    <th>Recall</th>
    <th>F1 Score</th>
    <th>Accuracy</th>
    <th>AUC score</th>
    <th>Link</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>SCENARIO I</td>
    <td>0.806</td>
    <td>0.816</td>
    <td>0.810</td>
    <td>0.756</td>
    <td>0.814</td>
    <td><a href="https://github.com/talhaanwarch/skin_cancer_detection_phone_camera/blob/master/base_model.ipynb">Click here</a></td>
  </tr>
  <tr>
    <td>SCENARIO II</td>
    <td></td>
    <td></td>
    <td>0.805</td>
    <td>0.750</td>
    <td>0.809</td>
    <td><a href="https://github.com/talhaanwarch/skin_cancer_detection_phone_camera/blob/master/Scenario_II.ipynb">Click here</a></td>
  </tr>
  <tr>
    <td>SCENARIO III</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>SCENARIO IV</td>
    <td>0.896</td>
    <td>0.861</td>
    <td>0.877</td>
    <td>0.780</td>
    <td>0.816</td>
    <td><a href="https://github.com/talhaanwarch/skin_cancer_detection_phone_camera/blob/master/Scenario_IV.ipynb">Click here</a></td>
  </tr>
</tbody>
</table>

# ISIC 2019  
Implementation for ISIC 2019 competation is available [here](https://github.com/talhaanwarch/ISIC2K19)
