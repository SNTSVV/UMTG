# UMTG

## Overview 

In safety critical domains, software engineers must ensure traceability between requirements and system test cases to comply with safety standards, e.g. ISO-26262. Requirements management tools like IBM Doors are commonly adopted in industry, but these tools provide support for only the maintenance of traceability links. Software engineers thus have both to manually derive system test cases from functional requirements written in natural language and establish traceability links between requirements and their corresponding test cases. 

UMTG is a toolset for automatically generating executable and traceable system test cases from use case specifications and domain model. In order to extract behavioral information from use case specifications and enable test automation, UMTG employs Natural Language Processing (NLP), a restricted form of use case specifications, and constraint solving.

UMTG is integrated with two tools, IBM Doors and IBM Rational Rhapsody that are widely adopted in industry to manage requirements and design systems. UMTG has been successfully evaluated on an industrial case study.

UMTG has been depevoled in a project in collaboration with IEE.

{% include youtube.html id=uLIio468jWE %}

## System Requirements

UMTG has been tested on Windows 7 with:

1. Java Development Kit (JDK) 1.7.0 and above
2. Telelogic DOORS 8.3 
3. IBM Rational Rhapsody 8.0.3
4. GATE Framework 7.1 release [Download]

A version of UTMG that does not require Telelogic DOORS will be released soon.

## Download & Installation


1. Download the Installation Package from the following link : [UMTG Distribution.zip](https://sntsvv.github.io/UMTG/data/UMTG_Distribution.zip).
2. To install UMTG, please follow the UMTG User Manual : [UMTG_Manual.pdf](https://sntsvv.github.io/UMTG/data/UMTG_Manual.pdf).



## Publications

Chunhui Wang, Fabrizio Pastore, Arda Goknil, Lionel Briand, and Zohaib Iqbal. 2015. Automatic generation of system test cases from use case specifications. In Proceedings of the 2015 International Symposium on Software Testing and Analysis (ISSTA 2015). ACM, New York, NY, USA, 385-396. DOI: http://dx.doi.org/10.1145/2771783.2771812 [link](http://orbilu.uni.lu/handle/10993/21147)

Chunhui Wang, Fabrizio Pastore, Arda Goknil, Lionel C. Briand, and Zohaib Iqbal. 2015. UMTG: a toolset to automatically generate system test cases from use case specifications. In Proceedings of the 2015 10th Joint Meeting on Foundations of Software Engineering (ESEC/FSE 2015). ACM, New York, NY, USA, 942-945. DOI: https://doi.org/10.1145/2786805.2803187 [link](http://orbilu.uni.lu/handle/10993/21772)

C. Wang, F. Pastore and L. Briand, "Automated Generation of Constraints from Use Case Specifications to Support System Testing," 2018 IEEE 11th International Conference on Software Testing, Verification and Validation (ICST), Vasteras, 2018, pp. 23-33.  doi: 10.1109/ICST.2018.00013 [link](http://orbilu.uni.lu/handle/10993/33914)


