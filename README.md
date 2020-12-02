### Introduction
    
At present, the layout analysis work after OCR is written by rules, and I also suffer from the rules. When I see a lot of text and coordinates output by OCR, my scalp is numb. Recently, inspired by the template engine of chineseocr authors, I have made an end-to-end layout analysis algorithm based on seq2seq, hoping to help every ocrer.

Link: https://blog.csdn.net/mochp/article/details/109491521


### Data annotation
   
    Just use labelme, mark the corresponding category of box in groupid

### Modify configuration items
   
    Modify the config.yaml file according to the scene

### Augmented visualization
    
    Run python plot/plot.py

### Model training
    
    Run python train.py

### Model test
    
    Run python test.py
    
    
Source: https://github.com/limengyang1992/seq2seq-ocr-analysis
