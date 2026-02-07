# Data Directory

## Structure

- **raw/** - Original, immutable data from Kaggle
- **interim/** - Intermediate data that has been transformed
- **processed/** - Final, canonical datasets for modeling
- **external/** - Data from third-party sources

## Download Competition Data
```bash
kaggle competitions download -c playground-series-s6e2
unzip playground-series-s6e2.zip -d data/raw/
rm playground-series-s6e2.zip
```

## Expected Files

### raw/
- train.csv
- test.csv
- sample_submission.csv
