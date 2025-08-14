# Exploring-Argumentation-in-Indian-Parliamentary-Debates-Using-NLP
In contemporary Indian parliamentary debates, understanding argumentation patterns is crucial for practical policy analysis and decision-making. Exploring Indian parliamentary debates, helps to grasp their linguistic characteristics, rhetorical strategies,and political implications. By analyzing speeches, it aims to understand how language is used to persuade, argue, and negotiate in this context, shedding light on the dynamics of Indian democracy and parliamentary discourse.<br>
[Research Paper]()

### 📌 Table of Contents
* [Problem Statement](#abstract)
* [Introduction](#introduction)
* [Methodology](#methodology)
* [Dataset](#dataset)
* [Annotation](#annotation)
* [Preprocessing](#preprocessing)
* [Tasks](#tasks)
* [Authors](#authors)

<a id="problem_statement"></a>
### 📖 Problem Statement:
* Developing an AI-driven solution to analyze Indian parliamentary debates poses unique challenges due to the complexity of the language used, the diverse topics discussed, and the need to accurately capture the nuances of political discourse. The problem involves designing algorithms that can extract meaningful insights, such as sentiment analysis, key topic identification, and tracking the evolution of debates over time, to facilitate a deeper understanding of parliamentary proceedings.

<a id="introduction"></a>
### 📚 Introduction:
* Argumentation in parliamentary debates refers to the process by which members of parliament present and defend their viewpoints on a particular issue. This project employs Natural Language Processing (NLP) techniques to delve into discourse dynamics, explicitly focusing on political alignment, gender representation, and opinion-topic analysis.

<a id="methodology"></a>
### ⚙️ Methodology Workflow:
![Flowchart Image](flowchart.png?raw=true "Title")

<a id="dataset"></a>
### 📊 Dataset: 
* The synopsis of Lok Sabha debates will be extracted from Digital Sansad (website) using a web crawler for the past five years. A generic software will be created to convert unstructured PDFs into structured formats to extract information.

<a id="annotation"></a>
### ✍🏼 Annotation:
* Analyzing the speeches in the Lok Sabha, we realized that every speech not only reflects a for or against stance in a particular matter but rather it has various hidden intents. For example, an MP can blame the government’s bill or raise an issue in Parliament. For this, we subdivided/annotated the collected dataset based on its content and intention in the following five categories: Motion to Raise Issue, Blame on Govt, Appreciative of Govt, Call For Action, and Neutral statements. This provides for a comprehensive analysis of the variety of speeches in Lok Sabha.

<a id="preprocessing"></a>
### 📝 Preprocessing: 
* This step is a prerequisite to training and extracting patterns in the written text. It involves using NLP techniques to clean and preprocess the collected data, using text normalization, tokenization, and removal of noise and irrelevant information. In our dataset, it also includes removing interruptions, and foreign language words from the corpus for enhanced accuracy.

<a id="tasks"></a>
### 💻  Tasks: 
- [ ] Key Phrase Extraction: We used techniques such as RAKE (Rapid Automatic Keyword Extraction), and ngrams to extract meaningful words and phrases. It helps to understand the most commonly used phrases and the significance of topics in the discussions in Lok Sabha.
- [ ] Polarity & Sentiment: Libraries such as Vader and Textblob are used for determining the consolidative sentiment of the speakers towards the issue or agenda. For example, a negative polarity determines that the house was critical of the bill, whereas a positive polarity denotes general consent.
- [ ] Similarity Clustering: Various ML algorithms such as agglomerative clustering are used to ascertain similar agendas over the years. It is indicative of the agendas/bills that have received similar attention in debates of Lok Sabha.
- [ ] Gender Representation Analysis: We intend to explore the impact of reservation policies on women's participation in parliamentary debates, analyzing whether reserved seats for women lead to increased involvement and influence. 

<a id="authors"></a>
## 👤 Authors
Contributors names and contact info :

Samya Jain<br>
[@Linkedin](https://www.linkedin.com/in/samya-jain-a68443204)
<br>
[@Github](https://github.com/samya02)
<br>

Kashika Akhouri<br>
[@Linkedin](https://www.linkedin.com/in/kashika-akhouri-050b4a202/)
<br>
[@Github](https://github.com/kashika0112)
<br>

Tanya Chhikara<br> 
[@Linkedin](https://www.linkedin.com/in/tanyachhikara24/)
<br>
[@Github](https://github.com/TanyaChhikara)
<br>

Punerva Singh<br> 
[@Linkedin](https://www.linkedin.com/in/punerva-singh-958305204)
<br>
[@Github](https://github.com/punervasingh)
<br>
