# EPC_Project_3_10_9
EPC project with correct installation parameters

A small installation guide (for starting from scratch to your own project):
* install python 3.10.9
* install pycharm
* install poetry
* add poetry to path
* create poetry project in pycharm, using python 3.10.9
* run poetry add -D kedro in console
* run kedro new in console
* add 
	"kedro-datasets[pandas.CSVDataSet, pandas.ExcelDataSet, pandas.ParquetDataSet]~=1.0.2
	kedro-viz~=5.0
	scikit-learn~=1.0"
  to src/requirements.txt
* run poetry add $( cat <PROJECT-NAME>/src/requirements.txt)   
* install git
* make github account
* link github account to pycharm (when problems arise, contact me for explanation)

A small installation guide (to clone this repo and getting it working): 
* ...
* ...

