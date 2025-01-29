# MCQ Generation
1. The code currently uses existing libraries to generate questions from exisitng libraries(lmqgen).
2. It uses Spacy trnasformer models to identify NER.
3. It uses vectordb to identify distractors for options in MCQ
# Ongoing Development:
1. Finetuning T5-small for question generation using LoRA on Squad V2 and custom dataset
2. Custom question Generation pipeline
3. Transformer based distrcator generation
 # Issues:
1. Restricted to question types in the datasets.
2. Some questions wont produce multiple options. 
# Future goal:
End to end pipeline to generate relevant MCQ's from maximum context possible.
