## Course Schedule
- [Week 0 Pre-course](#w0)

Knowledge and hands-on fundamentals

- [Week 1 Sep 9: Why this course?](#w1)
- [Week 2 Sep 16: Knowledge graph and Resource Description Framework](#w2)
- [Week 3 Sep 23: Open data policy and good enough research practice (TBD)](#w3)
- [Week 4 Sep 30: High-performance cloud computing and parallel computing (TBD)](#w4)
- [Week 5 Oct 7: Web crawling and research pipeline (TBD)](#w5)

Network analysis in social sciences

- [Week 6 Oct 14: Network analysis - basic concepts (TBD)](#w6)
- [Week 7 Oct 21: Network analysis - analysis of nodes (TBD)](#w7)
- [Week 8 Oct 28: Network analysis - analysis of communities (TBD)](#w8)
- [Week 9 Nov 4: Network analysis - Example studies in social sciences (TBD)](#w9)

Text analysis in social sciences

- [Week 10 Nov 11: Text analysis - Fundamentals and lexical resources (TBD)](#w10)
- [Week 11 Nov 18: Text analysis - Preprocessing and vectorization (TBD)](#w11)
- [Week 12 Nov 25: Text analysis - Topic modeling and classification (TBD)](#w12)
- [Week 13 Dec 2: Text analysis - Context aware and relation extraction (TBD)](#w13)
- [Week 14 Dec 9: Text analysis - Example studies in social sciences (TBD)](#w14)

[Reading Materials on Google Drive](#)

---
### <a name="w0"></a> Week 0 Pre-course
- [Complete course survey](https://utexas.instructure.com/courses/1261330/quizzes/1295833)
- Programming Basics:
	- [Linux terminal tutorial](http://linuxcommand.org/index.php)
	- [Basic Linux Commands for Beginners](https://maker.pro/linux/tutorial/basic-linux-commands-for-beginners)
- Register Accounts:
	- [GitHub](https://github.com/) / [Education (Students)](https://education.github.com/students)
	- [Chameleon Cloud](https://www.chameleoncloud.org/)


---
### <a name="w1"></a> Week 1 Sep 9: Why this course?

#### Before class
- Readings:
	- Lazer, David, Alex Pentland, Lada Adamic, Sinan Aral, Albert-László Barabási, Devon Brewer, Nicholas Christakis, et al. 2009. “Computational Social Science.” Science 323 (5915): 721–23. https://doi.org/10.1126/science.1167742.
	- Cioffi-Revilla, Claudio. 2017. Introduction to Computational Social Science. Texts in Computer Science. Cham: Springer International Publishing. https://doi.org/10.1007/978-3-319-50131-4.

### In class
- Discussion and lecture on readings.
- Course review: Syllabus, assignments, final project.

### After class
- <span style="color:red">**Assignment 1 due this week's Sunday.**</span>
- [Be familiar with "Getting started with Chameleon Cloud"](https://chameleoncloud.readthedocs.io/en/latest/getting-started/index.html)


---
### <a name="w2"></a> Week 2 Sep 16: Knowledge graph and Resource Description Framework

#### Before class
- Readings:
	- Miller, Eric J. 2001. “An Introduction to the Resource Description Framework.” Journal of Library Administration 34 (3–4): 245–55. https://doi.org/10.1300/J111v34n03_04.
- Software packages:
	- Yu, Shih Yuan, Sujit Rokka Chhetri, Arquimedes Canedo, Palash Goyal, and Mohammad Abdullah Al Faruque. 2019. “Pykg2vec: A Python Library for Knowledge Graph Embedding.” ArXiv:1906.04239 [Cs, Stat], June. http://arxiv.org/abs/1906.04239.
	- Costabello, Luca, Sumit Pai, Chan Le Van, Rory McGrath, and Nick McCarthy. 2019. “AmpliGraph: A Library for Representation Learning on Knowledge Graphs,” March. https://doi.org/10.5281/zenodo.2595043.

#### In class
- Discussion and lecture on readings.
- Group discussion: How can you use knowledge graph and RDF to solve a social science problem?
- Hands-on:
	- Start an instance on [Chameleon Cloud](https://www.chameleoncloud.org/): 1) book a lease, 2) setup a network interface for remote access, 3) start an instance.
	- Install [Anaconda Python](https://www.anaconda.com/distribution/) and [Jupyter Notebook](https://jupyter-notebook.readthedocs.io/en/stable/public_server.html)/[JupyterLab](https://jupyterlab.readthedocs.io/en/stable/getting_started/starting.html).
	- Snapshot the instance [as an image](https://chameleoncloud.readthedocs.io/en/latest/technical/images.html).

#### After class
- <span style="color:red">**Assignment 2 due this week's Sunday.**</span>


---
### <a name="w3"></a> Week 3 Sep 23: Open data policy and good enough research practice

#### Before class
- Readings:
	- Gentzkow, Matthew, and Jesse M. Shapiro. 2014. Code and Data for the Social Sciences: A Practitioner’s Guide.
	- Wilson, Greg, D. A. Aruliah, C. Titus Brown, Neil P. Chue Hong, Matt Davis, Richard T. Guy, Steven H. D. Haddock, et al. 2014. “Best Practices for Scientific Computing.” PLOS Biology 12 (1): e1001745. https://doi.org/10.1371/journal.pbio.1001745.
	- Wilson, Greg, Jennifer Bryan, Karen Cranston, Justin Kitzes, Lex Nederbragt, and Tracy K. Teal. 2017. “Good Enough Practices in Scientific Computing.” PLOS Computational Biology 13 (6): e1005510. https://doi.org/10.1371/journal.pcbi.1005510.

#### In class
- Discussion and lecture on readings.
- Data topic: [example data topic and link](https://ma-ji.github.io/open_data/data_topic/#d3)


---
### <a name="w4"></a> Week 4 Sep 30: High-performance cloud computing and parallel computing

#### Before class
- Readings:
	- Czech, Zbigniew J. 2017. “Concurrent Processes.” In Introduction to Parallel Computing, 1–34. Cambridge University Press.

#### In class
- Visit [Texas Advanced Computing Center](https://www.tacc.utexas.edu/).
- Data topic: TBD
- Hands-on:
	- Let's use [JupyterHub Server](https://chameleoncloud.readthedocs.io/en/latest/technical/jupyter.html) on Chameleon Cloud.
	- Install [`htop`](https://hisham.hm/htop/) (not easy):
		```
		$ sudo apt-get update
		$ sudo apt-get install build-essential
		$ sudo apt-get install libncurses5-dev libncursesw5-dev
		$ wget https://hisham.hm/htop/releases/2.2.0/htop-2.2.0.tar.gz
		$ tar xvfvz htop-2.2.0.tar.gz
		$ cd htop-2.2.0
		$ ./configure; make; sudo make install
		```
	- Define a function then parallel a job.

#### After class
- <span style="color:red">**Assignment 3 due this week's Sunday.**</span>


---
### <a name="w5"></a> Week 5 Oct 7: Web crawling and research pipeline


### <a name="w6"></a> Week 6 Oct 14: Network analysis - basic concepts

#### Before class
- Readings:
	- Scott, John. 2017. “What Is Social Network Analysis?” In Social Network Analysis, Fourth edition. Thousand Oaks, CA: SAGE Publications Ltd.
	- Scott, John. 2017. “Terminology for Network Analysis.” In Social Network Analysis, Fourth edition, 73–94. Thousand Oaks, CA: SAGE Publications Ltd.
	- Scott, John. 2017. “Organising and Analysing Network Data.” In Social Network Analysis, Fourth edition. Thousand Oaks, CA: SAGE Publications Ltd.

#### In class
- Discussion and lecture on readings.
- Data topic: TBD
- Hands-on practice.

#### After class
- Further readings:
	- Scott, John. 2017. “Data Collection for Social Network Analysis.” In Social Network Analysis, Fourth edition. Thousand Oaks, CA: SAGE Publications Ltd.
	- Scott, John. 2017. “The History of Social Network Analysis.” In Social Network Analysis, Fourth edition. Thousand Oaks, CA: SAGE Publications Ltd.


---
### <a name="w7"></a> Week 7 Oct 21: Network analysis - analysis of nodes

#### Before class
- Readings:
	- Scott, John. 2017. “Popularity Mediation and Exclusion.” In Social Network Analysis, Fourth edition. Thousand Oaks, CA: SAGE Publications Ltd.

#### In class
- Discussion and lecture on readings.
- Data topic: TBD
- Hands-on practice.


---
### <a name="w8"></a> Week 8 Oct 28: Network analysis - analysis of communities

#### Before class
- Readings:
	- Colizza, V., A. Flammini, M. A. Serrano, and A. Vespignani. 2006. “Detecting Rich-Club Ordering in Complex Networks.” Nature Physics 2 (2): 110–15. https://doi.org/10.1038/nphys209.

#### In class
- Discussion and lecture on readings.
- Data topic: TBD
- Hands-on practice.

#### After class
- <span style="color:red">**Assignment 4 due this week's Sunday.**</span>


---
### <a name="w9"></a> Week 9 Nov 4: Network analysis - Example social science studies

#### Before class
- Readings:
	- Heemskerk, Eelke M., and Frank W. Takes. 2016. “The Corporate Elite Community Structure of Global Capitalism.” New Political Economy 21 (1): 90–118. https://doi.org/10.1080/13563467.2015.1041483.

#### In class
- Discussion and lecture on readings.
- Data topic: TBD


---
### <a name="w10"></a> Week 10 Nov 11: Text analysis - Fundamentals and lexical resources
#### Before class
- [Complete all lessons on RegexOne](https://regexone.com/)
- Readings:
	- Jurafsky, Daniel, and James H. Martin. 2017. “Regular Expressions, Text Normalization, Edit Distance.” In Speech and Language Processing, 3rd draft. https://web.stanford.edu/~jurafsky/slp3/.
	- Bengfort, Benjamin, Rebecca Bilbro, and Tony Ojeda. 2018a. “Building a Custom Corpus.” In Applied Text Analysis with Python: Enabling Language-Aware Data Products with Machine Learning, 1 edition. Beijing Boston Farnham Sebastopol Tokyo: O’Reilly Media.
	- ———. 2018b. “Language and Computation.” In Applied Text Analysis with Python: Enabling Language-Aware Data Products with Machine Learning, 1 edition. Beijing Boston Farnham Sebastopol Tokyo: O’Reilly Media.
	- Bird, Steven, Ewan Klein, and Edward Loper. 2009a. “Accessing Text Corpora and Lexical Resources.” In Natural Language Processing with Python. Beijing ; Cambridge [Mass.]: O’Reilly. http://search.ebscohost.com/login.aspx?direct=true&scope=site&db=nlebk&db=nlabk&AN=415520.
	- ———. 2009b. “Language Processing and Python.” In Natural Language Processing with Python. Beijing ; Cambridge [Mass.]: O’Reilly. http://search.ebscohost.com/login.aspx?direct=true&scope=site&db=nlebk&db=nlabk&AN=415520.


#### In class
- Discussion and lecture on readings.
- Data topic: TBD
- Hands-on practice.


---
### <a name="w11"></a> Week 11 Nov 18: Text analysis - Preprocessing and vectorization

#### Before class
- Readings:
	- Bengfort, Benjamin, Rebecca Bilbro, and Tony Ojeda. 2018a. “Corpus Preprocessing and Wrangling.” In Applied Text Analysis with Python: Enabling Language-Aware Data Products with Machine Learning, 1 edition. Beijing Boston Farnham Sebastopol Tokyo: O’Reilly Media.
	- ———. 2018b. “Text Vectorization and Transformation Pipelines.” In Applied Text Analysis with Python: Enabling Language-Aware Data Products with Machine Learning, 1 edition. Beijing Boston Farnham Sebastopol Tokyo: O’Reilly Media.
	- Bird, Steven, Ewan Klein, and Edward Loper. 2009a. “Categorizing and Tagging Words.” In Natural Language Processing with Python. Beijing ; Cambridge [Mass.]: O’Reilly. http://search.ebscohost.com/login.aspx?direct=true&scope=site&db=nlebk&db=nlabk&AN=415520.
	- ———. 2009b. “Preprocessing Raw Text.” In Natural Language Processing with Python. Beijing ; Cambridge [Mass.]: O’Reilly. http://search.ebscohost.com/login.aspx?direct=true&scope=site&db=nlebk&db=nlabk&AN=415520.

#### In class
- Discussion and lecture on readings.
- Data topic: TBD
- Hands-on practice.


---
### <a name="w12"></a> Week 12 Nov 25: Text analysis - Topic modeling and classification
#### Before class
#### In class
- Data topic: TBD

#### After class
- <span style="color:red">**Assignment 5 due this week's Sunday.**</span>
 

---
### <a name="w13"></a> Week 13 Dec 2: Text analysis - Context aware and relation extraction

#### Before class
- Readings:
	- Bengfort, Benjamin, Rebecca Bilbro, and Tony Ojeda. 2018. “Context-Aware Text Analysis.” In Applied Text Analysis with Python: Enabling Language-Aware Data Products with Machine Learning, 1 edition. Beijing Boston Farnham Sebastopol Tokyo: O’Reilly Media.
	- Bengfort, Benjamin, Rebecca Bilbro, and Tony Ojeda. 2018. “Graph Analysis of Text.” In Applied Text Analysis with Python: Enabling Language-Aware Data Products with Machine Learning, 1 edition. Beijing Boston Farnham Sebastopol Tokyo: O’Reilly Media.

#### In class
- Data topic: TBD
- Hands-on practice.


---
### <a name="w14"></a> Week 14 Dec 9: Text analysis - Example social science studies
#### Before class
- Readings:
	- Grimmer, Justin, and Brandon M. Stewart. 2013. “Text as Data: The Promise and Pitfalls of Automatic Content Analysis Methods for Political Texts.” Political Analysis 21 (3): 267–97. https://doi.org/10.1093/pan/mps028.
	- Hollibaugh, Gary E. 2018. “The Use of Text as Data Methods in Public Administration: A Review and an Application to Agency Priorities.” Journal of Public Administration Research and Theory. https://doi.org/10.1093/jopart/muy045.

#### In class
- Data topic: TBD
- Hands-on practice.

