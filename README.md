java c
DATA1002 /   1902 -   Informatics:   Data and Computation
2024 Sem2
Group   Project Stage   1
Due: 11:59pm on Sunday at the end of week 6
Value: 5% of the unit
Note: Get started your project ASAP. Discuss with your tutors and make use of Ed to ask questions, using the category “Group Report”, and the sub-category of “Stage 1” as needed.
GROUPS
This   assignment   is   done   in   groups   of   3   or   4.   All   students   in   a   group   must   be   attending   the   same   lab   session and   will be reporting    progress to your lab demonstrators. The project is handed in as a   combined effort,   but there   is   individual work   prepared and   incorporated   into the whole   report.
THE   PROJECT   WORK   FOR   STAGE   1:
Task                                                   Description                                        Group/individual                               Details
1                                                           Identify Topic                                                            Group
1. The group should define questions or issues that are not simply a factual matter, but instead looks at relationships where insights might be impactful forsome stakeholder groups.
2. We realise that you may not find data that completely resolves the issue you are targeting at, but all the data should be at least helpful to provide some insights.
2                                   Obtain Datasets and   Metadata                                Individual
1. Each member needs to obtain a different dataset that can contribute to the group’s exploration of the topic.
2. You need to keep (and provide to us) a copy the data as you originally obtained it.
3. You need to state the relevant metadata, about this dataset, including a data dictionary (which indicates which attributes there are, and what each attribute means), and provenance (giving the whole chain, from the originalsource of the data, through any intermediate collections, up to the place where you got it from [and the date you obtained it]).
It is preferred to use publicly available data (so we can check your work if we need to) but it is OK for you to work on privately-owned data so long as you have permission to use it, and permission to show them to the markers.
If the group is hoping to score beyond average, the different datasets (from different members) should all come from different sources.
3                                                       Ensure Data Quality                                            Individual
1. Each member needs to work with his/her dataset to ensure high-quality data that can be analysed.
2. Each member can use Python or spreadsheet to transform. and clean the raw data. The details of this aspect vary a lot; it depends on the data you obtained.
a. The data needed to be cleaned.
b. If the data sources were carefully curated already, you would at least write a Python program that checks that the data is clean.
At the end of this part of the work, you will have a dataset which should be high-quality.
4                                                        Produce Summaries                                            Individual
Each member can use Python or spreadsheet to produce some very simple analysis of his/her cleaned dataset, that calculates some aggregate summaries of some of the attributes.
5                                                           Integrate Datasets                                                   Group
You need to bring your datasets to the group to create a single integrated/combined dataset. There is a data cleaning step involved here as well if there are duplicates, incomplete data, a need to group or aggregate cell contents etc. The effort ofthis can vary a lot, depending on the commonality between the datasets. It is fine if a member’s dataset is not integrated to the final dataset for future stage.
Note: If the datasets have different kinds of information for different kinds of entities, itis hard to see how they can be usefully linked together to bear on a single topic. For example, it doesn’t make much sense to combine weather data from cities in NSW, with demographic data from a different state.
6                                                                   Write Report                                                            Group
Working together as a group, you need to produce a report. The structure of the report is described in the Submission section below. There is a section of the report that will be written separately by each member, as well as a combined introduction that explains the topic or issue, and a combined discussion of the data integration activity.
SUBMISSION FOR STAGE 1
1. There are three deliverables (links) for Stage 1 of the Project to be submitted to Canvas site.
2. All three deliverables should be submitted by one person, on behalf of the whole group.
3. The overall mark from this stage will appear under report submission in Canvas gradebook.
Deliverable                                        Description
Report
The report should have a front page, that gives the group name, and lists the members involved (giving their SID and unikey, not their name). The report has 3 main sections as follows:
1. Introduction: Topic / Question (maximum: 1 page - Group)
A section that
(i) describes the topic or question that you are interested to explore,
(ii) defines some groups of stakeholders and says how they will be helped by understanding thistopic or addressing thistopic/issue, and
(iii) includes a short discussion of the data you have obtained.
2. Dataset to work on (maximum: 4 pages per group member)
In this section, there should be three subsections.
a. A subsection that gives an in-depth description of the dataset, including clear statements of the relevant metadata. You need to clearly state the format and structure of the da代 写DATA1002 / 1902 - Informatics: Data and Computation 2024 Sem2Python
代做程序编程语言ta. Please give a data dictionary listing the different attributes and their meaning. Also clearly identify the provenance: show the chain of transmission, from the original collector of the data to the place from which you obtained it; along with this, clearly show the rights or restrictionsfor use that are associated with the data. This subsection should give your thoughts on any strengths or limitations of the dataset, for the purpose of investigating the topic or question of interest.
b. A subsection that describes how you ensured the data quality in the dataset. If there were any quality problems, describe what they were and how you cleaned the data; even if there were no problems, you need to describe what problems you have checked, and how you did the checks. If the cleaning was done with a spreadsheet, describe the steps clearly; if the cleaning or checking was done by Python code, then include the code in your report.
c. A subsection that provides descriptive statistics of your dataset and explains how you did using Python code (show the code and also the output of the analysis).
3. Integration (maximum: 1 page - Group)
Describe the decision-making process of data integration that produced a single dataset from the separate cleaned ones described above (e.g. Are datasets from each member used? Which parts of the dataset were integrated?). This section should give a clear account of the schema of the combined dataset. You need to include the Python code to carry out this integration.
There is a restriction of number of pages for the report; write whatever is needed to show the reader that you have earned the marks, and don’t say more than that!
Per-Member Datasets
To submit your work, first create a single folder for the whole project. Inside this main folder, create separate subfolders for each group member, with each subfolder containing that member's work. Once organised, compress the main folder into a single file, such as a .zip or .tar.gz file. Finally, submit this compressed file through Canvas. The subfolderfor each membershould contain
a. the raw dataset as it was obtained from the source
b. any spreadsheet or Python code used for cleaning/checking
c. the Python code to calculate some summaries, and
d. the clean version of the dataset (if you have used Ed or some other browser-based approach to running your code, make sure you download a copy of the code to have a file you can include in yoursubmission).
e. The clean version of the dataset should have a minimum of 10 features (attributes/variables) and a minimum of 100 records.
You then compress the top folder (with all these subfolders and their contents), then submit the single compressed file.
Integrated Dataset
You will use this in later work. This should be submitted through the Canvas system, as a single file. Note that the integrated dataset needs to come with metadata which describes at least:
• the provenance of the data,
• any licence or other restrictions on use of the data,
• description of all the changes you did between the original datasets and the final dataset; and
• the meaning of each attribute, what format or units are used, etc
• The clean version of the integrated dataset should have a minimum of 10 features (attributes/variables) and a minimum of 100 records.
If the metadata is in a separate file from the integrated data, or if the data is divided among several files, then you need to put the multiple files into a folder and then compress the folder into one file for submission on Canvas.
MARKING
There are five components to be marked. Note that C1  C5 are group marks, and all members will receive the same score, whereas C2, 3  4 are individual marks for the person who write the individual part of Section 2 of the report. Details of the marking rubrics can be found in the Canvas site.
ID                                                        COMPONENT                                               MAX POINT                                             GROUP/IND                                DESCRIPTION
C1                                       IDENTIFYING THE TOPIC                                               1                                                                   Group
This component of assessment is based on the corresponding section of the report.
C2                                    DATASETS AND METADATA                                            1                                                                       Ind
This component is assessed based on the corresponding subsections of all the separate dataset sections of the report; the uploaded data and code may be checked by the marker as supporting evidence for claims made in the report
C3                                    ENSURING DATA QUALITY                                               1                                                                       Ind
This component is assessed based on the corresponding subsections of all the separate dataset sections of the report; the uploaded data and code may be checked by the marker as supporting evidence for claims made in the report.
C4              PRODUCE SOME SIMPLE DATA SUMMARIES                       1                                                                       Ind
This component is assessed based on the corresponding subsections of all the separate dataset sections of the report; the uploaded data and code may be checked by the marker as supporting evidence for claims made in the report.
C5                                INTEGRATE THE DATASETS                                                   1                                                                Group
This component is assessed based on the corresponding section of the report;the uploaded data and code may be checked by the marker as supporting evidence for claims made in the report.





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
