# IN3063-Coursework

All code related to the coursework is found in the `Coursework.ipynb` notebook.  
We suggest Jupyter to run the notebook.  

### Directory Structure  

Both datasets are in place and ready to be used for their respective tasks. It is possible that some relative path referencing might not work on Windows systems. In that case, just replace the relative path `./dataset/chest_xray/` with an absolute path `C:\\path\\to\\directory\\`.

The dataset was obtained from kaggle: https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia?resource=download

Place the `archive.zip` file in the `dataset/` directory and run `unzip archive.zip` to extract its contents.

The directory structure should look as follows:  

```bash
.
├── Coursework.ipynb
├── dataset
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
