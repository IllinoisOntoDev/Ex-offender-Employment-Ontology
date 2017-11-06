# Ex-offender Employment Reference Ontology

## Scope of the proposed area:
   
   According to the Champaign County Criminal Justice System Assessment, reentry is one of the most prioritized programs and a crucial step in reducing recidivism. The report states that newly-released offenders are inadequately prepared for their return to the community and “the only resource established to assist them is an overworked parole agent who lacks the time and training necessary to connect offenders with supportive services to aid in successful reentry” [1]. The benefits of having a comprehensive and effective reentry program extend to all factors involved in the criminal justice system, not only reducing jail crowding as well as law enforcement costs, but also enhancing efficient public safety. Reentry program requires intensive plans and works through collaborative efforts between multiple groups, including criminal justice and social services agencies and various community-based organizations. It contains a lot of components from education and skills training, employments seeking, to housing and family planning [1]. 

   One of the most important parts of the reentry program is to help offenders looking for jobs after being released from the jail. Research has shown a clear link between crime and work [2]. Having a legitimate job lessens the chances of re-offending following release from prison. Also, the higher the wages, the less likely it is that returning prisoners will return to crime. Although most prisoners held a job before their incarceration, they confront many barriers to employment such as low education levels, stigma, and lost time in the labor force, upon their return to the community. Thus, it is important to explore the role these factors play in the reintegration process. Inspire by this issue, I am particularly interested in exploring how to improve the ex-offender employment opportunities reference system, which would be beneficial not only for offenders who are in needs of information and supports to reintegrate into the society after being released; but also for society by greatly enhancing public safety, preserving families, and strengthening the supportive systems. Towards that objective, I want to propose an ontological approach in order to improve ex-offender employment case management that not only integrate information about ex-offender employments available from different sources, but also identify a standard process how this reference system should work and who are the parties could be involved.
	
   To support ex-offender reintegration into society, some states have adopted policies encourage employment opportunities for eligible applicants. At least 27 states limit or prohibit the use of criminal records in public or private employment and for licensing eligibility [3]. In Illinois state, there are several programming and resources targeted to providing services to individuals with a criminal background who have served their sentence and need a second chance such as: City of Chicago Hiring Guidelines [4] which is produced by Chicago Department of Human Resource for reviewing criminal convictions in order to make sure that ex-offenders are referred to occupy positions that are suitable and appropriate and do not place undue risk to the City. There are several parameters taken from the guidelines when it comes to consider employments for ex-offenders: “nature of convictions” (e.g. if the conviction is job-related then state laws allows denial of employment); “evidence of rehabilitation” (e.g. establishing proof of rehabilitation allows an ex-offender to have occupational disqualifications lifted), number of convictions, length of time has passed, age of the candidate by the time of conviction, etc. Illinois state also public a resource directory to the organizations that provide supports to people who are newly released from jail [5]. Chicago itself has the Chicago Mayor's WorkNet Agencies which connects organizations have experiences in working with ex-offenders [5]. Another supportive employment program is Customized Work Service Program which is created and by Department of Family & Support Services Programs. It provides information about “transitional jobs” which are combinations of training, skill development, supportive services and real work activities. Participants would be trained into certain job categorizations (e.g. ground maintenance, snow removal, small engine repairs) [6]. 
   
   The existences of such information, agencies and programs in Illinois (some of them from Champaign county) leads us to the question of how to connect these organizations together and consolidate the information into a comprehensive centralized resource that could support prisoners after being released sufficiently and effectively. And that would be the scope of the proposed area that I want to focus on in this study.

## Relationships to the case study:

   As mentioned above, the goal of this study is to propose an ontology approach to integrate available information from different sources that could support ex-offenders getting suitable jobs after being in jail. I also want to identify who are the organizations (some of them are mentioned in the above session) interested in and currently being involved in this employment reference process and propose a standard process show these organizations should collaborate to each other. Expectedly, each organization, agencies and programs have their own ways to collect, store data and provide services to ex-offenders. Therefore, figuring those available resources and how to use them along with our data is the top priority. So far, there is several information of our dataset seem to be relevant in this case, such as: occupation information of the offenders could be used to categorize and prioritize what kinds of jobs are most suitable for offenders after being released. Education information is also helpful in order to identify which job level is applicable for individual offenders. Other demographic information such as: age also could be used. The remaining times in jail of each individual is also a factor to consider. This information is very similar with what City of Chicago Hiring Guidelines suggested when reviewing employment opportunities based on criminal convictions. 
 
## Existing published vocabularies that are candidates for extension or adaptation:

   So far, there is no existing ontology that is designed specifically for ex-offender employment reference process. We always can base on the data available, objects (which are the organizations, agencies that involved the process) to define and develop our own vocabularies particularly for this domain. One existing ontology could be helpful for reference purpose (as I can found) is Human Resources Management Ontology [7] which includes several standard ontologies: occupation ontology (which models knowledge of occupations and job categories); skill ontology (which classifies 131 skills); education ontology (which models knowledge of education level and education fields). 

## Ideas for classes and properties:
  
  Several core classes and properties would be (subjected to change, depending on the process which would be identifed more clearly towards end of the study):
  
      - Class "Prisoner": with properties such as Age (number), Previous Occupation (class), Education (class), Jail Serving Time.
      
      - Class "Ocuppation": with properties such as Occupation Name (text), Occupation Description (text).
      
      - Class Education": with properties such as Field (text), Level (text).
      
      - Class "Employment Agencies".
      
      - Class "Employment Opportunities": with proterties such as Required Field, Required Education, Required Experience etc.
      
      - Class "Ex-offender Employment Reference": serves as the document matching between a prisoner with an employment opportunity.

## References:
1. Institute for Law and Policy Planning Team. September 24, 2013. Champaign County Criminal Justice System Assessment: Final Report. 
2. Illinois Department of Employment Security. (n.d.). Retrieved October 20, 2017, from http://www.ides.illinois.gov/Pages/default.aspx 
3. Kincaid, E., Lawrence, A., July, 2011. Ex-Offender Employment Opportunities
 National.
4. Ex-offenders Re-entry Inititatives. (n.d.). Retrieved October 20, 2017, from https://www.cityofchicago.org/city/en/depts/mayor/supp_info/ex-offender_re-entryinitiatives.html 
5. Re-Entry Illinois. (n.d.). Retrieved October 20, 2017, from http://www.reentryillinois.net/home.html.
6. Customized Work Services Program Serving Ex-Offenders. (n.d.). Retrieved October 20, 2017, from http://www.mayorsinnovation.org/images/uploads/pdf/Article9_HC.pdf 
7. Human Resources Management Ontology. (n.d.). Retrieved October 20, 2017, from http://mayor2.dia.fi.upm.es/oeg-upm/index.php/en/ontologies/99-hrmontology/index.html

Linh Hoang
