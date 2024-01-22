# Extending Open Health Stack

- Extend [Open Health Stack](https://developers.google.com/open-health-stack) so there are more foundational elements for designing and developing modern but standardized healthcare applications.
- The designs will draw on work already out there, including [Stanford Spezi](https://github.com/StanfordSpezi), but support both iOS and Android platforms, and also web through the use of Material 3.
- It is aimed at product managers and product designers who need to build healthcare apps quickly that focus on function over form.
- Having a highly modular UI library is great but having completed components or whole screens plus a pattern and user journey already created, it will greatly reduce development time.

## Features

Some features will evolve over time as other areas are added. Generally, support will be for iOS and Android first, with web coming later.

Code for each of the sections will hopefully come from other projects and contributors. The default stack should support iOS and Android by default but knowingly an org will have their own, compliant ready infrastructure ready to replace.

- Light and dark modes
- Web/responsive
- Dashboards
- Extend accessibility standards
- General guide
- Support & Information
- Knowledgebase, Inline support
- Health integration (HealthKit, Google Health)
- LLM Chatbot
- Sharing Health Data
- Scheduler, Notifications
- Insights & Trends
- Medication

## In Progress

- Authentication, Authorization
- Disclaimer, Privacy, Consent
- Offline sync
- Mental Health (PHQ-9, GAD-7), Results
- Health Profile
	- Additions: Family history, diet, activity, medication, surgery, allergies, blood type, fitzpatric skin type, mental health.
- (base) Home, Settings, App Navigation, Results

## Considerations

Clinically-validated self-assessment tools commonly used in various domains of health:

### Mental Health Assessments

- **~~Patient Health Questionnaire (PHQ-9)~~✅**~~: Screens for depression.~~
- **~~Generalized Anxiety Disorder Assessment (GAD-7)~~✅**~~: Screens for anxiety.~~
- **[Beck Depression Inventory](https://naviauxlab.ucsd.edu/wp-content/uploads/2020/09/BDI21.pdf) (BDI-II)❌©**: Assesses the severity of depression.
- **[Beck Anxiety Inventory](https://theinvictusclinic.com/wp-content/uploads/2019/10/Beck-Anxiety-Inventory.pdf) (BAI)❌©**: Measures the severity of anxiety.
    - https://pubmed.ncbi.nlm.nih.gov/11058490/
    - https://www.ncbi.nlm.nih.gov/pmc/articles/PMC314375/bin/i1523-5998-004-01-0009-ta01.jpg
    - **[Mood Disorder Questionnaire](https://www.ohsu.edu/sites/default/files/2019-06/cms-quality-bipolar_disorder_mdq_screener.pdf) (MDQ)❌©**: Screens for bipolar disorder.-[Requires written consent apparently](https://www.notion.so/Research-4355c4dd22c14981a3c55a7e6ce927d7?pvs=21)
    - There is also a ***Mood Disorder Questionnaire***-Adolescent Version for use in adolescent population.
- **[Alcohol Use Disorders Identification Test](https://auditscreen.org/) (AUDIT)✅**: Screens for alcohol abuse.
- **[Edinburgh Postnatal Depression Scale](https://www.blackdoginstitute.org.au/wp-content/uploads/2020/04/edinburgh-postnatal-depression-scale.pdf) (EPDS)✅**: Screens for postpartum depression.

### Physical Health Assessments

- **[International Prostate Symptom Score](https://www.healthymale.org.au/files/inline-files/Int.%20Prostate%20Symptom%20Score%20%28I-PSS0%29_Healthy%20Male%202019.pdf) (IPSS)✅**: Assesses urinary symptoms and possible benign prostatic hyperplasia.
- **[Asthma Control Test](https://asthma.org.au/wp-content/uploads/2021/09/The-Asthma-Control-Test-ACT-PDF-with-infographic_2021.pdf) (ACT)✅**: Assesses asthma control.
    - There is also a version for children between the ages of 4 and 11, known as the Childhood Asthma Control Test (C-ACT).
- **[Migraine Disability Assessment Test](https://headaches.org/wp-content/uploads/2018/02/MIDAS.pdf) (MIDAS)✅**: Measures the impact of migraines on daily life over a 3 month period.
- **[The International Physical Activity Questionnaire](https://youthrex.com/wp-content/uploads/2019/10/IPAQ-TM.pdf) (IPAQ)✅**: Measures physical activity levels.
    - The IPAQ steering committee, which governs the use and distribution of the questionnaire, requests that users register their studies or surveys when they are using the IPAQ.
    - Short and long forms exist.

### General Health and Quality of Life Assessments

- **[RAND 36-Item Health Survey (SF-36v2)](https://www.rand.org/health-care/surveys_tools/mos/36-item-short-form/survey-instrument.html)✅**: Assesses overall health and well-being.
    - Cite source https://www.rand.org/health-care/surveys_tools/mos/36-item-short-form/terms.html
    - **Short Form Health Survey (SF-12)**: A shorter version of SF-36.
- **European Quality of Life Five Dimension Five Level Scale (EQ-5D-5L)✅©**: Measures general health status and outcomes.
    - Free for non-commercial - just register to use. https://registration.euroqol.org/
    - Children & adolescents can use EQ-5D-Y
- **[PROMIS (Patient-Reported Outcomes Measurement Information System)](https://www.healthmeasures.net/explore-measurement-systems/promis)✅**: A set of measures that evaluates and monitors physical, mental, and social health.

### Nutritional Health Assessments
- **Mini Nutritional Assessment (MNA)**: Screens for malnutrition in older adults.
- **Eating Disorder Examination Questionnaire (EDE-Q)**: Screens for eating disorders.

### Cognitive and Neurological Assessments
- **Montreal Cognitive Assessment (MoCA)**: Screens for mild cognitive impairment.
- **Mini-Mental State Examination (MMSE)**: Assesses cognitive function.

### Women’s Health Assessments
- **Uterine Fibroid Symptom and Health-Related Quality of Life Questionnaire (UFS-QOL)**: Assesses the impact of uterine fibroids on quality of life.

### Sleep Assessments
- **Pittsburgh Sleep Quality Index (PSQI)**: Assesses sleep quality and disturbances.
- **Epworth Sleepiness Scale (ESS)**: Measures daytime sleepiness.

### Pain Assessments
- **Brief Pain Inventory (BPI)**: Assesses pain and its impact on function.
- **McGill Pain Questionnaire (MPQ)**: Describes qualitative and quantitative aspects of pain.





