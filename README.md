# Wireless-Multi-channel-EMG-on-Headphone-for-Silent-Speech

This repository contains the code and data used in our IEEE TIM submission:
“Wireless Silent Speech Interface Using Multi-Channel Textile EMG Sensors Integrated into Headphones.”

The system leverages wearable textile EMG sensors, integrated with commercial headphones, for hands-free and voice-free silent speech decoding using machine learning and adaptive channel selection.

Each .csv file in the data/ directory corresponds to one spoken word recorded via 4-channel EMG signals. The structure is as follows:

| Column       | Description                                              |
| ------------ | -------------------------------------------------------- |
| `sample_id`  | Identifier of the sample (e.g., always 1 if single word) |
| `time_index` | Timestamp/frame index (sequential)                       |
| `ch1`–`ch4`  | Raw EMG values from 4 textile channels                   |
| `label`      | Integer label representing the spoken word/class         |
