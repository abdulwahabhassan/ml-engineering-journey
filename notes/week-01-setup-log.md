# Week 1 setup log

## What I installed
- WSL2 + Ubuntu 24.04
- Python 3.12 via uv
- PyTorch 2.6.0+cu124, NumPy, Pandas, scikit-learn, Matplotlib, Jupyter
- VS Code with WSL remote + Python + Jupyter extensions
- Ollama with llama3.2:3b

## Notes
- Corporate network (Zscaler) required root CA install for SSL to work with curl/uv/git
- uv requires UV_SYSTEM_CERTS=true to use system trust store
- 4GB GPU (RTX 500 Ada) good for inference of 1-3B parameter models; cloud GPU for serious fine-tuning later
