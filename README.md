# Eye-Tracking and Empathy Dataset

This dataset contains eye-tracking measurements and empathy assessments collected from 60 participants during assistive technology tasks. It supports research intersecting gaze behavior, psychology, and human-computer interaction.

## Contents

The dataset includes:

- 502 eye tracking data files (360 for gaze typing, 142 for free viewing) 
- Pre and post task empathy questionnaires (40 questions each)
- Over 4 million data points  
- Gaze position, pupil diameter, and empathy score data

## Usage

The eye tracking data files are CSVs containing timestamps, x/y gaze coordinates, pupil diameter, and other measurements. Use sequential loading and preprocessing to prepare the data for analysis.  The following Python packages are recommended for loading and analyzing the data:

numpy
pandas
matplotlib
seaborn
scikit-learn

The questionnaire files provide empathy scores for each participant before and after the tasks. Scores can be correlated with gaze patterns.

See the associated paper for details on data collection, preprocessing code, and potential research applications.

## Citation

If using this dataset, please cite the following paper:

P. Lencastre, S. Bhurtel, A. Yazidi, S. Denysov, P. G. Lind, et al. EyeT4Empathy: Dataset of foraging for visual information, gaze typing and empathy assessment. Scientific Data, 9(1):1–8, 2022


## Contact

Please contact the authors with any questions:

Pedro Lencastre - pedro.lencastre@oslomet.no

## License

This dataset is made available under the Creative Commons Attribution 4.0 International (CC BY 4.0) license. See LICENSE file for details.

## Acknowledgements

We thank study participants and Norsk senter for forskningsdata for making this dataset possible.
