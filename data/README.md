# Data

The dataset is not stored in this repository. Download it from Kaggle and place the CSV in this folder.

**Source:** [Parkinson's Disease Dataset Analysis](https://www.kaggle.com/datasets/rabieelkharoua/parkinsons-disease-dataset-analysis) by Rabie El Kharoua
**License:** [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)
**Note:** the dataset is synthetic. Its author states it was generated for educational purposes.

## Option 1: Download in the browser

1. Open the Kaggle link above and click **Download** (a free Kaggle account is required).
2. Unzip the archive.
3. Move `parkinsons_disease_data.csv` into this folder.

## Option 2: Kaggle CLI

Run from the repository root:

```bash
pip install kaggle
kaggle datasets download -d rabieelkharoua/parkinsons-disease-dataset-analysis -p data --unzip
```

This needs a Kaggle API token. See the [Kaggle API documentation](https://www.kaggle.com/docs/api) for setup.

## Expected result

```
data/
├── README.md
└── parkinsons_disease_data.csv   (2,105 rows, 35 columns)
```
