# Skills prediction based on multi-label resume classification using CNN with model predictions explanation	

# Abstract
Skills extraction is a critical task when creating job recommender systems. It is also useful for building skills profiles andskills knowledge bases for organizations. The aim of skills extraction is to identify the skills expressed in documents suchas resumes or job postings. Several methods have been proposed to tackle this problem. These methods already performwell when it comes to extracting explicitly mentioned skills from resumes. But skills have different levels of abstraction:high-level skills can be determined by low-level ones. Instead of just extracting skill-related terms, we propose a multi-label classification architecture model based on convolutional neural networks to predict high-level skills from resumeseven if they are not explicitly mentioned in these resumes. Experiments carried out on a set of anonymous IT resumescollected from the Internet have shown the effectiveness of our method reaching 98.79% of recall and 91.34% of precision.In addition, features (terms) detected by convolutional filters are projected on the input resumes in order to present to theuser, the terms which contributed to the model decision.

# Dataset
This dataset contains 3 files :
- resumes_corpus.zip : This file contains a set of resumes files with the extension ".txt" with the corresponding list of labels in a file with the extension .lab
- resumes_sample.zip : This file represents the dataset of resumes in a single text file. Each line of the file contains informations about a text resume. Each line has 3 fields separeted by ":::". The first field is the reference id of the resume; the second field is the list of occupations separeted by ";" ; and the third field is the text resume.
- normalized_classes : This file contains the associations between the occupations as written by the experts and their corresponding normalized form.				
							
