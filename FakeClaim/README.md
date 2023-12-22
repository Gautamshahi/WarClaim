# FakeClaim: A YouTube video Dataset for Identification of Fake News on the 2023 Israel-Hamas War


This repository contains the first publicly available dataset of factual claims and fake YouTube videos on the 2023 Israel-Hamas war for auto-matic fake video classification. 
The claim data is collected from 60 fact-checking websites in 30 languages and enriched with metadata from the fact-checking websites. 
These sites are curated by trained journalists specialized in fact-checking. Further, we classify fake videos for the subset of YouTube videos using textual information and user comments. 
We used the pre-trained model to classify the video with different feature combinations. Our best-performing fine-tuned pre-trained model, Universal sentence encoder, 
achieves a Macro F1 of 87%, which shows that the trained model can be helpful for the prebunking of fake videos using user discussion as comments
