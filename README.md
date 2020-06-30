# molecules
Molecular simulations with quantum computers

## Installation
Install a virtual environment with Anaconda, Conda:
```
conda create --name cirq python=3.8 
conda activate cirq
conda install juypter
pip install cirq
pip install openfermion
pip install openfermioncirq
```
You may get ERROR: google-api-core 1.21.0 has requirement protobuf>=3.12.0, but you'll have protobuf 3.8.0 which is incompatible.
Apparently the error has no effect for now.


## Running

1. get the source

```
git clone https://github.com/ekkards/molecules.git
cd molecules
jupyter notebook
```

2. select ```LiH_trotter.ipynb```

3. and press ```Run``` a couple of times.
