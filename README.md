# clabby-classifier ☘️
Deploys a trained PyTorch image classification model with Flask and FloydHub.

## Deployment Steps

```bash
git clone https://github.com/whatrocks/clabby-classifier/
cd clabby-classifier
pip install -U floyd-cli
floyd login
floyd init clabby-classifier
floyd run --mode serve
```
