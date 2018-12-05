# Dealing-with-Caltech256
This is to generate .txt file of Caltech256 jpg paths with their labels as well as PyTorch Dataloader. (https://authors.library.caltech.edu/7694/)

You should have prepared Caltech-256 dataset from https://authors.library.caltech.edu/7694/. 

You should change the datasetpath to your own's in generate_file.py and then run:
```python
python3 ./generate_file.py
```
The you will find \*trn.txt and \*val.txt files like above.

The \*.txt files can be used like convert.py
