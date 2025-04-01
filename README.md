# SlavaKpss-Text-Generation
Я спарсил тексты песен исполнителя Слава КПСС с сайта genius и протестировал разные модели, чтобы
сгенерировать текст в его стиле.
Стек: selenium, tensorflow, transformers, FAISS, OpenAI API, RAG
 Протестировал модели: GPT-2, ruGPT-3, LSTM, Megatron-T5, GPT-J, GPT-4-turbo
 Реализовал RAG-систему на основе FAISS и GPT-4-turbo
 GPT-4-turbo показала наилучший результат по качеству рифмовки и стилю
