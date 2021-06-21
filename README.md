#  Diversity and Artificial Intelligence. Analyzing gender, geographical and business diversity in AI-related conferences.
### Bachelor Thesis Universitat Pompeu Fabra

#### Sara Estévez Manteiga

June 2021

-----


Recently, Artificial Intelligence (AI) has been reported to suffer from a diversity crisis, regarding gender, culture, ethnics and other factors. In order to contribute against this issue, we develop a framework for automatically measuring diversity in top AI conferences, as they are the most relevant outcome at the moment for AI research dissemination. We develop a DBLP automatic crawler for downloading authors information (name, surname and affiliation) for a further inference of gender, country and type of affiliation (academia vs industry). This information will be used to calculate a set of diversity indexes. This work has been developed in the context of the divinAI (https://divinai.org/)  project, an initiative from the Joint Research Centre (European Commission) and Universitat Pompeu Fabra for studying diversity of AI conferences.

‼️ The outputs are not shown in order to protect authors anonymity, as it includes personal data.


### Code

This repository contains the code developed for my Bachelor Thesis. It is organized in the following way:

- *parser* : Contains the DBLP parser devleoped which was designed to gather authors names and affiliations of some specified conference.
- *gender_inference* : Contains the method developed to infer gender based on the authors names.
- *country_inference*: Contains the country inference method based on the authors affiliation.
- *affiliation_inference*: Method that classifies the authors affiliation in three main groups.
