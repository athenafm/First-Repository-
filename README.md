
<!-- README.md is generated from README.Rmd. Please edit that file -->

# My First Repository

## Research Interests

I am currently completing a Masters in Medical Sciences and conducting research in Pediatric obesity under the supervisor Dr. Katherine Morrison. My research interests align with my Masters program as I enjoy working with children and have a fascination with cardiovascular research. Early diagnosis and prevention are critical in preventing obesity as it can lead to future health complications such as diabetes, stroke, and cardiovascular events. With additional research, this will help to create effective and tailored approaches in treatment plans delivered by physicians. Currently, there is very little known about the genetic influences on pediatric obesity and further inquiry into this field may help to target specific genes and prevent the onset of obesity. I believe this a pressing issue in our society and I am excited to be apart of this research for the next couple of years.

# Favourites

## Favourite Music

1.  *Espresso* by Sabrina Carpenter
2.  *Birds of a Feather* by Billie Eilish
3.  *Circles* by Post Malone
4.  *Pink + White* by Frank Ocean
5.  *Chanel* by Frank Ocean

## Favourite Equation

$$
y = mx + b 
$$

## Favourite Artists

| Name | Achievements |
|------------------------------------|------------------------------------|
| Sabrina Carpenter | Won Video Music Award for *Song of the Year* for her song Espresso |
| Billie Eilish | Won 9 Grammy Awards |
| Daniel Caesar | Won Grammy Award for *Best R&B Performance* in 2019 for his song Best Part |
| Harry Styles | Won Grammy Award for *Album of the Year* in 2023 for his album Harry's House |
| Ariana Grande | Won Billboard Music Award for *Top Female Artist* in 2019 |

# A Chunk of Code

```{r}
print("I am excited to learn how to code using R studio")
```


<!-- badges: start -->
<!-- badges: end -->



``` r
summary(cars)
#>      speed           dist       
#>  Min.   : 4.0   Min.   :  2.00  
#>  1st Qu.:12.0   1st Qu.: 26.00  
#>  Median :15.0   Median : 36.00  
#>  Mean   :15.4   Mean   : 42.98  
#>  3rd Qu.:19.0   3rd Qu.: 56.00  
#>  Max.   :25.0   Max.   :120.00
```

You can also embed plots, for example:

![](README_files/figure-gfm/pressure-1.png)<!-- -->

## Project Data Analysis 

**List of Data I have to collect for my thesis project** 
1. Resting energy expenditure in patients undergoing a pharmacological intervention for weight loss (adolescents 12-17 years old diagnosed with obesity)
2. Muscle work efficiency of patients undergoing a pharm intervention or a behavioural lifestyle program
3. Skeletal muscle mass at three different timepoints in the study (at baseline, 6 months and 12 months)

For the data collected above I will be using new datasets by collecting the data myself alongside another research coordinator. I will not be using existing datasets, however the study is based on previous studies that have been conducted in my research lab.

**Legal and ethical restrictions**

Some of the legal and ethical restrictions I must take into account is storing patient data. During each of the study visits, it is important that personal information such as name, phone number, email, medical history is kept privately and only shared between the research investigator and the participant. In order to ensure this is kept securely, personal info such as name will be kept under a serial number to avoid any breach of privacy. Additionally, the data will be stored in a secure place kept under "lock and key" in a file cabinet in which only certain members of the research team have access to. 

**Strategies to protect the value of my data through Quick Hits for Data Management** 

I will be sure to keep the raw data of my project on separate platforms to ensure there are multiple copies. For example, I will keep a copy on Rstudio itself and another copy will be present on Github as well. Additionally, I have a google drive and Onedrive account that is shared with multiple members of my team to ensure they have access and have multiple copies. Lastly, the raw data is also kept on a separate computer that has previous research and data from other studies as well 

Raw data will also be kept in a raw-data folder under my Github repository. I anticipate that the data will be kept in csv files and pdf files, all of wwhich can be converted to open formats. One of the naming conventions that I will use for my project data can be "my-first-project", using dashes to illustrate the spaces in between the words. 

