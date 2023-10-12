# LRW_ID
This repository contains the speaker labeled information of LRW audio-visual dataset, which is the outcome of the following paper:
> **Speaker-adaptive Lip Reading with User-dependent Padding**<br>
> Minsu Kim, Hyunjun Kim, and Yong Man Ro<br>
> \[[Paper](https://arxiv.org/abs/2208.04498)\]

## Data structure
`LRW_ID_v1.0.txt` contains the speaker ID for each video.
The total number of labeled speakers is 17,580 (0 ~ 17,579). <br>
Each line contains speaker ID number and its corresponding video name.
```shell
#Example
4243 SERVICES/train/SERVICES_00456
```
The line represents that the speaker ID of video SERVICES/train/SERVICES_00456.mp4 is 4243.

## LRW_ID data splits
In order to build unseen-speaker scenario (train and test speakers are not overlapped), 20 speakers are selected for test and validation (adaptation).
The dataset splits can be found in the `Splits` directory.

<div align="center"><img width="40%" src="img/Split_info.PNG?raw=true" /></div>
<div align="center"> Table 1. LRW_ID data splits. </div>
<br>
<br>
<div align="center"><img width="80%" src="img/Speaker_info.PNG?raw=true" /></div>
<div align="center"> Table 2. 20 speakers in the test set. They are not overlapped with the speakers in the train set. </div>
<br>
<br>
For more information, please refer to our paper.

### Contributing
For more accurate speaker information, we welcome your participation in improving label information.

## Citation
If you use the identity labeled LRW dataset, LRW-ID, please cite the paper:
```
@inproceedings{kim2022speaker,
  title={Speaker-adaptive lip reading with user-dependent padding},
  author={Kim, Minsu and Kim, Hyunjun and Ro, Yong Man},
  booktitle={European Conference on Computer Vision},
  pages={576--593},
  year={2022},
  organization={Springer}
}
```
