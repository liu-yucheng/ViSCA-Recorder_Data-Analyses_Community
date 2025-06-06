# ViSCA-Recorder_Data-Analyses\<_Community\>

\<Community version of\> a set of data analysis scripts and results for an HKUST (GZ) MPhil Thesis by LYC.

# Usage
## Viewing Graphical Analysis Results

- Download `Figures_Computed<_Community>.zip` from the latest release page.
- Decompress `Figures_Computed<_Community>.zip`.
- Overwrite `./Figures_Computed/` with the contents of `Figures_Computed<_Community>.zip`.
- View graphical analysis results in `./Figures_Computed/`.

## Viewing Textual Analysis Results

- Download `Texts_Computed<_Community>.zip` from the latest release page.
- Decompress `Texts_Computed<_Community>.zip`.
- Overwrite `./Texts_Computed/` with the contents of `Texts_Computed<_Community>.zip`.
- View textual analysis results in `./Texts_Computed/`.

## Preparing the Data to Analyze

- Download `Data_ToAnalyze<_Community>.zip` from the latest release page.
- Decompress `Data_ToAnalyze<_Community>.zip`.
- Overwrite `./Data_ToAnalyze/` with the contents of `Data_ToAnalyze<_Community>.zip`.
- Run the `_0_1_Data_Shared_Prepare.ipynb` file to prepared the shared data.
- Run the `*_Prepare.ipynb` files to prepare the rest of the data.

## Preparing the Data to Analyze (Alternative Method)

- Download `Data_All<_Community>.zip` from the latest release page.
- Decompress `Data_All<_Community>.zip`.
- Overwrite the repository root folder `./` with the contents of `Data_All<_Community>.zip`.

## Analyzing the Data with Python Jupyter Notebooks

- Install [Python](https://www.python.org/).
- Install dependencies by running `pip install -r requirements.txt`.
- Run and read the `*.ipynb` files.
- Checkout the data to analyze in `Data_ToAnalyze/`.

## Analyzing the Data with Python Jupyter Notebooks (Alternative Method)

- Install [Python](https://www.python.org/).
- Install dependencies by running `pip install -r requirements.txt`.
- Run and read the following files.
  - `./_0_0_HelloWorld.ipynb`
  - `./_0_1_Data_Shared_Prepare.ipynb`
  - `./_0_2_Data_All_Prepare.ipynb`
  - `./_0_3_Data_All_Analyze.ipynb`
- Checkout the data to analyze in `Data_ToAnalyze/`.

## Processing Large Files in Repo

- Use [`GitHub-ForceLargeFiles/main.py`](https://github.com/liu-yucheng/GitHub-ForceLargeFiles) to compress this repo for GitHub, online sync.
  - `python3 GitHub-ForceLargeFiles/main.py --delete_original True --threshold_size 50 --threshold_size_unit m --partition_size 48 --partition_size_unit m`.
- Use [`GitHub-ForceLargeFiles/reverse.py`](https://github.com/liu-yucheng/GitHub-ForceLargeFiles) to decompress this repo for local, offline development. 
  - `python3 GitHub-ForceLargeFiles/reverse.py --delete_partitions True`.
- If the large files get rejected by [GitHub](https://github.com/)...
  - Clear the large file folder out of the Git repo and the Git repo `.git` commit history.
  - Use a placeholder file to keep the large file folder.
  - [7-Zip](https://www.7-zip.org/) the large file folder and upload it to the latest [GitHub](https://github.com/) release page.

# Copyright
## If not Disclosed

```
Copyright (C) 2024-2025 Yucheng Liu. All rights reserved.
```

## Once Disclosed
### Textual and Code Contents

```
Copyright (C) 2024-2025 Yucheng Liu. Under the GNU AGPL 3.0 License.
GNU AGPL 3.0 License: https://www.gnu.org/licenses/agpl-3.0.txt .
```

- [The GNU AGPL 3.0 License.](./license)

### Non-textual or Non-code Contents

```
Copyright (C) 2024-2025 Yucheng Liu. Under the CC-BY-SA 4.0 License.
CC-BY-SA 4.0 License: https://creativecommons.org/licenses/by-sa/4.0/legalcode.txt .
```

- [The CC-BY-SA 4.0 License.](./license-2)
