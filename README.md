## README
### bis620.2022

<!-- badges: start -->

[![Codecov test coverage](https://codecov.io/gh/RabbitChowder/bis620.2022/branch/main/graph/badge.svg)](https://app.codecov.io/gh/RabbitChowder/bis620.2022?branch=main)
[![R-CMD-check](https://github.com/RabbitChowder/bis620.2022/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/RabbitChowder/bis620.2022/actions/workflows/R-CMD-check.yaml)
[![lint](https://github.com/RabbitChowder/bis620.2022/actions/workflows/lint.yaml/badge.svg)](https://github.com/RabbitChowder/bis620.2022/actions/workflows/lint.yaml)
<!-- badges: end -->

## Background and Motvation 

Urinary Tract Infections are common infections that happen when bacteria enter the urethra, and infect the urinary tract. UTIs can happen anywhere in the urinary system, including the kidneys, ureters, bladder, and urethra. UTIs are very common, especially in women. Women get UTIs up to 30 times more often than men do. Urine culture is a lab test for bacteria or germs in a urine sample. The results of urine culture usually take 1 to 3 days. 

UTIs are common clinical conditions in emergency department (ED), with more than 3 million ED visits each year for UTIs, while it also has high diagnostic error rates (30-50%). Urine culture as the standard for UTIs diagnosis is usually not available because of the time it takes. Evaluations and treatment decision in a wide spectrum of patient populations and disease severity are needed to be conducted in ED, and UTIs are typically diagnosed using a combination of methods in ED, including a physical examination and a review of the patient's symptoms. 

Emergency physicians also face a different set of challenges than those by infectious disease specialists in a non-ED environment, and that diagnosis of UTI can often be difficult when mixed with a plethora of other conditions such as urolithiasis. With such complexity in ED-environment and noticeable insufficient diagnosis accuracy in ED, a decision support system based on machine learning algorithms that incorporate data such as patients' demographics, vitals, labs, past medical and surgical history, and medications should be developed to assist with UTIs diagnosis. 

While many factors such as physical findings, urinalysis, and past medical history are researched to be correlated with UTI diagnosis by other studies. What motivate this study is to understand how demographics, socioeconomic, and arrival information factors would impact the diagnosis of urinary tract infections. Some previous studies have assessed the association between the use of Medicaid, use of an interpreter, and census tract–level deprivation and overall UTI or multidrug-resistant (MDR) UTI. UTI is one of the most prevalent infections occurring at various stages of life for women, and it is one of the most frequently diagnosed infections in older adults. 

This study also interested in exploring the dataset that are obtained and preprocessed in the study https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0194085#pone.0194085.ref001. Data included four emergency departments (ED) adult visits data between March 2013 to May 2016. Variables categories are ‘Urinalysis’, ‘Physical Findings’, ‘Demographics/Arrival Info’, ‘Vitals’, ‘Labs’, ‘Past Medical/Surgical History’, and ‘Outpatient Medications’. The outcome variable is denoted as “UTI_diag”. Features of exploring insights from the data such as functions for visualization plots will also be incorporated.

## Research Question 
Will the patients' Demographics/Arrival Information, including chief complaint, age, gender, race, marital status, employ status, insurance status, and arrival type influence the urinary tract infection diagnosis? In addition, are the same variables still important when a patient has recurrent UTI? How does knowing a patient is recurrent affect our model?

### Installation

You can install the development version of bis620.2022 from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("RabbitChowder/bis620.2022")
```
