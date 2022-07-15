# LRW_ID
This repository contains the speaker labeled information of LRW audio-visual dataset, which is the outcome of the following paper:
> **Speaker-adaptive Lip Reading with User-dependent Padding**<br>
> Minsu Kim, Hyunjun Kim, and Yong Man Ro<br>
> \[[Paper](link)\]

## Data structure
`LRW_ID_v1.0.txt` contains the speaker ID for each video.
Each line contains speaker ID number and its corresponding video name.
```shell
#Example
4243 SERVICES/train/SERVICES_00456
```
The line represents that the speaker ID of video SERVICES/train/SERVICES_00456.mp4 is 4243.

## LRW_ID data splits
In order to build unseen-speaker scenario (train and test speakers are not overlapped), 20 speakers are selected for test and validation (adaptation).
The dataset splits can be found in the `Splits` directory.

For the dataset information, please refer our paper.

### Contributing
For more accurate speaker information, we welcome your participation in improving label information.

<!--## Citation
If you use the identity labeled LRW dataset, LRW-ID, please cite the paper:
```
@article{kim2022distinguishing,
  title={Distinguishing Homophenes using Multi-head Visual-audio Memory for Lip Reading},
  author={Kim, Minsu and Yeo, Jeong Hun and Ro, Yong Man},
  year={2022}
}
```
-->
