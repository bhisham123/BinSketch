BinSketch algorithm takes high dimensional binary data set as input and outputs its low-dimensional binary sketch such that using the low-dimensional sketch we can accurately estimate the similarities (Inner product, Jaccard similarity, Cosine similarity, and Hamming distance) between the original data points.  The implementation is based on the paper “Efficient Sketching Algorithm for Sparse Binary Data” due to Pratap et al. https://ieeexplore.ieee.org/document/8970717 

Bibtex entry is as follows:

@inproceedings{binsketch,  
  author    = {Rameshwar Pratap and Debajyoti Bera and Karthik Revanuru},   
  title     = {Efficient Sketching Algorithm for Sparse Binary Data},  
  booktitle = {2019 {IEEE} International Conference on Data Mining, {ICDM} 2019,  
               Beijing, China, November 8-11, 2019},  
  pages     = {508--517},  
  year      = {2019},  
  crossref  = {DBLP:conf/icdm/2019},  
  url       = {https://doi.org/10.1109/ICDM.2019.00061},  
  doi       = {10.1109/ICDM.2019.00061},  
  timestamp = {Mon, 03 Feb 2020 19:47:40 +0100},  
  biburl    = {https://dblp.org/rec/conf/icdm/PratapBR19.bib},  
  bibsource = {dblp computer science bibliography, https://dblp.org}  
}



Please cite the paper if you wish to use this implementation. 

The code is developed by “Bhisham Dev Verma”. Please drop me an email at “bhishamdevverma@gmail.com”  if you seek any clarification on the code. 
