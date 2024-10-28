# NeuroSense
A Novel EEG Dataset Utilizing Low-Cost, Sparse Electrode Devices for Emotion Exploration

## 📥 **Download the NeuroSense Dataset**

The dataset is hosted on Zenodo and can be accessed upon request at the following link:

🔗 [**Download Dataset**](https://zenodo.org/records/14003181)


## 📚 **Citation**

If you find **NeuroSense** valuable for your research, please cite our work:

```bibtex
@article{colafiglio2024neurosense,
  title={NeuroSense: A Novel EEG Dataset Utilizing Low-Cost, Sparse Electrode Devices for Emotion Exploration},
  author={Colafiglio, Tommaso and Lombardi, Angela and Sorino, Paolo and Brattico, Elvira and Lof{u}, Domenico and Danese, Danilo and Di Sciascio, Eugenio and Di Noia, Tommaso and Narducci, Fedelucio},
  journal={IEEE Access},
  year={2024},
  doi={10.1109/ACCESS.2024.0429000},
  url={https://doi.org/10.1109/ACCESS.2024.0429000}
}
```



# README

## Details related to access to the data 

### Data user agreement
The terms and conditions for using this dataset are specified in the [LICENCE](LICENCE.md) file included in this repository. Please review these terms carefully before accessing or using the data.

### Contact person
For additional information about the dataset, please contact:
- **Name:** Angela Lombardi
- **Affiliation:** Department of Electrical and Information Engineering, Politecnico di Bari
- **Email:** angela.lombardi@poliba.it

### Practical information to access the data
The dataset can be accessed through our dedicated web platform. To request access:

1. Visit the main dataset page at: https://sisinflab.poliba.it/neurosense-dataset-request/
2. Follow the instructions on the website to submit your access request
3. Upon approval, you will receive further instructions for downloading the data

Please ensure you have read and agreed to the terms in the data user agreement before requesting access.

## Overview

### EEG Emotion Recognition - Muse Headset
#### 2023-2024

The experiment consists in 40 sessions per user. During each session, users are asked to watch a
music video with the aim to understand their emotions.  
Recordings are performed with a Muse EEG headset at a 256 Hz sampling rate.  
Channels are recorded as follows:
- Channel 0: AF7
- Channel 1: TP9
- Channel 2: TP10
- Channel 3: AF8

The chosen songs have various Last.fm tags in order to create different feelings. The title of every track
can be found in the "TaskName" field of sub-ID***_ses-S***_task-Default_run-001_eeg.json, while the author,
the Last.fm tag and additional information in "TaskDescription".

## Methods

### Subjects

The subject pool is made of 30 college students, aged between 18 and 35. 16 of them are males, 14 females.

### Apparatus

The experiment was performed using the same procedures as those to create
[Deap Dataset](https://www.eecs.qmul.ac.uk/mmv/datasets/deap/), which is a dataset to recognize emotions via a Brain
Computer Interface (BCI).  


### Task organization

Firstly, music videos were selected. Once 40 songs were picked, the protocol was chosen and the self-assessment
questionnaire was created.

### Task details

In order to evaluate the stimulus, Russell's VAD (Valence-Arousal-Dominance) scale was used.  
In this scale, valenza-arousal space can be divided in four quadrants:
- Low Arousal/Low Valence (LALV);
- Low Arousal/High Valence (LAHV);
- High Arousal/Low Valence (HALV);
- High Arousal/High Valence (HAHV).

### Experimental location

The experiment was performed in a laboratory located at DEI Department of
[Politecnico di Bari](https://www.poliba.it/).

### Missing data
Data recorded during session S019 - Session 2, ID021 - Session 23,  user was corrupted, therefore is missing.  
Sessions S033 and S038 of ID015 user show a calculated effective sampling rate lower than 256 Hz:
- ID015_ses-S033 has 226.1320 Hz
- ID015_ses-S038 has 216.9549 Hz
