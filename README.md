# PTM-BERT
Please install Anaconda first and then create a conda env.
Follow by the commands as below.
conda create -n PTM-BERT python=3.7
conda activate PTM-BERT
pip install -r requirements.txt


The env is bulit.
run python predict.py -h and will see the help
Input a Fasta file, output the predction results in CSV

optional arguments:
-h, --help show this help message and exit
--infasta INFASTA
--out OUT

for example

python predict.py --infasta ./data/Test.fasta --out Test.Result
