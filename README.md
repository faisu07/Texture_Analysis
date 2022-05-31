
# TEXTURE EXTRACTION TECHNIQUES FOR CLASSIFICATION


In this paper, we explored and proved a hypothesis with help of a framework which suggests, that
a group of distinct and unique weak learners when ensembled together form a strong learner. To prove
this hypothesis we have suggested a framework where various texture extraction techniques have been
ensembled after the convolution layers.


## Required Python Dependencies

To run the code, Install the dependencies first using the following commands

```bash
  pip3 install pillow==8.2.0
  pip3 install torch==1.7.1
  pip3 install torchvision==0.8.2
  pip3 install torch-encoding==1.2.2b20200808
  pip3 install mlflow
  pip3 install barbar
  pip3 install Ninja
```


## Code Run

Run the code using following command on colab or terminal


For FMD dataset
```bash
  python main.py --dataset=FMD  --n_classes=10 --train_need --test_need  --test_BS=16 --train_BS=16  --model=FENet --use_pretrained --num_epochs=60 --scheduler="cosine" --lr=0.001
```
 For KTH dataset
```bash
  python main.py --dataset=KTH --n_classes=11 --train_need --test_need  --test_BS=32 --train_BS=32  --model=FENet --use_pretrained --num_epochs=40 --scheduler="cosine" --lr=0.01
```   
## Demo

Insert gif or link to demo


## Deployment

To deploy this project run

```bash
  npm run deploy
```


## Screenshots

![Results of single combination](https://github.com/faisu07/Texture_Analysis/blob/main/resukts2.png)

![Results of double combination](https://drive.google.com/file/d/1OE4FqiPNOgue-yG3rrE5RvzbKx0eWsg6/view?usp=sharing)

![Results of triple combination](https://drive.google.com/file/d/1mDvr1oLa6dKix6qnpF8Z_AR-zV4sgBFg/view?usp=sharing)

## Research Paper

[Paper](https://linktodocumentation)


## Authors

- [@Vijay Pandey](https://www.linkedin.com/in/vijay-pandey-29a0a35a)
- [@Mohammed Faisal](www.linkedin.com/in/mohammed-faisal-771b8818b)
- [@Mayank Gubba](https://www.linkedin.com/in/mayank-gubba/)


## Appendix

Any additional information goes here

