# CTSpellingArticle2024
Data and result files for Tresoldi/Robinson work on CT spellings 2021-24

The data is contained in three folders, each folder corresponding to one of the three sets of data used in the article's analysis, as follows:

“sorted by regularization”. This folder contains spelling data and results derived from the regularization process, where (for example) spellings of forms regularized to “goode” are distinguished from spellings of forms regularized to “god”;

“sorted by part of speech”. This folder contains spelling data and results derived from a lemmatization and part-of-speech identification process, where (for example) spellings of forms lemmatized  to “goode” singular adjective are distinguished from spellings of forms regularized to “goode” plural adjective, and forms lemmatized to “gode” singular noun nominative case are distinguished from “gode” singular noun oblique case (as in “to gode”).

“all spellings unsorted”. This folder contains spelling data as undifferentiated counts of “bags of words”: for each witness: so many occurrences of “good”, so many of “goode”, so many of “god”, so many of “gode”.

Each folder contains the following files (under various names):

A . json file holding all the data, structured according to its categorization. The “sorted by part of speech” folder contains two .json files, one with spellings organized by headword lemma, the other organized by part-of-speech;

Two .nex Nexus files containing all the data. In the “sorted by regularization” and  “sorted by part of speech” folders one Nexus file groups spellings by variant sites within each line, the other Nexus file groups spellings  by words within each line. In the “all spellings unsorted” folder one Nexus file contains all the spellings organized by spelling; the second holds a Nexus distance matrix with distances created according to the Manhattan distance algorithm;

A .dst distance matrix file, containing a distance matrix constructed with distacnes calculated by the Manhattan distance algorithm;

A “features” file, containing a spreadsheet ranking each variant site according to its impact on the analysis 

Multiple .pdf files visualizing the results of our analysis, with the names reflecting the analysis each contains. Files with names including “Splits” were created using the SplitsTree algorithm and software (Huson and Bryant 2006; “SplitsTree | Universität Tübingen,” n.d.)

The “sorted by regularization” folder also contains a single image file, “tiagoplot1.jpg”, visualizing the results of PCA analysis on the “sorted by regularization” data.
