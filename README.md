# MSc-Thesis

This repository contains the code for the thesis. Instructions and a brief overview is given in this README.

Please refer to [MSc-Thesis/Bao](MSc-Thesis/Bao) for the main thesis repo.

Setting up:
NOTES: 
- an open-meteo API key is preferred to run the download_data.ipynb notebook which can be acquired by [mailing the open-meteo repo owners](https://github.com/open-meteo/open-meteo?tab=readme-ov-file#support) (Set .env file with OPENMETEO_API_KEY=), or alternatively you could utilizing their publicly available API (rate limited, requires adjusting the code). 
- file may need to be adjusted, please change the paths accordingly on your machine.
- It is suggested to run on Snellius as all notebooks and job scripts are setup for Snellius, see all_code/snellius_scripts/example_template.ipynb for Snellius setup

From all_code folder:

Step 1. Run download_data.ipynb notebook once to download the corresponding datasets

Step 2. Run MSc-Thesis\Bao\all_code\snellius_scripts\IntellEnv.job to setup the environment.yml in Snellius

Step 3. Optional: Run 21_EDA.ipynb

Step 4. Run 22_main_dataset_creation.ipynb (22_main_dataset_creation.job) , classification_base.ipynb (classification_base.job), classification_base_HPARAM.ipynb (classification_base_HPARAM.job), classification_base_t_abs.ipynb (classification_base_t_abs.job), classification_base_t_rel.ipynb (classification_base_t_rel.job), classification_new_NCW.ipynb (classification_new_NCW.job)

Step 5. Run 

Note: submit the job files to the snellius cluster to run the respective jupyter notebooks


Data is also available upon request