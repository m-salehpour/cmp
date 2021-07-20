# A Comparative Analysis of Knowledge Graph Query Performance
This code base is part of a research project to perform a comparative analysis of Knowledge Graph (KG) query performance. To this end, we designed and developed a parser to convert KG datasets from RDF/N-Triples syntax to the JSON-LD collections (please see Parser directory). We ran our experiment using the publicly available Benchmarks by loading the different representations corresponding to a KG into different data managment systems by mapping it onto the JSON-LD. The benchmark queries (Please see Queries file) were executed over each of the data management systems separately and query execution times computed to analyze the effects of the different representations on KG query performance. Our results are availablle here (Please see the ESWC2020 - LineGraphs -V2 file).

Please note that to run the parser, it is needed to set the path of input RDF/N-Triples KG dataset within the source code. The parser can be compiled using GNU C++ Compiler, e.g., g++ -std=c++11 JSON-LD.cpp -o runJSON (e.g., JSON-LD.cpp is the developed parser to generate the JSON-LD representation of a given KG).


# Benchmark Datasets

| Dataset  | Link |
| ------------- | ------------- |
| BioBench-Allie  | https://zenodo.org/record/3592209/files/BioBench-Allie.nt?download=1  |
| BSBM-10M  |  https://zenodo.org/record/3592209/files/BSBM-10M.nt?download=1 |
| BSBM-100M  | https://zenodo.org/record/3592209/files/BSBM-100M.nt?download=1  |
| FishMark  | https://zenodo.org/record/3592209/files/FishMark.nt?download=1  |
|WatDiv-10M   | http://dsg.uwaterloo.ca/watdiv/watdiv.10M.tar.bz2  |
|  WatDiv-100M |  http://dsg.uwaterloo.ca/watdiv/watdiv.100M.tar.bz2 |
| WatDiv-1000M  | http://dsg.uwaterloo.ca/watdiv/watdiv.1000M.tar.bz2  |
|BowlognaBench   | https://zenodo.org/record/3592209/files/BowlognaBench.nt?download=1  |



# Authors
* Masoud Salehpour (University of Sydney)
* Joseph G. Davis  (University of Sydney)

