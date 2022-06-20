# Medical-QA-data
**iclinic-data:**
Contains questions related to diabetes, extended question texts, answers and tags. Tags were collected from question url meta-data.  
**quora-data:**
Contains questions related to diabetes, anwsers and tags. Tags were assigned using glossary terms from the international diabetes forum (IDF) (https://www.idf.org/aboutdiabetes/what-is-diabetes/glossary.html) *LAST UPDATE: 18/06/2019*. 
**generated questions:**__ 
models used to generate questions:__ 
default (https://huggingface.co/valhalla/t5-base-e2e-qg);__
T5-base fine-tuned on SQuAD for Question Generation (https://huggingface.co/mrm8488/t5-base-finetuned-question-generation-ap);__
T5-pubmedqa (https://huggingface.co/frozenwalker/T5_pubmedqa_question_generation_preTrained_MedQuad)
