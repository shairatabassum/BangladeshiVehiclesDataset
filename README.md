# Poribohon-BD: BangladeshiVehiclesDataset

A partial dataset has been uploaded here. The complete dataset is available at [Mendeley (Poribohon-BD)](https://data.mendeley.com/datasets/pwyyg8zmk5/1).

<br>

Poribohon-BD is a vehicle dataset of 15 native vehicles of Bangladesh. The dataset contains a total of 9058 images with a high diversity of poses, angles, lighting conditions, weather conditions, backgrounds. All of the images are in JPG format. The dataset also contains 9058 image annotation files. These files state the exact positions of the objects with labels in the corresponding image. The annotation has been performed manually and the annotated values are stored in XML files. LabelImg tool by Tzuta Lin has been used to label the images. Moreover, data augmentation techniques have been applied to keep the number of images comparable to each type of vehicle. Human faces have also been blurred to maintain privacy and confidentiality. The data files are divided into 15 individual folders. Each folder contains images and annotation files of one vehicle type. The 16th folder titled ‘Multi-class Vehicles’ contains images and annotation files of more than one type of vehicle. Poribohon-BD is compatible with various CNN architectures such as YOLO, VGG-16, R-CNN, DPM.<br><br>

<h2>Dataset Description</h2>

|  Vehicle Name | Data Augmentation | Total Images | Total Appearance |
| :------------ |:-----------------:| :-----------:| :--------------: |
| Bicycle       |         -         |     707      |      1617        |
| Boat          |         -         |     613      |      1974        |
| Bus           |         -         |     452      |      3711        |
| Car           |         -         |     708      |      1698        |
| CNG           |         -         |     533      |      3214        |
| Easy-bike     |        261        |     616      |      2062        |
| Horse-cart    |        306        |     256      |      1581        |
| Launch        |        128        |     662      |       332        |
| Leguna        |         -         |     218      |      1686        |
| Motorbike     |        107        |     864      |       746        |
| Rickshaw      |         -         |     495      |      3386        |
| Tractor       |        216        |     433      |       509        |
| Truck         |        362        |     736      |      1673        |
| Van           |        298        |     615      |      2057        |
| Wheelbarrow   |        113        |     237      |       605        |
| Multi-class   |         -         |     913      |        -         |

<br>

<h2>Cite our paper:</h2>
<table>
  <tr>
    <td>Plain Text</td>
    <td>S. Tabassum, M. S. Ullah, and S. Shatabda, "Native Vehicles Classification on Bangladeshi Roads Using CNN with Transfer Learning," IEEE Region 10 Symposium (TENSYMP) 2020, Dhaka, Bangladesh, 2020.</td>
  </tr>
  <tr>
    <td>BibTeX</td>
    <td>@inproceedings{shaira2020native,<br>
      author={S. {Tabassum} and M. S. {Ullah} and S. {Shatabda}},<br>
      booktitle={IEEE Region 10 Symposium (TENSYMP) 2020},<br>
      title={Native Vehicles Classification on Bangladeshi Roads Using CNN with Transfer Learning},<br>
      year={2020},<br>
      publisher={IEEE}}</td>
  </tr>
</table>
