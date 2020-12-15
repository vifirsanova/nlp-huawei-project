# A Russian Question Answering System for Inclusive Education

The dataset used for the model training: https://doi.org/10.6084/m9.figshare.13295831

The repository contains the code for the data preprocessing, model fine-tuning and evaluation of two transformers adapted for the question answering task: 
1. BERT based QA model
2. GPT-2 based QA model

The BERT based system implementation is based on Question Answering with SQuAD 2.0 guide: https://huggingface.co/transformers/custom_datasets.html?highlight=custom#qa-squad 

The GPT-2 based system implementation is based on by gpt-2-simple package by Max Woolf: https://minimaxir.com/2019/09/howto-gpt2/

## Results

|Base model | F-Score |
|-----------|---------|
|Multilingual BERT | 0.55 |
|774M GPT-2 | 0.63 |

## Sample outputs

**BERT based model**

**Q:** Есть ли какие-то техники, чтобы научить ребенка с РАС вести себя в социальном мире?

**A:** Поговорите со специалистами, работающими с ребёнком, о каких-либо программах, которые могут ему помочь.

**GPT-2 based model**

**Q:** У детей-аутистов могут быть проблемы с одноклассниками?

**A:** У детей с расстройством аутистического спектра (РАС) высок риск подвергнуться травле, особенно в обычных школах.
