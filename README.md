# MSc-Thesis

This repository contains the code for the thesis. Instructions and a brief overview is given in this README.

Please refer to [MSc-Thesis/Bao](MSc-Thesis/Bao) for the main thesis repo.

Setting up:
NOTES: 
- an open-meteo API key is preferred to run the download_data.ipynb notebook which can be acquired by [mailing the open-meteo repo owners](https://github.com/open-meteo/open-meteo?tab=readme-ov-file#support), or utilizing their publicly available API (rate limited). 
- file may need to be adjusted, please change the paths accordingly on your machine.
- see notebook for additional instructions (DOWNLOAD: ) and all_code/snellius_scripts/example_template.ipynb for Snellius setup

From all_code folder:

Step 1. Run download_data.ipynb notebook once to download the corresponding datasets

Step 2. Run snellius_scripts\IntellEnv.job to setup environment.yml in Snellius

Step 3. Run 21_EDA.ipynb, 22_main_dataset_creation.ipynb (aggregate_monthly.job) , classification_base.ipynb (classification_base.job), classification_base_HPARAM.ipynb (classification_HPARAM.job), classification_new.ipynb (classification_new.job)

Note: submit the job files to the snellius cluster to run the respective jupyter notebooks
