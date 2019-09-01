## Assignments

- [Assignment 1: Complete data topic page (individual, 5% points)](#a1)
- [Assignment 2: Create your own cloud computing server (individual, 5% points)](#a2)
- [Assignment 3: Parallel computing (individual, 5% points)](#a3)
- [Assignment 4: Disambiguation using algorithm (individual/group, 15% points)](#a4)
- [Assignment 5: Network / text analysis (individual/group, 10% points)](#a5)

---
### <a name="a1"> Assignment 1: Complete data topic page (individual, 5% points) </a>

Tasks:
1. Complete the sign-up sheet.
2. Find a dataset of your interest and a related academic paper.
3. [Folk the course website](https://github.com/ma-ji/open_data), edit the [data topic page](/open_data/data_topic/) accordingly, and create a pull request.

Knowledge and skills practiced:
- Using GitHub;
- Markdown language.

---
### <a name="a2"> Assignment 2: Create your own cloud computing server (individual, 5% points) </a>

Tasks:
1. Create a 48-core VM on [ChameleonCloud](https://www.chameleoncloud.org/);
2. Install [Anaconda Python](https://www.anaconda.com/distribution/);
3. Run a [Jupyter Notebook](https://jupyter-notebook.readthedocs.io/en/stable/public_server.html)/[JupyterLab](https://jupyterlab.readthedocs.io/en/stable/getting_started/starting.html) server with password and SSL for encrypted communication;
4. Login your Jupyter Notebook/JupyterLab server through web-browser;
5. Open a terminal in Jupyter, [save an image of your instance](https://chameleoncloud.readthedocs.io/en/latest/technical/images.html), then submit a screenshot through Canvas showing: 1) instance image is saved successfully, and 2) Jupyter server is started successfully;
6. After submission, release your IP and server to other users (if you don't plan to use the instance).

Knowledge and skills practiced:
- Using cloud computing platform;
- Using command line terminal and Linux system.

---
### <a name="a3"> Assignment 3: Parallel computing (individual, 5% points) </a>

Tasks:
1. Start a Jupyter server as you did in Assignment#2;
2. Install [`htop`](https://hisham.hm/htop/);
3. Define a function to clean, process, or analyze a large dataset of your interest;
4. Compare the efficiency of serial computing to that of parallel computing;
5. Submit a screenshot of `htop` showing all cores are crunching numbers.

Knowledge and skills practiced:
- Using cloud computing platform;
- Using command line terminal and Linux system;
- Python programming: parallel computing.

---
### <a name="a4"> Assignment 4: Disambiguation using algorithm (individual/group, 15% points) </a>

Disambiguating entity is a common task in data preprocessing. For example, the University of Texas at Austin can be written as "UT Austin," "UT-Austin," or even "UTA." How can we recognize these records and give them a unique ID? This assignment will practice this ability.

Tasks:
[The dataset](https://utexas.instructure.com/files/50261524/download?download_frd=1) provided to you is retrieved from [Scopus](https://dev.elsevier.com/index.html), one of the largest bibliographical databases in the world. Each line is a record of a published paper on nonprofit studies. You are expected to:
1. Generate a codebook of this dataset;
2. Create criteria for disambiguating authors and affiliations.
3. Explain why the criteria can generate valid results.
3. Compile a function according to the criteria, run the function on records, and give unique IDs to these entities.
4. Verify accuracy: choose a random sample and manually check the false positive and false negative rates.
5. Describe: 1) who are the most productive authors in nonprofit studies? 2) Which are the most productive institutions in nonprofit studies? 3) How you define "productive."
6. Remember to document everything in detail using a Jupyter Notebook!

Example studies using this dataset:
- Ma, Ji, and Sara Konrath. 2018. “A Century of Nonprofit Studies: Scaling the Knowledge of the Field.” VOLUNTAS: International Journal of Voluntary and Nonprofit Organizations 29 (6): 1139–58. https://doi.org/10.1007/s11266-018-00057-5.

---
### <a name="a5"> Assignment 5: Network / text analysis (individual/group, 10% points) </a>

Choose an assignment of your interest:

#### Analysis of social networks 

#### Analysis of trends using topic modeling (individual/group, 10% points)
