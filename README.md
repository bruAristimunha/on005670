[![DOI](https://img.shields.io/badge/DOI-10.82901%2Fnemar.on005670-blue)](https://doi.org/10.82901/nemar.on005670)

 Dataset description

===================

This SEEG raw dataset includes resting state recordings for two patients with epilepsy. 

The depth electrodes used in this dataset are Sinovation SDE-08 medical-grade stainless steel electrodes, with the following specifications:
    Diameter: 0.8 mm
    Contact length: 2 mm
    Insulator length: 1.5 mm
    Distance between the center of two contacts: 3.5 mm
    Between 8 and 16 contacts on each electrode 

=======

For questions, please contact Pengfei Xu (pxu@bnu.edu.cn).

## Channels table generated from the data header (18 Oct 2026)

1 recording(s) had no channels.tsv, which BIDS requires for iEEG (bids-validator and `mne_bids` could not attach channel types or units). `sub-01_task-rest_channels.tsv` now lists the 238 channels of the EDF header: names and sampling frequency from the header, units from the header, type from the name (ECG/EMG/EOG/trigger) or, for contacts listed in electrodes.tsv, the iEEG type of the *_ieeg.json channel counts, scalp 10-20 labels not in electrodes.tsv EEG, otherwise MISC (types: ECG 2, MISC 12, SEEG 224); status n/a (no former status exists).

Note: The header names 150 contacts with a prime (`A'1`, shafts A', B', C', D', E', F', G', H', V', X', Y'); electrodes.tsv lists the same shafts with an `R` (`AR1`, same contact count per shaft), so positions attach after renaming `X'n` -> `XRn`; electrodes.tsv is unchanged. `sub-01_task-rest_ieeg.json` channel counts set to the generated channels.tsv: SEEGChannelCount 238 -> 224, ECGChannelCount 0 -> 2, MiscChannelCount 0 -> 12.
