# AMLToolTestingConda

## Installation

1. Initialize a dedicated environment using anaconda prompt (miniconda).
   ```
   conda create -n envART python==3.10.9
   ```
2. Activate the new conda-environment using anaconda prompt (miniconda).
   ```
   conda activate envART
   ```
   
3. Set up local repository using pip (already installed in miniconda and conda)
   
   ```
   pip install -r requirements.txt
   pip install -v -e .
   ```
4. Install further packages (toBeChecked)
   e.g. scipy
   ```
    conda install scipy=0.15.0
   ```
   or 
   ```
    pip install scipy=0.15.0
   ```
   
6. Update requirements.txt file by enviroment using pip (don't use conda export, with this step 4 wouldn't work anymore) 
  ```
  pip freeze > requirements.txt
  ```
