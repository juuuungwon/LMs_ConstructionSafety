# LMs_ConstructionSafety<br>
The objective of this study is to develop and evaluate prototypes of a construction safety specialized LLM and RAG model.<br><br>


## RAG Model<br>
To utilize the RAG model, the dump file of the Knowledge Graph (KG) is installed on Neo4j.

The reference of RAG inference process is [here](https://github.com/juuuungwon/LMs_ConstructionSafety/blob/main/RAG-inference-eg.ipynb).


### Neo4j Dump File<br>
You can download the dump file for the Knowledge Graph (KG) from the following link:
[Neo4j KG Dump File](https://github.com/juuuungwon/LMs_ConstructionSafety/blob/main/constructionsafety-KG.dump)<br><br>



## Fine-Tuning Model<br>
For the fine-tuning process, a QA dataset is utilized. This dataset is based on KOSHA GUIDELINES published by the Korean Occupational Safety and Health Administration.<br>

The dataset is uploaded on HuggingFace: [DBCMLAB/Constructionsafety_QApairs](https://huggingface.co/datasets/DBCMLAB/Constructionsafety_QApairs).<br>

The fine-tuned model is uploade on HuggingFace: .[DBCMLAB/KoAlpaca-Pyglot-12.8B-ConstructionSafety](https://huggingface.co/DBCMLAB/KoAlpaca-Pyglot-12.8B-ConstructionSafety).<br>




## Result
