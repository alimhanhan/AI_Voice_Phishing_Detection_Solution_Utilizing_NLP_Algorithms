# 📞A.I Voice Phishing Detection Solution Utilizing NLP Algorithms📞

https://github.com/alimhanhan/A.I_Voice_Phishing_Detection_Solution_Utilizing_NLP_Algorithms/assets/102565567/c8506bd6-b5a6-4d0b-b4a4-ed3b0ff6072f

<br><br><h2>🐟 Project Organizations Link</h2>
-->  https://github.com/Voice-Phishing-Prevention-Project<br>
<br><img width="319" alt="스크린샷 2023-11-03 121236" src="https://github.com/alimhanhan/test/assets/102565567/8908dce2-5d19-410e-a47d-d7f587cc4585">


<br><br><h2>🐟 Contents_1) Introduction to Project Background </h2>
<details>
<summary><h3>📑Analysis of Market & Tech Trends</h3></summary>
<div markdown="1">
<h3>👁️‍🗨 The Evolving Techniques of Voice Phishing & Increasing Risks</h3>

<img width="622" alt="스크린샷 2023-11-01 105929" src="https://github.com/alimhanhan/A.I_Voice_Phishing_Detection_Solution_Utilizing_NLP_Algorithms/assets/102565567/edadb3ec-4ec8-4d50-a58e-fcb1107cf4fa">

<h4>ㅤAs seen in the article, voice phishing techniques are evolving by the day. Existing voice phishing prevention apps are already active in the smartphone domain, but there is a significant limitation in that they are relatively unfamiliar in areas such as internet telephony and landline calls.<br><br>ㅤTherefore, we aim to develop a system that can analyze conversation contents in real-time to discern instances of voice phishing and effectively communicate this for some vulnerable groups susceptible to voice phishing. </h4><br><br>

<img width="621" alt="스크린샷 2023-11-01 110044" src="https://github.com/alimhanhan/A.I_Voice_Phishing_Detection_Solution_Utilizing_NLP_Algorithms/assets/102565567/c8399972-efe3-48b4-b2cd-093d5f39dd5f">

<h4>ㅤFurthermore, existing voice phishing prevention methods are primarily designed for non-disabled individuals, posing limitations in terms of accessibility and usability for people with visual, auditory, cognitive, and other disabilities.<br><br>ㅤTherefore, we aim to develop a system that facilitates individuals with disabilities to more easily benefit from voice phishing prevention technology.</h4><br><hr><br>
</details>
<details>
</div>
<summary><h3>📑Points of Differentiation from Existing Ideas & Products</h3></summary>
<div markdown="1">
<h3>👁️‍🗨️ Competitiveness of the Idea in terms of Functionality & Usability</h3>

<img width="608" alt="스크린샷 2023-11-01 110234" src="https://github.com/alimhanhan/A.I_Voice_Phishing_Detection_Solution_Utilizing_NLP_Algorithms/assets/102565567/35c615a0-e529-410e-8050-a63938644820">


<h4>ㅤMany services currently available in the market primarily focus on detecting phishing on smartphones, making it difficult for the elderly population, who may not be familiar with smartphone usage, to detect voice phishing. <br><br>ㅤAdditionally, while non-disabled individuals can use the service without inconvenience, there is no separate convenience device for people with disabilities, leading to difficulties for them in using such services.</h4><br>
<h3>➡️ For the reasons mentioned, this project has designated landline phones, rather than smartphones, as the primary target. The service has been designed with the primary target in mind, enabling easy and accurate phishing detection even on regular landline phones.<br><br> Additionally, to facilitate clear signal identification for disabled users, a method of conveying phishing alerts through both voice and text has been adopted.</h3>

<br><hr><br>
</div>
</details>

<br><br><br><h2>🐟 Contents_2) Hardware design and Implementation</h2>
<details>
<summary><h3>📑Sensors & Components Used</h3></summary>
<div markdown="1">

<img width="827" alt="스크린샷 2023-11-01 110804" src="https://github.com/alimhanhan/A.I_Voice_Phishing_Detection_Solution_Utilizing_NLP_Algorithms/assets/102565567/a8b9ca46-a83e-491c-8655-798d484e17da">

<br><hr><br></details>
<details>
</div>
<summary><h3>📑Detailed Hardware Design</h3></summary>
<div markdown="1">

<img width="681" alt="스크린샷 2023-11-01 110623" src="https://github.com/alimhanhan/A.I_Voice_Phishing_Detection_Solution_Utilizing_NLP_Algorithms/assets/102565567/c18f6d8a-9e42-45d8-a40a-aca06e4cf33d">


<br><hr><br>
</div>
</details>

<br><br><br><h2>🐟 Contents_3) Service Architecture & User Scenarios</h2><br>

<img width="630" alt="스크린샷 2023-11-01 110951" src="https://github.com/alimhanhan/A.I_Voice_Phishing_Detection_Solution_Utilizing_NLP_Algorithms/assets/102565567/3aa68415-a8cc-4f41-ac47-f6794065d886">