Some of the standards that are relevant to my project involve making sure the particpants fit inside the inclusion and exclusion criteria. For example, to elimiante variability and confounding variables, none of the participants can be pregnant as we do not know the effects of the drug on pregnancy outcomes. Additionally, the participants have to have bloodwork that fits within a certain range, if one of their liver enzymes are too high then this opens up the possibility that some of our results may be not representative of the general population. 

Some of the existing standards that are used in my project is to make sure that the methods that are used to measure energy expenditure are consistent. For example, prior to our metabolic visits, we have to measure body composition using either a DXA scan (gold standard) or a BIA scan. Sometimes, participants cannot fit onto DXA scans so we must use a BIA scan to accomodate them. If it turns out that they lose weight later on in the study using the weight loss drug, we need to use a BIA scanner consistenly throughout the study in order to eliminate variability. A standard that I want to create to help manage my data is to ensure that I am using the same instruments throughout different timepoints in the study. For example, if I use a different tape measurer to obtain waist circumference for one patient, then I must use this throughout the study for that participant to maintain consistency. 

In order to document my data throughout my project I will ensure a Github repository is created so that way I can save my changes and look at the different versions that I have created. This is helpful as it will ensure that I am able to see the progress of my project. 



## Data Management Plan 

# Measuring energy expenditure in adolescents with obesity administered a weight loss drug

A Data Management Plan created using DMP Assistant
Creator: Athena Flores Miranda
Principal Investigator: Katherine Morrison
Data Manager: Alessandro Malvestiti
Project Administrator: Alessandro Malvestiti
Affiliation: McMaster University
Funder: McMaster University
Template: Portage Template


# Project abstract

Over the course of 12 months, we will measure energy expenditure in adolescents with obesity who are enrolled in a Behavioural Lifestyle Program (BLP) and given semaglutide. As there is little research on adaptive thermogenesis, this will clarify the mechanism of how our body responds to weight loss. Adolescents will be divided into two groups; one group will recieve the drug during the first 6 months and then come off the drug in the last 6 months. This will also give us more insight into how individuals respond to the removal of weight loss medications. There will be metabolic visits where participants' energy expenditure will be measured through indirect calorimetry and and imaging visit where they will be exposed to a cold stimulus and their brown adipose tissue will be quantified.


# Data Collection
*What types of data will you collect, create, link to, acquire and/or record?* 

*Expected data product #1:*

*Data type:* Observational
*Responsible investigator:* Researcher
*Product description:* Resting Energy Expenditure will be measured by Indirect Calorimetry at the Hamilton Health Sciences building at McMaster University. This will be done by acquiring the
measurements of carbon dioxide and oxygen a participant will exhibit during a 60 minute period in the room.
*Intended repository:* Files will be in csv format, and will be stored on private Github repository with only some members having access to the storage in order to maintain patient privacy.

*Expected data product #2:*

*Data type:* Observational/Interventional
*Product description:* Physical Activity Energy expenditure will be measured by Indirect calorimetry. Participants will be hooked up to an ergometer which will measure their carbon dioxide and
oxygen levels and specific peak powers (5%, 10%, and 40%).
*Intended repository:* Files will be in csv format, and will be stored on private Github repository with only some members having access to the storage in order to maintain patient privacy.

*Expected data product #3:*

*Data type:* Observational/Interventional
*Product description:* Participants will visit St Joseph's hospital to recieve an MRI to measure their brown adipose tissue activity. Subjects will have a "pre-cold exposure" MRI and then will be asked
to wear a cold suit for 30 minutes. After the cold exposure, participants will then get a second MRI scan where the technician will measure their brown adipose tissue activity post cold exposure.
*Intended repository:* Files will be in csv format, and will be stored on private Github repository with only some members having access to the storage in order to maintain patient privacy.

*What file formats will your data be collected in? Will these formats allow for data re-use, sharing and long-term access to the data?*

