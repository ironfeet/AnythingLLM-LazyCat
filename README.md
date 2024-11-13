# AnythingLLM-LazyCat

# What

This project involves porting the lightweighted RAG implementation of AnythingLLM + Ollama to LazyCat MicroServer. 

So, please do not expect that this project can help you run this RAG implementation on platforms other than LazyCat MicroServer. 

# Dependencies

- AnythingLLM:1.2.4
- Ollama:0.4.1

# How

- How to Use AnythingLLM

    Please refer to [AnythingLLM Official Documentation](https://docs.anythingllm.com)

- How to Manage the Models with Ollama

    Please refer to [Ollama API Documentation](https://github.com/ollama/blob/main/docs/api.md)

    For example, the command below is to pull a model

```bash
        curl http://anythingllm.${YourLazyCatMicroServerName}.heiyu.space:11434/api/pull -d '{

            "name": "llama3.2"

        }
```
