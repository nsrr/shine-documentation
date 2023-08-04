## About

Rise & SHINE (Sleep Health in Infancy & Early Childhood) is a longitudinal cohort study that examines infants’ sleep patterns between birth and 2 years, familial and environmental determinants of these patterns and their effect on accelerated weight gain over the first two years of life. Secondary outcomes include measures of executive functioning.

Infants were enrolled from Massachusetts General Hospital (MGH) and eligibility criteria include:
- Biologic and birthing mother-child
- Mother is > 18 years old
- Singleton birth, born at least 37 week gestation
- Child will receive primary care from an MGH pediatric site,
- Family lives within 40 miles of Boston and does not plan to move in the next year, 
- Able to speak English or Spanish, 
- Child is in the Level 1 nursery and does not have a genetic disorder, congenital malformation, or other condition that affects sleep and
- Mother does not have a psychosocial/mental health condition, sleep disorder or substance use problem that prohibits her from participating in the study
- Mother does not have another child previously enrolled in the study


## Methods

The data sets include actigraphy studies, questionnaire/survey responses, and information abstracted from the electronic health record. Visits were conducted when the infant was 1, 6, 12, and 24 months of age. 

Validated instruments used include:
* 

## Data overview

### Actigraphy
Raw actigraphy data is available for XX subjects and covers a period of approximately 5-7 days. Each participant's actigraphy CSV file has activity and white light level scores per 30-second epoch, as well as derived(?) sleep/wake and mobility.
Device?

### Covariate/phenotype datasets
Covariate CSV files contain data on 433 subjects. The [nsrr](:variables_path:/subject) column is the unique SHINE participant identifier. 

The dataset columns are described in the accompanying data dictionary files. The **variables** data dictionary file includes column names (id), labels (display names), descriptions, and other metadata. Categorical variables also include an associated “domain” (e.g., 0=No, 1=Yes, 2=Unsure), which are described in the **domains** data dictionary file.

The history of the covariate dataset and data dictionary files have been tracked on GitHub (https://github.com/nsrr/shine-data-dictionary). 

### Electronic Health Records (?)

## Access and usage restrictions

The SHINE dataset is only available for non-commercial use.

## Citation and acknowledgement

When using this dataset, users must cite the following:

>[Zhang GQ, Cui L, Mueller R, Tao S, Kim M, Rueschman M, Mariani S, Mobley D, Redline S. The National Sleep Research Resource: towards a sleep data commons. J Am Med Inform Assoc. 2018 Oct 1;25(10):1351-1358. doi: 10.1093/jamia/ocy064. PMID: 29860441; PMCID: PMC6188513.](https://pubmed.ncbi.nlm.nih.gov/29860441/)

>[Yu X, Quante M, Rueschman M, Ash T, Kaplan ER, Guo N, Horan CM, Haneuse S, Davison K, Taveras EM, Redline S. Emergence of racial/ethnic and socioeconomic differences in objectively measured sleep-wake patterns in early infancy: results of the Rise & SHINE study. Sleep. 2021 Mar 12;44(3):zsaa193. doi: 10.1093/sleep/zsaa193. PMID: 33057653; PMCID: PMC7953214.](https://pubmed.ncbi.nlm.nih.gov/33057653/)

Users must include the following text in any Acknowledgements:

> The National Sleep Research Resource was supported by the U.S. National Institutes of Health, National Heart Lung and Blood Institute (R24 HL114473, 75N92019R002).
> The Rise & SHINE study was supported by the National Institute of Health (5R01DK107972).

## Changelog

*August 2023*

- Make SHINE dataset available for data requests

## References

- SHINE GitHub Documentation: https://github.com/nsrr/shine-documentation
- SHINE GitHub Data Dictionary: https://github.com/nsrr/shine-data-dictionary

## Questions?

Please reach out to us at support@sleepdata.org or in the [Forum](https://sleepdata.org/forum) if you have questions.

