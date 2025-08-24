### Code for **'What is in a name? Mitigating Name Bias in Text Embedding Similarity via Anonymization'**
### Authors: Sahil Manchanda and Pannaga Shivaswamy
### Published at ACL Findings 2025.
### Paper link: https://aclanthology.org/2025.findings-acl.914.pdf



#### Installation 
`pip install -r requirements.txt`
<br/><br/>

##### Config
Add api keys in `config`. <br/>

#### Download data files
Download the files present in https://drive.google.com/drive/folders/1RjnTvOZsEgdwgndennxHaQ1Yp61VKQM9?usp=sharing and store inside BENCHMARKING/cmu_book folder


### Benchmarking  Experiments

 In order to run benchmarking experiments to measure bias in text-embedding models, run the following scripts in order.

* `Run notebook benchmark_create_embeddings` : **_Create embeddings_**

* `Run notebook benchmark_similarity_computation` : **_Compute similarity metric_**

<br/>

### Semantic Similarity Task 1 
 To run STS experiment run the following codes:

* `Run notebook STS_Task_1` :  **_This notebook runs STS Task 1._**  

<br/>

### Semantic Similarity Task 2
 To run STS experiment task with graded relevance run the following codes in order:

* `Run notebook STS_Task2_anonymize` : **_This notebook Performs anonymization._**

* `python STS_Task2_embed_and_evaluate` : **_This notebook computes embedding and performs evaluation._**


### Semantic Similarity Task 3: Paraphrase
 To run STS experiment task on Paraphrase detection:

* `Run notebook STS_Task3_Paraphrase` : **_This notebook Performs anonymization and evaluation._**


 
 
