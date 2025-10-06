# Speech Denoising and Evaluation

This repository contains Jupyter notebooks for mixing speech with noise and applying denoising and evaluation techniques on the resulting audio.

## Notebooks

### `main.ipynb`

Primary notebook for processing and evaluating noisy speech signals. It includes:

- **BPF Estimated Function**  
  Performs band-pass filtering and noise estimation.

- **Denoise Function**  
  Applies denoising techniques to clean the audio.

- **Run, Plot, and Save Functions**  
  Executes the full denoising pipeline, visualizes waveforms/spectrograms, and saves output audio.

- **Evaluate Function**  
  Measures quality using evaluation metrics (e.g., SNR, PESQ, STOI).

---

### `mix_noise.ipynb`

Notebook for generating noisy audio inputs:

- **Mix Speech with Noise Function**  
  Mixes clean speech samples with various background noises at different SNR levels.

---

## Usage

1. Run `mix_noise.ipynb` to generate noisy speech data.
2. Run `main.ipynb` to:
   - Apply denoising.
   - Visualize and save the results.
   - Evaluate the denoised outputs.

---

## Requirements

* Python 3.13.3
* Jupyter Notebook
* Numpy
* Scipy
* Librosa
* Soundfile
* Pandas
* Mathplotlib
* Speechmose
* Pesq

---

## License

[MIT](LICENSE) – feel free to use and adapt.

---
This project is a part of class 01204496 Algorithmic-Oriented Digital Signal Processing
developed by Nakharet Mueangphakdee 6610505438