<details>
<summary><h3>📑Detailed Service Flow</h3></summary>
<div markdown="1">
<h3>👁️‍🗨️ Detailed UX</h3>

![스크린샷 2023-11-02 191134](https://github.com/alimhanhan/A.I_Voice_Phishing_Detection_Solution_Utilizing_NLP_Algorithms/assets/102565567/8afff2c4-d4f5-498c-b2e4-1784e6c2be4a)


<h4>
1️⃣ When the recipient initiates a call with the sender, AWS Transcribe collects the contents of the conversation in real time and performs Speech-to-Text (STT).<br><br>After that, utilizing natural language processing model algorithms, it undergoes preprocessing and is stored in a database. Using the stored database, it provides phishing alert functionality.<br>
<br><br><br>2️⃣ Based on the conversation content database, a pre-trained and customized NLP algorithm conducts binary classification for phishing detection.
 <br><br>Ultimately, this result is communicated to the user through text and a light signal to indicate the presence of phishing.
</h4>
</details>
<details>
<summary><h3>📑Explanation of the Service Flow</h3></summary>
<div markdown="1">
<h3>👁️‍🗨️ Additional Explanations for Each Step</h3><br>

<img width="595" alt="스크린샷 2023-11-01 111050" src="https://github.com/alimhanhan/A.I_Voice_Phishing_Detection_Solution_Utilizing_NLP_Algorithms/assets/102565567/8329f946-3a03-4e42-8bc5-b2ffce1e256e">

<img width="611" alt="스크린샷 2023-11-01 111059" src="https://github.com/alimhanhan/A.I_Voice_Phishing_Detection_Solution_Utilizing_NLP_Algorithms/assets/102565567/d88f53e2-62c8-4dd9-af77-c1687e8f12a5">

 
 <h4>
<br>1️⃣  Start recording voice at the beginning of the call.<br>
<br>2️⃣  Save the recorded data on the laptop at the end of the call.<br>
<br>3️⃣  Upload the MP3 file to Google Colab from the laptop.<br>
<br>4️⃣  Transfer the file from Google Colab to the AWS S3 bucket.<br>
<br>5️⃣  Perform speech-to-text (STT) on the file stored in the S3 bucket.<br>
<br>6️⃣  Save the STT results in a .json file.<br>
<br>7️⃣  Transmit the saved JSON file to the model.<br>
<br>8️⃣  Classify the presence of phishing in the model.<br>
<br>9️⃣  Save the derived classification results to the AWS S3 bucket.<br>
<br>🔟➖🅰️ Read the values stored in the S3 bucket on the Raspberry Pi.<br>
<br>🔟➖🅱️ Read the values stored in the S3 bucket on the responsive Flask web.<br>
<br>1️⃣1️⃣➖🅰️ Provide guidance through LED flashing based on the result.<br>
<br>1️⃣1️⃣➖🅱️ Provide guidance through a web pop-up window based on the result.</h4>
<br><hr><br>
</details>

<br><br><br><h2>🐟 Contents_4) Used Algorithms and Models</h2>
<details>
<summary><h3>📑Algorithm Specifications</h3></summary>
<div markdown="1">
<h3>👁️‍🗨️ Voice Phishing Detection Algorithm Through Voice Data Processing</h3><br>

