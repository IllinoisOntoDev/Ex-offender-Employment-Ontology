
# Ex-offender Employment Reference Ontology Final Write-up

### 1. Link to access my ontology without imports: 

https://github.com/IllinoisOntoDev/Ex-offender-Employment-Ontology/blob/master/ExoffenderEmploymentReference_Ontology_withoutImports.owl

### 2. Link to access my ontology using some other volobularies: 

https://github.com/IllinoisOntoDev/Ex-offender-Employment-Ontology/blob/master/ExoffenderEmploymentReference_Ontology.owl

In particular, I imported and used 2 vocabularies:

- Jail Program Ontology from Janina: I used Education Program class (which includes several lower classes such as Computer Skill Program, Vocational training Program). The idea is if a prison is refered to an employment opportunity throughout my system, depending on which type of employment opportunity is, the person then would be assigned to an appropriate training program within the jail in order to be ready for the opportunity after being released. 

- Employment Ontology from Anna: since both of us have the same theme about employment so I imported Anna's ontology to make sure our employment categorizations are matched with each other. I also can use her Employment Organization to refer to the companies who have intentions to hire ex-offenders.

You also can access the published ontology via the link: http://purl.org/lis590od/Fall17/XOffenderEmp

### 3. Using one of the Angency relationship terms: 

_ I imported the http://purl.org/lis590od/Fall17/OrgRel#agency into my ontology and used this as a super class for my Employment_Agency class which represents for Angency to take responsibility to refer prisoner to an employment opportunity.

### 4. Testing the imported vocabularies and new inferences:

- Inference 1: Prisoner class has 2 sub-classes: Non-degree and Degree. For those who non-degree, the previous education level should be empty (since they didn't have any education before, we assume). I created a reference to setup this rule and it ran successfully in Protege. Everytime you create a new Non-degree prisoner, the system will automatically fill  in the Education Level to "non-degree".

- Inference 2: I tried to create a new inference as in the following example: Prison Linh Hoang is referred to a Computer Engineer employment opportunity. Then she is assigned to Computer Skill Program (under Education Program class) automatically through inference in Protege. However, it doesn't work quite correctly. I hope we can take a look of it after the class is ended if we intend to follow up this. 

Thank you!
Linh



