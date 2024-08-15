# pm4py project work

This repository contains the code associated with the project.

./Exploration.ipynb - contains the example code for the exploration part of the project
./CaseStudy.ipynb   - contains the code for the case study which was conducted in the project
./data/*            - contains the event logs

### Installation
Before running the Jupyter Notebooks the following pip-packages have to be installed:

```pip install pm4py``` <br />
```pip install pandas``` <br />
```pip install graphviz```

Another step which has to done before the Notebooks can be executed is to download the required data sets. The data sets are not included in this repository due to them being too large. The following two data sets have to be downloaded:

[BPI Challenge 2019](https://data.4tu.nl/articles/_/12715853/1) (Sales-department event log)

[BPI Challenge 2013](https://data.4tu.nl/articles/_/12693914/1) (Volvo IT incidents)

Both xes files have to be decompressed and moved to the ./data folder.
The structure after importing the files should be as follows:

./data/BPI_Challenge_2013_incidents.xes <br />
./data/BPI_Challenge_2019.xes
