# Frequency-Specific Neural Response and Cross-Correlation Analysis of Envelope Following Responses to Native Speech and Music Using Multichannel EEG Signals: A Case Study

This repository contains the code for the above-mentioned paper, authored by _Md. Mahbub Hasan, Md Rakibul Hasan, Md Zakir Hossain_ and _Tom Gedeon_. **Code is primarily developed by Md. Mahbub Hasan.**

**Abstract:** Although native speech and music envelope following responses (EFRs) play a crucial role in auditory processing and cognition, their frequency profile, such as the dominating frequency and spectral coherence, is largely unknown. We have assumed that the auditory pathway - which transmits envelope components of speech and music to the scalp through time-varying neurophysiological processes - is a linear time-varying system, with the envelope and the multi-channel EEG responses as excitation and response, respectively. This paper investigates the transfer function of this system through two analytical techniques - time-averaged spectral responses and cross-spectral density - in the frequency domain at four different positions of the human scalp. Our findings suggest that _alpha (8-11 Hz)_, _lower gamma (53-56 Hz)_, and _higher gamma (78-81 Hz)_ bands are the peak responses of the system. These frequently appearing dominant frequency responses may be the key components of familiar speech perception, maintaining attention, binding acoustic features, and memory processing. The cross-spectral density, which reflects the spatial neural coherence of the human brain, shows that _10-13 Hz_, _27-29 Hz_, and _62-64 Hz_ are common for all channel pairs. As neural coherences are frequently observed in these frequencies among native participants, we suggest that these distributed neural processes are also dominant in native speech and music perception.

## How to run the code
First, download the "Auditory evoked potential EEG-Biometric dataset", which is available at [PhysioNet](https://doi.org/10.13026/ps31-fc50).

`main.ipynb` is the main notebook, which includes all steps of the analysis reported in the paper. Code is primarily developed in Google Colab, using Python 3.11.

## Citation
```bibtex
@misc{hasan2025frequency,
      title={Frequency-Specific Neural Response and Cross-Correlation Analysis of Envelope Following Responses to Native Speech and Music Using Multichannel EEG Signals: A Case Study}, 
      author={Md. Mahbub Hasan and Md Rakibul Hasan and Md Zakir Hossain and Tom Gedeon},
      year={2025},
      eprint={},
      archivePrefix={arXiv},
      primaryClass={eess.SP}
}
```

## Contact
For questions or collaboration opportunities, please contact the lead author, Md. Mahbub Hasan.

## Acknowledgments
We thank the authors of the "[Auditory evoked potential EEG-Biometric dataset](https://doi.org/10.13026/ps31-fc50)" for making the data available.
