# OCLGen

## Overview of the approach

System testing plays a crucial role in safety-critical domains, e.g., automotive, where system test cases are used to demonstrate the compliance of software with its functional and safety requirements. Unfortunately, since requirements are typically written in natural language, significant engineering effort is required to derive test cases from requirements.

In such a context, automated support for generating system test cases from requirements specifications written in natural language would be highly beneficial. Unfortunately, existing approaches have limited applicability. For example, some of them require that software engineers provide formal specifications that capture some of the software behavior described using natural language. The effort needed to define such specifications is usually a significant deterrent for software developers.

OCLgen is an approach which largely automates the generation of the additional formal specifications required by an existing test generation approach named UMTG. More specifically, OCLgen relies on semantic analysis techniques to automatically derive the pre- and post-conditions of the activi- ties described in use case specifications. The generated conditions are used by UMTG to identify the test inputs that cover all the use case scenarios described in use case specifications. In practice, the proposed approach enables the automated generation of test cases from use case specifications while avoiding most of the additional modeling effort required by UMTG.

Results from an industrial case study show that the approach can automatically and correctly generate more than 75% of the pre- and post-conditions characterizing the activities described in use case specifications.


## Data

The list of VerbNet classes that are likely/unlikely to appear in use case specifications and the list of VerbNet classes whose members can be processed by means of the meta-verb-transformation rule described in the paper are enclosed in a Excel document that can be downloaded from the following URL .

