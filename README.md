# A Baseline Analysis for Podcast
This repo is for our paper "A Baseline Analysis for Podcast Abstractive Summarization". In this paper, we build several baseline models, and also fine-tuned the current state-of-the-art (SOTA) summarization models on podcast dataset. 

Detailed codes and pre-trained models will be released after the TREC 2020 competition.

## Local Setup

Tested with Python 3.7 via virtual environment.

Clone the repo, go to the repo folder, setup the virtual environment, and install the required packages:

```bash
$ python3 -m venv venv
$ source venv/bin/activate
$ pip install -r requirements.txt
```

## Example

In the ```example``` folder, you can find some sample generated podcast summaries from different models.