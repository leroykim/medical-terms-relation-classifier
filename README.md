# medical-terms-relation-classifier

## Dataset
### Original data
Original data is in data/figure-eight-medical-sentence-summary.zip
These are original files from the zip file:
- data/test.csv
- data/train.csv
- data/validation.csv
### Interim data
The interim form of data for backup is stored in `data/processed` directory. Files in this directory did not used for training.
### Training data
`.csv` files in `data\for_training` are used for train the models.

{train | validation | test}.csv files contains unique sentences with direction of relation is determine by majority vote.

*_downsampled.csv files contains downsampled rows of `causes` and `treats`.