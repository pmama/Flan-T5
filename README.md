# Building Chatbot using Flan-T5 Model
![image](https://github.com/pmama/chatbot/assets/26107548/f3a09ab7-1a54-45aa-a159-12b5ab61aaeb)



LangChain is an open source orchestration framework for the development of applications using large language models (LLMs). 
LangChain’s tools and APIs simplify the process of building LLM-driven applications like chatbots and virtual agents. 

LLMs are not standalone applications: they are pre-trained statistical models that must be paired with an application in order to meet their purpose. 
Many open source models, like BigScience’s BLOOM, Meta AI’s LLaMa and Google’s Flan-T5, can be accessed through Hugging Face.

![image](https://github.com/pmama/chatbot/assets/26107548/3c1fc1eb-aefc-43de-a906-1bff85d8abc7)

I have used 'google/flan-t5-large' for this chatbot building, it has 770 million parameters.
FLAN-T5 is a Large Language Model which was open sourced by Google at the end of 2022. It has been fine-tuned on multiple tasks, but can be further fine-tuned.
The T5 transformer model works by using the same standard encoder-decoder structure as standard transformer models. It consists of 12-pair blocks of encoder-decoder. Each block contains self-attention, a feed-forward network, and optional encoder-decoder attention.
