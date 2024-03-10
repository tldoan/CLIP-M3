# A streamlined Approach to Multimodal Few-Shot Class Incremental Learning for Fine-Grained Datasets (CLIP-M3)

We release our three introduced fine-grained datasets below: (Code coming soon) 

## FGVCAircraft

```
gdown https://www.robots.ox.ac.uk/~vgg/data/fgvc-aircraft/archives/fgvc-aircraft-2013b.tar.gz;
tar -xzf fgvc-aircraft-2013b.tar.gz;
    
```

## StanfordCars


```
pip install kaggle;
kaggle datasets download -d jessicali9530/stanford-cars-dataset -p [FOLDER];
unzip stanford-cars-dataset.zip;
    
```

## iNF200
Train and test sets available [here](https://huggingface.co/datasets/tldoan/iNF200/tree/main)

['iNF200_dict.pkl'](https://huggingface.co/datasets/tldoan/iNF200/tree/main) contains:
- Train set meta data
- Test set meta data
- labels to classnames
- classname to label