The data collected will be stored on an Excel spreadsheet that will be converted to a CSV file to enable sharing and access to other project users. Additionally, XML files may be used if CSV is not
permitted. This data will be stored on a separate work computer to ensure there is no breech of personal information. It will also be back up onto the Github repository to ensure that if the
laptop/work computer breaks down then there is an extra copy that the data can be accessed from. These formats allow for data re-use, sharing and long term access.
What conventions and procedures will you use to structure, name and version-control your files to help you and others better understand how your data are organized?

*File names:*
Relevant details pertaining to the data file will be included in the file naming process
Example: Participantx_CRF_V1_2024-10-22.XML

Dates:
Ensure that the date is written on each of the files and also in a consistent format that is agreed upon prior to the completion of the study
Example: DD-MM-YY

Versions:
As versions are edited by other collaborators, it is important to write down the version number that the file so other individuals are aware that they are working on the most recent version
Example: V1_2024-11-22, V2_ 2024-11-22

# Documentation and Metadata
*What documentation will be needed for the data to be read and interpreted correctly in the future?*

Documentation that will be needed includes a proper Data Management Plan as it describes how the data will be collected, processed and stored for future use. Additionally, an manual of procedures (MOP) will be created which outlines all the required procedures needed for the study. For example, in the MOP there will be a detailed, step by step procedure that illustrates how to properly store data information, how to keep storage secure and anything pertaining to the study. This is useful as it allows new students coming onto the project to have a list of instructions when
going into a study visit.

In terms of elements that are important to document, there should be variable definitions. For example, when making a database on RedCAP, a code dictionary can be used to keep track of all the variable names and definitions

*How will you make sure that documentation is created or captured consistently throughout your project?*

In order to make sure that documentation is created/captured consistently throughout my project, I will start the project off by creating a set of standards. These will be the guidelines for the rest
of the project to ensure that file formats, data and information are stored in a way that is comprehensible for everybody on the team. Additionally, several checkpoints throughout the project will be
implemented to ensure that research team members have the ability/opportunity to capture any potential changes in the data collection/processing.

*If you are using a metadata standard and/or tools to document and describe your data, please list here.*

Some of the tools that will be used to document and describe the data is the database "RedCAP". This is a secure, online, free program that allows you to upload patient specific information pertaining to the study and build surveys to administer to participants. Additionally, R/R Studio will be used for statistical computing and graphics.

# Storage and Backup

*What are the anticipated storage requirements for your project, in terms of storage space (in megabytes, gigabytes, terabytes, etc.) and the length of time you will be storing it?*

The storage requirements for the project will be around 5GB and it will be stored for up to 15 years in the secure offices of Dr. Katherine Morrison. This storage space will be comprised of patient information, data collection from the interventions provided and corresponding Case Report Forms if necessary.

*How and where will your data be stored and backed up during your research project?*

Data will be stored on fixed laptop hard drives and networked onto cloud based servers. For example, the data will be present on a secure GitHub repository and will be on Microsoft Teams so
everybody on the team can have access to the data. Additionally, there will be a USB drive that is password protected that will serve as a "back up" in case any of the files get compromised.
How will the research team and other collaborators access, modify, and contribute data throughout the project?
The research team will have access to every file and have the ability to edit as well. They can contribute to the data through specific permission that will be granted to each team member at the beginning of the project. Once access is granted, collaborators will be able to add to the research.

*Preservation*

Where will you deposit your data for long-term preservation and access at the end of your research project?
The data will be deposited in a secure repository that is used for clinical trials. The website is called clinicaltrials.gov, which is a specialized clinical research repository ensuring compliance and
transparency standards. Additionally, as mentioned previously, it will be stored on Microsoft Teams and Github to ensure that multiple team members are able to collaborate/edit this research

*Indicate how you will ensure your data is preservation ready. Consider preservation-friendly file formats, ensuring file integrity, anonymization and de-identification, inclusion of supporting
documentation.*

