# Research-Paper-Genome-Sequencing-and-Analysis-of-Cancer-Codons

## Complete Implementation of Various Algorithms related to Bioinformatics,which helped in successful paper presentation in RTEICT-2019.

## Paper from Proceedings were missing because of technical issues from their editorial team.

## Hence the paper was published in an International Journal "IJSRET" under July-2020 Issue.

Link : https://ijsret.com/wp-content/uploads/2020/07/IJSRET_V6_issue4_508.pdf

**First Author**: SHAILESH DHAMA

**Co-Authors** : Prof.Anooja Ali; Prof.Vishwanath Hulipalled

### Description

Genome Sequencing in the field of Bioinformatics is quite an evolving application as all the information of an organism is carried on its DNA.

Sequencing and Analysis of genome helps in rapid clinical diagnosis and treatment of diseases and advanced scientific research.

In this paper, We increase the efficiency of finding mutations with primary techniques namely, indexing, pattern matching, sequence alignments and comparison of FASTA files to find out variation, leading to the increase in accuracy of finding cancer genome mutation.


### Data
DATASET OBTAINED FROM THIS WEBSITE → https://www.ncbi.nlm.nih.gov/--


## Steps:
- Data Preprocessing.
- Pattern Matching Techniques on dataset.
- Sequence Alignment Techniques on dataset.
- Precise Detection of mutated codons from dataset.

## Results

#### Data Preprocessing
![Boyer-Moore](./CERVICAL%20CANCER%20RESULTS/1.PreProcessing/boyer%20moore.JPG)

![Kmer Indexing](./CERVICAL%20CANCER%20RESULTS/1.PreProcessing/kmer%20indexing.JPG)

#### Pattern Matching
![Approximate Matching](./CERVICAL%20CANCER%20RESULTS/2.Pattern%20Matching/approximate.JPG)

![Exact Naive Matching](./CERVICAL%20CANCER%20RESULTS/2.Pattern%20Matching/exact%20naive.JPG)

#### Sequence Alignment
![Local Alignment](./CERVICAL%20CANCER%20RESULTS/2.Pattern%20Matching/approximate.JPG)

![Global Alignment](./CERVICAL%20CANCER%20RESULTS/2.Pattern%20Matching/exact%20naive.JPG)

#### Mutation Detection
![Mutation Percentage](./CERVICAL%20CANCER%20RESULTS/4.RESULTS/results.JPG)

![Mutation Visualisation](./CERVICAL%20CANCER%20RESULTS/4.RESULTS/Cervical.JPG)

## Future Enhancements

➢ Genome Assembly and Sequencing .is emerging technology and incorporates new approaches frequently
➢ We will be researching and working further on Multiple Sequence Alignments and Chromosomal Aberrations.

### For further information

Please review the narrative of our analysis in [our jupyter notebook](./PAPER%20IMPLEMENTATION/PROJECT-FINAL.ipynb) or review our [presentation](./PAPER%20ID--449.pptx)

For any additional questions, please contact **shaileshshettyd@gmail.com)

### REFERENCES:

[1] P. Fournier-Viger, J. C. W. Lin, R. U. Kiran, Y. S. Koh, and R. Thomas, "A survey of sequential pattern mining," Data Science and Pattern Recognition, vol. 1(1), pp. 54-77, 2017.

[2.] M. S. Chen, J. S. Park, and P. S. Yu, "Efficient data mining for path traversal patterns," IEEE Transactions on Knowledge and Data Engineering, vol. 10, no. 2, pp. 209-221, 1998.

[3] C. Creighton and S. Hanash, "Mining gene expression databases for association rules," Bioinformatics, vol. 19, no. 1, pp. 79-86, 2003.
[4] Pritchard L, White JA, Birch PR, and Toth IK (2006) Genome Diagram: a Python package for the visualization of large-scale genomic data. Bioinformatics, 22, 616-617

[5] Cock PJ, Fields CJ, Goto N, Heuer ML and Rice PM (2009) The Sanger FASTQ file format for sequences with quality scores, and the Solexa/Illumina FASTQ variants. Nucleic Acids Res., 38, 1767-1771

[6]. Baeza-Yates, R.; Navarro, G. (June 1996). "A faster algorithm for approximate string matching." In Dan Hirschberg; Gene Myers (eds.). Combinatorial Pattern Matching (CPM'96), LNCS 1075. Irvine, CA. Pp. 1–23.

##### Repository Structure:

Here is where you would describe the structure of your repoistory and its contents, for example:

```

├── README.md                                           <- The top-level README for reviewers of this project.
├── A3 BATCH--FINAL REPORT.pdf                          <- Narrative documentation of analysis in pdf.
├── Genome Sequencing and Analysis of Cancer Codons.pdf <- Submitted International paper. 
├── PAPER ID--449.pptx                                  <- project presentation.
├── PAPER IMPLEMENTATION                                <- Paper Implementation Notebook on Cervical Cancer Dataset. 
    └── 1DNA Sequencing Analysis.ipynb
    └── 2PREPROCESSING.ipynb
    └── 3APPROXIMATE MATCHING.ipynb
    └── 4NAIVE.ipynb
    └── 5ALIGNMENT.ipynb
    └── 6FINAL RESULTS.ipynb
    └── PROJECT-FINAL.ipynb
├── CERVICAL CANCER RESULTS                             <- both sourced externally and generated from code.
    └── 1.PreProcessing
    └── 2.Pattern Matching
    └── 3.Sequence Alignment
    └── 4.RESULTS                                         
```
## Citing

```
@misc{Shailesh:2019,
  Author = {Shailesh Dhama},
  Title = {Research-Paper-Genome-Sequencing-and-Analysis-of-Cancer-Codons},
  Year = {2019},
  Publisher = {GitHub},
  Journal = {GitHub repository},
  Howpublished = {\url{https://github.com/ShaileshDhama/Research-Paper-Genome-Sequencing-and-Analysis-of-Cancer-Codons}}
}
```
