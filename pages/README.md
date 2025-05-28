## About

Rise & SHINE (Sleep Health in Infancy and Early Childhood) is a longitudinal cohort study that examines infants' sleep patterns between one month and 2 years, familial and environmental determinants of these patterns and their effect on accelerated weight gain over the first two years of life. Secondary outcomes include measures of executive functioning.

Infants were enrolled from Massachusetts General Hospital (MGH) and eligibility criteria included:

- Biologic and birthing mother-child
- Mother is > 18 years old
- Singleton birth, born at least 37 weeks gestation
- Child will receive primary care from an MGH pediatric site
- Family lives within 40 miles of Boston and does not plan to move in the next year 
- Able to speak English or Spanish
- Child is in the Level 1 nursery and does not have a genetic disorder, congenital malformation, or other condition that affects sleep
- Mother does not have a psychosocial/mental health condition, sleep disorder or substance use problem that prohibits her from participating in the study
- Mother does not have another child previously enrolled in the study

## Methods

Rise & SHINE followed a five-time point visit schedule for child subjects, encompassing the recruitment visit and up to four study visits. The initial intake visit involved eligibility screening, informed consent, maternal surveys, extraction of prenatal health record data, and scheduling the first home visit. Mothers who enrolled their infants in the study's stool collection segment were requested to save a diaper with stool. Subsequent Rise & SHINE study visits, occurring approximately at 1, 6, 12, and 24 months, replicated components of the initial visit, focusing on measurements such as infant and maternal height/weight, surveys, and the provision of actigraphs for infant sleep data. Additionally, stool collection continued at each Rise & SHINE study visit, requiring mothers to save diapers with stool within 24 hours prior to the visits.

Data collection spanned various domains within the Rise & SHINE project, including maternal and infant anthropometrics, sleep data through actigraphy, and microbiome analysis from collected stool samples. The study employed surveys at each visit to gather information on maternal and infant health, with a particular emphasis on sleep patterns. Stool samples underwent metagenomic analysis for microbiome composition, relying on 16S ribosomal RNA gene sequence-based methods. Fathers were involved through online surveys, and a qualitative sub-study within Rise & SHINE delved into factors impacting infant sleep disparities through phone interviews with a subset of mothers. Safety protocols and participant privacy measures were implemented, with staff traveling in pairs for home visits, and secure email links for survey dissemination.

The data posted on NSRR include actigraphy studies, questionnaire/survey responses, and information abstracted from the electronic health record. Visits were conducted when the infant was 1, 6, 12, and 24 months of age. 

## Data de-identification

All personally identifiable information (PII) has been removed from the data files by the NSRR team.

## Data overview

### Actigraphy
[Raw actigraphy data from Philips Actiwatch 2](:files_path:/actigraphy) (Philips Healthcare, Andover, MD, USA) is available for 373 subjects at age 1 months, 322 subjects at age 6 months, 301 subjects at age 12 months and 261 subjects at age 24 months and covers a period of approximately 5-7 days (minimum 3 days and nights of valid actigraphy data for analytic purposes). Each participant's actigraphy CSV file has activity level scores per 30-second epochs, as well as manually annotated sleep/wake data analyzed with Respironics Actiware 6 software (Version 6.09, Philips/Respironics).  Scorers manually edited rest and active intervals based on caregiver-completed logs and observation of a sharp decrease/increase in activity. The start of nighttime rest interval was identified based on reported sleep on the sleep diary and the actogram showing reduced activity (> 5 minutes) within or overlapping the night period (7:00 PM – 07:59 AM). The end of a rest interval (beginning of an active interval) was based on diary report of awakening and increased activity on the actogram (> 5 minutes). An active interval was defined as the time between two rest intervals. Additional active intervals were annotated if periods > 60 consecutive minutes of activity were observed. Within each rest interval, epochs of sleep and wake were determined based on the actogram activity using a low threshold of 80 counts for sleep.

### Covariate/phenotype datasets
[Covariate CSV files](:files_path:/datasets) contain data on 433 subjects. The [nsrrid](:variables_path:/nsrrid) column is the unique SHINE participant identifier. 

