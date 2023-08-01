### Notebooks and Code

#### Sesion : LLMOps – The Next Frontier of Scaling Generative AI Powered Applications

#### Speaker : Abhishek Kumar

Notebooks

1. Langchain Prompt Tracking with LangSmith and Weights & Biases
2. Download model weights from HuggingFace and Pushing to GCS
3. Use hosted LLM API with Langchain
4. Fine tuning LLAMA-2 models
5. Using Argilla for Data Preperation ( for RLHF, Fine-Tuning)
6. Creating Programmatic Guardrails for LLMs

`Note : replace the keys and tokens to excute the python codes and YAML files.`

Demos were tested in GKE Autopilot.
Once the Kubernetes cluster is configured.

```bash
# setup storage class
kubectl apply -f deployment/storage.yaml
# deploy llama 2 model
kubectl apply -f deployment/llama2-v1-deployment.yaml
# deploy fine-tuned llama 2 model
kubectl apply -f deployment/llama2-v2-deployment.yaml
# deploy argilla
kubectl apply -f deployment/argilla.yaml
```