![스크린샷 2023-11-02 192343](https://github.com/alimhanhan/A.I_Voice_Phishing_Detection_Solution_Utilizing_NLP_Algorithms/assets/102565567/43011728-5473-46e0-94a2-e8a40e4381b0)

<h4><br>1️⃣ Send the collected voice file data to the AWS Transcribe server.
<br><br>2️⃣ Perform speech-to-text (STT) through AWS Transcribe and preprocess the text data obtained from the file.
<br><br>3️⃣ Perform binary classification on the phishing status based on the preprocessed text data using an appropriate model.</h4>
-->  Return 1 if phishing, and 0 if not phishing.<h4>
4️⃣ Based on the result, perform text notification and LED notification services.</h4>
--> red LED(🔴) for phishing, green LED(🟢) for non-phishing<h4>
5️⃣ Terminate all services upon completion.</h4><br><hr><br>
</details>
<details>
<summary><h3>📑Model Selection</h3></summary>
<div markdown="1">
<h3>👁️‍🗨️ Model Training Performance Evaluation</h3>

![스크린샷 2023-11-02 193500](https://github.com/alimhanhan/A.I_Voice_Phishing_Detection_Solution_Utilizing_NLP_Algorithms/assets/102565567/12ee705f-d498-4270-b8b0-7c0943dfc2a1)

<br><h4>ㅤBased on the model performance comparison results, both the accuracy and F1-score evaluation metrics confirm the superiority of KoBIGBIRD. Furthermore, an inference test was conducted using a new test dataset consisting of 10 normal datasets and 10 phishing datasets, where both models correctly classified 19 out of the 20 test data.</h4><h3>➡️ Consequently, the KoBIGBIRD model was selected for use in voice phishing detection, and the solution proceeded accordingly. </h3><br><hr><br></details>
<details>
<summary><h3>📑Model Concatenation</h3></summary>
<div markdown="1">
<h3>👁️‍🗨️ Considered & Utilized Models</h3>
<h4>⏩ In this project, we utilized the concatenation and customization of the KoBIGBIRD, R-BERT, and KR-BERT models.</h4>

![스크린샷 2023-11-02 193837](https://github.com/alimhanhan/A.I_Voice_Phishing_Detection_Solution_Utilizing_NLP_Algorithms/assets/102565567/5d8cc645-747c-49a3-9bae-8ee3cafaaec5)


<h3>#️⃣ KoBIGBIRD</h3>
<h4>KoBIGBIRD is a model developed for Korean natural language processing, based on Transformers. It can handle longer sequences than conventional BERT, dealing with a maximum of 4096 tokens, eight times more than BERT's 512 tokens.</h4>
<br><h3>#️⃣ KR-BERT</h3>
<h4>A BERT-based model for Korean natural language processing, KR-BERT provides excellent performance in various NLP tasks through pre-training tailored to Korean text, learning sentence and word-level representations. In the field of Korean natural language processing, KR-BERT is utilized for various NLP tasks, including semantic interpretation and sentence structure analysis.</h4>
<br><h3>#️⃣ R-BERT</h3>
<h4>R-BERT, based on BERT, is specialized in context-aware entity relationship inference, effectively inferring relationships between entities in natural language processing tasks. By integrating entity and relationship information, it achieves improved performance in information extraction and relationship inference tasks.</h4>
<br><hr><br></details>
<details>
<summary><h3>📑Model Customization</h3></summary>
<div markdown="1">
<h3>👁️‍🗨️ The Process of Model Customization</h3>
<h4>ㅤOur custom model is inspired by the R-BERT model and built upon the architecture of the KoBIGBIRD model. In the Relation Extraction Task, the R-BERT model enhances its performance by utilizing not only the CLS token but also the embedding vectors of entity1 and entity2.<br><br>ㅤIn this regard, our model can be characterized as a customized model that leverages not only the CLS token but also the entire dialogue data, extracted morphemes and keywords, and their respective embedding vectors in the training process.<br><br>ㅤFurthermore, by combining the CLS tokens of Kr-BERT and KoBIGBIRD, our model aims to integrate the diverse features of both models, leveraging their respective strengths and compensating for their shortcomings.</h4>

 
![스크린샷 2023-11-02 194711](https://github.com/alimhanhan/A.I_Voice_Phishing_Detection_Solution_Utilizing_NLP_Algorithms/assets/102565567/a32c8d54-cb69-49dd-999b-87a0c5cbdfbc)


<h4>ㅤThis model combines the embedding values of the CLS tokens from Kr-BERT and KoBIGBIRD.<br><br>ㅤSubsequently, the entire dialogue data and the data extracted only for keywords and morphemes are separated into vectors using an index that indicates the end of the sentence. This process is designed to understand the context of the conversation through the entire dialogue data and to learn the important parts of the conversation through morphemes and keywords.<br><br>ㅤFinally, through the FCLayer class, the dimensions of each vector are adjusted and combined to create a single vector, which is used as the input value of the model. Using this generated data, the model can predict the final class, i.e., whether it is a phishing attempt, through the label classifier.<br><br>ㅤBy combining Kr-BERT's language understanding capabilities and KoBIGBIRD's ability to handle long texts, the model incorporates various features of the input text. It is expected to leverage KoBIGBIRD's strengths in handling long dialogue data and Kr-BERT's strengths in understanding subtle meanings and expressions within sentences.</h4>
<br><hr><br></details>

<br><br><br><h2>🐟 Contents_5) Collected Data & Methodology for Utilization.</h2>
<details>
<summary><h3>📑 The Types of Collected Data</h3></summary>
<div markdown="1">

![스크린샷 2023-11-02 194843](https://github.com/alimhanhan/A.I_Voice_Phishing_Detection_Solution_Utilizing_NLP_Algorithms/assets/102565567/a945031a-fa26-4f77-9db3-6af269de9a80)
<br><h4>👉ㅤIn this project, the collected data is in unstructured form, categorized into phishing and legitimate data. To address class imbalance, augmentation was conducted only for the phishing data.</h4>
<br><h4> Financial Supervisory Service Voice Phishing Voice Data:</h4>
➖ Loan fraud type: 185 instances<br>
➖ Financial fraud type: 227 instances
<h4>👉 AI Hub Complaints Query-Response Data:</h4>
➖ Financial/Insurance, Transfer, Withdrawal, Loan Service Type: 48,476 instances
<br><hr><br></details>
<details>
<summary><h3>📑 Data Collection Methodology</h3></summary>
<div markdown="1">
<h4>
1️⃣ Collecting phishing voice data through dynamic web crawling.
<br><br>2️⃣ Downloading legitimate data.
<br><br>3️⃣ Transforming the data using AWS Transcribe and uploading it as JSON files.
<br><br>4️⃣ Creating TXT files through data parsing.
<br><br>5️⃣ Converting the generated TXT files into CSV files.
</h4>
<br><hr><br></details>
<br><br><br>


