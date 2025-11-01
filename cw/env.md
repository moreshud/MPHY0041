## Micromamba environments for coursework
- Create a module PyTorch environment `mphy0041cw2-pt`.
```bash
micromamba create -n mphy0041cw2-pt python=3.12
micromamba activate mphy0041cw2-pt  
pip install torch==2.7.1  
pip install numpy matplotlib requests h5py nibabel
```

- Create a module TensorFlow environment `mphy0041cw2-tf`.
```bash
micromamba create -n mphy0041cw2-tf python=3.12
micromamba activate mphy0041cw2-tf  
pip install tensorflow==2.16.1  
pip install matplotlib nibabel
