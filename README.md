# Federated-LLM: Simulating Federated Learning for LLM Updates with RAG

This project simulates and experiments with federated learning. The specific scope is LLM updates with RAG. 

Robots that do chores around the house... check-in AI assistants at the airport... personal life coaches on your phones... should not always be buffering and should never spy on you - unintentionally or not. It should only go to sleep, wake up and do its job, and "attend night school on the cloud" while keeping everything it talks with, hears from, and knows of you completely off limits. 

However, there is heavy technical debt to achieve this convenience of ubiquitous AI in daily life. 
The main value proposition are scoped as scalable and personalizable edge models with low cloud-latency and high privacy, high security raw data treatment. The main pain points of current iteration includes implementation frameworks for global updates of ensemble models, the case for personalized and separate RAG upkeeping, heterogeneous edge devices... 

This project focuses on federated LLM updates as the entry step for ensemble model updates. That is, we explore empirical insights by generalizing FROM the scope next-word-prediction model updates TO overall updates for multi-modal ensemble models on edges.

### **Setting up Virtual Environment**

This project utilizes Conda for venv setup due to .
To replicate, utilize `environment.yml` and reference the following steps in cmd.

```bash
conda env create -f environment.yml
conda activate ml_general

python -m fedllm/etl.py
python -m fedllm/dt.py
```

### **Setting up local repo**

Clone and create dir federated-llm in your current dir in cmd

```bash
git clone https://github.com/ben-truong-0324/federated-llm.git
```


## License

This project is licensed under the MIT License.
MIT License

Copyright (c) 2025 Ben Truong

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
