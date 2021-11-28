## Task Description

The main goal of this task is to train a simple multi-label text classifier using a small dataset of articles with one or more topics assigned to them.

The articles can be found in this file: [https://drive.google.com/file/d/1oH97WOudbjwEUvFSmtQ7QcZlmcqgCUT0/view?usp=sharing](https://drive.google.com/file/d/1oH97WOudbjwEUvFSmtQ7QcZlmcqgCUT0/view?usp=sharing)

## Requirements

- You must use Python 3.8 or newer
- The input for the notebook does not need to be the .odf file on Google Cloud. Feel free to export the data in any format you think its best: csv, json, xml, etc.
- The delivery deadline should be ideally up to 1 week after receiving the assignment but its ok if you need more time.
- You should use the latest version of FastAI to train the model
- If you are having trouble with FastAI or feel much more comfortable with other library, like PyTorch, you can use it, however we will prefer candidates that stick to FastAI.

## Deliverable

The deliverable is a Jupiter Notebook that uses the data on Google Docs to train a simple multi label classifier using FastAI and show it working by classifying other texts not present on the provided dataset.

Build it like you were dealing with a large text dataset, but don't worry with the results as the dataset is very small we expect the model to be inaccurate.

What is important to us is to see if you are able to use FastAI, how the code is structured, documented and how do you measure the results of the model, no matter how bad the metrics are.

## Massive Bonus

If you are able to build the model, show it working and use Snorkel  ([https://www.snorkel.org/](https://www.snorkel.org/)) to apply keyword heuristics on the article topics, like biasing articles with the `money` keyword to be of the `finance` topic, you can consider yourself practically hired. 

Again, no matter how bad the metrics and result of the classifications are, we are evaluating the thought process, code structure, ability to use the libraries we need and the metrics you use to measure the quality of the model.

## Tips

- Create functions for common logic instead of duplicating the code
- Make sure the code is well documented
- Do not over-engineer things. We value simple solutions for complex problems.