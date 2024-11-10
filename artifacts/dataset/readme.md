## Datasets

**NSynth:** We used the samples from the NSynth dataset {engelNeuralAudio2017a}. It is an audio dataset with 305,979 musical notes. Each sample note is a four-second, monophonic audio snippet with a 16kHz sampling rate. Further, the notes have been annotated using human evaluation and heuristic algorithms with the following information.

  - **Source:** How the sound was produced for the note? Whether it was produced by acoustic instruments, electronic instruments or synthesized instruments?
  - **Family:** Each instrument is a member of exactly one family which decides the note's family attribute.
  - **Qualities:** Sonic qualities of the note. For example, there are spectral qualities such as bright and dark, and temporal qualities such as fast decay and long release.
\
In our project, we focused on a subset of samples from the NSynth dataset. We considered all the **acoustic source flute sound samples only**. We had a total of 6572 samples (802 MB in total). We implemented our deep learning model using the PyTorch framework {Specifically, we use version 2.2.2 of PyTorch in [url](https://pytorch.org/).}. The training was run on our setup locally. We had Nvidia RTX 3070 laptop with 8GB VRAM at our disposal.

The preprocessed files are available here(8773 flute sounds): https://mcgill-my.sharepoint.com/:f:/g/personal/boyu_sun_mail_mcgill_ca/ErYfs6CYdYREn3WxQ0aKT2sB7Ylk8_28adimLCNyADJCaQ?e=v5Qdgc
