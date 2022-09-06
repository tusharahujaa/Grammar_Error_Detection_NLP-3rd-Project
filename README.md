# Grammar_Error_Detection_NLP(3rd Project)
## Grammar checker using BERT and XLNET.

**Input:** Sentence.

**Output:** If it is grammatically correct or not(using both BERT and XLNET).

Both models here are trained on Google-colab and after training the classifiers are downloaded and further used for grammar checking. 

I have used The Corpus of Linguistic Acceptability (CoLA) dataset for predicting a single sentence as grammatically correct or not. The dataset used consists a set of sentences labeled as grammatically correct or incorrect represented by labels 1 and 0 respectively. It was first published in May of 2018, and is one of the tests included in the "GLUE Benchmark" on which models like BERT are competing.

### Requirements
#### Install Required Libraries

```bash
   pip install tensorflow
```
```bash
   pip install transformers
```
```bash
   pip install torch
```
```bash
   pip install wget
```
```bash
   pip install numpy 
```
```bash
   pip install pandas
```
```bash
   pip install seaborn
```
```bash
   pip install matplotlib
```
```bash
   pip install scikit-learn
```
