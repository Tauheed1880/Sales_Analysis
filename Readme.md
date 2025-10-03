# Steps for Data Analysis report
This repositery provides step by step guidance to create an effective data analysis report, wheather you are a begginer or expert in data analyst. 

## Install packages on seperete environment using conda
To install packages on virtual environmet follow these steps

```bash
# First activate conda environment in windows using gitbash 
source /C/Users/HP/miniconda3/Scripts/activate

# create a new virtual environment and install python with specific version
conda create --name data_analysis python=3.13.0

# create requirements.txt and add libraries inside it
# then install required libraries
pip install -r requirements.txt

# another way to install libraries is:
pip install pandas numpy matplotlib seaborn ipykernel

# create a jupitor notebook inside Scripts folder
mkdir scripts
cd scripts
touch 01_sales_data_analysis.ipynb
```


