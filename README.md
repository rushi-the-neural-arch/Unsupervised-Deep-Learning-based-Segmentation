# Unsupervised Segmentation 

## Requirements

python3, pytorch, opencv2, scikit-image

## Getting started

    $ python demo.py --input images/101027.jpg
    
    %%time 
    python3 demo.py --maxIter 300 --lr 0.1 --num_superpixels 200 --input /content/texture2.jpg
    
    python3 demo.py --maxIter 2 --minLabels 50 --lr 0.01 --nConv 2 --num_superpixels 10000 \
                 --compactness 10 --input chyron002.png
