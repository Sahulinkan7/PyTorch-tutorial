# PyTorch-tutorial
Exploring PyTorch library

Pytorch Tutorial live documentation : [click here](https://sahulinkan7.github.io/PyTorch-tutorial/) 

Above documentation is associated with this repository.

To add mkdocs materials execute below command which creates docs folder and mkdocs.yml file.

```bash
mkdocs new .
```

To serve the mkdocs material as webapp.

```bash
mkdocs serve
```

github action workflow file ci.yaml will be used for deploying mkdocs documentation web page as github page.

```python
pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu124
```
