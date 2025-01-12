# FANE
FANE is a Feature-Aware Nonlinear Ensemble (FANE) model for SDS-FSW mechanical property prediction that has been submitted to ADVEI. The code will be made public after the acceptance of the paper.
## Requirements
1.Python 3.x    

2.Pytorch 1.13.0  

3.torchvision  

4.pandas 

5.skimage

### Quick start
1.Clone this repository:  
git clone https://github.com/TJU-IRA/FANE.git  
2.Download our pre-trained models from the links below, unzip the models and place them to <td bgcolor=gray>./models. </td>

<table class="tg"><thead>
  <tr>
    <th class="tg-c3ow">Scale</th>
    <th class="tg-c3ow">Link</th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-c3ow">x2</td>
    <td class="tg-c3ow"><a href="https://drive.google.com/drive/folders/1jq6xowAfEymklsMCwllfrJ26723_yBcR?usp=sharing" target="_blank" rel="noopener noreferrer">[GoogleDrive]</a></td>
  </tr>
  <tr>
    <td class="tg-c3ow">x4</td>
    <td class="tg-c3ow"><a href="https://drive.google.com/drive/folders/1jq6xowAfEymklsMCwllfrJ26723_yBcR?usp=sharing" target="_blank" rel="noopener noreferrer">[GoogleDrive]</a></td>
  </tr>
  <tr>
    <td class="tg-c3ow">x8</td>
    <td class="tg-c3ow"><a href="https://drive.google.com/drive/folders/1jq6xowAfEymklsMCwllfrJ26723_yBcR?usp=sharing" target="_blank" rel="noopener noreferrer">[GoogleDrive]</a></td>
  </tr>
</tbody>
</table>

3.Then, cd to <td bgcolor=gray>FANE</td> and run  following commands:  
python test.py -opt options/test/test.yml

4.Finally, you can find the result in <td bgcolor=gray>./results .
