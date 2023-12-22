# FakeClaim: A YouTube video Dataset for Identification of Fake News on the [2023 Israel–Hamas war](https://en.wikipedia.org/wiki/2023_Israel%E2%80%93Hamas_war)


This repository contains the first publicly available dataset of factual claims and fake YouTube videos on the 2023 Israel-Hamas war for automatic fake video classification. 
The claim data is collected from 60 fact-checking websites in 30 languages and enriched with metadata from the fact-checking websites. 
These sites are curated by trained journalists specialized in fact-checking. Further, we classify fake videos for the subset of YouTube videos using textual information and user comments. 
We used the pre-trained model to classify the video with different feature combinations. Our best-performing fine-tuned pre-trained model, Universal sentence encoder, 
achieves a Macro F1 of 87%, which shows that the trained model can be helpful for the prebunking of fake videos using user discussion as comments.

## Data Details
The dataset contains around 1500 YouTube videos in 2 different categories. The format of data is as follows.

* **video_id** - unique ID of a Tweet
* **video_class** - class of the tweet defined by us.


#### How do I cite this work?

Please cite the [ECIR 2024 paper](https://doi.org/10.1016/j.osnem.2020.100104):

```
@inproceedings{shahi2024fakeclaim,
  title={FakeClaim: A YouTube video Dataset for Identification of Fake News on the 2023 Israel-Hamas War},
  author={Shahi, Gautam Kishore and Jaiswal, Amit Kumar and Mandl, Thomas},
  booktitle={Advances in Information Retrieval: 46th European Conference on IR Research, ECIR 2024, Virtual Event, March 24--28, 2024},
  year={2024}
}
```


## Contact information

For help or issues using data, please submit a GitHub issue.
