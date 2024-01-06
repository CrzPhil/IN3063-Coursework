# IN3063-Coursework

All code related to the coursework is found in the `Coursework.ipynb` notebook.  
We suggest Jupyter to run the notebook.  

### Directory Structure  

The dataset for task one is already in place and ready to be used by the codebase.  
The dataset for task two needs to be downloaded and extracted in the dataset directory.  

It was too big to push to GitHub (>2GB), so you will have to download it from here: https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia?resource=download

Place the `archive.zip` file in the `dataset/` directory and run `unzip archive.zip` to extract its contents.

The directory structure should look as follows:  

```bash
.
├── Coursework.ipynb
├── dataset
│   ├── archive.zip
│   ├── chest_xray
│   │   ├── __MACOSX
│   │   ├── test
│   │   ├── train
│   │   └── val
│   ├── t10k-images-idx3-ubyte
│   ├── t10k-labels-idx1-ubyte
│   ├── train-images-idx3-ubyte
│   └── train-labels-idx1-ubyte
```

### Dependencies

We included a `requirements.txt` file covering the dependencies. It is possible (though unlikely) we missed one; typically they can all be installed via `pip3`.  

```bash
pip3 install -r requirements.txt
```
