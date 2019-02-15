# UMTG

## Overview 

In safety critical domains, software engineers must ensure traceability between requirements and system test cases to comply with safety standards, e.g. ISO-26262. Requirements management tools like IBM Doors are commonly adopted in industry, but these tools provide support for only the maintenance of traceability links. Software engineers thus have both to manually derive system test cases from functional requirements written in natural language and establish traceability links between requirements and their corresponding test cases. 

UMTG is a toolset for automatically generating executable and traceable system test cases from use case specifications and domain model. In order to extract behavioral information from use case specifications and enable test automation, UMTG employs Natural Language Processing (NLP), a restricted form of use case specifications, and constraint solving.

UMTG is integrated with two tools, IBM Doors and IBM Rational Rhapsody that are widely adopted in industry to manage requirements and design systems. UMTG has been successfully evaluated on an industrial case study.

UMTG has been depevoled in a project in collaboration with IEE.

## System Requirements

UMTG has been tested on Windows 7 with:

    Java Development Kit (JDK) 1.7.0 and above
    Telelogic DOORS 8.3 
    IBM Rational Rhapsody 8.0.3
    GATE Framework 7.1 release [Download]


System testing plays a crucial role in safety-critical domains, e.g., automotive, where system test cases are used to demonstrate the compliance of software with its functional and safety requirements. Unfortunately, since requirements are typically written in natural language, significant engineering effort is required to derive test cases from requirements.

In such a context, automated support for generating system test cases from requirements specifications written in natural language would be highly beneficial. Unfortunately, existing approaches have limited applicability. For example, some of them require that software engineers provide formal specifications that capture some of the software behavior described using natural language. The effort needed to define such specifications is usually a significant deterrent for software developers.

OCLgen is an approach which largely automates the generation of the additional formal specifications required by an existing test generation approach named UMTG. More specifically, OCLgen relies on semantic analysis techniques to automatically derive the pre- and post-conditions of the activi- ties described in use case specifications. The generated conditions are used by UMTG to identify the test inputs that cover all the use case scenarios described in use case specifications. In practice, the proposed approach enables the automated generation of test cases from use case specifications while avoiding most of the additional modeling effort required by UMTG.

Results from an industrial case study show that the approach can automatically and correctly generate more than 75% of the pre- and post-conditions characterizing the activities described in use case specifications.


## Data

The list of VerbNet classes that are likely/unlikely to appear in use case specifications and the list of VerbNet classes whose members can be processed by means of the meta-verb-transformation rule described in the paper are enclosed in a Excel document that can be downloaded from the following URL .


## Download & Installation


Download Installation Package: [UMTG Distribution.zip](https://sntsvv.github.io/UMTG/data/UMTG_Distribution.zip).
Please follow the RUCM User Manual to do the installation : [UMTG_Manual.pdf](https://sntsvv.github.io/UMTG/data/UMTG_Manual.pdf).



## Publications

Chunhui Wang, Fabrizio Pastore, Arda Goknil, Lionel Briand, and Zohaib Iqbal. 2015. Automatic generation of system test cases from use case specifications. In Proceedings of the 2015 International Symposium on Software Testing and Analysis (ISSTA 2015). ACM, New York, NY, USA, 385-396. DOI: http://dx.doi.org/10.1145/2771783.2771812 [link](http://orbilu.uni.lu/handle/10993/21147)

Chunhui Wang, Fabrizio Pastore, Arda Goknil, Lionel C. Briand, and Zohaib Iqbal. 2015. UMTG: a toolset to automatically generate system test cases from use case specifications. In Proceedings of the 2015 10th Joint Meeting on Foundations of Software Engineering (ESEC/FSE 2015). ACM, New York, NY, USA, 942-945. DOI: https://doi.org/10.1145/2786805.2803187 [link](http://orbilu.uni.lu/handle/10993/21772)

C. Wang, F. Pastore and L. Briand, "Automated Generation of Constraints from Use Case Specifications to Support System Testing," 2018 IEEE 11th International Conference on Software Testing, Verification and Validation (ICST), Vasteras, 2018, pp. 23-33.  doi: 10.1109/ICST.2018.00013 [link](http://orbilu.uni.lu/handle/10993/33914)