The dataset columns are described in the accompanying data dictionary files. The **variables** data dictionary file includes column names (id), labels (display names), descriptions, and other metadata. Categorical variables also include an associated "domain" (e.g., 0=No, 1=Yes, 2=Unsure), which are described in the **domains** data dictionary file.

The history of the covariate dataset and data dictionary files have been tracked on GitHub (https://github.com/nsrr/shine-data-dictionary). 

The harmonized-dataset contains many of the most frequently used demographic and sleep variables. These variables were curated by the NSRR team to allow ready inter-operability with other NSRR datasets. 

<details>
  <summary>Expand to see the list of key harmonized variables:</summary>

  <table>
    <tr><td><b>Variable</b></td><td><b>Label</b></td></tr>
    <tr><td><a href=":variables_path:/nsrr_age">nsrr_age</a></td><td>Subject age: Infant</td></tr>
    <tr><td><a href=":variables_path:/nsrr_sex">nsrr_sex</a></td><td>Subject sex: Infant</td></tr>
    <tr><td><a href=":variables_path:/nsrr_race">nsrr_race</a></td><td>Subject race: Infant</td></tr>  
    <tr><td><a href=":variables_path:/nsrr_bmi">nsrr_bmi</a></td><td>Body mass index (BMI): Infant</td></tr>  

  </table>

</details>  

## Access and usage restrictions

The SHINE dataset is only available for non-commercial use.

## Citation and acknowledgement

When using this dataset, users must cite the following:

>[Zhang GQ, Cui L, Mueller R, Tao S, Kim M, Rueschman M, Mariani S, Mobley D, Redline S. The National Sleep Research Resource: towards a sleep data commons. J Am Med Inform Assoc. 2018 Oct 1;25(10):1351-1358. doi: 10.1093/jamia/ocy064. PMID: 29860441; PMCID: PMC6188513.](https://pubmed.ncbi.nlm.nih.gov/29860441/)

>[Yu X, Quante M, Rueschman M, Ash T, Kaplan ER, Guo N, Horan CM, Haneuse S, Davison K, Taveras EM, Redline S. Emergence of racial/ethnic and socioeconomic differences in objectively measured sleep-wake patterns in early infancy: results of the Rise & SHINE study. Sleep. 2021 Mar 12;44(3):zsaa193. doi: 10.1093/sleep/zsaa193. PMID: 33057653; PMCID: PMC7953214.](https://pubmed.ncbi.nlm.nih.gov/33057653/)

Users must include the following text in any Acknowledgements:

> The Rise & SHINE study was supported by the National Institute of Health (5R01DK107972). The National Sleep Research Resource was supported by the U.S. National Institutes of Health, National Heart Lung and Blood Institute (R24 HL114473, 75N92019R002). 

## Changelog

*January 2024*

- Make SHINE dataset available for data requests

## References

- [Ash T, Davison KK, Haneuse S, Horan C, Kitos N, Redline S, Taveras EM. Emergence of racial/ethnic differences in infant sleep duration in the first six months of life. Sleep Med X. 2019 May 18;1:100003. doi: 10.1016/j.sleepx.2019.100003. PMID: 33870162; PMCID: PMC8041110.](https://pubmed.ncbi.nlm.nih.gov/33870162/)
- [Quante M, McGee GW, Yu X, von Ash T, Luo M, Kaplan ER, Rueschman M, Haneuse S, Davison KK, Redline S, Taveras EM. Associations of sleep-related behaviors and the sleep environment at infant age one month with sleep patterns in infants five months later. Sleep Med. 2022 Jun;94:31-37. doi: 10.1016/j.sleep.2022.03.019. Epub 2022 Apr 7. PMID: 35489116; PMCID: PMC10315002.](https://pubmed.ncbi.nlm.nih.gov/35489116/)
- SHINE GitHub Data Dictionary: https://github.com/nsrr/shine-data-dictionary
- SHINE GitHub Documentation: https://github.com/nsrr/shine-documentation

## Questions?

Please reach out to us at support@sleepdata.org or in the [Forum](https://sleepdata.org/forum) if you have questions.
