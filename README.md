# sentiment-analysis-workshop

## Requirements

We recommend to create a new environment for experiments using conda:
```bash
conda create -y -n sentiment-analysis python=3.9
conda activate sentiment-analysis
```

Then, from the project root, run:
```bash
pip install -r requirements.txt
```

## Q&A
### [Problem 1]
If you see the error message:
```
Running cells with 'Python 3.9.13 ('sentiment-analysis')' requires ipykernel package.
Run the following command to install 'ipykernel' into the Python environment. 
Command: 'conda install -n sentiment-analysis ipykernel --update-deps --force-reinstall'
```

Please try to use the following command to fix it:
```
conda install -n sentiment-analysis ipykernel --update-deps --force-reinstall
```