# Zhuang - ShelfNet for Fast Semantic Segmentation
### 
- Jaeson Pyeon
- Felix Yang

Implementing ShelfNet and a reduced channel portion on the [Cityscapes dataset](https://www.cityscapes-dataset.com/)

### Website
https://expo.baulab.info/2024-Spring/fzyang1227/.

### Paper
https://arxiv.org/abs/1811.11254

### Info
Download the cityscapes dataset above into a 'ShelfNet18_realtime/data/' folder in this repository
- leftImg8bit
- gtFine

Additionally will need to fork over the `ShelfNet18_realtime` folder from [ShelfNet Github](https://github.com/juntang-zhuang/ShelfNet-lw-cityscapes)
- load in the weights as directed from the Github
- make changes to the resnets to use pytorch's `BatchNorm2d` layers
