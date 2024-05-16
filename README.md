# NLG-rPPG-dataset

## 1.Overview
NLG-rPPG dataset is a dataset consists of 3 lighting conditions which collected in indoor environment. In order to evaluate the performance of deep learning based rPPG under different lighting conditions, we recruited fourteen healthy subjects (10 males and 4 females) on campus, with a  mean age of 23, SD of 1.95. 

## 2.Device setup
There is only a light sources (a fill-in light) that creates different lighting conditions. The ground truth PPG data is obtained by using a finger-type HKG-07C infrared pulse sensor. Video data synchronized with the pulse oximeter was recorded using an Intel RealSense D455C camera. 

![Alt text](images/collection.jpg)

## 3.Data details
The videos had a resolution of 640 * 480, and the actual frame rate of the camera was 30 fps. The illuminance levels for the three lighting conditions were 25 Lux, 45 Lux, and 100 Lux, respectively. For each subject, we recorded two one-minute videos under each lighting condition, resulting in a total of six video clips per individual and 84 (14*3*2) video clips in total. The example of different lighting conditions are shown below.

![Alt text](images/examples.jpg)

## 4.Contact
Zinan Huang (znhuang@njust.edu.cn), Nanjing University of Science and Technology

## 5.Download
* This database is released to universities and research institutes for research purpose only.

* Note that please contact znhuang@njust.edu.cn for requests using an official email address (that is, university or institute email address, and non-official email addresses such as Gmail and 163 are not acceptable). When we receive your reply, we would provide the download link to you.

## 6.Citation
If you find our paper or this dataset useful for your research, please cite our work.

@article{Huang2024DeepLR,
  title={Deep learning-based robust heart rate estimation using remote photoplethysmography under different illuminations},
  author={Zinan Huang and Chang-Hong Fu and Li Zhang and Hong Hong},
  journal={Fifteenth International Conference on Signal Processing Systems (ICSPS 2023)},
  year={2024},
  url={https://api.semanticscholar.org/CorpusID:268826631}
}
