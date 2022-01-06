# [CLINC_OSS](https://www.tensorflow.org/datasets/catalog/clinc_oos)

## Overview

* These notebooks have different techniques which I used to do intent classification in clinc_oss dataset.
* The data folder have dataset which is used to create these notebooks.

## Context

* We have 150 intents in the dataset which we have to classify. And those sentences which don't fall on any intents we have to classify it as Out of Scope(oos). So, we have 150 + 1 = 151 intents. I have created multiple notebooks which have classification of intents without Out of Scope(oos) and with oos. You can read the descriptions of notebooks on below table. And the results of notebooks in Results section

## Notebooks Description

| Notebook | Description |
|--------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [1_clinc_oos_RNN_CNN_Glove_no_oos](https://github.com/ianuragbhatt/clinc_oos/blob/main/1_clinc_oos_RNN_CNN_Glove_no_oos.ipynb) | RNN+CNN using Glove Embeddings with no oos intent.  |
| [2_clinc_oos_RNN_CNN_Glove_with_oos](https://github.com/ianuragbhatt/clinc_oos/blob/main/2_clinc_oos_RNN_CNN_Glove_with_oos.ipynb) | RNN+CNN using Glove Embeddings with oos intent. |
| [3_clinc_oss_BERT_with_oos](https://github.com/ianuragbhatt/clinc_oos/blob/main/3_clinc_oss_BERT_with_oos.ipynb) | RNN+CNN with BERT Embeddings with oos intent. |

## Results

Below table have Accuracy Score(ACC), Adjusted Random Score(ARS), Normalized Mutual Info(NMI) which I got on CLINC_OOS Dataset.

| Notebooks| ACC  | ARS  | NMI  |
|-----------|--------|--------|------------|
| [1_clinc_oos_RNN_CNN_Glove_no_oos](https://github.com/ianuragbhatt/clinc_oos/blob/main/1_clinc_oos_RNN_CNN_Glove_no_oos.ipynb)  | 91.4  | 83.74  | 93.45  |
| [2_clinc_oos_RNN_CNN_Glove_with_oos](https://github.com/ianuragbhatt/clinc_oos/blob/main/2_clinc_oos_RNN_CNN_Glove_with_oos.ipynb)  | 77.22  | 19.48  | 82.52  |
| [3_clinc_oss_BERT_with_oos](https://github.com/ianuragbhatt/clinc_oos/blob/main/3_clinc_oss_BERT_with_oos.ipynb)  | 80.75  | 28.2  | 84.42  |

## Contribution

Contributions are welcome!  For bug reports or requests please [submit an issue](https://github.com/ianuragbhatt/clinc_oos/issues).

## contact-info

Feel free to contact me to discuss any issues, questions, or comments.

* Email : [anur4g.bhatt@gmail.com](mailto:anur4g.bhatt@gmail.com)
* Medium : [ianuragbhatt](https://ianuragbhatt.medium.com/)
* Twitter : [@ianuragbhatt](https://twitter.com/ianuragbhatt)
* GitHub : [ianuragbhatt](https://github.com/ianuragbhatt)
* LinkedIn : [ianuragbhatt](https://www.linkedin.com/in/ianuragbhatt)
