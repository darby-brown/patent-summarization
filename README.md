# A Study of Patent Summarization Capabilities of Large Language Models

## Description
This is an ongoing projec to experiment with the effectiveness of LLMs to summarize long documents of complex, domain-specific language. 

* **Task:** The goal of all models is to present an abstract-style summary of sample patents given the summary, background, description, and claims of the document.
* **Datasets:** Patents in the HUPD dataset, filtered for organic chemistry filings only. Find this dataset on HuggingFace: https://huggingface.co/datasets/HUPD/hupd 
* **Tools used:** Pegasus model, extractive summarization, fine-tuning
* **Key Results:**
* **Next Steps:** 

## Contents



## How to use this Project

To run the LLM and implement fine-tuning, this project must be run on a GPU. Due to the enormous size of the HUPD dataset, do not download all the data at once unless you ensure sufficient memory. The organic chemistry subset alone is ~50GB. 

I implemented this project in Colab. For fine-tuning, Colab Pro is required.

## Credits

Thank you to the faculty of the UC Berkeley Natural Language Processing course (datasci 266) for inspiring this project, and specifically to Peter Grabowski and Mark Butler for their instruction and mentorship.