To ensure that the data is preservation ready, preservation-friendly file formats will be used such as CSV or TSV (tabular data) or PDF documents. Additionally, participant's personal information
such as name and birthdate will be anonymized to a series of numbers to maintain confidentiality. For example, if someone's name is 'Athena' with a birthday of Dec-04-01, their information will be
stored as JOULE-02 birthday- 12-01.

# Sharing and Reuse

*What data will you be sharing and in what form? (e.g. raw, processed, analyzed, final).*

The team will be divided into different tasks to allow for the processing of data. Each stage/team will have different forms of data that will allow for the final product to be in processed form. The following is a list of each of the groups that will be involved in data sharing process: De-identifiers, Processors of data, Analyzed data, Final end-points/finishing touches.

The first group, the 'de-identifiers' will be in charge of ensuring that any personal information will be hidden and replaced with a series of numbers to avoid any breach of confidentiality. The paper
files that have the participant's information will be stored in a secure locker in the facilities of Dr. Morrison.

The second group will be involved in the processing of data. These members will take the raw data and eliminate/account for any outliers and will ensure that the data will be ready for the next
stage.

The next team will be involved with analyzing the data. This will include using programs and softwares like R studio, Redcap, and other graphical softwares to predict/show any trends in the data. This will help to determine if the study produced the predicted effect.

Lastly, the final touches will be for those at the final end-point stage, where everything that has been done will be
The data that will be shared will be in raw form with other team members. This will be done in order to allow for data analysis and allow the comparison/examination of outliers, variables etc.

*Have you considered what type of end-user license to include with your data?*

A restricted access license will most likely be used for the data. This will be used as there is sensitive clinical data. This allows users to apply for access and comply with ethical guidelines.

*What steps will be taken to help the research community know that your data exists?*

There are weekly newsletters in my department that showcases the newest research. This is called the Metabolism, Obesity diabetes Research newsletter which highlights different students'
research and publications. The research community can read these newsletters as they are emailed to everybody in the department once a week. Additionally, the data will be accessed via pubmed, nich once published.

# Responsibilities and Resources
Identify who will be responsible for managing this project's data during and after the project and the major data management tasks for which they will be responsible.
The person who is responsible for the managing this project's data will be the research coordinator as they are in charge of everything related to the study protocol, data management. The major
tasks they will be responsible for are as follows:

1. Data collection
2. Data storage
3. Data cleaning
4. Data backup
5. Data security

*How will responsibilities for managing data activities be handled if substantive changes happen in the personnel overseeing the project's data, including a change of Principal Investigator?*

In the event that the Principal Investigator leaves there is another co-investigator on the study that will take full control of the project. If it turns out that the co-investigator does not want to take full
control the research coordinator take partial responsibility for the study.

*What resources will you require to implement your data management plan? What do you estimate the overall cost for data management to be?*
Below is a breakdown of the resources/cost associated with data management:
Personnel:
Data Manager: Overseeing data management tasks.
Data Analysts: Conducting analyses and maintaining data integrity.
Software Tools:
Data Collection Tools: RedCAP, ASA or custom databases.
Data Cleaning and Analysis Software: Tools like R, Python, SAS, or SPSS.
Data Management Systems: Clinical trial management systems (CTMS) or electronic data capture (EDC) systems.
Servers/Cloud Storage: For data storage and backup solutions.
Computers/Workstations: For data entry and analysis.
Training: other students or coordinators
TOTAL COST: 100,000-200,000

# Ethics and Legal Compliance

*If your research project includes sensitive data, how will you ensure that it is securely managed and accessible only to approved members of the project?*

Members who have access to the data will have to sign a confidentiality agreement before coming into the lab. In this contract, members will agree to keep the information they come into contact
private and only share with other members who have access to this data. Additionally, the data will be password protected so that way the information is kept private and only those who are doing
research in the lab will be able to access it.

*How will you manage legal, ethical, and intellectual property issues?*
To manage legal ethical and intellectual use we have a legal team that consists of lawyers that will help us to execute the research required in a safe and controlled way. Additionally, before a
study is published it has to be submitted to the ethics board. The ethics board that is being used for this study is the Hamilton Research Ethics Board.



