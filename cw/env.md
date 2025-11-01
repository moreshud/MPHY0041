## Micromamba environments for coursework
- Create a module PyTorch environment `mphy0041cw-pt`.
```bash
micromamba create -n mphy0041-pt python=3.12
micromamba activate mphy0041-pt  
pip install torch==2.7.1  
pip install numpy matplotlib requests h5py nibabel
```

- Deactivate the environment before switching/creating a new one:
```bash
micromamba deactivate 
```

- Create a module TensorFlow environment `mphy0041cw-tf`.
```bash
micromamba create -n mphy0041-tf python=3.12
micromamba activate mphy0041-tf  
pip install tensorflow==2.16.1  
pip install matplotlib nibabel