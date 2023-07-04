---
_id: 2
name: Alba Cristina Magalhaes Alves de Melo
department: Department of Computer Science
affiliation: University of Brasilia (UnB)
photo: alba_melo.jpg
bio:
    obtained her PhD in Computer Science from the Institut National Polytechnique de Grenoble (INPG), France, in 1996. Since 1997, she works at the Department of Computer Science at the University of Brasilia, Brazil, where she is Full Professor. Prof. Melo is IEEE Senior Member, Latin America Coordinator of the IEEE Technical Community of Parallel Processing (TCPP), Member of the BRICS (Brazil, Russia, India, China and South Africa) Working Group on High Performance Computing, Brazilian CNPq Researcher level 1C and Member of the Council of the Brazilian Computer Society. Prof. Melo is Associate Editor of many prestigious journals such as IEEE Transactions on Computers, Journal of Parallel and Distributed Computing and Future Generation Computer Systems. She has also served as Program Committee Member in many prestigious conferences such as IPDPS, Supercomputing, ICPP, ICS, Euro-Par, CCGrid, Cluster, ISC, SBAC-PAD and HiPC. Her research interests are high performance computing, bioinformatics and cloud computing.

# Talk
keynote_date: "Friday, October 20th — 11:00 am"
keynote_room: "TBD"
keynote_title: "Pairwise, Structural and Multiple Biological Sequence Comparison in HPC Platforms: the Quest for the Optimal Solution"
keynote_abstract:
    Biological sequence comparison is an important problem in Bioinformatics and its goal is to define how similar the sequences are, producing a score, and highlighting their similarities, producing an alignment. There are many ways to compare biological sequences and all of them require high performance computing solutions, when the optimal solution is needed. In this talk, we will deal with three types of sequence comparison. First, we discuss pairwise sequence comparison, which is often solved with dynamic programming using variants of the Smith-Waterman algorithm, producing the optimal solution with time complexity O(n^2), where n is the length of the sequences. We present our MASA tools, which can be used in CPU or GPU to pairwise compare long DNA sequences. The last version of MASA for GPUs (MASA-CUDAlign-MultiBP) attained the best performance in the literature in 2021. Then, we examine the structural RNA alignment problem, that is also solved with dynamic programming, using the Sankoff algorithm, with time complexity O(n^6). We present our CUDA-Sankoff tool and show that it has very good speedups. Next, we discuss the multiple sequence alignment (MSA) problem, which is proven NP-Complete. We present our PA-Star CPU-based tool, which executes a variant of the A-Star algorithm to compute the optimal MSA. We show that PA-Star is able to compare multiple sequences in reduced time, when compared to the literature. At the end of the talk, we will do a covid-19 case study, showing how our three tools are used to compare SARS-CoV-2 sequences.
---
