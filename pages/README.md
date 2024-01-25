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

The data sets include actigraphy studies, questionnaire/survey responses, and information abstracted from the electronic health record. Visits were conducted when the infant was 1, 6, 12, and 24 months of age. 

## Data overview

### Actigraphy
[Raw actigraphy data from Philips Actiwatch 2](:files_path:/actigraphy) (Philips Healthcare, Andover, MD, USA) is available for 384 subjects at age 1 months, 337 subjects at age 6 months, 315 subjects at age 12 months and 290 subjects at age 24 months and covers a period of approximately 5-7 days (minimum 3 days and nights of valid actigraphy data). Each participant's actigraphy CSV file has activity level scores per 30-second epochs, as well as manually annotated sleep/wake data analyzed with Respironics Actiware 6 software (Version 6.09, Philips/Respironics).  Scorers manually edited rest and active intervals based on caregiver-completed logs and observation of a sharp decrease/increase in activity. The start of nighttime rest interval was identified based on reported sleep on the sleep diary and the actogram showing reduced activity (> 5 minutes) within or overlapping the night period (7:00 PM – 07:59 AM). The end of a rest interval (beginning of an active interval) was based on diary report of awakening and increased activity on the actogram (> 5 minutes). An active interval was defined as the time between two rest intervals. Additional active intervals were annotated if periods > 60 consecutive minutes of activity were observed. Within each rest interval, epochs of sleep and wake were determined based on the actogram activity using a low threshold of 80 counts for sleep.

### Covariate/phenotype datasets
[Covariate CSV files](:files_path:/datasets) contain data on 433 subjects. The [nsrrid](:variables_path:/nsrrid) column is the unique SHINE participant identifier. 

The dataset columns are described in the accompanying data dictionary files. The **variables** data dictionary file includes column names (id), labels (display names), descriptions, and other metadata. Categorical variables also include an associated "domain" (e.g., 0=No, 1=Yes, 2=Unsure), which are described in the **domains** data dictionary file.

The history of the covariate dataset and data dictionary files have been tracked on GitHub (https://github.com/nsrr/shine-data-dictionary). 

## Access and usage restrictions

The SHINE dataset is only available for non-commercial use.

## Citation and acknowledgement

When using this dataset, users must cite the following:

>[Zhang GQ, Cui L, Mueller R, Tao S, Kim M, Rueschman M, Mariani S, Mobley D, Redline S. The National Sleep Research Resource: towards a sleep data commons. J Am Med Inform Assoc. 2018 Oct 1;25(10):1351-1358. doi: 10.1093/jamia/ocy064. PMID: 29860441; PMCID: PMC6188513.](https://pubmed.ncbi.nlm.nih.gov/29860441/)

>[Yu X, Quante M, Rueschman M, Ash T, Kaplan ER, Guo N, Horan CM, Haneuse S, Davison K, Taveras EM, Redline S. Emergence of racial/ethnic and socioeconomic differences in objectively measured sleep-wake patterns in early infancy: results of the Rise & SHINE study. Sleep. 2021 Mar 12;44(3):zsaa193. doi: 10.1093/sleep/zsaa193. PMID: 33057653; PMCID: PMC7953214.](https://pubmed.ncbi.nlm.nih.gov/33057653/)

Users must include the following text in any Acknowledgements:

> The National Sleep Research Resource was supported by the U.S. National Institutes of Health, National Heart Lung and Blood Institute (R24 HL114473, 75N92019R002). The Rise & SHINE study was supported by the National Institute of Health (5R01DK107972).

## Changelog

*January 2024*

- Make SHINE dataset available for data requests

## References

- SHINE GitHub Data Dictionary: https://github.com/nsrr/shine-data-dictionary
- SHINE GitHub Documentation: https://github.com/nsrr/shine-documentation

## Questions?

Please reach out to us at support@sleepdata.org or in the [Forum](https://sleepdata.org/forum) if you have questions.
