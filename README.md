# Federated-LLM: Simulating Federated Learning for LLM Updates with RAG

This project simulates and experiments with federated large language model (LLM) updates integrated with retrieval-augmented generation (RAG) features.

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
