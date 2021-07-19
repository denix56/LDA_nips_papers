The "topic_modeling_dp.ipynb" file contains the code used to generate the results.

The results folder containts figures and text files corresponding to each alpha value, with name "a{alpha}.txt". These contain information about the cluster parameters at initialization and after execution, as well as a number of words corresponding to the top-k word counts for each cluster.

To install:
python -mvenv .env
source .env/bin/activate
pip3 install -U pip
pip3 install -r requirements.txt
