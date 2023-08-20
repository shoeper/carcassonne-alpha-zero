# carcassonne-alpha-zero
TF2/Keras Implementation of AlphaZero on Carcassonne.

## Training
```bash
python carcassonne_train.py with 'tag="test"'
```

### From checkpoint
```bash
python carcassonne_train.py with 'tag="test"' 'load_checkpoint_path="<path-to-checkpoint>"'
```

# Nvidia with WSL

Requires cuda 11.8 - no other version

Extend path: fish_add_path -g /usr/local/cuda-11.8/bin/

https://developer.nvidia.com/cuda-11-8-0-download-archive