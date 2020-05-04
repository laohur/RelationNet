## LearnToCompareText
implement "StructuredSelfAttention" + "RelationNetwork" for few shot learning of text

## step 
python Util.py
python fewshot_main.py

## how
    more data via manual annotation or data augmentation
    more features via transfer learning
    more train via meta learning
    less parameters and other robust

## performance
    10seq 10000step 300dim minum100shot
    embeeding +cosine  0.54   
    embedding+ attn BiLSTM + cosine 0.66
    embedding+ attn BiLSTM + concat not converge
    bert... tokenize in task_generator

    data augmentation √
    seqquence length √
    pretrain √
    less parameters √
    c-way-k-shot √

## Reference：
1. Few-Shot Text Classification with Induction Network https://arxiv.org/abs/1902.10482    
2. Learning to Compare: Relation Network for Few-Shot Learning https://arxiv.org/abs/1711.06025 https://github.com/floodsung/LearningToCompare_FSL
3. A Structured Self-attentive Sentence Embedding  https://arxiv.org/abs/1703.03130 https://github.com/kaushalshetty/Structured-Self-Attention     
4. corpus  https://github.com/fate233/toutiao-multilevel-text-classfication-dataset
5. char_vector https://github.com/Embedding/Chinese-Word-Vectors
