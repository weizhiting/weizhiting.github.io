# neoFusion: predict fusion neoantigen and assess immunogenecity  
  
Fusion, an important class of somatic mutation, is an ideal source of tumor-derived neoantigens for the capability of creating open reading frame. In this study, the first one-top pipeline for identifying and prioritizing fusion neoantigen are presented.            
     
## Dependencies   

#### Required software:  
* [NetMHCpan 4.0](http://www.cbs.dtu.dk/cgi-bin/nph-sw_request?netMHCpan)
* [OptiType](https://github.com/FRED-2/OptiType)
* [netchop](http://www.cbs.dtu.dk/cgi-bin/nph-sw_request?netchop)
* [STAR-Fusion](https://github.com/STAR-Fusion/STAR-Fusion)
* pepmatch  module of MuPeXI, for convenience, we provide this binary tool.


#### Python package     
     xgboost
     biopython
     scikit-learn
     pandas
     numpy
     subprocess
     multiprocessing
     pickle   

#### reference  
     download from (https://data.broadinstitute.org/Trinity/CTAT_RESOURCE_LIB/) please refer to STAR-Fusion for more detail.        All the other needed materials can be found at data directory   


## Usage

