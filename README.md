<p align="center"><img src="docs/banner.png" alt="Pixel art: a small neural network feeds a chart where a smooth line tracks noisy dots" width="100%"></p>

# Kalman filter

Kalman filter notebooks and data for the IEEE ICONAT 2022 paper on a neural-network-aided Kalman filter ([DOI](https://doi.org/10.1109/ICONAT53423.2022.9726059)). The neural network is not in this repository.

## Run it

```bash
pip install numpy matplotlib scipy jupyter
jupyter notebook
```

Open `Kalman Theory/1D.ipynb` for the walkthrough. For the experiment, run `Research Code/Sample Data Generation.ipynb` first, then `Implementing the improved Kalman Filter.ipynb`. More in [docs/about.md](docs/about.md).

## Build and test

```bash
make check    # compiles the code and checks the notebooks; CI runs it
```

Cite it with `CITATION.cff` ("Cite this repository" on GitHub). Finished; see [STATUS.md](STATUS.md). MIT licence.
