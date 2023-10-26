# EdgarGPT

The EdgarGPT project uses OpenAI language models to create a chatbot that was trained on information about myself. The chatbot answers questions based on my CV, my personal website, and PDFs that are available on my website.


## Methodology

The chatbot measures the relatedness of presented text based on the numerical representation of trained text. Thus, it will answer questions about myself based on the most similar context from the learned input. More precisely, it sends received questions about my person to the OpenAI completions API endpoint to create an answer to the user. 


## Deployment

The chatbot is deployed on HuggingFace and embedded on my personal website. Furthermore, the interface is made with Gradio.

Go to my website <https://edgar-treischl.de/project/> to visit the deployed app.


## Limitations

EdgarGPT has limited information and only illustrates how language models can be exploit as personal assistant. In addition, EdgarGPT is freely available but the services from OpenAI are not free of charge, which is why EdgarGPT throws an error if the OpenAI limit has been reached. 

