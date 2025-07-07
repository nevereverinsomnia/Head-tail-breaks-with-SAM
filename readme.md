# This is a head/tail breaks application with SAM model
This project is inspired from Prof. Bin Jiang(HKUSTGZ) 
who is the author of Living Images: A Recursive Approach to Computing the Structural Beauty of Images or the Livingness of Space. If you are interested, PLZ refer [paper url](https://arxiv.org/abs/2301.01814) 
## Model pipeline
![Model pipeline](./model_img/model.png)

### SAM
![segment anything model pipeline](./model_img/sam.png)

## This project results
![project results](./model_img/results.drawio.svg)
## Images living scores
![scores](./model_img/results%20excel.png)

## Reproduce of Living Images
![Living Images results](./model_img/living%20img%20results.png)

## installation
```
pip install torch torchvision opencv-python matplotlib
```

```angular2html
git+https://github.com/facebookresearch/segment-anything.git
```